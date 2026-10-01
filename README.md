<div align="center">

# Nitin Kaushal

**Senior Solution Architect** · AWS Certified · Open Source Builder

Building distributed systems, AI infrastructure and observability, developer tooling, and cloud-native platforms with TypeScript.

<br />

[![TypeScript](https://img.shields.io/badge/TypeScript-5.x-3178C6?style=flat-square&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Node.js](https://img.shields.io/badge/Node.js-20+-339933?style=flat-square&logo=nodedotjs&logoColor=white)](https://nodejs.org/)
[![AWS](https://img.shields.io/badge/AWS-Certified-FF9900?style=flat-square&logo=amazonwebservices&logoColor=white)](https://aws.amazon.com/)
[![npm](https://img.shields.io/badge/npm-nkcodedev-CB3837?style=flat-square&logo=npm&logoColor=white)](https://www.npmjs.com/~nkcodedev)

[GitHub](https://github.com/nkcodedev) · [npm](https://www.npmjs.com/~nkcodedev) · [Medium](https://medium.com/@nitink4107)

</div>

---

## About

- Senior Solution Architect with 14+ years building enterprise software
- AWS Certified
- Creator of open-source developer infrastructure including **Resili** and **AgentGauge**
- Publisher of open-source npm packages
- Focused on system design, cloud architecture, and developer tools that solve real problems

---

## Focus

I design and ship distributed systems that stay reliable under failure — with an emphasis on **resilience patterns**, **AI observability**, **developer experience**, and **cloud architecture**.

| Domain | What I work on |
| --- | --- |
| Resilience & Reliability | Retry, timeout, circuit breaker, bulkhead, rate limiting |
| AI Infrastructure & Observability | LLM usage, cost, latency, model telemetry, AI workload visibility |
| Developer Tools | AI-assisted review, static analysis, DX tooling |
| Cloud & Platform | AWS, serverless, containers, infrastructure as code |

---

## Open Source

### [Resili](https://github.com/nkcodedev/resili) — featured

TypeScript-first resilience toolkit for production Node.js services.

Composable primitives for fault-tolerant applications:

- **Retry** — controlled recovery from transient failures
- **Timeout** — bounded execution with clear failure modes
- **Circuit Breaker** — fail fast when downstream systems degrade
- **Bulkhead** — isolate critical paths under load
- **Rate Limiter** — protect services from traffic spikes
- **Adapters** — native Fetch, Axios, and Undici
- **Plugin System** — extend resilience behavior for your stack

```bash
npm install @resili/core
```

→ [github.com/nkcodedev/resili](https://github.com/nkcodedev/resili)

#### Published packages

- [@resili/core](https://www.npmjs.com/package/@resili/core)
- [@resili/fetch](https://www.npmjs.com/package/@resili/fetch)
- [@resili/axios](https://www.npmjs.com/package/@resili/axios)
- [@resili/undici](https://www.npmjs.com/package/@resili/undici)

→ [npmjs.com/~nkcodedev](https://www.npmjs.com/~nkcodedev)

---

### [AgentGauge](https://github.com/nkcodedev/agentgauge)

Open-source observability and cost intelligence for AI agents.

AgentGauge gives engineering teams visibility into how LLM-powered agents behave in production: which agents are running, how many tokens they consume, what they cost, which models they use, where failures occur, and how usage changes over time. Telemetry is metadata-first — prompts and completions are not stored by default.

The Node SDK sends traces to a self-hosted API. PostgreSQL is the source of truth, and a dashboard shows overview metrics, agents, runs, traces, API keys, and model pricing. Cost is estimated server-side from historical, effective-dated pricing, including custom models managed from the dashboard.

Key capabilities:

- Manual tracing, plus automatic instrumentation for OpenAI, Anthropic, and Gemini
- Token usage, latency, errors, estimated cost, and agent, model, and provider breakdowns
- Run and trace observability with retry and attempt visibility
- Real-time dashboard updates over SSE, with project API keys and a trace explorer

```bash
npm install @agentgauge/node
```

→ [github.com/nkcodedev/agentgauge](https://github.com/nkcodedev/agentgauge)

---

### [Pullsense](https://github.com/nkcodedev/pullsense)

AI-powered pull-request review tool with [Model Context Protocol (MCP)](https://modelcontextprotocol.io) support.

Watches GitHub webhooks, reviews diffs with Ollama or OpenAI, and posts check runs with inline comments. MCP is built in both directions — Pullsense exposes an MCP server for Cursor / Claude Desktop, and can also call external MCP servers to enrich review context.

→ [github.com/nkcodedev/pullsense](https://github.com/nkcodedev/pullsense)

---

## Project Map

| Project | Stack | Status | Link |
| --- | --- | --- | --- |
| **Resili** | TypeScript · Node.js | Open source | [Repo](https://github.com/nkcodedev/resili) |
| **AgentGauge** | TypeScript · Node.js · PostgreSQL | Open source | [Repo](https://github.com/nkcodedev/agentgauge) |
| **Pullsense** | TypeScript · AI · MCP · GitHub Apps | Open source | [Repo](https://github.com/nkcodedev/pullsense) |

---

## Tech Stack

| Area | Technologies |
| --- | --- |
| Languages | TypeScript · JavaScript · PHP · Python |
| Backend | Node.js · Express · REST APIs · GraphQL |
| Cloud | AWS · Lambda · DynamoDB · S3 · API Gateway · ECS |
| DevOps | Docker · Terraform · GitHub Actions |
| Data | PostgreSQL · MySQL · DynamoDB · Redis |
| Architecture | System Design · Distributed Systems · Microservices · Event-Driven |

---

## Currently Building

- Hardening and expanding **Resili** for real-world production workloads
- Expanding **AgentGauge** for AI agent observability and cost tracking
- Shipping **Pullsense** as an AI + MCP code-review companion
- **FlowIQ** — VS Code tooling to trace Express request flows in large backends
- System design resources and developer utilities

---

## Connect

<p align="center">

<a href="https://github.com/nkcodedev">
<img src="https://img.shields.io/badge/GitHub-nkcodedev-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub" />
</a>
<a href="https://www.npmjs.com/~nkcodedev">
<img src="https://img.shields.io/badge/npm-nkcodedev-CB3837?style=flat-square&logo=npm&logoColor=white" alt="npm" />
</a>
<a href="https://medium.com/@nitink4107">
<img src="https://img.shields.io/badge/Medium-Nitin%20Kaushal-000000?style=flat-square&logo=medium&logoColor=white" alt="Medium" />
</a>

</p>

---

## GitHub Statistics

<p align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=nkcodedev&show_icons=true&theme=transparent&hide_border=true&rank_icon=github" alt="Nitin's GitHub stats" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=nkcodedev&layout=compact&theme=transparent&hide_border=true" alt="Top languages" />

</p>

<p align="center">

<img width="700" src="https://streak-stats.demolab.com?user=nkcodedev&theme=default&hide_border=true" alt="GitHub streak" />

</p>

---

<div align="center">

**Building tools that make systems more reliable — and developers more effective.**

⭐ Thanks for visiting

</div>
