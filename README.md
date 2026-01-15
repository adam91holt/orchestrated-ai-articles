# Orchestrated AI Team — Technical Articles

Public home for technical write‑ups on orchestrated, multi‑agent AI systems.

```mermaid
graph TD
    subgraph "The Orchestrator"
        Kev[Kev\n(Opus 4.5)]
    end
    
    subgraph "The Specialists"
        Rex[Rex\n(Codex)]
        Scout[Scout\n(Gemini Flash)]
        Hawk[Hawk\n(Opus)]
        Pixel[Pixel\n(Gemini Pro)]
    end
    
    Kev -->|Delegates| Rex
    Kev -->|Delegates| Scout
    Kev -->|Delegates| Hawk
    Kev -->|Delegates| Pixel
```

## Contents
- [**The Manifesto**](MANIFESTO.md) — Our principles: Orchestration > Chat, Specialization > Generalization, and the future of Deployable Intelligence Units.
- [**Kev's Dream Team**](KEVS_DREAM_TEAM.md) — Technical walkthrough of the architecture (gateway, agents, sandboxing, webhooks, heartbeats, delegation, model selection).
- Public article: https://adams-ai-journey.ghost.io/2026-the-year-of-the-orchestrator/

## Why this repo
I’m publishing these as standalone articles so they can evolve independently of internal notes. Future posts and revisions will live here.

## Contributing
PRs welcome if you have concrete improvements, corrections, or diagrams to add.
