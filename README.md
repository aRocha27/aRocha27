<h1 align="center">Hi, I'm Antonio Rocha 👋</h1>

<p align="center">
  <em>Computer Science Engineering student · AI/ML & full-stack systems builder</em><br/>
  Hamburg, DE 🇩🇪 · Coimbra, PT 🇵🇹
</p>

<p align="center">
  BSc Computer Science Engineering (European Programme) @ <a href="https://www.isec.pt/">Instituto Politécnico de Coimbra</a><br/>
  Erasmus+ EU mobility @ HAW Hamburg (2025–2026) · expected graduation March 2027
</p>

---

I'm an AI/ML and full-stack engineer who actually ships — from a monetized
production SaaS to a local-first AI agent OS with hash-chained audit logs and a
hand-implemented transformer in PyTorch. I work **security-first** by instinct:
TOCTOU-safe billing with Postgres advisory locks, prompt-injection defenses, and
the discipline to know what *not* to ship. I'm motivated by honest,
well-architected AI that reaches production — not demos.

## 🚀 Featured Projects

### Public

| Project | What it is | Stack |
|---|---|---|
| [`atlas-agent-os`](https://github.com/aRocha27/atlas-agent-os) | Local-first AI agent orchestration OS — a layered permission pipeline (Tool Gateway → Permission Broker → Guardian), a SHA-256 hash-chained append-only audit log with verifier, and streaming Ollama tool-use with capability-scored agent assignment | TypeScript · Node/Express · Next.js · SQLite |
| [`llm-from-scratch`](https://github.com/aRocha27/llm-from-scratch) | A transformer built from scratch in PyTorch — character tokenizer, sinusoidal positional encoding, single-head self-attention, causal masking, pre-norm GPT blocks, LM head + next-token loss. No `nn.MultiheadAttention`/`nn.Transformer` | Python · PyTorch · NumPy |
| [`rocha-tea`](https://github.com/aRocha27/rocha-tea) | Tea e-commerce MVP — server-validated Stripe checkout, Supabase RLS schema, and a hand-written GLSL silk-flow shader on the marketing site | Express · Supabase · Stripe · Next.js · Three.js |
| [`sonarWork`](https://github.com/aRocha27/sonarWork) | Underwater object detection on Ping360 sonar scans — YOLOv8 trained over 200 epochs, with a red-excess + density post-processor that classifies each detection into low/medium/high acoustic reflection | Python · ultralytics · OpenCV |
| [`dd-devdiary`](https://github.com/aRocha27/dd-devdiary) | VS Code extension to save, organize, and annotate code snippets as structured notes — tags, priorities, gutter indicators, and JSON/TXT export | TypeScript · VS Code API · esbuild |

### Private 🔒 (available on request)

| Project | What it is | Stack |
|---|---|---|
| 🔒 [Percorsi — AI Travel Planner SaaS](https://github.com/Sir-Olexander/Percorsi) <sub>(group project)</sub> | AI travel-planner SaaS, shipped & monetized at perkorsi.com — TOCTOU-safe billing caps with `pg_advisory_xact_lock`, a custom PL/pgSQL rate limiter, and Efraimidis-Spirakis weighted + geo-diverse trending; shared entitlements across web + Expo mobile | Next.js · Supabase · Stripe · Groq · Expo |
| 🔒 [Energy-System Optimization (Oxford OPEN)](https://github.com/aRocha27/EnergieInformatikPrject) | Scheduling flexible energy resources with Oxford's OPEN framework — MILP optimization for EV smart-charging, building HVAC, and a 10-house community battery on a 3-phase distribution network, with benchmark runs | Python · PICOS · pandapower · cvxopt |
| 🔒 [Robotics Lab — Control & Simulation](https://github.com/aRocha27/Int.RoboticsKursB) | Hands-on robotics labs: PID control on Arduino/ELEGOO hardware, cart-pole and self-balancing-robot dynamics, and Husky rover navigation in Gazebo simulation | Arduino · Gazebo · ROS · Python |
| 🔒 [Distributed Systems — RPC Framework](https://github.com/miguelrealinho/DistributedSystems) <sub>(group project)</sub> | A custom RPC framework — JavaCC parser-compiled message grammar, JSON serialization, client/server stubs, and a registry-based robot-coordination demo | Java · JavaCC · Jackson |
| 🔒 [War & Wit: Nation Commanders](https://github.com/rafa9-labs/allmighty) <sub>(collab)</sub> | Geopolitical strategy PWA game — AFK progression, gacha leader collection, PvE campaigns, and PvP battles; offline-first via a service worker | JavaScript · PWA |

## 🛠️ Tech Stack

**Languages:** Python · TypeScript/JavaScript · SQL · Java · Bash · GLSL
**AI/ML:** PyTorch · LLM engineering · RAG · agent orchestration · tool-use · MCP · prompt-injection defense
**Backend:** Node/Express · FastAPI · Next.js API routes · pnpm + Turborepo
**Frontend:** React/Next.js · Tailwind · Radix/shadcn · Expo/React Native · Three.js
**Data:** PostgreSQL (RLS, PL/pgSQL, advisory locks) · PostGIS · Supabase · DuckDB · SQLite · ChromaDB
**Systems & security:** Electron · Monaco · LSP/node-pty · hash-chained audit logs · permission pipelines
**DevOps:** Docker · Caddy · GitHub Actions · GitLab CI · Vercel · Vitest/Playwright

## 🎓 Education

- **BSc in Computer Science Engineering — European Programme** — Instituto Politécnico de Coimbra, Portugal (expected March 2027)
- **Erasmus+ (EU mobility programme)** — HAW Hamburg, Germany (2025–2026)
  - Coursework: AI Engineering, Introduction to Robotics, Distributed Systems, Energy Informatics
  - Thesis: *Distributed AI for Public Procurement Audit* — Benford's Law anomaly detection over Portuguese public-procurement data (Python, DuckDB, scipy)

## 🌍 Languages

Portuguese (native) · English (C1) · German (A1.2, actively learning)

---

<p align="center"><em>Three recurring themes across my work: security-first systems, architectural discipline, and range across the stack.</em></p>