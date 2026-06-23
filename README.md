# Ahmed Khaled Mohamed

Senior engineering leader building platform systems at Spotify. Leading messaging infrastructure for 700M+ users — client SDKs, delivery systems, experimentation primitives, and ML-driven relevance. 12+ years across engineering, product, and leadership.

**Website**: [ahmedkhaledmohamed.github.io/me](https://ahmedkhaledmohamed.github.io/me) · **LinkedIn**: [ahmedkhaledmohamed](https://linkedin.com/in/ahmedkhaledmohamed) · **Email**: ahmed.khaled.a.mohamed@gmail.com

---

## Projects

### Compass AI

Cursor for Product Managers. AI-native product discovery that connects to your product's evidence sources -- code, docs, analytics, and user feedback -- finds where they disagree, and generates agent-ready specifications.

Available as a CLI, desktop app (macOS/Windows/Linux), and MCP integration for Claude Code and Cursor.

[GitHub](https://github.com/Compass-AI-App/compass-AI) · [Website](https://compass-ai-app.github.io/compass-AI/) · [Download](https://github.com/Compass-AI-App/compass-AI/releases/latest)

### PM AI Partner Framework

AI-powered skills, workflows, and methodology for Product Managers. 12 agent skills, 6 workflow commands, and 3 automation hooks for Claude Code, Cursor, and Codex.

```bash
npx pm-ai-partner@latest
```

[GitHub](https://github.com/ahmedkhaledmohamed/PM-AI-Partner-Framework) · [npm](https://www.npmjs.com/package/pm-ai-partner) · [Landing Page](https://ahmedkhaledmohamed.github.io/PM-AI-Partner-Framework/)

### The Hub

Personal command center and workspace intelligence platform. Scans directories, indexes documents, and surfaces everything in a searchable, AI-augmented interface with document hygiene analysis, knowledge graphs, predictive briefings, and hub-to-hub federation.

60+ REST API endpoints, 23 MCP tools, 1000+ tests. Built with Next.js 15, React 19, SQLite FTS5, and MCP SDK.

[GitHub](https://github.com/ahmedkhaledmohamed/the-hub) · [Website](https://ahmedkhaledmohamed.github.io/the-hub/)

### Bézier

AI-powered design generation desktop app. Transforms text prompts into professional designs with structured regions -- lock what you love, regenerate the rest. Features selective regeneration, version timeline, semantic diff, and quality validation.

Built with Electron, React, TypeScript, Claude API, and Ideogram API. Local-first with SQLite.

[GitHub](https://github.com/BezierAI) · [Website](https://bezierai.github.io/bezierai.github.io/)

### Zia

AI-powered family assistant for meal planning, chore scheduling, and routine building. Multi-provider LLM orchestration (Claude, GPT, open-source models), RAG with pgvector, and real-time streaming.

Full-stack: FastAPI backend on DigitalOcean + native iOS app on the App Store.

[GitHub](https://github.com/ParentingAssistant)

### Khalil

Self-healing personal AI assistant. Multi-channel messaging (Telegram, Slack, Discord, WhatsApp), 37 self-describing action modules with skill-based dispatch, three-tier autonomy model, hybrid local/cloud LLM orchestration, and a self-healing engine that reads its own source code, generates patches, and opens PRs.

Built with Python, FastAPI, SQLite + sqlite-vec, Ollama, and Claude.

[GitHub](https://github.com/ahmedkhaledmohamed/khalil)

### AI Evals Framework

Quality evaluation framework for AI-assisted PM workflows. Structured eval pipelines with LLM-as-judge scoring, regression detection, calibration against human ratings, and automated reporting dashboards.

[GitHub](https://github.com/ahmedkhaledmohamed/ai-thinking-partner-evals-framework)

### LLM Toolkit

Collection of tools and utilities for working with large language models — prompt engineering patterns, token management, model comparison, and evaluation harnesses.

[GitHub](https://github.com/ahmedkhaledmohamed/llm-toolkit)

---

## Spotify Internal Tools

Built for Client Messaging (Messaging Platform & Technology) at Spotify. These run on Spotify's internal infrastructure.

### Client Messaging Product Catalog

Delivery intelligence platform for the Client Messaging team. Interactive roadmaps, analytics dashboards, system maps, prototypes, and planning tools — all powered by a Node.js server with SQLite, synced daily with Groove (Spotify's work graph).

**Pages**: Gantt Roadmap · Waterfall Roadmap · MP&T Platform Roadmap · System Map · Gap Analysis · Workstreams · Prototypes · AI Quality Dashboard

[Live](https://client-messaging-catalog.taskforce.spotify.net)

### Moments Catalog

Visual catalog builder for defining behavioral Moments — 20 moments, 26 signals, 18 eligibility rules, 16 triggers. Next.js with shadcn/ui.

[Live](https://snow.spotify.net/spa/moments-catalog)

### Orchestration Dashboard

Cross-channel messaging orchestration dashboard. BigQuery-powered analytics showing message volume, delivery funnels, and cross-channel conflicts across push, in-app, and inbox.

[Live](https://snow.spotify.net/spa/messaging-orchestration-dashboard)

### User Journey Explorer

Per-user moment intelligence platform. Explores the intersection of user behavior, messaging history, and moment signals. Next.js + BigQuery + Postgres.

[Live](https://user-journey-explorer.taskforce.spotify.net)

### Nestor

MP&T knowledge system. Hybrid search + knowledge graph over 200+ messaging platform documents with semantic retrieval and entity relationships.

---

## This Site

Pure HTML/CSS/JS, no framework dependencies, responsive design, hosted on GitHub Pages.

```bash
python -m http.server 8000
```
