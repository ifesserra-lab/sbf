# Integrações Do Projeto

## Slack

Canal oficial:
`SBF`

## Notificações GitHub Para Slack

O repositório possui um workflow em `.github/workflows/slack-notifications.yml` para notificar o canal Slack `SBF` quando:

- houver push/commit em qualquer branch;
- uma issue for aberta;
- uma issue for reaberta;
- uma issue for fechada.

## Configuração Necessária

Para ativar as notificações, crie um Incoming Webhook no Slack apontando para o canal `SBF` e salve a URL como secret do repositório:

```bash
gh secret set SLACK_WEBHOOK_URL --repo ifesserra-lab/sbf
```

O workflow foi preparado para não falhar se o secret ainda não estiver configurado. Nesse caso, ele apenas pula o envio da notificação.

## Eventos Monitorados

| Evento GitHub | Notificação enviada |
| --- | --- |
| `push` | Resumo com repositório, branch, autor, quantidade de commits e link de comparação. |
| `issues.opened` | Aviso de issue aberta com número, título e link. |
| `issues.reopened` | Aviso de issue reaberta com número, título e link. |
| `issues.closed` | Aviso de issue fechada com número, título e link. |
