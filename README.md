# Enterprise Architect Course

Repositório oficial de diretivas, currículos, roteiros, templates, decisões, prompts e materiais de produção da trilha **Enterprise Architect em português**.

Este repositório funciona como a fonte da verdade editorial, pedagógica e estratégica do empreendimento educacional.

---

## Propósito

Centralizar a construção de uma trilha educacional prática sobre **Enterprise Architecture**, voltada para profissionais de tecnologia que desejam evoluir de uma visão técnica de sistemas para uma visão estratégica de arquitetura corporativa.

A trilha busca conectar:

- negócio;
- aplicações;
- dados;
- integrações;
- cloud;
- segurança;
- governança;
- modernização;
- tomada de decisão arquitetural;
- comunicação executiva.

---

## Visão

Criar uma formação prática, madura e acessível em português sobre **Enterprise Architecture**, com foco em aplicação real de mercado.

A proposta não é criar apenas um curso teórico sobre frameworks. O objetivo é ajudar profissionais técnicos a desenvolverem uma visão arquitetural corporativa, capaz de apoiar decisões melhores em organizações reais.

---

## Princípio central

> Arquitetura corporativa não é apenas desenhar sistemas.  
> É ajudar a organização a tomar melhores decisões de tecnologia em alinhamento com estratégia, risco, custo, evolução e valor de negócio.

---

## Trilha educacional

A trilha será inicialmente composta por três cursos progressivos.

### 1. Enterprise Architect: Fundamentos de Arquitetura Corporativa

Objetivo: ensinar o aluno a **pensar como Enterprise Architect**.

Este curso apresenta os conceitos fundamentais de arquitetura corporativa, o papel do Enterprise Architect, os principais domínios da disciplina e os primeiros artefatos usados para conectar negócio e tecnologia.

Foco principal:

- fundamentos de Enterprise Architecture;
- diferença entre Enterprise Architect, Solution Architect, Software Architect e Cloud Architect;
- negócio e capacidades;
- visão introdutória de aplicações, dados, integrações e tecnologia;
- princípios arquiteturais;
- roadmap inicial;
- primeiro case prático.

---

### 2. Enterprise Architect: Artefatos, Diagnóstico e Roadmaps

Objetivo: ensinar o aluno a **trabalhar como Enterprise Architect**.

Este curso aprofunda a aplicação prática da arquitetura corporativa em organizações reais, usando assessments, mapas, matrizes, diagnósticos, arquitetura alvo e roadmaps.

Foco principal:

- assessment arquitetural;
- entrevistas com stakeholders;
- Business Capability Mapping;
- Application Portfolio Management;
- matriz TIME;
- mapas de dados críticos;
- mapas de integração;
- arquitetura alvo;
- arquitetura de transição;
- ADRs;
- governança leve;
- roadmap de modernização.

---

### 3. Enterprise Architect Avançado: Estratégia e Transformação

Objetivo: ensinar o aluno a **liderar como Enterprise Architect**.

Este curso prepara o aluno para atuar em decisões estratégicas envolvendo portfólio, investimento, cloud, plataformas, dados, segurança, governança, modernização e transformação corporativa.

Foco principal:

- Enterprise Architecture como função estratégica;
- governança federada;
- operating model de arquitetura;
- portfólio e investimento;
- business case arquitetural;
- cloud strategy;
- platform strategy;
- data strategy;
- security by design;
- compliance;
- FinOps;
- modernização em escala;
- comunicação executiva.

---

## Público-alvo

A trilha é voltada para:

- desenvolvedores plenos e sêniores;
- tech leads;
- arquitetos de software;
- arquitetos de soluções;
- engenheiros cloud;
- engenheiros de plataforma;
- consultores de tecnologia;
- analistas de sistemas experientes;
- gestores técnicos;
- profissionais em transição para Enterprise Architecture.

---

## Estrutura do repositório

```txt
enterprise-architect-course/
│
├── README.md
├── AGENTS.md
├── LICENSE.md
├── CHANGELOG.md
├── CONTRIBUTING.md
│
├── docs/
│   ├── 00-visao/
│   │   ├── manifesto.md
│   │   ├── proposta-de-valor.md
│   │   ├── publico-alvo.md
│   │   ├── posicionamento.md
│   │   └── roadmap-produto.md
│   │
│   ├── 01-diretivas/
│   │   ├── diretiva-editorial.md
│   │   ├── diretiva-pedagogica.md
│   │   ├── diretiva-comercial.md
│   │   ├── diretiva-visual.md
│   │   ├── diretiva-linguagem.md
│   │   ├── diretiva-qualidade.md
│   │   └── diretiva-uso-ia.md
│   │
│   ├── 02-trilha/
│   │   ├── visao-geral-trilha.md
│   │   ├── curso-01-fundamentos.md
│   │   ├── curso-02-intermediario.md
│   │   ├── curso-03-avancado.md
│   │   └── matriz-progressao-competencias.md
│   │
│   ├── 03-curriculos/
│   │   ├── fundamentos/
│   │   │   ├── editorial.md
│   │   │   ├── ementa.md
│   │   │   ├── modulos.md
│   │   │   ├── projeto-final.md
│   │   │   └── pagina-udemy.md
│   │   │
│   │   ├── intermediario/
│   │   │   ├── editorial.md
│   │   │   ├── ementa.md
│   │   │   ├── modulos.md
│   │   │   ├── projeto-final.md
│   │   │   └── pagina-udemy.md
│   │   │
│   │   └── avancado/
│   │       ├── editorial.md
│   │       ├── ementa.md
│   │       ├── modulos.md
│   │       ├── projeto-final.md
│   │       └── pagina-udemy.md
│   │
│   ├── 04-roteiros/
│   │   ├── fundamentos/
│   │   ├── intermediario/
│   │   └── avancado/
│   │
│   ├── 05-templates/
│   │   ├── aulas/
│   │   │   ├── template-roteiro-aula.md
│   │   │   ├── template-slide-aula.md
│   │   │   └── template-checklist-aula.md
│   │   │
│   │   ├── arquitetura/
│   │   │   ├── template-capability-map.md
│   │   │   ├── template-application-portfolio.md
│   │   │   ├── template-adr.md
│   │   │   ├── template-roadmap-arquitetural.md
│   │   │   └── template-architecture-review.md
│   │   │
│   │   └── operacao/
│   │       ├── template-briefing-modulo.md
│   │       ├── template-backlog-task.md
│   │       └── template-decisao-editorial.md
│   │
│   ├── 06-cases/
│   │   ├── atlas-retail-bank/
│   │   │   ├── contexto.md
│   │   │   ├── dores.md
│   │   │   ├── capacidades.md
│   │   │   ├── aplicacoes.md
│   │   │   ├── riscos.md
│   │   │   └── entregavel-final.md
│   │   │
│   │   └── README.md
│   │
│   ├── 07-backlog/
│   │   ├── epicos.md
│   │   ├── user-stories.md
│   │   ├── tasks.md
│   │   └── kanban.md
│   │
│   ├── 08-decisoes/
│   │   ├── ADR-0001-estrutura-trilha.md
│   │   ├── ADR-0002-repositorio-docs-as-code.md
│   │   └── README.md
│   │
│   └── 09-prompts/
│       ├── prompt-criacao-roteiro-aula.md
│       ├── prompt-revisao-editorial.md
│       ├── prompt-geracao-slides.md
│       ├── prompt-criacao-quiz.md
│       ├── prompt-criacao-template.md
│       └── prompt-qa-conteudo.md
│
├── assets/
│   ├── brand/
│   │   ├── paleta.md
│   │   ├── tipografia.md
│   │   └── referencias-visuais.md
│   │
│   ├── imagens/
│   ├── diagramas/
│   └── thumbnails/
│
├── production/
│   ├── checklist-publicacao-udemy.md
│   ├── checklist-gravacao.md
│   ├── checklist-audio-video.md
│   ├── checklist-revisao-conteudo.md
│   └── plano-lancamento.md
│
└── scripts/
    └── README.md
```

---

## Diretórios principais

### `docs/00-visao/`

Contém documentos estratégicos do empreendimento.

Exemplos:

* manifesto;
* proposta de valor;
* público-alvo;
* posicionamento;
* roadmap do produto educacional.

---

### `docs/01-diretivas/`

Contém as regras editoriais, pedagógicas, comerciais, visuais e operacionais da trilha.

Esses documentos orientam a criação de todos os cursos e materiais.

---

### `docs/02-trilha/`

Contém a visão geral da trilha e a separação entre os níveis:

* Fundamentos;
* Intermediário;
* Avançado.

Também contém a matriz de progressão de competências.

---

### `docs/03-curriculos/`

Contém o currículo detalhado de cada curso.

Cada curso deve possuir, no mínimo:

* editorial;
* ementa;
* módulos;
* projeto final;
* página preliminar da Udemy.

---

### `docs/04-roteiros/`

Contém os roteiros das aulas.

Cada roteiro deve seguir o padrão definido em `AGENTS.md` e nas diretivas pedagógicas.

---

### `docs/05-templates/`

Contém templates usados na produção do curso e nas atividades dos alunos.

Os templates podem ser divididos em:

* templates de aula;
* templates de arquitetura;
* templates de operação.

---

### `docs/06-cases/`

Contém os estudos de caso da trilha.

O primeiro case será:

```txt
Atlas Retail Bank
```

Esse case será usado inicialmente no curso Fundamentos.

---

### `docs/07-backlog/`

Contém o backlog do empreendimento, incluindo:

* épicos;
* user stories;
* tasks;
* kanban textual.

---

### `docs/08-decisoes/`

Contém decisões arquiteturais, editoriais, pedagógicas e estratégicas no formato ADR.

Exemplos:

* decisão sobre divisão da trilha;
* decisão sobre uso de docs-as-code;
* decisão sobre projeto prático;
* decisão sobre posicionamento comercial.

---

### `docs/09-prompts/`

Contém prompts padronizados para apoiar tarefas com IA.

Exemplos:

* criação de roteiro de aula;
* revisão editorial;
* geração de slides;
* criação de quizzes;
* criação de templates;
* QA de conteúdo.

---

### `assets/`

Contém materiais visuais, referências de marca, thumbnails, diagramas e elementos gráficos.

Arquivos pesados, como vídeos brutos e gravações, não devem ser versionados neste repositório.

---

### `production/`

Contém checklists e documentos operacionais para produção e publicação do curso.

Exemplos:

* checklist de gravação;
* checklist de áudio e vídeo;
* checklist de revisão;
* checklist de publicação na Udemy;
* plano de lançamento.

---

### `scripts/`

Reservado para automações futuras.

Exemplos possíveis:

* geração de índice;
* validação de links;
* exportação de documentos;
* geração de pacotes de templates;
* conversão de Markdown para PDF.

---

## Status atual

Fase atual:

```txt
MVP editorial e estruturação do repositório
```

Prioridades atuais:

1. Consolidar as diretivas do empreendimento.
2. Fechar a estrutura da trilha Fundamentos, Intermediário e Avançado.
3. Detalhar o currículo do curso Fundamentos.
4. Criar o case prático Atlas Retail Bank.
5. Criar os templates mínimos do curso Fundamentos.
6. Criar os primeiros roteiros de aula.
7. Preparar a página preliminar da Udemy.

---

## Princípios de conteúdo

Todo conteúdo produzido neste repositório deve seguir os princípios abaixo.

### Clareza antes de sofisticação

O conteúdo deve ser claro, progressivo e compreensível.

Jargões técnicos podem ser usados, mas devem ser explicados quando aparecerem pela primeira vez.

---

### Aplicação prática antes de teoria abstrata

Toda explicação conceitual deve estar conectada a um problema real, exemplo de mercado, artefato ou decisão arquitetural.

---

### Frameworks são ferramentas, não o centro da narrativa

TOGAF, ArchiMate, Zachman, BIAN e outros modelos podem ser abordados, mas não devem transformar a trilha em conteúdo burocrático ou excessivamente acadêmico.

---

### Arquitetura é decisão

A trilha deve reforçar que arquitetura não é apenas documentação ou desenho.

Arquitetura envolve escolhas sob restrição, considerando:

* valor;
* risco;
* custo;
* governança;
* segurança;
* operação;
* evolução;
* experiência;
* capacidade de execução.

---

### Negócio e tecnologia devem caminhar juntos

Sempre que possível, os conteúdos devem conectar:

* objetivo de negócio;
* capacidade de negócio;
* aplicação;
* dado;
* integração;
* tecnologia;
* risco;
* custo;
* governança;
* decisão arquitetural.

---

### Conteúdo em português do Brasil

Todo conteúdo final deve ser produzido em português do Brasil.

Termos técnicos amplamente utilizados em inglês podem ser mantidos quando fizer sentido, desde que contextualizados.

---

## Padrão de versionamento

Este repositório utiliza Git para versionamento dos artefatos.

### Branch principal

```txt
main
```

A branch `main` representa a versão estável dos documentos.

### Branches de trabalho

Sugestões de nomes:

```txt
feature/diretivas-iniciais
feature/curso-fundamentos
feature/case-atlas-retail-bank
feature/templates-fundamentos
feature/roteiros-modulo-01
```

### Commits

Os commits devem ser claros, preferencialmente em inglês.

Exemplos:

```txt
chore: initialize repository structure
docs: add editorial directive
docs: add pedagogical directive
docs: define enterprise architect learning path
docs: add foundations course outline
docs: add atlas retail bank case context
docs: add architecture decision record template
```

---

## Convenções de escrita

### Idioma

Português do Brasil para conteúdo final do curso.

Inglês pode ser usado em:

* nomes de branches;
* mensagens de commit;
* termos técnicos consolidados;
* nomes de arquivos quando fizer sentido.

---

### Nomes de arquivos

Usar letras minúsculas, sem acentos e com hífens.

Exemplos:

```txt
diretiva-editorial.md
curso-01-fundamentos.md
template-roadmap-arquitetural.md
prompt-criacao-roteiro-aula.md
```

---

### Formato dos documentos

Preferencialmente Markdown.

Usar títulos hierárquicos claros:

```md
# Título principal

## Seção

### Subseção
```

---

## Definition of Done

### Uma diretiva está pronta quando:

* possui objetivo claro;
* define regras aplicáveis;
* evita ambiguidades relevantes;
* está alinhada ao posicionamento da trilha;
* pode orientar criação e revisão de conteúdo.

---

### Um currículo está pronto quando:

* possui público-alvo definido;
* possui promessa clara;
* possui módulos organizados;
* possui aulas propostas;
* possui projeto prático;
* possui entregáveis;
* está alinhado ao nível correto da trilha.

---

### Uma aula está pronta quando:

* possui objetivo claro;
* resolve um problema específico;
* explica conceitos principais;
* inclui exemplo prático;
* possui síntese final;
* conecta com a próxima aula ou módulo;
* pode ser convertida em slides sem reestruturação profunda.

---

### Um curso está pronto para produção quando:

* possui editorial;
* possui ementa;
* possui módulos fechados;
* possui roteiros das aulas;
* possui projeto final;
* possui materiais complementares;
* possui página preliminar da Udemy;
* possui checklist de gravação;
* passou por revisão editorial e pedagógica.

---

## Uso de IA

Ferramentas de IA podem ser usadas para apoiar:

* brainstorming;
* criação de roteiros;
* revisão editorial;
* geração de quizzes;
* criação de templates;
* revisão de consistência;
* preparação de materiais complementares.

Entretanto, todo conteúdo gerado por IA deve passar por revisão humana antes de ser publicado.

A IA não deve substituir julgamento técnico, pedagógico, editorial ou estratégico.

---

## O que não versionar neste repositório

Evitar versionar:

* vídeos brutos;
* áudios brutos;
* exports pesados;
* arquivos temporários;
* materiais privados;
* credenciais;
* arquivos `.env`;
* gravações locais;
* arquivos proprietários sem autorização.

Esses materiais devem ser armazenados em local apropriado fora do Git, como Google Drive, OneDrive, Dropbox, storage privado ou solução equivalente.

---

## Roadmap inicial

### Fase 1 — Estruturação

* Criar estrutura base do repositório.
* Criar README.
* Criar AGENTS.md.
* Criar diretivas iniciais.
* Criar ADRs iniciais.
* Criar backlog inicial.

### Fase 2 — Trilha

* Consolidar visão geral da trilha.
* Definir curso Fundamentos.
* Definir curso Intermediário.
* Definir curso Avançado.
* Criar matriz de progressão de competências.

### Fase 3 — Curso Fundamentos

* Criar editorial do curso.
* Criar ementa.
* Criar módulos.
* Criar projeto final.
* Criar página preliminar da Udemy.
* Criar templates mínimos.
* Criar roteiros das aulas.

### Fase 4 — Produção

* Criar slides.
* Gravar aulas.
* Revisar áudio e vídeo.
* Criar materiais complementares.
* Preparar publicação na Udemy.
* Publicar MVP.

### Fase 5 — Evolução

* Coletar feedback dos alunos.
* Ajustar curso Fundamentos.
* Planejar curso Intermediário.
* Planejar curso Avançado.
* Expandir materiais, cases e templates.

---

## Licença

Este repositório contém propriedade intelectual educacional em desenvolvimento.

O conteúdo não deve ser copiado, redistribuído, publicado ou utilizado comercialmente sem autorização.

---

## Observação final

Este repositório deve preservar a visão de longo prazo do empreendimento:

> Construir uma formação de Enterprise Architecture prática, respeitada, acessível e aplicável ao mercado brasileiro e lusófono.
