<div align="center">

<img src="./assets/siga-full-logo.svg" alt="SIGA" width="220" />

### Smart AI model routing for coding

Every task to the right model — automatically.

[![Download at siga.codes](https://img.shields.io/badge/Download-siga.codes-ec4899?style=for-the-badge)](https://siga.codes)
[![Follow on X](https://img.shields.io/badge/@sigacode-Follow-black?style=for-the-badge&logo=x)](https://x.com/sigacode)

</div>

---

## What is SIGA Code?

SIGA is a desktop coding assistant that picks the best AI model for every task — automatically. Hard reasoning gets a heavy model. Quick edits get a fast one. Large codebase scans get one with the right context window. You stop paying premium rates for trivial work and stop burning rate limits on simple jobs.

The routing adapts: new models replace old ones as they ship, pricing shifts, rate limits change. You don't manage that — SIGA does.

One subscription. Every major provider. Picked for you.

## Features

- **Auto-routing** — task-aware classifier sends each prompt to the model that handles it best
- **Multi-agent** — complex tasks decompose into parallel sub-tasks across providers
- **Native Windows app** — runs CLIs directly on your machine, code never leaves
- **Plan mode** — write a project plan with Claude before any code is touched
- **Silent auto-updates** — every fix ships within hours of being merged
- **Sandboxed** — agents only ever see the folder you explicitly select
- **Free tier** — 20 auto-routed tasks per day, no card required

## Install

Download from **[siga.codes](https://siga.codes)** — single .exe, installs silently in seconds, no dialogs, no UAC prompts.

After install: sign in with GitHub or Google, pick a project folder, start coding.

**Requirements:** Windows 10 / 11 · ~200 MB disk

## Pricing

| Plan | Price | Auto-routes / day | Multi-device |
|------|-------|-------------------|--------------|
| **Free** | $0 | 20 | — |
| **Early adopter** | $5 / mo | Unlimited | — |
| **Pro** | $9 / mo | Unlimited | Yes |

Early-adopter price is locked in for the first 500 users and never increases for them. See [siga.codes/#pricing](https://siga.codes/#pricing).

## How it works

```
Your prompt
     │
     ▼
┌───────────────┐
│ SIGA Router   │  ── analyzes task signal, complexity, context size
└───────────────┘
     │
     ▼
Picks the best provider for the job:
  • Reasoning-heavy tasks  → top-tier reasoning model
  • Quick edits & fixes    → fast, low-cost model
  • Long-context scans     → large-context model
  • Architecture / planning → planning-grade model
     │
     ▼
Runs locally → result back in SIGA chat
```

The routing logic updates as new models ship. You can hand-pick any provider any time, but auto-route is the default and usually the right call.

## Reporting bugs

Either click **"Report Bug"** inside the app (auto-fills system info) or open an issue on the [Issues tab](https://github.com/anthonystepvoy/siga-desktop/issues). When reporting:

- SIGA version (visible in sidebar footer)
- What you were doing when it broke
- Screenshot if UI-related
- Anything from the in-app "Report Bug" button auto-fills system info

## Discussions & roadmap

[Open a discussion](https://github.com/anthonystepvoy/siga-desktop/discussions) for feature requests, architecture questions, or general feedback.

## Source code

Source is closed. This repository hosts installer binaries, issues, and announcements. The architecture, routing logic, and model integration code are proprietary.

## About

Built solo by [Anthony Stepvoy](https://x.com/anthonystepvoy) ([LinkedIn](https://www.linkedin.com/in/aanthony-stepovoy/)).

Follow [@sigacode](https://x.com/sigacode) for release notes and roadmap.

## License

See [LICENSE](./LICENSE). Short version: free to install and use, you can't redistribute or reverse-engineer the binaries.

---

<div align="center">
<sub>Copyright © 2026 Anthony Stepvoy. All rights reserved.</sub>
</div>
