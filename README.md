<a href="https://github.com/DreViz">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="banner_dark.svg">
    <img alt="Vaibhav Deori" src="banner_light.svg">
  </picture>
</a>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="ticker_dark.svg">
  <img alt="stack ticker" src="ticker_light.svg">
</picture>

### Who

<img src="terminal.svg" alt="terminal intro">

Engineer in Bangalore. I build LLM agents that earn their keep: they plan,
call tools, review their own output, and run on hardware I control. When the
model isn't the hard part, I build what's around it — gateways, routing,
per-token billing.

Most of my repos start from a question I actually had. How small can a local
model be before a multi-step agent breaks? What does an OpenAI-compatible
gateway owe everyone pointing an SDK at it? I like systems with real
constraints: no customer data leaving the machine, every token accounted for.

### Now

Shipping **[GoodFood](https://github.com/DreViz/GoodFood)** phase 7 —
deployment, walkthrough video, and the writeup of the 4 GB model-selection
measurements. Going deeper on **Go**, agent evaluation, and MCP tooling.

### Building

**[GoodFood](https://github.com/DreViz/GoodFood)** — two-agent restaurant
concierge. A Planner decides the next action as strict JSON, a Responder
turns tool output into human text, all on a local Ollama model so no
customer data leaves the machine. The interesting question: how small can
the model go before multi-step agency breaks — measured, not guessed.
`python` `fastapi` `next.js` `ollama` `postgres`

**[Open-Router](https://github.com/DreViz/Open-Router)** — OpenAI-compatible
LLM gateway. Point any OpenAI SDK at it: it authenticates, rate-limits,
routes to the right upstream provider, streams over SSE, and deducts
per-token credits atomically. `go` `postgres` `next.js`

**[doc_agent](https://github.com/DreViz/doc_agent)** — autonomous document
agent. Plans its own work, drafts with explicitly recorded assumptions, runs
a bounded self-review loop, then renders a polished .docx.
`python` `fastapi`

**[InfraForge](https://github.com/DreViz/Infra4rge)** — describe cloud
infrastructure in plain English, get production-ready Terraform with
architecture diagrams, cost estimates, and security audits. In the browser,
no account. `typescript`

**[Playwrite_MCP](https://github.com/DreViz/Playwrite_MCP)** — custom
Playwright MCP server: distributed test execution and browser automation
with its own tool implementations. `typescript` `playwright`

### Earlier

Manim animations and small Python experiments — sentiment, stocks, a music
API. Kept for the record.

### Stack

| | |
|---|---|
| **Languages** | Python · Go · TypeScript · JavaScript |
| **AI/LLM** | Ollama · qwen3 · multi-agent · tool calling · self-review loops · MCP |
| **Backend** | FastAPI · Next.js · REST · SSE streaming |
| **Data** | PostgreSQL |

### Languages

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="langs_anim_dark.svg">
  <img alt="Top languages" src="langs_anim_light.svg">
</picture>

<!-- Uncomment and fill in when ready:
### Elsewhere

[linkedin](https://www.linkedin.com/in/YOUR-HANDLE) · [resume](LINK-TO-RESUME) · YOUR-EMAIL@example.com
-->
