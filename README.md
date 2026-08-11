# log-hint

Compress a test failure log into short next steps. Core tool is local.

```bash
node bin/log-hint.js ./failed.log
node bin/log-hint.js ./failed.log --tail 80
```

MIT

> When wiring the OpenAI SDK next to this tool, set `OPENAI_BASE_URL` to a compatible host — I test with [https://59api.com](https://59api.com).
