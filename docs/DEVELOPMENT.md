# Desenvolvimento do Projeto

[README.md](/README.md)

## Prompt Mestre da Base de Conhecimento (Root Prompt)

Como etapa inicial do projeto, foi desenvolvido um [Root Prompt](./ROOT%20PROMPT.md) responsável por estabelecer a identidade, a missão e os princípios de funcionamento da base de conhecimento antes da inserção das fontes históricas.

Seu papel não é substituir os _guardrails_ nativos do NotebookLM, mas orientar a forma como o conhecimento deve ser organizado, interpretado e conectado ao longo da pesquisa.

O _Root Prompt_ define o foco analítico da base, incentivando a construção progressiva de um perfil histórico e estratégico de George S. Patton Jr., priorizando relações entre acontecimentos, identificação de padrões recorrentes e contextualização cronológica de sua trajetória.

Além disso, estabelece um padrão de qualidade para todas as respostas, orientando a IA a validar suas análises sob diferentes perspectivas (Evidência, Relação, Padrão e Aplicação) e a distinguir claramente fatos documentados, inferências e hipóteses fundamentadas.

Dessa forma, cada nova interação contribui para expandir uma base de conhecimento consistente, estruturada e progressivamente refinada, transformando documentos históricos em um modelo analítico capaz de apoiar estudos aprofundados e cenários hipotéticos fundamentados.

---

## Curadoria de Fontes

Especifiquei cada arquivo utilizado na coleta de fontes e alimentação da IA no arquivo [FONTS.md](./FONTS.md)

## Estruturação dos Prompts

Seguindo a estrutura desenvolvida na _"Framework"_, estruturei uma base de prompt que pode ser quase inteiramente replicável, alterando apenas o objetivo, tarefa e restrições.
Deixei o histórico de aplicação dos prompts no arquivo [PROMPTS.md](./PROMPTS.md)
