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

I like systems with real constraints. No customer data leaving the machine.
Every token accounted for. Most repos below started as a question I couldn't
answer by reading — so I built the answer.

### Now

Shipping **[GoodFood](https://github.com/DreViz/GoodFood)** phase 7:
deployment, walkthrough video, and the writeup of the 4 GB model-selection
measurements. Going deeper on **Go**, agent evaluation, and MCP tooling.

Open to AI/backend roles — Bangalore or remote.

### Building

**[GoodFood](https://github.com/DreViz/GoodFood)** — *how small can a model
be before a multi-step agent breaks?*
Two-agent restaurant concierge. A Planner decides the next action as strict
JSON, a Responder speaks human, all on a local Ollama model so no customer
data leaves the machine. The 4 GB question is measured, not guessed.
`python` `fastapi` `next.js` `ollama` `postgres`

**[Open-Router](https://github.com/DreViz/Open-Router)** — *what does a
gateway owe everyone pointing an SDK at it?*
OpenAI-compatible LLM gateway in Go: auth, rate limits, provider routing,
SSE streaming, atomic per-token billing. Point any OpenAI SDK at it —
nothing changes client-side. `go` `postgres` `next.js`

**[doc_agent](https://github.com/DreViz/doc_agent)** — *can an agent
critique its own draft, honestly?*
Plans its own work, drafts with explicitly recorded assumptions, runs a
bounded self-review loop, then renders a polished .docx. Ships with
hermetic tests. `python` `fastapi`

**[InfraForge](https://github.com/DreViz/Infra4rge)** — *what if describing
infrastructure was the whole job?*
Plain English in, production-ready Terraform out — architecture diagrams,
cost estimates, security audits. In the browser, no account. `typescript`

**[Playwrite_MCP](https://github.com/DreViz/Playwrite_MCP)** — *what does a
browser-automation server look like from scratch?*
Custom Playwright MCP server: distributed test execution, own tool
implementations, multiple browser contexts. `typescript` `playwright`

### Earlier

Where the questions started. Manim animations, sentiment analysis, stocks,
a music API. Kept for the record.

### Stack

| | |
|---|---|
| **Languages** | Python · Go · TypeScript · JavaScript |
| **AI/LLM** | Ollama · qwen3 · multi-agent · tool calling · self-review loops · MCP |
| **Backend** | FastAPI · Next.js · REST · SSE streaming |
| **Data** | PostgreSQL |
| **Tooling** | Playwright · Manim · Docker |

### Languages

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="langs_anim_dark.svg">
  <img alt="Top languages" src="langs_anim_light.svg">
</picture>

<!-- Uncomment and fill in when ready:
### Elsewhere

[linkedin](https://www.linkedin.com/in/YOUR-HANDLE) · [resume](LINK-TO-RESUME) · YOUR-EMAIL@example.com
-->
