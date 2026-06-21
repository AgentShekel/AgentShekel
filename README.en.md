[Русский](./README.md) · **English**

Product and AI-implementation manager. 13 years in IT.
I build products that turn a profit, design multi-agent systems, and embed them into business processes.

📫 Telegram [@agent_shekel](https://t.me/agent_shekel)

What I do and have done is below.

---

## Open source

### [agentic-workflow](https://github.com/AgentShekel/agentic-workflow)

Multi-agent development framework for Claude Code: tier-aware acceptance (S/M/L), isolated adversary review, a second opinion from a different model family via Codex MCP, an acceptor/optimizer role split, a self-learning skills loop based on Microsoft SkillOpt, observability through an event ledger, and a human as the final judge at critical steps.

Stack: Python, LangGraph, Pydantic, SQLite, Claude, Codex, MCP, JavaScript

### [hh-bot](https://github.com/AgentShekel/hh-bot)

Telegram bot for job search: browser automation, vacancy relevance scoring, cover-letter generation, a Telegram bot interface.

Stack: Python, aiogram, Playwright, SQLite

---

## Case studies

I own the architecture, model choices, and economics; I assemble the implementation by orchestrating models. Architecture write-ups are open in the repositories.

### [call-analytics-system](https://github.com/AgentShekel/call-analytics-system)

Call analytics service for sales and customer-service teams: pulls calls from the CRM, runs speech recognition, transcription, diarization, and LLM scoring, and returns the result with detailed recommendations on each conversation. Delivered as SaaS and on-premise, with model providers behind an abstraction. I led the architecture, implementation, model and cost choices, unit economics, and analysis quality. Modules built for Bitrix24 (cloud and on-premise), AmoCRM, Planfix.

Stack: Python, FastAPI, PostgreSQL, Celery, Redis, React, TypeScript

### [content-generation-pipeline](https://github.com/AgentShekel/content-generation-pipeline)

Content generation platform: analytics, content generation, a pipeline builder, reusable stages, human review as a dedicated stage, multi-channel publishing. Stages snap together like building blocks, so a new scenario does not need to be built from scratch.

Stack: Python, FastAPI, PostgreSQL, Celery, Redis, React, TypeScript

### [site-generator](https://github.com/AgentShekel/site-generator)

A platform that generates sites optimized for both classic and AI search from a ready semantic core. The generation pipeline is predictable, and per-field source tracking lets you edit content by hand without losing changes on regeneration. Each site is generated with an admin panel that simplifies further support and operation.

Stack: Python, FastAPI, PostgreSQL, Jinja2, HTMX, Caddy

---

## Products

B2B SaaS products I ran as product manager (roadmap, priorities, requirements, acceptance).

### [Seodroid](https://seodroid.ru)

SaaS for automating Yandex.Direct: bidding strategies, rules and schedules, position control, dynamic ad generation from price feeds, auto-UTM, role-based access. For advertisers and agencies.

### [Datadroid](https://datadroid.ru)

SaaS ETL service for end-to-end analytics: connectors to ad systems, web analytics, CRMs, and marketplaces, export to warehouses and BI, cloud and on-premise, no-code source setup.

---

## Examples of sites I worked on

- ВЦЭРМ МЧС России, EMERCOM medical center, [nrcerm.ru](https://nrcerm.ru)
- «Выбор», industrial battery distributor, [wybor-battery.com](https://wybor-battery.com)
- МИРПАК, packaging manufacturer, [mirpack.ru](https://mirpack.ru)
- ГТС, warehouse racking and equipment, [gts.systems](https://gts.systems)
- Manupackaging, packaging equipment, [manupackaging.ru](https://manupackaging.ru)
- FrenchPharmacy, pharmacy cosmetics, [frenchpharmacy.ru](https://frenchpharmacy.ru)
- Домотехника, fireplaces and heating equipment, [kamin.ru](https://kamin.ru)
- Cardplace, board games, [cardplace.ru](https://cardplace.ru)
- Светодиоды России, LED screens, [svetodiodyrossii.ru](https://svetodiodyrossii.ru)
- KELI, load cells and weighing equipment, [keli.ru](https://keli.ru)
- БелДорТехника, road and special machinery, [dks-tehnika.ru](https://dks-tehnika.ru)
- Eden-stone, engineered stone products, [eden-stone.ru](https://eden-stone.ru)
- VULKAN, modular chimneys, [dymohodvulkan.ru](https://dymohodvulkan.ru)
- SmartLift, warehouse equipment, [smartlift.ru](https://smartlift.ru)
- Горторгснаб, warehouse equipment, [gortorgsnab.ru](https://gortorgsnab.ru)
- Metbiz, metal furniture, [metbiz.ru](https://metbiz.ru)
- Kamaspring, spring manufacturing, [kamaspring.ru](https://kamaspring.ru)
- ДАР, packaging and eco goods, [dareco.ru](https://dareco.ru)
- Петровский, car dealership, [petrovskiy.ru](https://petrovskiy.ru)
- Kazan Palace, hotel, [kazanpalace.com](https://kazanpalace.com)

---

## CRM modules

Modules for Planfix CRM:

- [Marketing agency services](https://planfix.ru/configurations/uslugi-merketingovyx-agenstv2-p244/)
- [Sales funnel](https://planfix.ru/configurations/voronka-prodazh-p244/)
- [Employee surveys](https://planfix.ru/configurations/provedenie-oprosa-sotrudnikov-p244/)
- [Time tracking](https://planfix.ru/configurations/rabochee-vremya-p244/)
- [Request for response and review on a task](https://planfix.ru/configurations/podklyuchenie-sotrudnikov-k-zadache-nuzhen-otvet--proverka-p244/)
- [Finding and managing duplicate contacts](https://planfix.ru/configurations/poisk-i-kontrol-dublikatov-kontaktov-p244/)

---

## Certificates

Anthropic (Claude and platform, agents and MCP, AI Fluency) and OpenAI Academy, 2026.
