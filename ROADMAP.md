# ROADMAP — Manual de Psicologia

Fila **executável** e autoritativa de autoria. Uma linha por capítulo, com caminho de
arquivo e status. O Claude Code consome este arquivo para saber o que escrever a seguir.

## Como o Claude Code usa este arquivo

1. Pegue o **próximo capítulo `⬜ pendente`** respeitando a **fatia vertical**: complete o
   volume atual antes de abrir o próximo; complete a fase atual antes da próxima.
2. Escreva o capítulo inteiro seguindo a anatomia do gabarito (Cap. 1) — ver `CLAUDE.md §4`.
3. Ao concluir: adicione o `.qmd` ao `_quarto.yml`, atualize o status aqui para `✅ concluído`
   e faça `git commit -m "cap NN: <título>"`.
4. Os caminhos abaixo são **canônicos**: crie os stubs e os capítulos exatamente nesses paths.

**Legenda de status:** ⬜ pendente · 🔄 em andamento · ✅ concluído

**Progresso:** 75 / 105 concluídos · Fase 1: 21/21 · Fase 2: 35/35 · Fase 3: 19/49

> **Vol 1 ✅ · Vol 2 ✅ · Vol 3 ✅ · Vol 4 ✅ · Vol 5 ✅ · Vol 6 ✅ · Vol 7 ✅ · Vol 8 ✅ · Vol 9 ✅ · Vol 10 ✅ · Vol 11 ✅ · Vol 12 ✅** Próximo: Fase 3, Vol 13 (Psicopatologia).

---

## FASE 1 — Fundamentos, História e Métodos

### Vol 1 — O que é Psicologia
| Cap | Título | Arquivo | Status |
|-----|--------|---------|--------|
| 01 | Introdução: definição, objeto de estudo, senso comum × ciência | `capitulos/vol01-o-que-e-psicologia/cap-01-introducao.qmd` | ✅ |
| 02 | As grandes questões (natureza × cultura, mente–corpo, consciência, livre-arbítrio) | `capitulos/vol01-o-que-e-psicologia/cap-02-grandes-questoes.qmd` | ✅ |
| 03 | Psicologia como ciência: o método científico aplicado ao comportamento | `capitulos/vol01-o-que-e-psicologia/cap-03-psicologia-como-ciencia.qmd` | ✅ |
| 04 | Áreas e campos de atuação do psicólogo | `capitulos/vol01-o-que-e-psicologia/cap-04-areas-atuacao.qmd` | ✅ |
| 05 | Mitos e concepções equivocadas sobre a psicologia | `capitulos/vol01-o-que-e-psicologia/cap-05-mitos.qmd` | ✅ |

### Vol 2 — História e Sistemas
| Cap | Título | Arquivo | Status |
|-----|--------|---------|--------|
| 06 | Raízes filosóficas: da filosofia à ciência | `capitulos/vol02-historia-sistemas/cap-06-raizes-filosoficas.qmd` | ✅ |
| 07 | Estruturalismo e Funcionalismo (Wundt, Titchener, James) | `capitulos/vol02-historia-sistemas/cap-07-estruturalismo-funcionalismo.qmd` | ✅ |
| 08 | Behaviorismo (Watson, Skinner) | `capitulos/vol02-historia-sistemas/cap-08-behaviorismo.qmd` | ✅ |
| 09 | Gestalt | `capitulos/vol02-historia-sistemas/cap-09-gestalt.qmd` | ✅ |
| 10 | Psicanálise (Freud e desdobramentos) | `capitulos/vol02-historia-sistemas/cap-10-psicanalise.qmd` | ✅ |
| 11 | Humanismo (Rogers, Maslow) | `capitulos/vol02-historia-sistemas/cap-11-humanismo.qmd` | ✅ |
| 12 | A revolução cognitiva | `capitulos/vol02-historia-sistemas/cap-12-revolucao-cognitiva.qmd` | ✅ |
| 13 | Perspectivas contemporâneas (evolucionista, sociocultural, neurociência) | `capitulos/vol02-historia-sistemas/cap-13-perspectivas-contemporaneas.qmd` | ✅ |

### Vol 3 — Métodos de Pesquisa e Estatística
| Cap | Título | Arquivo | Status |
|-----|--------|---------|--------|
| 14 | O método experimental | `capitulos/vol03-metodos-estatistica/cap-14-metodo-experimental.qmd` | ✅ |
| 15 | Métodos não-experimentais (correlacional, observacional, survey, estudo de caso) | `capitulos/vol03-metodos-estatistica/cap-15-metodos-nao-experimentais.qmd` | ✅ |
| 16 | Variáveis, validade e confiabilidade | `capitulos/vol03-metodos-estatistica/cap-16-variaveis-validade.qmd` | ✅ |
| 17 | Amostragem | `capitulos/vol03-metodos-estatistica/cap-17-amostragem.qmd` | ✅ |
| 18 | Estatística descritiva | `capitulos/vol03-metodos-estatistica/cap-18-estatistica-descritiva.qmd` | ✅ |
| 19 | Estatística inferencial (fundamentos) | `capitulos/vol03-metodos-estatistica/cap-19-estatistica-inferencial.qmd` | ✅ |
| 20 | Ética em pesquisa (comitês, consentimento, TCLE) | `capitulos/vol03-metodos-estatistica/cap-20-etica-pesquisa.qmd` | ✅ |
| 21 | Leitura crítica de artigos científicos | `capitulos/vol03-metodos-estatistica/cap-21-leitura-critica.qmd` | ✅ |

---

## FASE 2 — Processos Psicológicos Básicos

### Vol 4 — Bases Biológicas do Comportamento
| Cap | Título | Arquivo | Status |
|-----|--------|---------|--------|
| 22 | O neurônio e a comunicação neural | `capitulos/vol04-bases-biologicas/cap-22-neuronio.qmd` | ✅ |
| 23 | O sistema nervoso (central e periférico) | `capitulos/vol04-bases-biologicas/cap-23-sistema-nervoso.qmd` | ✅ |
| 24 | O cérebro: estruturas e funções | `capitulos/vol04-bases-biologicas/cap-24-cerebro.qmd` | ✅ |
| 25 | Sistema endócrino e hormônios | `capitulos/vol04-bases-biologicas/cap-25-sistema-endocrino.qmd` | ✅ |
| 26 | Genética do comportamento | `capitulos/vol04-bases-biologicas/cap-26-genetica-comportamento.qmd` | ✅ |
| 27 | Métodos de estudo do cérebro (neuroimagem) | `capitulos/vol04-bases-biologicas/cap-27-neuroimagem.qmd` | ✅ |
| 28 | Plasticidade neural | `capitulos/vol04-bases-biologicas/cap-28-plasticidade.qmd` | ✅ |

### Vol 5 — Sensação e Percepção
| Cap | Título | Arquivo | Status |
|-----|--------|---------|--------|
| 29 | Princípios de sensação (psicofísica, limiares) | `capitulos/vol05-sensacao-percepcao/cap-29-principios-sensacao.qmd` | ✅ |
| 30 | Visão | `capitulos/vol05-sensacao-percepcao/cap-30-visao.qmd` | ✅ |
| 31 | Audição | `capitulos/vol05-sensacao-percepcao/cap-31-audicao.qmd` | ✅ |
| 32 | Outros sentidos (olfato, paladar, tato, propriocepção, dor) | `capitulos/vol05-sensacao-percepcao/cap-32-outros-sentidos.qmd` | ✅ |
| 33 | Organização perceptual (Gestalt, profundidade, constâncias) | `capitulos/vol05-sensacao-percepcao/cap-33-organizacao-perceptual.qmd` | ✅ |
| 34 | Atenção, percepção e ilusões | `capitulos/vol05-sensacao-percepcao/cap-34-atencao-ilusoes.qmd` | ✅ |

### Vol 6 — Consciência
| Cap | Título | Arquivo | Status |
|-----|--------|---------|--------|
| 35 | A natureza da consciência | `capitulos/vol06-consciencia/cap-35-natureza-consciencia.qmd` | ✅ |
| 36 | Sono e ritmos circadianos | `capitulos/vol06-consciencia/cap-36-sono-ritmos.qmd` | ✅ |
| 37 | Sonhos | `capitulos/vol06-consciencia/cap-37-sonhos.qmd` | ✅ |
| 38 | Estados alterados (hipnose, meditação, substâncias psicoativas) | `capitulos/vol06-consciencia/cap-38-estados-alterados.qmd` | ✅ |

### Vol 7 — Aprendizagem
| Cap | Título | Arquivo | Status |
|-----|--------|---------|--------|
| 39 | Condicionamento clássico (Pavlov) | `capitulos/vol07-aprendizagem/cap-39-condicionamento-classico.qmd` | ✅ |
| 40 | Condicionamento operante (Skinner) | `capitulos/vol07-aprendizagem/cap-40-condicionamento-operante.qmd` | ✅ |
| 41 | Aprendizagem observacional (Bandura) | `capitulos/vol07-aprendizagem/cap-41-aprendizagem-observacional.qmd` | ✅ |
| 42 | Cognição e aprendizagem | `capitulos/vol07-aprendizagem/cap-42-cognicao-aprendizagem.qmd` | ✅ |

### Vol 8 — Memória e Cognição
| Cap | Título | Arquivo | Status |
|-----|--------|---------|--------|
| 43 | Modelos de memória | `capitulos/vol08-memoria-cognicao/cap-43-modelos-memoria.qmd` | ✅ |
| 44 | Codificação, armazenamento e recuperação | `capitulos/vol08-memoria-cognicao/cap-44-codificacao-recuperacao.qmd` | ✅ |
| 45 | Esquecimento e memória falsa | `capitulos/vol08-memoria-cognicao/cap-45-esquecimento-memoria-falsa.qmd` | ✅ |
| 46 | Pensamento, conceitos e resolução de problemas | `capitulos/vol08-memoria-cognicao/cap-46-pensamento-problemas.qmd` | ✅ |
| 47 | Tomada de decisão e heurísticas (vieses cognitivos) | `capitulos/vol08-memoria-cognicao/cap-47-decisao-heuristicas.qmd` | ✅ |
| 48 | Linguagem | `capitulos/vol08-memoria-cognicao/cap-48-linguagem.qmd` | ✅ |
| 49 | Inteligência: teorias | `capitulos/vol08-memoria-cognicao/cap-49-inteligencia-teorias.qmd` | ✅ |
| 50 | Inteligência: avaliação e controvérsias | `capitulos/vol08-memoria-cognicao/cap-50-inteligencia-avaliacao.qmd` | ✅ |

### Vol 9 — Motivação e Emoção
| Cap | Título | Arquivo | Status |
|-----|--------|---------|--------|
| 51 | Teorias da motivação | `capitulos/vol09-motivacao-emocao/cap-51-teorias-motivacao.qmd` | ✅ |
| 52 | Motivações básicas (fome, sede, sexo) | `capitulos/vol09-motivacao-emocao/cap-52-motivacoes-basicas.qmd` | ✅ |
| 53 | Motivações sociais (realização, pertencimento) | `capitulos/vol09-motivacao-emocao/cap-53-motivacoes-sociais.qmd` | ✅ |
| 54 | Teorias da emoção | `capitulos/vol09-motivacao-emocao/cap-54-teorias-emocao.qmd` | ✅ |
| 55 | Expressão e regulação emocional | `capitulos/vol09-motivacao-emocao/cap-55-expressao-regulacao.qmd` | ✅ |
| 56 | Estresse e enfrentamento (coping) | `capitulos/vol09-motivacao-emocao/cap-56-estresse-coping.qmd` | ✅ |

---

## FASE 3 — Diferenças, Sociedade e Aplicações

### Vol 10 — Desenvolvimento Humano
| Cap | Título | Arquivo | Status |
|-----|--------|---------|--------|
| 57 | Conceitos e questões do desenvolvimento | `capitulos/vol10-desenvolvimento/cap-57-conceitos-desenvolvimento.qmd` | ✅ |
| 58 | Desenvolvimento pré-natal e infância | `capitulos/vol10-desenvolvimento/cap-58-pre-natal-infancia.qmd` | ✅ |
| 59 | Desenvolvimento cognitivo (Piaget, Vygotsky) | `capitulos/vol10-desenvolvimento/cap-59-desenvolvimento-cognitivo.qmd` | ✅ |
| 60 | Desenvolvimento social e emocional (apego, Erikson) | `capitulos/vol10-desenvolvimento/cap-60-desenvolvimento-social-emocional.qmd` | ✅ |
| 61 | Desenvolvimento moral (Kohlberg e críticas) | `capitulos/vol10-desenvolvimento/cap-61-desenvolvimento-moral.qmd` | ✅ |
| 62 | Adolescência | `capitulos/vol10-desenvolvimento/cap-62-adolescencia.qmd` | ✅ |
| 63 | Idade adulta e envelhecimento | `capitulos/vol10-desenvolvimento/cap-63-adultez-envelhecimento.qmd` | ✅ |

### Vol 11 — Personalidade
| Cap | Título | Arquivo | Status |
|-----|--------|---------|--------|
| 64 | O conceito de personalidade | `capitulos/vol11-personalidade/cap-64-conceito-personalidade.qmd` | ✅ |
| 65 | Teorias psicodinâmicas | `capitulos/vol11-personalidade/cap-65-psicodinamicas.qmd` | ✅ |
| 66 | Teorias humanistas | `capitulos/vol11-personalidade/cap-66-humanistas.qmd` | ✅ |
| 67 | Teorias dos traços (Big Five / CGF) | `capitulos/vol11-personalidade/cap-67-tracos-big-five.qmd` | ✅ |
| 68 | Teorias sociocognitivas | `capitulos/vol11-personalidade/cap-68-sociocognitivas.qmd` | ✅ |
| 69 | Avaliação da personalidade | `capitulos/vol11-personalidade/cap-69-avaliacao-personalidade.qmd` | ✅ |

### Vol 12 — Psicologia Social
| Cap | Título | Arquivo | Status |
|-----|--------|---------|--------|
| 70 | Cognição social e atribuição | `capitulos/vol12-psicologia-social/cap-70-cognicao-social.qmd` | ✅ |
| 71 | Atitudes e persuasão | `capitulos/vol12-psicologia-social/cap-71-atitudes-persuasao.qmd` | ✅ |
| 72 | Conformidade, obediência e influência social | `capitulos/vol12-psicologia-social/cap-72-conformidade-obediencia.qmd` | ✅ |
| 73 | Relações interpessoais e atração | `capitulos/vol12-psicologia-social/cap-73-relacoes-atracao.qmd` | ✅ |
| 74 | Comportamento pró-social e agressão | `capitulos/vol12-psicologia-social/cap-74-pro-social-agressao.qmd` | ✅ |
| 75 | Grupos, preconceito e processos intergrupais | `capitulos/vol12-psicologia-social/cap-75-grupos-preconceito.qmd` | ✅ |

### Vol 13 — Psicopatologia
| Cap | Título | Arquivo | Status |
|-----|--------|---------|--------|
| 76 | Normalidade e anormalidade | `capitulos/vol13-psicopatologia/cap-76-normalidade-anormalidade.qmd` | ✅ |
| 77 | Sistemas de classificação (DSM-5-TR e CID-11) | `capitulos/vol13-psicopatologia/cap-77-classificacao-dsm-cid.qmd` | ✅ |
| 78 | Transtornos de ansiedade | `capitulos/vol13-psicopatologia/cap-78-transtornos-ansiedade.qmd` | ✅ |
| 79 | Transtornos do humor (depressivos e bipolares) | `capitulos/vol13-psicopatologia/cap-79-transtornos-humor.qmd` | ✅ |
| 80 | Transtornos relacionados a trauma e estresse | `capitulos/vol13-psicopatologia/cap-80-trauma-estresse.qmd` | ✅ |
| 81 | TOC e transtornos relacionados | `capitulos/vol13-psicopatologia/cap-81-toc-relacionados.qmd` | ✅ |
| 82 | Esquizofrenia e transtornos psicóticos | `capitulos/vol13-psicopatologia/cap-82-esquizofrenia-psicoticos.qmd` | ✅ |
| 83 | Transtornos de personalidade | `capitulos/vol13-psicopatologia/cap-83-transtornos-personalidade.qmd` | ⬜ |
| 84 | Transtornos alimentares | `capitulos/vol13-psicopatologia/cap-84-transtornos-alimentares.qmd` | ⬜ |
| 85 | Transtornos do neurodesenvolvimento (TEA, TDAH) | `capitulos/vol13-psicopatologia/cap-85-neurodesenvolvimento.qmd` | ⬜ |
| 86 | Transtornos por uso de substâncias | `capitulos/vol13-psicopatologia/cap-86-uso-substancias.qmd` | ⬜ |

### Vol 14 — Tratamentos e Terapias
| Cap | Título | Arquivo | Status |
|-----|--------|---------|--------|
| 87 | Fundamentos da intervenção psicológica | `capitulos/vol14-tratamentos-terapias/cap-87-fundamentos-intervencao.qmd` | ⬜ |
| 88 | Terapias psicodinâmicas | `capitulos/vol14-tratamentos-terapias/cap-88-terapias-psicodinamicas.qmd` | ⬜ |
| 89 | Terapias humanistas | `capitulos/vol14-tratamentos-terapias/cap-89-terapias-humanistas.qmd` | ⬜ |
| 90 | Terapia comportamental | `capitulos/vol14-tratamentos-terapias/cap-90-terapia-comportamental.qmd` | ⬜ |
| 91 | Terapia cognitivo-comportamental (TCC) | `capitulos/vol14-tratamentos-terapias/cap-91-tcc.qmd` | ⬜ |
| 92 | Terapias contextuais (ACT, DBT, mindfulness) | `capitulos/vol14-tratamentos-terapias/cap-92-terapias-contextuais.qmd` | ⬜ |
| 93 | Terapias sistêmicas e de grupo | `capitulos/vol14-tratamentos-terapias/cap-93-terapias-sistemicas.qmd` | ⬜ |
| 94 | Tratamentos biomédicos (psicofármacos) | `capitulos/vol14-tratamentos-terapias/cap-94-psicofarmacos.qmd` | ⬜ |
| 95 | Eficácia e prática baseada em evidências | `capitulos/vol14-tratamentos-terapias/cap-95-pratica-baseada-evidencias.qmd` | ⬜ |

### Vol 15 — Psicologia Aplicada e Fronteiras
| Cap | Título | Arquivo | Status |
|-----|--------|---------|--------|
| 96 | Psicologia da saúde | `capitulos/vol15-aplicada-fronteiras/cap-96-psicologia-saude.qmd` | ⬜ |
| 97 | Psicologia organizacional e do trabalho | `capitulos/vol15-aplicada-fronteiras/cap-97-organizacional-trabalho.qmd` | ⬜ |
| 98 | Psicologia escolar e educacional | `capitulos/vol15-aplicada-fronteiras/cap-98-escolar-educacional.qmd` | ⬜ |
| 99 | Neuropsicologia | `capitulos/vol15-aplicada-fronteiras/cap-99-neuropsicologia.qmd` | ⬜ |
| 100 | Psicologia positiva | `capitulos/vol15-aplicada-fronteiras/cap-100-psicologia-positiva.qmd` | ⬜ |
| 101 | Psicologia jurídica e forense | `capitulos/vol15-aplicada-fronteiras/cap-101-juridica-forense.qmd` | ⬜ |
| 102 | Psicologia do esporte | `capitulos/vol15-aplicada-fronteiras/cap-102-esporte.qmd` | ⬜ |
| 103 | Psicologia, cultura e diversidade (transcultural) | `capitulos/vol15-aplicada-fronteiras/cap-103-cultura-diversidade.qmd` | ⬜ |
| 104 | A psicologia no Brasil (história, profissão, CFP/CRP, ética) | `capitulos/vol15-aplicada-fronteiras/cap-104-psicologia-no-brasil.qmd` | ⬜ |
| 105 | Tópicos contemporâneos e fronteiras (ciberpsicologia, IA, replicabilidade, ciência aberta) | `capitulos/vol15-aplicada-fronteiras/cap-105-topicos-contemporaneos.qmd` | ⬜ |
