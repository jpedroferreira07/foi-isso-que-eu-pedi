# Processo ScrumBan da equipe

## Equipe

| Papel | Pessoa |
| --- | --- |
| Product Owner (PO) | Giovanni |
| Scrum Master (SM) | Bernardo N. |
| Desenvolvedores (Devs) | Alexia, Vitor, Bernardo V. e João Pedro Ferreira Afonso |

## Visão do produto

| Pergunta | Resposta da equipe |
| --- | --- |
| A solução vai atender as necessidades de quem? | Estudantes e professores de escolas do estado do Rio de Janeiro sem conectividade ou com conexão de baixa qualidade. |
| Qual problema pretende solucionar? | A exclusão de milhões de estudantes brasileiros que vivem no Rio de Janeiro do aprendizado de como usar as diversas ferramentas de IA generativa. |
| Qual o objetivo da solução? | Dar uma oportunidade de aprendizagem dos fundamentos da Engenharia de Prompt Ética a estudantes e professores. |

## Quadro Kanban

O quadro foi mantido no Notion (acesso restrito ao grupo), com as colunas:

**Backlog → A Fazer → Fazendo → Feedback → Pronto** (uma coluna "Sprint Done" por sprint, para guardar o histórico de cada ciclo).

Cada sprint guarda, além das tarefas, os registros da **reunião de planejamento**, das **reuniões semanais**, da **revisão**, da **retrospectiva** e do **incremento** (os artefatos entregues). O resumo de cada uma está em [sprints.md](sprints.md).

### Limites de WIP

| Coluna | Limite |
| --- | --- |
| Backlog | sem limite |
| A Fazer | 8 cartões (só o que a Sprint Planning puxou) |
| Fazendo | 4 cartões (1 por pessoa) |
| Feedback | 3 cartões (revisão por outro membro, como pede a DoD) |
| Pronto | sem limite |

### Pontos e capacidade

- 1 ponto equivale a cerca de 1 hora de trabalho de uma pessoa.
- Capacidade de **36 pontos por sprint de 1 semana** (4 pessoas, cerca de 9 horas cada).
- A Sprint 2 teve **48 pontos**, porque durou 2 semanas (semana dos feriados de 12 e 15/10).

## Definição de Pronto (DoD)

Um item só está pronto se:

1. a tarefa foi executada;
2. foi revisada por alguém da equipe;
3. está documentada no Kanban;
4. atende aos critérios de aceite de "trabalho finalizado" da sprint.

Além disso, cada história do Sprint Backlog tem a própria DoD, com critérios de aceite específicos (ver [sprints.md](sprints.md)).

## Cerimônias

| Cerimônia | Como a equipe fez |
| --- | --- |
| Reunião de planejamento | No início de cada sprint: define o objetivo (Goal), puxa as histórias do backlog e registra responsável e DoD de cada uma. |
| Weekly | Reunião rápida (versão adaptada da daily) com o formato "fiz, estou fazendo, meu impedimento é". |
| Revisão | No fim da sprint: apresenta ao cliente (o professor) as histórias entregues e registra o feedback. |
| Retrospectiva | No fim da sprint, no formato Keep, Stop, Start. |
| Incremento | Os artefatos que cada sprint entregou (ver [README](../README.md)). |

## Como histórias, épicos e temas foram definidos

Orientação do professor na revisão da Sprint 1: começar pelas histórias de usuário no proto-backlog, usando os pedidos do cliente como fonte; listar as tarefas de cada história; e checar se cada uma cabe em **1 semana** (tamanho da sprint). Se precisar de 2 a 4 semanas, é um **épico**; se ocupar as 5 semanas do projeto, é um **tema**.

O resultado está em [roadmap-e-backlog.md](roadmap-e-backlog.md).
