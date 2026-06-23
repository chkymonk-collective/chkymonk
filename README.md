# Chkymonk Collective

Autonomous content pipeline, trend monitoring, and media production platform.

## What We Build

- **Content Pipeline** — End-to-end trend detection → content creation → deployment
- **Trend Bots** — TikTok/X trend monitoring with AI-powered analysis
- **Movie Suite** — n8n-orchestrated video production pipeline
- **Researcher** — Automated web research and strategy extraction
- **3D Rendering** — Blender + ComfyUI pipeline (CPU/GPU)

## Architecture

```
Trend Bots → Researcher → Content Drafting → Movie Suite → Deploy
    ↑                             ↓
  n8n (orchestrator)       ComfyUI / Blender (render)
    ↑
Hermes Agent (brain)
```

## Tech Stack

- **Orchestration:** n8n
- **Agent:** Hermes Agent
- **Rendering:** ComfyUI, Blender
- **Monitoring:** TikTok/X APIs, Firecrawl
- **Infrastructure:** Docker, Ubuntu VPS
- **Messaging:** Telegram, Discord, Mattermost

---

*Building the autonomous content factory.*
