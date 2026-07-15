<div align="center">

# Diego Costa

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=6366F1&center=true&vCenter=true&width=520&lines=AI+Engineer;Products+with+an+LLM+inside;The+model+is+rarely+the+hard+part)](https://git.io/typing-svg)

📍 Montevideo, Uruguay · UTC-3 &nbsp;|&nbsp; 🤖 Products with an LLM inside &nbsp;|&nbsp; 📦 [diegocosta.dev](https://diegocosta.dev)

</div>

---

## About

AI Engineer. Since mid-2025 I build products with an LLM inside, full time — an agent orchestration platform, a construction-bidding product, and an internal desktop app, all in the same engagement. The model is rarely the hard part. The hard part is everything around it: grounding an assistant so a user can check the answer instead of trusting it, keeping each client's documents inside their own tenant, and being able to tell what the thing actually did at 3am.

Before software, six years in ad operations — where I automated my own job until automating became the job.

---

## What I've shipped

**Grounded the assistant, and closed the tenant gap** — On [AnswerAgent](https://github.com/the-answerai/theanswer) I found a five-second timeout that was a no-op because the MCP subprocess never inherited its env, batched an unindexed vectorstore lookup that ran once per document, and closed a multi-tenancy hole where document chunks were written with no owner id so tenant filters matched nothing. [My merged PRs →](https://github.com/the-answerai/theanswer/pulls?q=is%3Apr+author%3Adiecoscai+is%3Amerged)

**Wrote the manual, built the tool that answers from it** — On a construction-bidding product I documented all eight workflows screen by screen, checked against the code, then built the tool that answers "how do I do X" with a link to the exact section — and says the manual doesn't cover it instead of inventing UI.

**Kept a desktop product shipping** — Fixed macOS notarization on signed builds, split the auto-update manifest so arm64 users stopped updating into the wrong binary, and built the production monitoring that never existed (CloudWatch alarms had sat in `INSUFFICIENT_DATA` for a month because nothing emitted metrics).

---

## Featured open source

### 🔧 [`hevy-mcp`](https://github.com/diecoscai/hevy-mcp) — MCP server for the Hevy fitness API
A public, CI-backed MCP server exposing the Hevy API as **23 strongly-typed tools** over stdio for Claude Desktop, Cursor and VS Code. Zod edge-validation with self-correcting errors, dry-run-by-default writes, and schemas auto-generated from Hevy's OpenAPI spec via a weekly workflow that opens PRs on drift.

`TypeScript` · `Zod` · `Vitest` · `GitHub Actions (OIDC)` · `npm`

---

## Stack

**Every day** — TypeScript · Node.js · React · PostgreSQL · MCP · RAG · Flowise · Langfuse · Fiddler · AWS

**Shipped with** — Electron · Docker · Playwright · Vitest · GitHub Actions · Angular · Azure

**Earlier** — Ruby on Rails · Python

---

## Contact

[![Portfolio](https://img.shields.io/badge/Portfolio-diegocosta.dev-6366F1?style=flat&logo=astro&logoColor=white)](https://diegocosta.dev)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Diego%20Costa-6366F1?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/diecoscai)
[![Email](https://img.shields.io/badge/Email-diecoscai@gmail.com-6366F1?style=flat&logo=gmail&logoColor=white)](mailto:diecoscai@gmail.com)
