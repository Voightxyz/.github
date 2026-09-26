<p align="center">
  <a href="https://voight.xyz"><img src="https://raw.githubusercontent.com/Voightxyz/.github/main/profile/assets/banner.png" alt="Voight: built for the agentic era" width="100%" /></a>
</p>

<h1 align="center">Voight</h1>

<p align="center">
  Observability and debugging for AI agents and autonomous systems.<br />
  Live traces, root-cause debugging and an audit trail for every run.
</p>

<p align="center">
  <a href="https://voight.xyz">Website</a> ·
  <a href="https://docs.voight.xyz">Docs</a> ·
  <a href="https://docs.voight.xyz/quickstart">Quickstart</a> ·
  <a href="https://www.npmjs.com/org/voightxyz">npm</a> ·
  <a href="https://x.com/Voightxyz">X</a>
</p>

---

## What Voight does

Voight captures every prompt, tool call, model response, decision and error your agents and AI applications make, and turns that stream into three things:

- **Live traces.** A timeline for every run, grouped into traces, with token, cost and latency attribution down to the end user.
- **Root-cause debugging.** Failed runs land in an issue queue with an AI diagnosis of what went wrong, not just the stack trace.
- **An audit trail.** Every event is hashed and kept with its full context, so any run can be searched, replayed and reviewed later. Tamper-evident by architecture, not policy.

It works with the agents you already have: coding agents (Claude Code, Cursor, Codex), production LLM apps (OpenAI, Anthropic, the Vercel AI SDK, any Python stack) and custom runtimes over a plain HTTP API. The same event model is built to extend to robots, drones and other physical autonomous systems.

## Start here

| Package | For | Install |
| --- | --- | --- |
| [`@voightxyz/sdk`](https://github.com/Voightxyz/voight-sdk) | Coding agents (Claude Code, Cursor, Codex sessions) and any TypeScript agent | `npx -y @voightxyz/sdk setup` |
| [`@voightxyz/openai`](https://github.com/Voightxyz/voight-openai) | Production apps on the OpenAI Node SDK | `npm install @voightxyz/openai` |
| [`@voightxyz/anthropic`](https://github.com/Voightxyz/voight-anthropic) | Production apps on the Anthropic Node SDK | `npm install @voightxyz/anthropic` |
| [`@voightxyz/vercel-ai`](https://github.com/Voightxyz/voight-vercel-ai) | Apps on the Vercel AI SDK (OpenTelemetry span exporter) | `npm install @voightxyz/vercel-ai` |
| [`bitfrost`](https://github.com/Voightxyz/bitfrost) | Python LLM apps (OpenTelemetry, standalone or shipping to Voight) | `pip install bitfrost` |
| HTTP API | Any language | [`POST /v1/events`](https://docs.voight.xyz/api-reference/events) |

Events from every package land in the same dashboard, under the same agent. Three capture levels (Minimal, Standard, Full) decide how much content leaves your machine; tokens, cost and latency always flow.

## Don't have agents yet?

**[Voight Agents](https://agent.voight.xyz)** is a separate product: autonomous agents that Voight hosts and runs for you, live in about a minute on cloud or GPU, and observable with the platform from day one. It is built for the web3 market: each agent gets an on-chain identity and can run on decentralized GPU.

| Repository | What it is |
| --- | --- |
| [`agents-mcp`](https://github.com/Voightxyz/agents-mcp) | MCP server to deploy, operate, schedule and orchestrate Voight Agents from Claude Code, Cursor, Codex or any MCP client: `npx -y @voightxyz/agents-mcp` |
| [`nosana-agents`](https://github.com/Voightxyz/nosana-agents) | Agent container image, deploy tooling and job templates for Nosana GPUs |
| [`Nosana-SDK`](https://github.com/Voightxyz/Nosana-SDK) | Detect, verify and showcase agents running on Nosana GPU compute |

## Documentation

- [Introduction](https://docs.voight.xyz/introduction) and [Quickstart](https://docs.voight.xyz/quickstart)
- [Codex sessions as traces](https://docs.voight.xyz/sdk/codex) · [Library mode](https://docs.voight.xyz/sdk/library-mode) · [HTTP API](https://docs.voight.xyz/sdk/http-api)
- [Per-user cost attribution](https://docs.voight.xyz/concepts/per-user-spend)
- [Trust and security](https://docs.voight.xyz/trust/overview): GDPR, OWASP LLM Top 10, NIST AI RMF, SOC 2 readiness
- For AI assistants: [llms.txt](https://voight.xyz/llms.txt) and the [complete docs in one file](https://docs.voight.xyz/llms-full.txt)

## Company

Voight is built by Galaxyhub Labs Inc. (d/b/a Voight). [Privacy and terms](https://docs.voight.xyz/legal/privacy).
