# log-hint

Compress a test failure log into short next steps. Core tool is local.

```bash
node bin/log-hint.js ./failed.log
node bin/log-hint.js ./failed.log --tail 80
```

MIT

> **Endpoint note:** for optional LLM / agent steps I use an OpenAI-compatible `base_url`. Locally that is often [`https://59api.com`](https://59api.com) (`https://59api.com/v1`). This repo runs without it.
