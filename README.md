# Projeto: [Patton Decision Model](https://notebooklm.google.com/notebook/81a7fedc-cae0-46a9-bfdd-51240475a500) (PDM)

[Patton Decision Model](./assets/PDM.png)

## Proposta

### Visão Geral

Este projeto tem como objetivo explorar o potencial do **Google NotebookLM** como uma plataforma de construção de bases de conhecimento especializadas, utilizando como estudo de caso o General _George S. Patton Jr._, um dos comandantes militares mais influentes da Segunda Guerra Mundial.

Mais do que reunir informações históricas, a proposta consiste em organizar, estruturar e relacionar diferentes fontes de informação para permitir que a Inteligência Artificial compreenda os padrões de pensamento, filosofia militar, estilo de liderança e processo de tomada de decisão de Patton.

O objetivo final não é criar um chatbot que apenas responda perguntas sobre sua biografia, mas sim desenvolver uma base de conhecimento capaz de fundamentar respostas analíticas e cenários hipotéticos utilizando exclusivamente as evidências presentes nas fontes estudadas.

---

## Objetivos

### Objetivo Geral

Construir uma base de conhecimento especializada sobre _George S. Patton Jr._ utilizando o **NotebookLM**, engenharia de prompts para estruturar reconstruir seu modelo de raciocínio estratégico.

### Objetivos Específicos

> - Organizar fontes históricas confiáveis sobre George S. Patton.
> - Identificar padrões recorrentes em sua filosofia militar.
> - Mapear sua evolução como comandante durante a Segunda Guerra Mundial.
> - Compreender sua relação com aliados, subordinados e adversários.
> - Analisar decisões marcantes tomadas durante campanhas militares.
> - Desenvolver prompts capazes de explorar análises históricas profundas.
> - Validar o NotebookLM como ferramenta de aprendizagem ativa e organização do conhecimento.

---

## Curadoria de Fontes

As fontes serão selecionadas considerando diferentes perspectivas históricas.

A prioridade será dada a:

_Fontes primárias_

> - Relatórios militares
> - Correspondências
> - Diários
> - Discursos

_Fontes secundárias_

> - Biografias
> - Livros acadêmicos
> - Artigos históricos

_Fontes complementares_

> - Documentários
> - Entrevistas
> - Produções audiovisuais

As fontes serão utilizadas não apenas para responder perguntas factuais, mas para identificar padrões de comportamento e tomada de decisão.

---

## Framework de Engenharia de Prompt

### Introdução

Um dos objetivos deste projeto é demonstrar que a qualidade das respostas geradas por uma Inteligência Artificial depende diretamente da qualidade das instruções fornecidas.

Em vez de elaborar perguntas isoladas, foi desenvolvido um `Framework de Engenharia de Prompt` próprio para o **PDM**, permitindo que todas as interações com o NotebookLM sigam uma estrutura padronizada, reutilizável e progressivamente refinável.

Essa abordagem reduz ambiguidades, facilita a evolução dos prompts ao longo do projeto e torna o processo de pesquisa reproduzível para outros estudos históricos.

---

### Estrutura do Framework

Todo prompt desenvolvido neste projeto deverá seguir uma arquitetura composta por sete elementos.

ELEMENTOS
|---|
CONTEXTO
OBJETIVO
TAREFA
RESTRIÇÕES
FORMATO DE SAÍDA
CRITÉRIOS DE QUALIDADE
VALIDAÇÃO

Essa estrutura busca garantir clareza, contexto, objetividade e consistência nas respostas obtidas.

---

#### 1. Contexto

_Objetivo_

Definir claramente o cenário em que a análise será realizada.

O contexto informa ao modelo:

> - Em qual etapa do projeto estamos.
> - Qual dimensão do estudo será analisada.
> - Qual o propósito da interação.

_Exemplos_

- Construção da linha do tempo.
- Identificação do modelo cognitivo.
- Análise de campanhas militares.
- Extração de padrões comportamentais.
- Consolidação da filosofia militar.

---

#### 2. Objetivo

_Objetivo_

Explicar exatamente o que deverá ser descoberto ou produzido.

O objetivo deve responder:

> "Ao final desta resposta, qual conhecimento novo espero obter?"

_Boas práticas_

> - utilizar verbos objetivos;
> - solicitar apenas um objetivo principal por prompt;
> - evitar perguntas excessivamente amplas.

_Exemplos_

- Identificar padrões de liderança.
- Comparar decisões militares.
- Explicar mudanças de comportamento.
- Construir uma linha cronológica.
- Consolidar princípios estratégicos.

---

#### 3. Tarefa

_Objetivo_

Descrever exatamente o trabalho que deverá ser executado.

Enquanto o objetivo explica `por quê`, a tarefa explica `como`.

Sempre que possível, tarefas complexas deverão ser divididas em etapas menores.

_Exemplo_

Etapa 1

Identifique os acontecimentos relevantes.

Etapa 2

Explique cada acontecimento.

Etapa 3

Identifique padrões.

Etapa 4

Relacione esses padrões com decisões futuras.

---

#### 4. Restrições

_Objetivo_

Definir os limites da análise.

As restrições evitam respostas genéricas, extrapolações indevidas e interpretações incompatíveis com o propósito da pesquisa.

_Exemplos_

- Utilizar exclusivamente as informações presentes na base.
- Não assumir fatos sem evidências.
- Diferenciar fatos de inferências.
- Não preencher lacunas documentais com especulações.
- Informar explicitamente quando houver informações conflitantes.

---

#### 5. Formato de Saída

_Objetivo_

Padronizar todas as respostas produzidas durante o projeto.

Uma estrutura consistente facilita futuras consultas e comparações entre análises.

Dependendo da atividade, poderão ser utilizados:

> - listas;
> - tabelas;
> - linhas do tempo;
> - resumos estruturados;

Sempre que possível, respostas analíticas deverão separar:

> - Evidências;
> - Inferências;
> - Hipóteses fundamentadas.

---

#### 6. Critérios de Qualidade

Toda resposta deverá buscar responder não apenas `o que aconteceu`, mas também:

> - Por que aconteceu.
> - Quais fatores influenciaram a decisão.
> - Quais padrões esse evento revela.
> - Como esse padrão aparece em outros momentos da carreira.

Conclusões importantes somente deverão ser consolidadas quando houver recorrência suficiente em diferentes documentos ou períodos históricos.

---

#### 7. Validação

Antes de considerar uma resposta concluída, ela deverá ser analisada sob quatro perspectivas:

_Evidência_

`O que está explicitamente documentado?`

_Relação_

`Como essa informação se conecta com outros acontecimentos?`

_Padrão_

`Esse comportamento aparece em outros momentos da trajetória?`

_Aplicação_

`Como esse padrão pode contribuir para compreender decisões futuras ou responder cenários hipotéticos?`

### Benefícios do Framework

A utilização de uma estrutura padronizada oferece diversas vantagens durante o desenvolvimento do projeto.

> - Prompts mais claros e objetivos.
> - Maior consistência entre diferentes análises.
> - Facilidade para evoluir e reutilizar prompts.
> - Melhor rastreabilidade das respostas.
> - Redução de ambiguidades.
> - Organização do processo de pesquisa.
> - Aplicação prática dos conceitos de Engenharia de Prompt estudados na DIO.

Mais do que produzir respostas, este Framework busca transformar o processo de interação com a IA em uma metodologia estruturada de investigação histórica, permitindo que a construção do conhecimento seja progressiva, transparente e fundamentada nas fontes disponíveis.

### Critério de Qualidade das Respostas

As respostas deverão diferenciar claramente três níveis de informação:

_Evidências_

`Informações explicitamente presentes nas fontes utilizadas.`

_Inferências_

`Conclusões obtidas pela relação entre diferentes evidências.`

_Hipóteses Fundamentadas_

`Possíveis interpretações construídas a partir dos padrões identificados, deixando explícito quando não houver confirmação documental.`

---

## Resultado Esperado

Ao final do projeto espera-se obter uma base de conhecimento especializada capaz de:

> - Responder perguntas históricas complexas.
> - Explicar o contexto das decisões tomadas por Patton.
> - Identificar padrões de liderança e pensamento estratégico.
> - Fundamentar cenários hipotéticos utilizando evidências históricas.
> - Demonstrar o uso do NotebookLM como ferramenta de aprendizagem ativa e organização do conhecimento.

Mais do que um repositório de informações, este projeto busca demonstrar como uma Inteligência Artificial pode ser orientada a reconstruir modelos de raciocínio histórico a partir de uma curadoria criteriosa de fontes confiáveis.

---

# Desenvolvimento do Projeto

## Prompt Mestre da Base de Conhecimento

Como etapa inicial do projeto, foi desenvolvido um **Root Prompt** responsável por estabelecer a identidade, a missão e os princípios de funcionamento da base de conhecimento antes da inserção das fontes históricas.

Seu papel não é substituir os _guardrails_ nativos do NotebookLM, mas orientar a forma como o conhecimento deve ser organizado, interpretado e conectado ao longo da pesquisa.

O Root Prompt define o foco analítico da base, incentivando a construção progressiva de um perfil histórico e estratégico de George S. Patton Jr., priorizando relações entre acontecimentos, identificação de padrões recorrentes e contextualização cronológica de sua trajetória.

Além disso, estabelece um padrão de qualidade para todas as respostas, orientando a IA a validar suas análises sob diferentes perspectivas (Evidência, Relação, Padrão e Aplicação) e a distinguir claramente fatos documentados, inferências e hipóteses fundamentadas.

Dessa forma, cada nova interação contribui para expandir uma base de conhecimento consistente, estruturada e progressivamente refinada, transformando documentos históricos em um modelo analítico capaz de apoiar estudos aprofundados e cenários hipotéticos fundamentados.
