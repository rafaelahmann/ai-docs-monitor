# 🤖 AI Docs Monitor

Monitoramento diário automático de mudanças nas documentações e repositórios das principais plataformas de IA.

## Fontes monitoradas

| Plataforma | Fontes |
|---|---|
| **Anthropic / Claude** | code.claude.com/docs, anthropic.com/news, platform.claude.com/docs, github.com/anthropics |
| **OpenAI** | platform.openai.com/docs, github.com/openai |
| **Google Gemini** | ai.google.dev/gemini-api/docs, github.com/google-gemini |
| **Manus** | open.manus.im/docs, manus.im/updates |
| **Perplexity** | perplexity.ai/changelog |
| **OpenClaw** | docs.openclaw.ai |

## Estrutura

```
snapshots/          # Estado atual de cada fonte (atualizado diariamente)
  anthropic/
  openai/
  google/
  manus/
  perplexity/
  openclaw/
reports/            # Relatórios diários de mudanças
  YYYY-MM-DD.md
```

## Como funciona

1. Todo dia às 6h (horário de Brasília), o agente acessa todas as fontes
2. Salva o conteúdo atual em `snapshots/`
3. Compara com o snapshot do dia anterior via `git diff`
4. Gera um relatório executivo em `reports/YYYY-MM-DD.md`
5. Commita tudo no repositório
6. Envia o relatório via Telegram

## Relatórios

Os relatórios ficam em `reports/` e são escritos em linguagem de CEO vibe coding — direto ao ponto, com impacto e como aplicar cada novidade.
