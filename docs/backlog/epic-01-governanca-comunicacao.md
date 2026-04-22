# EPIC 1: Governança E Comunicação Do Projeto

Objetivo:
Criar canais, papéis e rotinas mínimas para coordenar alunos, professores e clientes durante o mês de construção do site.

Publico-alvo:
Equipe do projeto, alunos, professores responsáveis, Leandro e clientes/stakeholders.

Escopo inicial:
- Canal de comunicação no Slack.
- Definição de participantes do canal.
- Rotina de acompanhamento semanal.
- Registro de decisões relevantes em `docs/`.

Fora de escopo:
- Gestão completa de todos os canais institucionais do evento.

Métricas de sucesso:
- Equipe sabe onde comunicar dúvidas e decisões.
- Reuniões ou checkpoints têm responsáveis e pauta mínima.

Riscos e dependências:
- Participação dos clientes no Slack ainda precisa ser validada.

Status:
Em desenvolvimento

## User Stories

| US | Nome | Responsável | Prioridade | Estimativa | Status | Tasks |
| --- | --- | --- | --- | --- | --- | ---: |
| US 1.1 | Criar canal de comunicação no Slack | Coordenação (Paulo/Leandro) | Alta | P | Em desenvolvimento | 3 |
| US 1.2 | Definir rotina de acompanhamento | Coordenação (Paulo/Leandro) | Alta | P | A fazer | 1 |

<a id="us-11-criar-canal-de-comunicacao-no-slack"></a>

## US 1.1: Criar Canal De Comunicação No Slack

Como coordenador do projeto,
quero criar um canal no Slack para reunir alunos, professores e, se fizer sentido, clientes,
para centralizar comunicação, dúvidas, decisões e alinhamentos do site.

Contexto:
O projeto tem prazo de 1 mês, então a comunicação precisa ser rápida e rastreável.

Critérios de aceitação:
- Dado que o projeto começou, quando a equipe precisar alinhar decisões, então existe um canal oficial no Slack.
- Dado que o canal foi criado, quando os participantes acessam o Slack, então encontram alunos e professores responsáveis adicionados.
- Dado que há clientes no projeto, quando avaliamos a governança, então a necessidade de incluí-los no canal está registrada.

Prioridade:
Alta

Estimativa:
P

Dependências:
- Lista de alunos participantes.
- Confirmação sobre participação dos clientes no Slack.

Status:
Em desenvolvimento

### Tasks Da US 1.1

| Task | Resultado esperado | Status |
| --- | --- | --- |
| TASK 1.1.1: Criar canal no Slack | Canal oficial do projeto criado no Slack: `SBF`. | Concluído |
| TASK 1.1.2: Adicionar participantes ao canal | Alunos e professores responsáveis adicionados ao canal. | A fazer |
| TASK 1.1.3: Registrar decisão sobre clientes no Slack | Decisão documentada sobre clientes participarem ou não do canal. | A fazer |

Validação:
- Canal criado e acessível pela equipe.
- Lista de participantes conferida.
- Decisão sobre clientes encontrada na documentação do projeto.

<a id="us-12-definir-rotina-de-acompanhamento"></a>

## US 1.2: Definir Rotina De Acompanhamento

Como equipe do projeto,
quero ter uma rotina semanal de acompanhamento,
para garantir avanço dentro do prazo de 1 mês.

Contexto:
Sem uma cadência curta, o projeto corre risco de atrasar pesquisa, protótipo, validação e implementação.

Critérios de aceitação:
- Dado que a semana começou, quando a equipe verifica o projeto, então existe uma data ou horário de checkpoint.
- Dado que há bloqueios, quando o checkpoint acontece, então bloqueios e próximos passos são registrados.
- Dado que há decisões, quando elas são tomadas, então são consolidadas em `docs/`.

Prioridade:
Alta

Estimativa:
P

Dependências:
- Disponibilidade dos participantes principais.

Status:
Em desenvolvimento

### Tasks Da US 1.2

| Task | Resultado esperado | Status |
| --- | --- | --- |
| TASK 1.2.1: Definir checkpoint semanal | Dia, horário e formato do checkpoint definidos. | A fazer |

Validação:
- Rotina comunicada no Slack.
- Pauta mínima definida: andamento, bloqueios, decisões e próximos passos.
