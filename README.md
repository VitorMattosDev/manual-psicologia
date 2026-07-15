# Manual de Psicologia

Livro-texto aberto de psicologia em português do Brasil, da série **Manuais de Ciências**.
Cobre a disciplina do básico ao avançado em 15 volumes (~105 capítulos), construído com
[Quarto](https://quarto.org) e publicado em HTML + PDF via GitHub Pages.

- **Proposta editorial:** [`PLANO.md`](PLANO.md)
- **Fila de autoria (status por capítulo):** [`ROADMAP.md`](ROADMAP.md)
- **Instruções operacionais para o Claude Code:** [`CLAUDE.md`](CLAUDE.md)

> **Aviso.** Este manual é **educacional**. Não oferece diagnóstico, avaliação ou
> orientação clínica, e não substitui um profissional qualificado.

---

## Estrutura

```
_quarto.yml                     # config do livro (lang: pt no ROOT)
index.qmd                       # capa + grafo de pré-requisitos (mermaid)
referencias.qmd                 # bibliografia gerada
referencias.bib                 # BibTeX (chaves @autor_ano)
abnt.csl                        # estilo de citação ABNT
styles.css                      # SCSS (1ª linha: marcador de layer)
capitulos/volNN-*/cap-NN-*.qmd  # capítulos
_extensions/danmackinlay/tikz/  # extensão TikZ COM PATCHES LOCAIS
.github/workflows/publish.yml   # CI: chrome-headless-shell + TinyTeX + publish
```

## Build local

### Pré-requisitos

- [Quarto](https://quarto.org/docs/get-started/) ≥ 1.9
- TinyTeX + pacotes LaTeX para as figuras TikZ:

```bash
quarto install tinytex
tlmgr install standalone pgf pgfplots dvisvgm xcolor amsmath amsfonts
```

### ⚠️ PATH do TinyTeX — o bloqueador recorrente

`quarto install tinytex` **não** adiciona o bin do TinyTeX ao PATH da sessão. Sem isso as
figuras TikZ não renderizam e `tikz.lua` falha com `imgdata nil` por volta da linha 587.
**O sintoma parece pacote LaTeX faltando, mas é PATH.**

Prepende o bin ao PATH **antes** de qualquer render:

```bash
# Windows (Git Bash)
export PATH="$HOME/AppData/Roaming/TinyTeX/bin/windows:$PATH"

# Linux / macOS
export PATH="$HOME/.TinyTeX/bin/x86_64-linux:$PATH"   # ajuste a plataforma
```

No Windows, `tlmgr` é `tlmgr.bat` — `which tlmgr` não o encontra mesmo com o PATH correto.

### Renderizar

```bash
quarto preview                                                  # HTML com live reload
quarto render                                                   # livro completo (HTML + PDF)
quarto render capitulos/vol01-o-que-e-psicologia/cap-01-introducao.qmd --to html
```

## Contribuindo

A fila autoritativa é o `ROADMAP.md`: um capítulo por linha, com caminho canônico e
status (⬜ pendente · 🔄 em andamento · ✅ concluído). A autoria segue **fatia vertical** —
completa-se um volume antes de abrir o próximo, e uma fase antes da próxima. O Cap. 1 é o
**gabarito de estilo**: replique sua anatomia (`CLAUDE.md §4`).

Commits de capítulo: `cap NN: <título>`.

### Regras que não se negociam

- **Nunca** rodar `quarto add` ou `quarto update` na extensão TikZ. `_extensions/danmackinlay/tikz/`
  é patchada localmente; o upstream sem os patches quebra a renderização das figuras.
- `lang: pt` fica no **nível raiz** do `_quarto.yml`, nunca dentro de `book:`.
- A primeira linha de `styles.css` é `/*-- scss:rules --*/`. Sem ela o render inteiro
  quebra ("doesn't contain at least one layer boundary").
- Ordem dos filtros: `danmackinlay/tikz` **antes** de `quarto`.
- Sem `siunitx`, `physics`, `bussproofs`, `mhchem` ou `chemfig` — notação estatística usa
  MathJax/LaTeX padrão.
- Nunca inventar referência ou DOI. Na dúvida, reescreva a afirmação.

## Publicação (GitHub Pages)

O workflow `.github/workflows/publish.yml` roda a cada push na `main`: instala Quarto,
TinyTeX, `chrome-headless-shell` (necessário para o grafo mermaid do `index.qmd` não
travar o PDF em runner Ubuntu) e os pacotes LaTeX, depois publica na branch `gh-pages`.

### Correção one-time do gh-pages

`quarto-actions/publish@v2` **aborta se a branch `gh-pages` não existir** no remoto. Antes
do primeiro push, crie-a vazia:

```bash
git push origin $(git commit-tree $(git hash-object -t tree /dev/null) -m 'init gh-pages'):refs/heads/gh-pages
```

Depois, em **Settings → Pages**, aponte a fonte para a branch `gh-pages` (root) e
re-dispare o workflow.

## Licença

Conteúdo educacional aberto. Ver `LICENSE` quando definida.
