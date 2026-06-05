### Elijah Wilkins — AI Systems Builder

**Self-taught. Local-first. Off-grid by design.**

I build infrastructure for running AI privately on your own hardware — not apps that require a subscription or an internet connection to think.

---

#### What I build

**[CLAF — Closed-Loop Agent Framework](https://github.com/ebey317/claf)**
A FastAPI proxy that intercepts Anthropic's API format and routes LLM calls across tiers: local Ollama first, free cloud APIs second, paid APIs only when necessary. Off-grid mode is the default — the cloud path literally isn't constructed at import time unless you opt in.

- Local Ollama proxy (`/v1/messages` → Ollama chat format translation)
- Tier-based routing: local → free cloud → paid cloud based on task complexity signals
- Off-grid lock: `423 Locked` if anything tries to route to cloud while in off-grid mode
- Hard budget ceiling, token tracking, and cost-aware escalation

**Master AI — Private AI stack that runs on your hardware**
Full agent loop with browser control, terminal execution, memory, and multi-model orchestration. Runs on a Linux laptop. Doesn't phone home.

- Hook system for pre/post tool enforcement (retry policy, auth visibility, routing guards)
- MCP-native browser automation (CDP-based, no Chrome extension dependency)
- Cross-session memory with typed entries (user / project / feedback / reference)
- Multi-agent planner/executor split to control API cost

---

#### About me

No CS degree. Started with "paste this in your terminal" and built from there. The whole stack is on Linux Mint, portable on a USB drive.

I don't chase the newest model — I build the wiring that makes any model useful.

Indianapolis, Indiana · ebey317@gmail.com
