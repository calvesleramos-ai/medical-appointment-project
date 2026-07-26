# Estratégias de Resposta aos Riscos

## Objetivo

Definir estratégias de resposta para os principais riscos identificados no projeto de desenvolvimento do aplicativo móvel de agendamento de consultas médicas.

As estratégias foram definidas considerando o impacto dos riscos, a criticidade da integração com o sistema externo de prontuário e a capacidade atual da equipe.

---

# R01 — Instabilidade da API do Sistema de Prontuário

## Estratégia de Resposta

**Mitigar**

## Justificativa

A integração com o sistema externo é crítica para a entrega do projeto. Como a equipe não possui controle total sobre a API de terceiros, não é possível eliminar completamente o risco.

A estratégia escolhida busca reduzir o impacto da instabilidade e permitir que o desenvolvimento continue mesmo em períodos de indisponibilidade.

## Ações Associadas

- Criar uma Mock API para testes e desenvolvimento.
- Solicitar documentação atualizada ao fornecedor.
- Implementar logs para identificação de falhas.
- Criar mecanismos de retry para chamadas que apresentem erro temporário.
- Monitorar disponibilidade e tempo de resposta da integração.

---

# R02 — Alterações Frequentes nos Requisitos

## Estratégia de Resposta

**Mitigar**

## Justificativa

As mudanças solicitadas pelos stakeholders fazem parte da evolução do produto, porém alterações sem controle podem comprometer prazo e qualidade.

A estratégia busca estabelecer um processo formal para avaliação e priorização das mudanças.

## Ações Associadas

- Registrar solicitações de alteração.
- Realizar análise de impacto antes da implementação.
- Avaliar impacto em prazo, custo e esforço da equipe.
- Atualizar o backlog do produto.
- Validar prioridades com stakeholders.

---

# R03 — Sobrecarga da Equipe de Desenvolvimento

## Estratégia de Resposta

**Mitigar**

## Justificativa

A equipe possui quatro desenvolvedores e um tester. O aumento da demanda pode comprometer a qualidade das entregas e gerar atrasos.

A mitigação busca equilibrar capacidade da equipe e volume de trabalho.

## Ações Associadas

- Revisar estimativas das tarefas.
- Repriorizar funcionalidades de maior valor.
- Dividir entregas maiores em partes menores.
- Acompanhar capacidade da equipe em cada sprint.
- Identificar antecipadamente bloqueios.

---

# R04 — Dependência Crítica do Sistema Externo

## Estratégia de Resposta

**Mitigar e Aceitar**

## Justificativa

A integração com o prontuário eletrônico é necessária para o funcionamento completo do sistema, portanto não pode ser removida.

Como existe dependência de um fornecedor externo, parte do risco precisa ser aceita e monitorada.

## Ações Associadas

- Definir acordos de comunicação com o fornecedor.
- Estabelecer acompanhamento periódico da integração.
- Criar plano de contingência.
- Evitar dependência direta durante desenvolvimento utilizando ambientes simulados.

---

# R05 — Defeitos Identificados Apenas Próximos da Entrega

## Estratégia de Resposta

**Mitigar**

## Justificativa

A identificação tardia de problemas pode gerar retrabalho e comprometer o cronograma.

A estratégia busca aumentar a qualidade desde as primeiras etapas do desenvolvimento.

## Ações Associadas

- Realizar testes contínuos durante as sprints.
- Envolver o tester desde o planejamento.
- Criar critérios de aceite para cada funcionalidade.
- Automatizar testes quando aplicável.

---

# Conclusão

As estratégias definidas priorizam a redução dos riscos mais críticos para o projeto, principalmente aqueles relacionados à integração com o sistema externo e às mudanças de escopo.

A abordagem adotada busca aumentar a previsibilidade das entregas, melhorar a comunicação entre equipes e garantir maior qualidade no produto final.