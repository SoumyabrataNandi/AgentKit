# AgentKit

**Build AI agents in plain language. Run them reliably. They ask instead of guessing.**

AgentKit is an engine for AI agents that behave like careful colleagues:

- **Ask, don't guess** — when a goal is ambiguous, the agent pauses and asks you a
  question (with tappable options) instead of fabricating a preference.
- **Human-gated actions** — consequential actions (sending, deleting, paying) pause
  for your explicit approval, enforced by the runtime, not by prompt hopes.
- **Never breaks in the middle** — every step is checkpointed; a killed process
  resumes exactly where it stopped.
- **Any MCP server is a tool** — connect Gmail, filesystems, your own services.

## ✦ AgentKit Console

The web console lives here, served from this repository via GitHub Pages:

**https://soumyabratanandi.github.io/AgentKit/**

It is a thin client — a mission-control dashboard with a live event timeline,
plain-language agent builder, clarification answering, and approval gates.
Your runs, credentials, and data never leave your machine: the console talks
only to the AgentKit engine URL you configure (default `http://localhost:4747`).

### Using the console

1. Start your AgentKit engine locally (`agentkit serve`).
2. Open the console link above.
3. If needed, set your engine URL under **Settings**.

## Distribution

This repository ships the **compiled AgentKit Console** (see [`docs/`](docs/)).
The engine and SDKs are distributed separately as packages; the source code of
AgentKit is not published here. You are free to use the product; see
[LICENSE](LICENSE) for terms of the distributed files.

---

© 2026 Soumyabrata Nandi
