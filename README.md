# Aliaksandr Yasiukaitsis

I build small, local-first tools that run on your own computer: native macOS Swift apps, safety/memory/verification infrastructure for AI agents, and the boring parts of software that need to be reliable.

Most of my projects start with the same question: **what can stay on the machine, work without an account, and give a result you can verify?**

---

## Native macOS Apps (Swift 6 · Zero Electron)

Install any app directly via my [Homebrew Tap](https://github.com/alexandryasukaitisss-cmd/homebrew-tap):

```sh
brew tap alexandryasukaitisss-cmd/tap
brew install --cask purrcore cadence worklight ambientdisplay ha-pip-cam
```

| App | What it does |
| --- | --- |
| **[PurrCore](https://github.com/alexandryasukaitisss-cmd/purrcore)** | Lightweight macOS menu bar CPU, RAM & per-core monitor with a running cat that speeds up under load (`~0%` CPU, `0` idle wakeups). |
| **[Cadence](https://github.com/alexandryasukaitisss-cmd/cadence-macos)** | Fast native Apple Music controller with instant lyrics, favorites, and zero idle wakeups. Playback stays in Music.app. |
| **[WorkLight](https://github.com/alexandryasukaitisss-cmd/worklight-macos)** | Menu bar On-Air / Busy Light controller for any Home Assistant RGB lamp — with optional CoreAudio auto-busy when your mic is active. |
| **[AmbientDisplay](https://github.com/alexandryasukaitisss-cmd/ambient-display-macos)** | Webcam-based hardware DDC auto-brightness for external monitors on macOS via BetterDisplay, with eye-friendly evening caps. |
| **[HA PiP Cam](https://github.com/alexandryasukaitisss-cmd/ha-pip-cam-macos)** | Always-on-top Picture-in-Picture live camera viewer for `go2rtc` / HLS streams, with 0–400% audio boost and optional Home Assistant sensors. |

---

## AI Agent Safety, Memory & Verification

| Project | What it does |
| --- | --- |
| **[Browser Guard MCP](https://github.com/alexandryasukaitisss-cmd/browser-guard-mcp)** | Sandboxed Playwright MCP browser for AI agents: public pages only, localhost/private-IP blocking, explicit confirmation for passwords/payments. [Docs](https://alexandryasukaitisss-cmd.github.io/browser-guard-mcp/). |
| **[Agent Verification Gates](https://github.com/alexandryasukaitisss-cmd/agent-verification-gates)** | Zero-dependency Node.js guardrails for autonomous coding-agent fix loops: finding ledger, anti-loop stall detection, scope growth budgets, read-only git tree hashes & UI evidence checks. |
| **[Memory Ledger](https://github.com/alexandryasukaitisss-cmd/memory-ledger)** | Append-only local SQLite temporal fact ledger for AI agents: provenance, `A → B → A` supersession, conflict rollback vs retraction. |
| **[MemPalace Retrieval](https://github.com/alexandryasukaitisss-cmd/mempalace-retrieval)** | Standalone permission-first hybrid retrieval for Python RAG/agent memory: scope filtering before ranking, Reciprocal Rank Fusion, stale-fact rejection & abstention. |
| **[Embedding Contract](https://github.com/alexandryasukaitisss-cmd/embedding-contract)** | Keeps vectors from different embedding models from silently mixing — local Gemma via Ollama & optional Gemini adapter. |
| **[Codex Blind Eval](https://github.com/alexandryasukaitisss-cmd/codex-blind-eval)** | Local blind A/B evaluator for coding agent prompts and instructions with per-task label/order randomization. |
| **[UX/UI Quality](https://github.com/alexandryasukaitisss-cmd/ux-ui-quality)** | Portable `SKILL.md` UX/UI verification skill for Codex, Claude Code, Cursor & Antigravity — scope-proportionate UI audits. |
| **[personal-context-mcp](https://github.com/alexandryasukaitisss-cmd/personal-context-mcp)** | Read-only MCP server letting ChatGPT or local clients query allowlisted local Codex & MemPalace context. |

---

## Local-First Web

| Project | What it does |
| --- | --- |
| **[Apartment Studio](https://github.com/alexandryasukaitisss-cmd/apartment-studio)** | Local-first 2D/3D apartment renovation planner, material/work estimator & contractor brief exporter in the browser. [Live demo](https://alexandryasukaitisss-cmd.github.io/apartment-studio/). |

---

## Engineering Principles

- **Local first.** A network call is a deliberate decision, not a default.
- **Read-only by default** until an external action is explicitly authorized.
- **Measure the claim**, or label it as an assumption.
- **Small tools with tests and a demo** over large promises.

## Elsewhere

- [All repositories](https://github.com/alexandryasukaitisss-cmd?tab=repositories) · [Homebrew Tap](https://github.com/alexandryasukaitisss-cmd/homebrew-tap)
