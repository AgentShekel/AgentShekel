[Русский](./README.ru.md) · **English**

# Dmitry Silnov

AI Product Lead — designing, building, and shipping LLM-driven
products end-to-end.

13 years in IT. Started in network and systems administration, moved
through project management, and the last few years went deep into
LLM engineering and AI product work. Comfortable owning architecture,
code, and product decisions on the same team — the kind of role where
the same person picks the model, designs the agent flow, writes the
API, and watches the production logs.

📫 Telegram [@agent_shekel](https://t.me/agent_shekel)

---

## Selected work

### [agentic-workflow](https://github.com/ElPinus/agentic-workflow) — multi-agent framework for Claude Code

Tier-aware acceptance (S/M/L), filesystem-isolated adversary review in
fresh subprocesses, cross-family second opinion via Codex MCP (GPT-5),
human as supreme judge at critical transitions. 60 specialized agents,
45 methodology skills, 21 Python orchestration scripts.

Solves three failure modes of single-model agent pipelines: framing
contamination, Goodhart on validators, and undifferentiated rigour.

Stack: Python · Claude · Codex · MCP · Mermaid

---

### [call-analytics-system](https://github.com/ElPinus/call-analytics-system) — LLM call analytics service (architecture case-study)

Production LLM service for sales / customer-service call analysis.
Ingests calls from CRMs, runs STT + diarization + LLM scoring,
pushes results back. SaaS with on-premise readiness via provider
abstractions. End-to-end ownership: architecture, backend, frontend,
deployment.

Stack: Python · FastAPI · async SQLAlchemy · Celery · Redis ·
PostgreSQL · React · TypeScript · Fernet encryption · JWT + RBAC

---

### [content-generation-pipeline](https://github.com/ElPinus/content-generation-pipeline) — composable content generation platform (architecture case-study)

Multi-tenant platform with a UI pipeline builder, reusable stages,
human-in-the-loop approvals as a first-class stage type, and
multi-channel publication scheduling. Solo full-stack ownership from
product idea to operations.

Stack: Python · FastAPI · async SQLAlchemy · Celery · Redis ·
PostgreSQL · React · TypeScript · Fernet encryption · JWT

---

### [hh-bot](https://github.com/ElPinus/hh-bot) — Telegram bot for LLM-driven job filtering

Browser-automation pipeline for vacancy search, LLM-based relevance
scoring with score-driven routing (auto-apply / manual / skip), cover
letter generation, autopilot loop with Telegram delivery.

Stack: Python · aiogram · Playwright · SQLite · OpenAI-compatible
LLM client

---

## What I do

**AI & LLM engineering**
Designing agentic workflows, picking models for the job, prompt
engineering, RAG, evaluation. Comfortable across major LLM
providers — Anthropic, OpenAI, Google — plus open-weight options for
cost-sensitive cases, and the differences that matter day-to-day:
context windows, tool-use semantics, output reliability, latency.
Two patterns I keep coming back to — **Individual AI** (personal-
productivity skills and agents for one employee) and **Institutional
AI** (agents wired into team and product processes).

**Backend**
Python is my main language. Async web services and APIs, task queues
and background workers, ORMs, message brokers, relational and key-
value storage. Comfortable with the security fundamentals you need
to take a service to production: auth, encryption at rest, rate
limiting, input validation, the OWASP top-10 surface.

**Frontend**
React + TypeScript ecosystem for internal tools, admin panels,
dashboards, and product UIs. Component libraries, design tokens,
charts. Not a frontend specialist by trade — but enough to ship a
product when there isn't a dedicated frontend developer on the team.

**Operations & deploy**
Docker, Linux administration (Ubuntu / CentOS / Debian), Git
workflows, CI/CD pipelines (GitLab CI, GitHub Actions). Comfortable
taking a clean VPS to a running production server: nginx, systemd,
TLS, monitoring, alerting. Have done this on bare-metal and on
managed platforms.

**Product & project management**
PM since 2018, including running up to 25 parallel client projects
in a web-development practice. Methodology picked per project —
Scrum, Kanban, LeSS, Waterfall hybrids — instead of forcing one
template. Discovery, KPI definition, stakeholder management, scope
and budget control, hiring and onboarding for small teams.

**Infrastructure roots** (earlier career)
Spent several years as a sysadmin, then leading an IT department,
before moving into PM and AI work. Networking (MikroTik / Cisco),
Active Directory, Windows Server, Linux server admin, telephony
(Asterisk), monitoring. Useful background for end-to-end AI products
— when something breaks below the application layer, I can go look.

---

## Open to opportunities

AI Product Lead · AI Implementation Lead · AI Product Manager ·
solo or lead engineer roles on small AI-product teams.
