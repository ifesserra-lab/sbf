# EPIC 9: Suporte Ao Cliente E Sistema De Tickets

Objetivo:
Pesquisar e implementar uma ferramenta de tickets para o suporte com o cliente do site.

Publico-alvo:
Participantes do evento e usuários do site com dúvidas.

Escopo inicial:
- Pesquisa de mercado de ferramentas de helpdesk/tickets.
- Definição da ferramenta ideal considerando custos e necessidades.
- Integração ou implementação da ferramenta escolhida no site.

Fora de escopo:
- Atendimento humano via chat em tempo real 24/7.

Métricas de sucesso:
- Ferramenta de tickets escolhida e aprovada.
- Sistema de tickets integrado e funcional na landing page.

Riscos e dependências:
- Custos das ferramentas de terceiros.
- Aprovação de orçamento pelos stakeholders.

Status:
A fazer

## User Stories

| US | Nome | Responsável | Prioridade | Estimativa | Status | Tasks |
| --- | --- | --- | --- | --- | --- | ---: |
| US 9.1 | Pesquisar ferramentas de tickets | Equipe de produto | Alta | P | A fazer | 2 |
| US 9.2 | Implementar ferramenta de tickets no site | Equipe técnica | Alta | M | A fazer | 2 |

<a id="us-91-pesquisar-ferramentas-de-tickets"></a>

## US 9.1: Pesquisar Ferramentas De Tickets

Como equipe de produto,
quero pesquisar opções de ferramentas de tickets,
para escolher a melhor solução de suporte para o site.

Contexto:
Há uma demanda para profissionalizar o atendimento aos usuários do site, utilizando uma ferramenta de tickets. O primeiro passo é entender o que o mercado oferece e o que se adequa ao orçamento e necessidades do SBF.

Critérios de aceitação:
- Dado que a pesquisa iniciou, quando concluída, então deve apresentar ao menos 2 opções viáveis com prós, contras e preços.
- Dado que as opções foram apresentadas, quando avaliadas, então uma delas deve ser formalmente escolhida.

Prioridade:
Alta

Estimativa:
P

Dependências:
- Nenhuma.

Status:
A fazer

### Tasks Da US 9.1

| Task | Resultado esperado | Status |
| --- | --- | --- |
| TASK 9.1.1: Levantar opções de mercado e custos | Documento com as opções pesquisadas. | A fazer |
| TASK 9.1.2: Definir ferramenta a ser utilizada | Ferramenta oficialmente aprovada. | A fazer |

Validação:
- Aprovação da ferramenta pela coordenação/stakeholders.

<a id="us-92-implementar-ferramenta-de-tickets-no-site"></a>

## US 9.2: Implementar Ferramenta De Tickets No Site

Como usuário do site,
quero poder abrir um ticket de suporte,
para resolver dúvidas ou reportar problemas.

Contexto:
Após a escolha da ferramenta de suporte, é necessário integrá-la ao site, geralmente via widget, link ou formulário de contato, para que o usuário final possa abrir tickets diretamente.

Critérios de aceitação:
- Dado que o site está no ar, quando o usuário precisar de ajuda, então haverá um meio claro de abrir um ticket (ex: botão ou formulário).
- Dado que um ticket foi enviado pelo site, quando verificado no painel da ferramenta, então ele deve aparecer corretamente registrado.

Prioridade:
Alta

Estimativa:
M

Dependências:
- Conclusão da US 9.1 (ferramenta escolhida).

Status:
A fazer

### Tasks Da US 9.2

| Task | Resultado esperado | Status |
| --- | --- | --- |
| TASK 9.2.1: Configurar a ferramenta e obter código de integração | Conta configurada e chaves/códigos de integração gerados. | A fazer |
| TASK 9.2.2: Adicionar a integração no código do site | Widget ou formulário funcionando no frontend. | A fazer |

Validação:
- Teste end-to-end simulando a abertura de um ticket por um usuário no site.
