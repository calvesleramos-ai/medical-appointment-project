# Análise de Riscos do Projeto

## Objetivo

Identificar os principais riscos do projeto, avaliar seus impactos e definir estratégias para reduzir seus efeitos durante o desenvolvimento.

## Matriz de Riscos

| ID | Risco | Probabilidade | Impacto | Prioridade | Estratégia |
|----|--------|---------------|---------|------------|------------|
| R01 | Instabilidade da API do sistema de prontuário | Alta | Alto | Crítica | Criar ambiente de testes utilizando Mock API, registrar logs e implementar mecanismo de retry. |
| R02 | Alterações frequentes nos requisitos | Alta | Alto | Crítica | Formalizar processo de gestão de mudanças e realizar refinamentos semanais com stakeholders. |
| R03 | Sobrecarga da equipe de desenvolvimento | Média | Alto | Alta | Repriorizar backlog, redistribuir atividades e revisar estimativas das próximas sprints. |
| R04 | Atraso na entrega devido à dependência externa | Alta | Alto | Crítica | Trabalhar com integração desacoplada e realizar testes utilizando serviços simulados. |
| R05 | Defeitos identificados apenas no final da sprint | Média | Médio | Média | Executar testes contínuos durante o desenvolvimento e antecipar validações do tester. |

---

## Plano de Resposta

### API Externa

Como a integração é crítica, o desenvolvimento das demais funcionalidades não deve depender exclusivamente da disponibilidade da API externa. Sempre que possível será utilizada uma Mock API para permitir a continuidade dos trabalhos.

### Gestão de Mudanças

Toda solicitação de alteração deverá passar por análise de impacto antes de ser incluída no backlog.

### Capacidade da Equipe

Considerando uma equipe formada por quatro desenvolvedores e um tester, novas demandas serão priorizadas conforme valor de negócio, evitando sobrecarga e redução da qualidade das entregas.

### Monitoramento

Os riscos serão revisados ao final de cada Sprint Review e durante o Sprint Planning seguinte.