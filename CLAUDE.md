# CLAUDE.md — Manual de Psicologia

> Instruções operacionais para o Claude Code neste repositório.
> Leia este arquivo **inteiro** antes de qualquer ação em toda nova sessão.

---

## 1. Identidade do projeto

- **Nome:** Manual de Psicologia
- **Série:** *Manuais de Ciências* (educacionais, open-source, em **português do Brasil**)
- **Autoria:** autônoma via Claude Code
- **Stack:** Quarto (livro, saída **HTML + PDF**) → GitHub Pages via GitHub Actions
- **Público:** do estudante iniciante ao leitor avançado. O manual vai **do básico ao avançado** e cobre o assunto **como um todo**.
- **Idioma de todo o conteúdo:** pt-BR.

### Proposta pedagógica
Psicologia é uma ciência empírica. O manual trata a disciplina com **rigor científico** (método, evidência, replicabilidade) e ao mesmo tempo com **acessibilidade didática**. Sempre que possível: distinguir senso comum de ciência, ancorar afirmações em evidência/estudos, apresentar teorias concorrentes de forma equilibrada, e conectar conceito → experimento → aplicação.

---

## 2. Estrutura do manual (15 volumes, 3 fases, ~105 capítulos)

A fonte autoritativa da fila de tarefas é o **`ROADMAP.md`** (caminho de arquivo + status por capítulo). O quadro abaixo é o mapa geral.

### FASE 1 — Fundamentos, História e Métodos (Vols 1–3)

**Vol 1 — O que é Psicologia**
1. Introdução: definição, objeto de estudo, senso comum × ciência
2. As grandes questões (natureza × cultura, mente–corpo, consciência, livre-arbítrio)
3. Psicologia como ciência: o método científico aplicado ao comportamento
4. Áreas e campos de atuação do psicólogo
5. Mitos e concepções equivocadas sobre a psicologia

**Vol 2 — História e Sistemas**
6. Raízes filosóficas: da filosofia à ciência
7. Estruturalismo e Funcionalismo (Wundt, Titchener, James)
8. Behaviorismo (Watson, Skinner)
9. Gestalt
10. Psicanálise (Freud e desdobramentos)
11. Humanismo (Rogers, Maslow)
12. A revolução cognitiva
13. Perspectivas contemporâneas (evolucionista, sociocultural, neurociência)

**Vol 3 — Métodos de Pesquisa e Estatística**
14. O método experimental
15. Métodos não-experimentais (correlacional, observacional, survey, estudo de caso)
16. Variáveis, validade e confiabilidade
17. Amostragem
18. Estatística descritiva
19. Estatística inferencial (fundamentos)
20. Ética em pesquisa (comitês, consentimento, TCLE)
21. Leitura crítica de artigos científicos

### FASE 2 — Processos Psicológicos Básicos (Vols 4–9)

**Vol 4 — Bases Biológicas do Comportamento**
22. O neurônio e a comunicação neural
23. O sistema nervoso (central e periférico)
24. O cérebro: estruturas e funções
25. Sistema endócrino e hormônios
26. Genética do comportamento
27. Métodos de estudo do cérebro (neuroimagem)
28. Plasticidade neural

**Vol 5 — Sensação e Percepção**
29. Princípios de sensação (psicofísica, limiares)
30. Visão
31. Audição
32. Outros sentidos (olfato, paladar, tato, propriocepção, dor)
33. Organização perceptual (Gestalt, profundidade, constâncias)
34. Atenção, percepção e ilusões

**Vol 6 — Consciência**
35. A natureza da consciência
36. Sono e ritmos circadianos
37. Sonhos
38. Estados alterados (hipnose, meditação, substâncias psicoativas)

**Vol 7 — Aprendizagem**
39. Condicionamento clássico (Pavlov)
40. Condicionamento operante (Skinner)
41. Aprendizagem observacional (Bandura)
42. Cognição e aprendizagem

**Vol 8 — Memória e Cognição**
43. Modelos de memória
44. Codificação, armazenamento e recuperação
45. Esquecimento e memória falsa
46. Pensamento, conceitos e resolução de problemas
47. Tomada de decisão e heurísticas (vieses cognitivos)
48. Linguagem
49. Inteligência: teorias
50. Inteligência: avaliação e controvérsias

**Vol 9 — Motivação e Emoção**
51. Teorias da motivação
52. Motivações básicas (fome, sede, sexo)
53. Motivações sociais (realização, pertencimento)
54. Teorias da emoção
55. Expressão e regulação emocional
56. Estresse e enfrentamento (coping)

### FASE 3 — Diferenças, Sociedade e Aplicações (Vols 10–15)

**Vol 10 — Desenvolvimento Humano**
57. Conceitos e questões do desenvolvimento
58. Desenvolvimento pré-natal e infância
59. Desenvolvimento cognitivo (Piaget, Vygotsky)
60. Desenvolvimento social e emocional (apego, Erikson)
61. Desenvolvimento moral (Kohlberg e críticas)
62. Adolescência
63. Idade adulta e envelhecimento

**Vol 11 — Personalidade**
64. O conceito de personalidade
65. Teorias psicodinâmicas
66. Teorias humanistas
67. Teorias dos traços (Big Five / CGF)
68. Teorias sociocognitivas
69. Avaliação da personalidade

**Vol 12 — Psicologia Social**
70. Cognição social e atribuição
71. Atitudes e persuasão
72. Conformidade, obediência e influência social
73. Relações interpessoais e atração
74. Comportamento pró-social e agressão
75. Grupos, preconceito e processos intergrupais

**Vol 13 — Psicopatologia**
76. Normalidade e anormalidade
77. Sistemas de classificação (DSM-5-TR e CID-11)
78. Transtornos de ansiedade
79. Transtornos do humor (depressivos e bipolares)
80. Transtornos relacionados a trauma e estresse
81. TOC e transtornos relacionados
82. Esquizofrenia e transtornos psicóticos
83. Transtornos de personalidade
84. Transtornos alimentares
85. Transtornos do neurodesenvolvimento (TEA, TDAH)
86. Transtornos por uso de substâncias

**Vol 14 — Tratamentos e Terapias**
87. Fundamentos da intervenção psicológica
88. Terapias psicodinâmicas
89. Terapias humanistas
90. Terapia comportamental
91. Terapia cognitivo-comportamental (TCC)
92. Terapias contextuais (ACT, DBT, mindfulness)
93. Terapias sistêmicas e de grupo
94. Tratamentos biomédicos (psicofármacos)
95. Eficácia e prática baseada em evidências

**Vol 15 — Psicologia Aplicada e Fronteiras**
96. Psicologia da saúde
97. Psicologia organizacional e do trabalho
98. Psicologia escolar e educacional
99. Neuropsicologia
100. Psicologia positiva
101. Psicologia jurídica e forense
102. Psicologia do esporte
103. Psicologia, cultura e diversidade (transcultural)
104. A psicologia no Brasil (história, profissão, CFP/CRP, ética)
105. Tópicos contemporâneos e fronteiras (ciberpsicologia, IA, crise de replicabilidade, ciência aberta)

> **Estratégia de fatia vertical:** completar um volume inteiro antes de abrir o próximo; completar a Fase 1 antes da Fase 2. O **Cap. 1** é escrito primeiro, como **gabarito de estilo** (ver §4).

---

## 3. Arquivos do scaffold

```
_quarto.yml                     # config do livro (lang: pt no ROOT)
CLAUDE.md                       # este arquivo
PLANO.md                        # visão editorial e diretrizes de conteúdo
ROADMAP.md                      # fila executável: 1 linha por capítulo + status
README.md                       # visão geral + fixes one-time (gh-pages)
PROMPT-CLAUDE-CODE.md           # prompt de abertura de sessão
styles.css                      # SCSS (com marcador de layer obrigatório)
referencias.bib                 # BibTeX (chaves @autor_ano)
abnt.csl                        # estilo de citação ABNT
.github/workflows/publish.yml   # CI: chrome-headless-shell + TinyTeX + publish
_extensions/danmackinlay/tikz/  # extensão TikZ COM PATCHES LOCAIS (nunca atualizar)
index.qmd                       # capa + grafo de pré-requisitos (mermaid)
capitulos/**/cap-NN-*.qmd       # capítulos (stubs + gabarito)
```

---

## 4. Anatomia do capítulo (gabarito)

Todo capítulo segue esta estrutura. O **Cap. 1** é a referência canônica: escreva-o **completo** antes da autoria em massa.

1. **Cabeçalho / Abertura**
   - Título `# NN. Título`
   - Bloco de **Objetivos de aprendizagem** (`::: {.callout-objetivos}`)
   - Parágrafo de abertura que situa o tema e conecta ao capítulo anterior.
2. **Desenvolvimento** — seções `##` e `###`, texto em prosa densa e clara.
3. **Elementos didáticos recorrentes** (usar quando pertinente):
   - `::: {.experimento}` 🔬 **Experimento Clássico** — desenho, resultado, interpretação e limitações de um estudo marcante (ex.: Pavlov, Milgram, Bandura, Loftus, Rosenhan). Sempre com referência `@chave`.
   - `::: {.estudo-caso}` 📋 **Estudo de Caso** — vinheta clínica/aplicada (fictícia ou histórica documentada).
   - `::: {.base-neural}` 🧠 **Base Neural** — ponte com o substrato biológico do fenômeno.
   - `::: {.na-pratica}` 💡 **Na Prática** — aplicação concreta no dia a dia, clínica, trabalho ou educação.
   - `::: {.atencao}` ⚠️ **Atenção** — erro comum, mito desmontado, ou distinção conceitual fina.
4. **Figuras** — TikZ para esquemas didáticos (ver §7). Fenômenos que dependem de fotografia recebem SVG/PNG embarcado ou placeholder documentado.
5. **Síntese** — `::: {.callout-sintese}` recapitulando os pontos-chave.
6. **Glossário do capítulo** — termos-chave em negrito com definição curta.
7. **Para refletir / Questões de revisão** — 4–8 questões (mistura de recuperação factual e reflexão crítica).
8. **Referências** — geradas via `@chave` ao longo do texto + `referencias.bib`.

### Diretrizes de estilo
- Português do Brasil, registro didático-acadêmico, mas fluente e envolvente.
- **Citação intensiva:** toda afirmação empírica relevante recebe `@chave` (ex.: `@bandura1977`). Priorize fontes primárias e revisões.
- Apresentar **teorias concorrentes de forma equilibrada**; sinalizar controvérsias e limites de evidência.
- Em psicopatologia, referenciar **DSM-5-TR** e **CID-11**; nunca oferecer diagnóstico ou orientação clínica ao leitor — o manual é educacional.
- Sensibilidade ética: casos clínicos são ilustrativos; evitar linguagem estigmatizante.

---

## 5. Regras de execução autônoma

Você (Claude Code) está **pré-aprovado** para, sem pausar por aprovação:
- criar/editar arquivos `.qmd`, `.bib`, config;
- criar figuras TikZ/SVG;
- rodar comandos de validação (`quarto render`, preview de figura);
- fazer `git commit` **por capítulo**.

**Pare apenas em erro bloqueante real** (ex.: toolchain quebrada que você não consegue reparar seguindo §7–§8).

- **Commit por capítulo**, formato: `cap NN: <título>`
- Commits de tarefas mecânicas (ajuste de `_quarto.yml`, mudança de status no ROADMAP): mensagem descritiva curta.
- Ao concluir um capítulo: atualizar o **status no `ROADMAP.md`** e incluir o `.qmd` no `_quarto.yml`.

### Fluxo de sessão recomendado
- **1 capítulo por sessão**; `/clear` entre capítulos; `/compact` ao atingir ~80% de contexto.
- `/model opus` para escrever capítulos novos; `/model sonnet` para tarefas mecânicas.
- `ROADMAP.md` é a fila autoritativa — sempre pegue o próximo capítulo pendente segundo a fatia vertical.

---

## 6. Configuração do `_quarto.yml` (pontos críticos)

- `lang: pt` no **nível RAIZ** do arquivo — **nunca** aninhado dentro de `book:`.
- Ordem dos filtros: `danmackinlay/tikz` **antes** de `quarto`.
- `tikz: svg-engine: dvisvgm`.
- `theme: [cosmo, styles.css]` → isso faz o Quarto tratar `styles.css` como camada SCSS (ver §8.4).
- Bibliografia: `bibliography: referencias.bib` + `csl: abnt.csl`.
- Exclusões de pacote LaTeX (ver §8.8).

---

## 7. Figuras TikZ — convenções

- Extensão: `danmackinlay/tikz` com **patches locais** vindos de `figuras-tikz-kit.zip` / `FIGURAS.md`.
- **NUNCA** rodar `quarto add` ou `quarto update` na extensão — isso baixa o upstream sem os patches e quebra a renderização. Arquivos ficam em `_extensions/danmackinlay/tikz/`.
- Sintaxe da figura:
  ```
  ::: {#fig-nome}
  ```{.tikz}
  %%| filename: nome
  %%| alt: descrição acessível da figura
  \begin{tikzpicture}
    ...
  \end{tikzpicture}
  ```
  Legenda da figura aqui.
  :::
  ```
  Referenciar no texto via `@fig-nome`.
- Estilos predefinidos: `curva, destaque, auxiliar, eixo, ponto, vetor`.
- Cores: `manualblue, manualred, manualgreen, manualyellow, manualgray`.
- **Bibliotecas disponíveis** (as do preâmbulo da extensão): `calc, angles, quotes, arrows.meta, positioning, intersections, decorations.pathreplacing, decorations.markings, patterns, through, backgrounds`. **Não** há `shapes.geometric` nem `fit` — usar apenas formas nativas (`rectangle`, `circle`, `ellipse`, `rounded corners`).
- **Quebra de linha em nó: `\\` só no nível superior.** Dentro de um grupo aninhado — `{\tiny linha um\\linha dois}` — o `\\` quebra o alinhamento do TikZ e o build falha com `Undefined control sequence` em `\tikz@finish@orig`/`\pgfutil@next`, e o erro reportado é o enganoso `\begin{document} ended by \end{tikzpicture}`. Escrever cada linha em seu próprio grupo:
  ```
  ✗ {\textbf{Título}\\{\tiny linha um\\linha dois}}
  ✓ {\textbf{Título}\\{\tiny linha um}\\{\tiny linha dois}}
  ```
- **Uso típico neste manual:** diagramas de neurônio/sinapse, mapas de estruturas cerebrais (esquemáticos), arcos reflexos, desenhos experimentais (grupos/condições), fluxogramas de processos (memória, condicionamento), curvas (curva do esquecimento de Ebbinghaus, funções psicofísicas), hierarquias (pirâmide de Maslow), modelos conceituais (Big Five, modelo ABC da TCC).

---

## 8. Toolchain — correções obrigatórias (NÃO redescobrir)

Estas são correções já pagas com sangue em manuais anteriores. Devem estar sempre ativas.

### 8.1 `chrome-headless-shell` na CI
O grafo mermaid de pré-requisitos em `index.qmd` trava o render do PDF em runners Ubuntu (sem Chromium). No `.github/workflows/publish.yml`, **antes** do passo de render/publish:
```yaml
- run: quarto install chrome-headless-shell
```
Usar `chrome-headless-shell` especificamente — **não** `chromium`.

### 8.2 Extensão TikZ — nunca atualizar
Ver §7. `_extensions/danmackinlay/tikz/` é patchada localmente. Jamais `quarto add`/`quarto update`.

### 8.3 TikZ toolchain — PATH é o bloqueador recorrente
`quarto install tinytex` **não** adiciona o bin do TinyTeX ao PATH da sessão. Sintoma: figura não renderiza, `tikz.lua` erra com `imgdata nil` por volta da linha 587. **Isso é problema de PATH, não de pacote faltando.**

Prepender o bin do TinyTeX ao PATH **antes** de qualquer render/preview:
- Windows: `$HOME/AppData/Roaming/TinyTeX/bin/windows`
- Linux/macOS: `~/.TinyTeX/bin/<plataforma>`

Instalação local:
```
quarto install tinytex
tlmgr update --self      # ver 8.3.1 — sem isso o install aborta
tlmgr install standalone pgf pgfplots dvisvgm xcolor amsmath amsfonts
```
Na CI: após instalar Quarto + TinyTeX, localizar `tlmgr` se não estiver no PATH, e rodar o mesmo `tlmgr install`. Este bootstrap deve rodar automaticamente na primeira sessão (está no `PROMPT-CLAUDE-CODE.md`).

#### 8.3.1 `tlmgr update --self` antes de qualquer `tlmgr install`
O `tlmgr` que vem no TinyTeX recém-instalado costuma estar defasado em relação ao repositório CTAN e **recusa qualquer instalação** até se atualizar, com a mensagem `tlmgr itself needs to be updated` e **exit 255**. Sempre rodar `tlmgr update --self` antes do `install`. Vale local e na CI.

#### 8.3.2 No Windows, `tlmgr` é `tlmgr.bat`
`which tlmgr` / `command -v tlmgr` **não** encontram o binário mesmo com o PATH correto. Chamar `tlmgr.bat` explicitamente.

#### 8.3.3 Os binários do TinyTeX são symlinks
Em `TinyTeX/bin/<plataforma>/`, `tlmgr` e companhia são **symlinks**, não arquivos regulares. Um `find ... -name tlmgr -type f` retorna vazio e faz a CI abortar com "tlmgr não encontrado". Usar `\( -type f -o -type l \)`, ou testar caminhos conhecidos com `[ -x ... ]`. No Linux, o `quarto-actions/setup@v2` instala em `~/.TinyTeX/bin/x86_64-linux/`.

### 8.4 Marcador de camada SCSS no `styles.css`
Com `styles.css` sob `theme:` no `_quarto.yml`, o Quarto ≥1.9 o trata como camada SCSS e **exige** a primeira linha:
```
/*-- scss:rules --*/
```
Sem isso, o render inteiro quebra com erro "doesn't contain at least one layer boundary". Já deve nascer com o marcador.

### 8.5 Branch `gh-pages` deve pré-existir
`quarto-actions/publish@v2` aborta se o branch `gh-pages` não existir no remoto. Fix one-time, antes do primeiro push (está no README):
```
git push origin $(git commit-tree $(git hash-object -t tree /dev/null) -m 'init gh-pages'):refs/heads/gh-pages
```
Depois, re-disparar o workflow.

### 8.6 Commits git no Windows (Claude Code)
Usar apenas flags `-m "..."` simples. **Não** usar here-strings do PowerShell (`@'...'@`) dentro do Bash — o `@` vaza para dentro da mensagem de commit.

### 8.7 `lang: pt` no nível raiz
Ver §6. Nível RAIZ do `_quarto.yml`, nunca dentro de `book:`.

### 8.8 Exclusões de pacote (tipo Psicologia)
- **Excluir** `siunitx`, `physics` e `bussproofs` (não são necessários e quebram HTML/MathJax).
- Notação estatística e matemática usa **MathJax/LaTeX padrão** (ex.: `\bar{x}`, `\sigma`, `p < .05`, `\chi^2`, `d`, `r`). Para unidades simples, `\mathrm{}` + `\,`.
- **Sem** `mhchem`/`chemfig` (isso é do manual de Química).

---

## 9. Checklist antes de dar um capítulo por concluído

- [ ] Estrutura do gabarito (§4) presente e completa.
- [ ] Afirmações empíricas com `@chave`; entradas correspondentes no `referencias.bib`.
- [ ] Ao menos um elemento didático (experimento/caso/na prática) quando o tema permite.
- [ ] Figuras TikZ renderizam localmente (PATH ok) com `alt` preenchido.
- [ ] `render` do capítulo sem erro em HTML.
- [ ] Capítulo adicionado ao `_quarto.yml`; status atualizado no `ROADMAP.md`.
- [ ] `git commit -m "cap NN: <título>"`.
