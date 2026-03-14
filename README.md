# conan-skill-web-search

> Web search skill for [Conan AI](https://github.com/AmrLotfy/Conan-ai).

[![npm](https://img.shields.io/npm/v/conan-skill-web-search?color=crimson)](https://www.npmjs.com/package/conan-skill-web-search)
[![License: MIT](https://img.shields.io/badge/license-MIT-gold.svg)](LICENSE)

Real-time web search with sources, powered by [Tavily](https://tavily.com). No more stale training data — get live results.

```
You: search for the latest news about GPT-5
Conan: **Answer:** OpenAI has announced GPT-5 with significant improvements...

       **Search results for:** latest news about GPT-5

       1. **GPT-5 Is Here — What You Need to Know**
          OpenAI officially unveiled GPT-5 today with enhanced reasoning...
          🔗 techcrunch.com/2025/...

       2. **GPT-5 vs Claude 4 — Full Comparison**
          🔗 theverge.com/...
```

---

## Install

```bash
conan skill install conan-skill-web-search
```

## Setup

Get a free API key at [tavily.com](https://tavily.com) (1000 calls/month free), then:

```bash
conan config set tavilyKey YOUR_KEY
```

---

## Usage

Just ask naturally:

```
"search for latest AI news"
"find information about React 19 new features"
"what happened in Egypt today?"
```

---

## Parameters

| Parameter | Type | Required | Description |
|---|---|---|---|
| `query` | string | ✅ | The search query |
| `max_results` | number | — | Number of results to return (1–5, default 3) |

---

## License

MIT · [Amr Lotfy](https://github.com/AmrLotfy)
