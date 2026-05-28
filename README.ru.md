**Русский** · [English](./README.md)

# Дмитрий Сильнов

AI Product Lead — проектирую, собираю и довожу до продакшена
LLM-продукты.

13 лет в IT. Начинал с сетевого и системного администрирования,
прошёл через проджект-менеджмент, последние несколько лет — глубоко
в LLM-инженерии и AI-продуктах. Комфортно держу одновременно
архитектуру, код и продуктовые решения на небольшой команде — это
та роль, где один человек выбирает модель, проектирует агентский
флоу, пишет API и смотрит логи в проде.

📫 Telegram [@Crimson_Beherit](https://t.me/Crimson_Beherit)

---

## Избранные проекты

### [agentic-workflow](https://github.com/AgentShekel/agentic-workflow) — фреймворк многоагентной разработки на Claude Code

Tier-aware acceptance (S/M/L), filesystem-isolated adversary-проверки
в свежих subprocess'ах, cross-family второе мнение через Codex MCP
(GPT-5), разделение ролей acceptor/optimizer (per-engagement менеджеры
vs out-of-band оптимизаторы SkillOpt-стиля), event ledger observability,
человек как supreme judge на критических переходах.
66 специализированных агентов, 48 методологических skills,
14 + 3 Python-скрипта оркестрации, 2 LangGraph движка с native HITL
`interrupt()`.

Решает три типичных провала single-model agent pipelines: framing
contamination, Goodhart на validators, undifferentiated rigour.

Стек: Python · LangGraph · Pydantic · SQLite · Claude · Codex · MCP · Mermaid

---

### [call-analytics-system](https://github.com/AgentShekel/call-analytics-system) — LLM-сервис речевой аналитики звонков (case-study)

Продакшен-сервис для анализа звонков отдела продаж и клиентского
сервиса. Приём звонков из CRM, STT + диаризация + LLM-оценка, push
результата обратно. SaaS с готовностью к on-premise через
провайдер-абстракции. End-to-end ownership: архитектура, backend,
frontend, деплой.

Стек: Python · FastAPI · async SQLAlchemy · Celery · Redis ·
PostgreSQL · React · TypeScript · Fernet encryption · JWT + RBAC

---

### [content-generation-pipeline](https://github.com/AgentShekel/content-generation-pipeline) — композируемая платформа генерации контента (case-study)

Multi-tenant платформа с UI-конструктором пайплайнов, переиспользуемыми
стадиями, human-in-the-loop approval как полноценным типом стадии и
многоканальным расписанием публикаций. Соло full-stack от идеи до
эксплуатации.

Стек: Python · FastAPI · async SQLAlchemy · Celery · Redis ·
PostgreSQL · React · TypeScript · Fernet encryption · JWT

---

### [hh-bot](https://github.com/AgentShekel/hh-bot) — Telegram-бот с LLM-фильтрацией вакансий

Browser-automation пайплайн для поиска вакансий, LLM-оценка
релевантности с маршрутизацией по баллу (автодействие / ручное /
пропуск), генерация сопроводительных, autopilot-цикл с доставкой в
Telegram.

Стек: Python · aiogram · Playwright · SQLite · OpenAI-совместимый
LLM-клиент

---

## Что я делаю

**AI и LLM-инженерия**
Проектирую агентские воркфлоу, подбираю модели под задачу, занимаюсь
prompt engineering, RAG, evaluation. Уверенно работаю с основными
LLM-провайдерами — Anthropic, OpenAI, Google — плюс open-weight
варианты для cost-sensitive кейсов, и понимаю разницу между ними на
уровне которое важно day-to-day: context window, семантика tool-use,
надёжность вывода, латентность. Применяю две парадигмы — **Individual
AI** (персональные скиллы и агенты для одного сотрудника) и
**Institutional AI** (агенты, встроенные в командные и продуктовые
процессы).

**Backend**
Python — основной язык. Async веб-сервисы и API, очереди задач и
background workers, ORM, message broker, реляционные и key-value
хранилища. Уверенно с базовыми вопросами безопасности при выводе
сервиса в продакшен: auth, шифрование at rest, rate-limit, валидация
ввода, OWASP top-10 surface.

**Frontend**
Экосистема React + TypeScript для внутренних инструментов,
админок, дашбордов и продуктовых UI. Component-библиотеки, design
tokens, графики. Не профильный фронтендер, но уровень достаточный,
чтобы собрать продукт когда отдельного фронтенд-разработчика в
команде нет.

**Эксплуатация и деплой**
Docker, администрирование Linux (Ubuntu / CentOS / Debian), Git
workflows, CI/CD пайплайны (GitLab CI, GitHub Actions). Уверенно
довожу чистый VPS до рабочего боевого сервера: nginx, systemd,
TLS, мониторинг, алертинг. Делал это и на bare-metal, и на
managed-платформах.

**Управление продуктом и проектами**
PM-опыт с 2018 года, в том числе ведение до 25 параллельных
клиентских проектов в направлении веб-разработки. Методология под
проект — Scrum, Kanban, LeSS, гибриды с Waterfall — а не один
шаблон на всё. Discovery, постановка KPI, stakeholder management,
контроль скоупа и бюджета, найм и онбординг на небольших командах.

**Инфраструктурный фундамент** (ранний этап карьеры)
Несколько лет работал сисадмином, потом руководил IT-отделом — до
перехода в PM и AI. Сети (MikroTik / Cisco), Active Directory,
Windows Server, администрирование Linux-серверов, телефония
(Asterisk), мониторинг. Полезный бэкграунд для end-to-end
AI-продуктов — когда что-то ломается ниже application layer, могу
спуститься и разобраться.

---

## Открыт к предложениям

AI Product Lead · AI Implementation Lead · AI Product Manager ·
solo или lead engineer роли в небольших AI-продуктовых командах.
