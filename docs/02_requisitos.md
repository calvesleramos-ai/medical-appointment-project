# Requisitos do Sistema

## Requisitos Funcionais

### RF01 – Cadastro de Usuários
O sistema deve permitir o cadastro de pacientes e médicos.

### RF02 – Autenticação
O sistema deve permitir login seguro utilizando e-mail e senha.

### RF03 – Gestão da Agenda Médica
O médico deve poder definir seus horários disponíveis para atendimento.

### RF04 – Agendamento de Consultas
O paciente deve conseguir visualizar horários disponíveis e agendar consultas.

### RF05 – Cancelamento de Consultas
O sistema deve permitir o cancelamento de consultas respeitando as regras de negócio.

### RF06 – Notificações
O sistema deve enviar notificações sobre confirmações, alterações e cancelamentos.

### RF07 – Integração com o Sistema de Prontuário
Após a confirmação da consulta, o sistema deve registrar as informações no sistema externo de prontuário eletrônico.

---

# Requisitos Não Funcionais

### RNF01 – Segurança
Os dados devem ser protegidos conforme a LGPD.

### RNF02 – Disponibilidade
O sistema deve possuir alta disponibilidade durante o horário de atendimento.

### RNF03 – Desempenho
As operações de agendamento devem ser respondidas em até 3 segundos em condições normais.

### RNF04 – Escalabilidade
A arquitetura deve permitir o aumento da quantidade de usuários sem perda significativa de desempenho.

### RNF05 – Confiabilidade
Falhas na integração com o sistema externo devem ser registradas em log e tratadas automaticamente sempre que possível.