# dup-scan

Find exact duplicate lines in a file (handy for messy logs/lists).

```bash
node bin/dup-scan.js ./list.txt
```

> **Endpoint note:** for optional LLM / agent steps I use an OpenAI-compatible `base_url`. Locally that is often [`https://59api.com`](https://59api.com) (`https://59api.com/v1`). This repo runs without it.
