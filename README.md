# Elijah Wilkins

> Applied AI Engineer — local-first agent infrastructure, voice/HCI automation, and developer tooling.

[![Portfolio](https://img.shields.io/badge/Portfolio-ebey317.github.io-2ea44f?logo=github)](https://ebey317.github.io)
[![GitHub](https://img.shields.io/badge/GitHub-ebey317-181717?logo=github)](https://github.com/ebey317)
[![Email](https://img.shields.io/badge/Email-ebey317%40gmail.com-D14836?logo=gmail)](mailto:ebey317@gmail.com)

I build **local-first AI agents that safely operate machines**. My work sits at the intersection of agent runtimes, multi-provider model routing, desktop accessibility, and human-computer interaction — all designed to run on the user's own hardware with their own API keys.

- **Agent infrastructure:** multi-provider routing, MCP tool protocol, memory, subagents, safety/approval layers, headless delegation
- **Voice & HCI automation:** push-to-talk STT, TTS, on-screen keyboard, controller-driven desktop control, HUD overlays
- **Systems/integration focus:** Linux services, systemd, browser automation, local model inference, cloud fallback strategies

I'm self-taught — HVAC engineer by background, systems builder by practice. I build tools that solve real gaps: offline-capable agents, accessible desktop input, and infrastructure that doesn't require a subscription.

---

## Flagship Projects

### [Master AI CLI](https://github.com/ebey317/master-ai-cli)
A local-first AI agent runtime with multi-provider routing, MCP tooling, browser automation, voice/vision, subagents, and a safety layer.

- ~43K lines Python, 57 test files, terminal + browser extension surfaces
- Routes between Ollama (local) and OpenRouter / Groq / Gemini / Anthropic / OpenAI (cloud)
- Headless delegation mode for CI and agent orchestration
- Approval queue, typed action dispatch, and privacy-cloud guard

### [AI Controller](https://github.com/ebey317/ai-controller)
Voice-first desktop accessibility for Linux. Control the entire desktop with an Xbox controller — no keyboard, no mouse required.

- Push-to-talk speech-to-text via Groq Whisper
- GTK floating on-screen keyboard and controller legend HUD
- FastAPI voice bridge for STT/TTS on `:8002`
- Auto profile switching and systemd-managed services

### [CLAF — Closed-Loop Agent Framework](https://github.com/ebey317/claf)
A FastAPI proxy that routes Claude Code CLI calls to local Ollama first, with selective cloud escalation.

- Off-grid mode prevents cloud calls unless explicitly enabled
- Charter injection, persistent task state, permission-mode sync
- Multi-provider cloud tiers: Anthropic, OpenRouter, Groq, Cerebras, Fireworks

### [us211-api](https://github.com/ebey317/us211-api)
An open, HSDS-shaped REST API + assistant for 2-1-1 health and human services data across the US.

- Federates ~200 local/state services behind one unified API
- Assistant actions: summarize, read aloud, print, email, pinpoint documents, fill forms
- Built as a tool for AI agents rather than a standalone app

### [reentry-desk](https://github.com/ebey317/reentry-desk)
An MCP server + HTTP bridge for managing client intake and form completion across reentry programs.

- JSON-based profiles and templates — no database required
- Browser autofill handoff payload
- Optional REST bridge for web UI integration

---

## Certifications

- **Claude 101** — Anthropic (May 2026)
- **Claude Code 101** — Anthropic (May 2026)
- **Introduction to Claude Cowork** — Anthropic (May 2026)
- **AI Fluency: Framework & Foundations** — Anthropic, co-badged UCC / Ringling College of Art + Design / HEA / National Forum (May 2026)

Full records: [ebey317/cert-path](https://github.com/ebey317/cert-path)

---

## Tech Stack

| Area | Tools |
|---|---|
| Languages | Python, Bash, JavaScript, HTML |
| Agent stack | Ollama, OpenRouter, Groq, Anthropic, Gemini, OpenAI |
| Frameworks | FastAPI, GTK3, PyGObject, Flask |
| Protocols | MCP, CDP, systemd, native messaging |
| Voice/audio | Piper TTS, edge-tts, Groq Whisper, PulseAudio |
| Desktop automation | AntiMicroX, xdotool, xtest, pynput |
| Deployment | Linux, systemd, Tailscale, GitHub Pages |

---

## GitHub Stats

[![GitHub Stats](https://github-readme-stats.vercel.app/api?username=ebey317&show_icons=true&theme=dark&hide_border=true)](https://github.com/ebey317)
[![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=ebey317&layout=compact&theme=dark&hide_border=true)](https://github.com/ebey317)

---

## Contact

- Indianapolis, Indiana
- ebey317@gmail.com
- Portfolio: [ebey317.github.io](https://ebey317.github.io)
- GitHub: [@ebey317](https://github.com/ebey317)
