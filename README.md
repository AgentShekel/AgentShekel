**Русский** · [English](./README.en.md)

Менеджер продуктов и внедрения AI. 13 лет в IT.
Делаю продукты, приносящие прибыль, проектирую многоагентные системы и встраиваю их в рабочие процессы.

📫 Telegram [@agent_shekel](https://t.me/agent_shekel)

Чем именно я занимаюсь или занимался можете ознакомиться ниже

---

## Открытый код

### [agentic-workflow](https://github.com/AgentShekel/agentic-workflow)

Фреймворк многоагентной разработки на Claude Code: приёмка по уровням сложности (S/M/L), изолированная adversary-проверка, второе мнение от модели другого семейства через Codex MCP, разделение ролей на приёмку и оптимизацию, петля самообучения на базе Microsoft SkillOpt, наблюдаемость через журнал событий, человек как финальный судья на критических шагах.

Стек: Python, LangGraph, Pydantic, SQLite, Claude, Codex, MCP, JavaScript

### [hh-bot](https://github.com/AgentShekel/hh-bot)

Telegram-бот для поиска вакансий: автоматизация браузера, оценка релевантности вакансий, генерация сопроводительных, интерфейс в телеграм-боте.

Стек: Python, aiogram, Playwright, SQLite

---

## Кейс-стади

Архитектуру, выбор моделей и экономику веду сам, реализацию собираю, оркеструя модели. Разборы архитектуры открыты в репозиториях.

### [call-analytics-system](https://github.com/AgentShekel/call-analytics-system)

Сервис речевой аналитики звонков для отделов продаж и сервиса: приём звонков из CRM, распознавание речи, транскрибация, диаризация и оценка через LLM, возврат результата обратно и детальные рекомендации по итогам разговора. Поставка как SaaS и on-premise, провайдеры моделей за абстракцией. Вёл архитектуру, реализацию, выбор моделей и стоимость, юнит-экономику и качество разбора. Реализованы модули для Битрикс 24 (облачный и коробочный), AmoCRM, Planfix.

Стек: Python, FastAPI, PostgreSQL, Celery, Redis, React, TypeScript

### [content-generation-pipeline](https://github.com/AgentShekel/content-generation-pipeline)

Платформа генерации контента: аналитика, генерация контента, конструктор пайплайнов, переиспользуемые стадии, проверка человеком как отдельная стадия, публикация по нескольким каналам. Стадии собираются как конструктор, новый сценарий не нужно делать с нуля.

Стек: Python, FastAPI, PostgreSQL, Celery, Redis, React, TypeScript

### [site-generator](https://github.com/AgentShekel/site-generator)

Платформа, которая генерирует сайты оптимизированные под классический и нейросетевой поиск из готового семантического ядра. Конвейер генерации предсказуемый, пофайловое отслеживание источника позволяет править контент руками и не терять правки при перегенерации. Сайт генерируется с админкой, облегчающей дальнейшую поддержку и эксплуатацию.

Стек: Python, FastAPI, PostgreSQL, Jinja2, HTMX, Caddy

---

## Продукты

B2B SaaS-продукты, которые вёл как менеджер продукта (роадмап, приоритеты, требования, приёмка).

### [Seodroid](https://seodroid.ru)

SaaS для автоматизации работы с Яндекс.Директ: стратегии ставок, правила и расписания, контроль позиций, динамическая генерация объявлений из прайсов, авто-UTM, ролевой доступ. Для рекламодателей и агентств.

### [Datadroid](https://datadroid.ru)

SaaS ETL-сервис для сквозной аналитики: коннекторы к рекламным системам, веб-аналитике, CRM и маркетплейсам, выгрузка в хранилища и BI, облако и on-premise, no-code подключение источников.

---

## Примеры сайтов, над которыми работал

- ВЦЭРМ МЧС России, медцентр МЧС, [nrcerm.ru](https://nrcerm.ru)
- «Выбор», дистрибьютор промышленных АКБ, [wybor-battery.com](https://wybor-battery.com)
- МИРПАК, производство упаковки, [mirpack.ru](https://mirpack.ru)
- ГТС, складские стеллажи и оборудование, [gts.systems](https://gts.systems)
- Manupackaging, упаковочное оборудование, [manupackaging.ru](https://manupackaging.ru)
- FrenchPharmacy, аптечная косметика, [frenchpharmacy.ru](https://frenchpharmacy.ru)
- Домотехника, камины и отопительное оборудование, [kamin.ru](https://kamin.ru)
- Cardplace, настольные игры, [cardplace.ru](https://cardplace.ru)
- Светодиоды России, светодиодные экраны, [svetodiodyrossii.ru](https://svetodiodyrossii.ru)
- KELI, тензодатчики и весоизмерительное оборудование, [keli.ru](https://keli.ru)
- БелДорТехника, дорожная и спецтехника, [dks-tehnika.ru](https://dks-tehnika.ru)
- Eden-stone, изделия из искусственного камня, [eden-stone.ru](https://eden-stone.ru)
- VULKAN, модульные дымоходы, [dymohodvulkan.ru](https://dymohodvulkan.ru)
- SmartLift, складская техника, [smartlift.ru](https://smartlift.ru)
- Горторгснаб, складское оборудование, [gortorgsnab.ru](https://gortorgsnab.ru)
- Metbiz, металлическая мебель, [metbiz.ru](https://metbiz.ru)
- Kamaspring, производство пружин, [kamaspring.ru](https://kamaspring.ru)
- ДАР, упаковка и эко-товары, [dareco.ru](https://dareco.ru)
- Петровский, автодилер, [petrovskiy.ru](https://petrovskiy.ru)
- Kazan Palace, отель, [kazanpalace.com](https://kazanpalace.com)

---

## Модули для CRM

Модули для CRM Planfix:

- [Услуги маркетинговых агентств](https://planfix.ru/configurations/uslugi-merketingovyx-agenstv2-p244/)
- [Воронка продаж](https://planfix.ru/configurations/voronka-prodazh-p244/)
- [Опросы сотрудников](https://planfix.ru/configurations/provedenie-oprosa-sotrudnikov-p244/)
- [Учёт рабочего времени](https://planfix.ru/configurations/rabochee-vremya-p244/)
- [Запрос ответа и проверки в задаче](https://planfix.ru/configurations/podklyuchenie-sotrudnikov-k-zadache-nuzhen-otvet--proverka-p244/)
- [Поиск и контроль дубликатов контактов](https://planfix.ru/configurations/poisk-i-kontrol-dublikatov-kontaktov-p244/)

---

## Сертификаты

Anthropic (Claude и платформа, агенты и MCP, AI Fluency) и OpenAI Academy, 2026.