# Awesome OpenClaw [![Awesome](https://awesome.re/badge.svg)](https://github.com/sindresorhus/awesome) [![CI](https://img.shields.io/github/actions/workflow/status/vincentkoc/awesome-openclaw/ci.yml?label=CI)](https://github.com/vincentkoc/awesome-openclaw/actions/workflows/ci.yml) [![Link Check](https://img.shields.io/github/actions/workflow/status/vincentkoc/awesome-openclaw/ci.yml?label=Link%20Check)](https://github.com/vincentkoc/awesome-openclaw/actions/workflows/ci.yml) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

**[English](README.md) | [简体中文](README.zh-CN.md) | [日本語](README.ja.md) | [한국어](README.ko.md) | [Español](README.es.md) | [Deutsch](README.de.md) | [Français](README.fr.md) | [Русский](README.ru.md)**

![Awesome OpenClaw Banner](banner.jpg)

Кураторский список высокосигнальных ресурсов по **OpenClaw** (ранее **Moltbot**, изначально **Clawdbot**): фреймворки, навыки, инструменты, деплой и реальные кейсы.

OpenClaw — это open-source фреймворк self-hosted AI-агентов, который связывает LLM с инструментами, каналами сообщений и системами памяти, чтобы агенты выполняли реальные рабочие процессы. Ранее проект назывался Moltbot и Clawdbot; он рассчитан на расширяемость через skills, плагины и интеграции экосистемы.

<a id="navigation"></a>

## Навигация

- [Альтернативные архитектуры](#alternative-architectures)
- [Каналы сообщества](#community-channels)
- [Вклад](#contributing)
- [Подборки](#curated-collections)
- [Инструменты разработки и наблюдаемость](#developer-tooling-and-observability)
- [Развертывание и эксплуатация](#deployment-and-operations)
- [Лицензия](#license)
- [Локализация и региональные форки](#localization-and-regional-forks)
- [MCP и серверы инструментов](#mcp-and-tool-servers)
- [Медиа и статьи](#media-and-papers)
- [Память и контекст](#memory-and-context-systems)
- [Официальные ресурсы](#official-resources)
- [Плагины и интеграции](#plugins-and-integrations)
- [Навыки и индексы](#skills-and-skill-indexes)

<a id="status-markers"></a>

## Метки статуса

- 🎖️ Официальный ресурс, поддерживаемый OpenClaw (репозиторий организации, официальная документация или каналы).
- 💵 Для полного использования часто требуется платный сервис/тариф.

## Примечание по безопасности

Плагины, навыки, MCP-серверы и интеграции сообщества могут выполнять код, работать с учетными данными, отправлять сообщения и получать доступ к внешним системам. По умолчанию считайте их недоверенными.

Только записи с `🎖️` являются официальными ресурсами, поддерживаемыми OpenClaw. Записи сообщества добавлены для discovery, а не как результат проверки безопасности или официальной рекомендации. Перед использованием проверьте исходный код, разрешения, шаги установки и статус поддержки.

---

<a id="community-channels"></a>

## Каналы сообщества

- [4claw.org](https://www.4claw.org) - Имиджборд в стиле 4chan для автономных разговоров агентов.
- [Clawk](https://www.clawk.ai/) - Соцсеть в стиле Twitter, где агенты публикуют, подписываются, ставят лайки и репостят короткие обновления.
- [GitHub Issues](https://github.com/openclaw/openclaw/issues) - Отчеты об ошибках и запросы функций для ядра OpenClaw. 🎖️
- [MoltBook](https://www.moltbook.com/) - Социальная платформа agent-first, связанная с более широким Molt-экосистемой.
- [Moltbook](https://moltbookai.net) - Соцсеть в стиле Reddit для AI-агентов, где люди могут только наблюдать взаимодействия.
- [MoltHub](https://moithub.com/) - Платформа агентов с тематикой adult-моделей.
- [MoltThreats](https://promptintel.novahunting.ai/molt) - Первый threat intelligence фид для AI-агентов: делитесь новыми угрозами и получайте автоматическую защиту.
- [Moltx](https://moltx.io/) - Лента в стиле X с ответами, лайками и подписками.
- [Shellmates](https://www.shellmates.app) - Сервис матчмейкинга, который подбирает агентам собеседников для краткой и долгой переписки.

<a id="alternative-architectures"></a>

## Альтернативные архитектуры

- [gavrielc/nanoclaw](https://github.com/qwibitai/nanoclaw) - Легкая альтернативная архитектура/реализация в экосистеме OpenClaw. ![GitHub stars](https://img.shields.io/github/stars/qwibitai/nanoclaw?style=social)
- [HKUDS/nanobot](https://github.com/HKUDS/nanobot) - Ультралегкая реализация персонального AI-ассистента. ![GitHub stars](https://img.shields.io/github/stars/HKUDS/nanobot?style=social)
- [jlia0/tinyclaw](https://github.com/jlia0/tinyclaw) - OpenClaw на 400 строках кода. ![GitHub stars](https://img.shields.io/github/stars/jlia0/tinyclaw?style=social)
- [microclaw/microclaw](https://github.com/microclaw/microclaw) - Ассистент на Rust с выполнением инструментов. ![GitHub stars](https://img.shields.io/github/stars/microclaw/microclaw?style=social)
- [memovai/mimiclaw](https://github.com/memovai/mimiclaw) - Превращает маленькую плату ESP32-S3 в персонального AI-ассистента. ![GitHub stars](https://img.shields.io/github/stars/memovai/mimiclaw?style=social)
- [nearai/ironclaw](https://github.com/nearai/ironclaw) - Реализация на Rust, вдохновленная OpenClaw, с фокусом на приватность и безопасность. ![GitHub stars](https://img.shields.io/github/stars/nearai/ironclaw?style=social)
- [puremachinery/carapace](https://github.com/puremachinery/carapace) - Безопасностно-ориентированная реализация с sandboxing и изоляцией плагинов. ![GitHub stars](https://img.shields.io/github/stars/puremachinery/carapace?style=social)
- [sipeed/picoclaw](https://github.com/sipeed/picoclaw) - Реализация на Go: работает на $10 железе с <10MB RAM. ![GitHub stars](https://img.shields.io/github/stars/sipeed/picoclaw?style=social)
- [ysz/nanoClaw](https://github.com/ysz/nanoClaw) - Легкий и более безопасный ассистент с быстрым стартом. ![GitHub stars](https://img.shields.io/github/stars/ysz/nanoClaw?style=social)

<a id="official-resources"></a>

## Официальные ресурсы

- [OpenClaw Website](https://openclaw.ai) - Главная страница продукта и проекта. 🎖️
- [OpenClaw Docs](https://docs.openclaw.ai) - Основной портал документации. 🎖️
- [Getting Started](https://docs.openclaw.ai/start/getting-started) - Самый быстрый путь к рабочей установке. 🎖️
- [Plugin Docs](https://docs.openclaw.ai/tools/plugin) - Официальное руководство по разработке и запуску плагинов. 🎖️
- [Skills Docs](https://docs.openclaw.ai/tools/skills) - Официальная документация по модели и использованию навыков. 🎖️
- [openclaw/openclaw](https://github.com/openclaw/openclaw) - Репозиторий основного фреймворка ассистента. 🎖️ ![GitHub stars](https://img.shields.io/github/stars/openclaw/openclaw?style=social)
- [openclaw/clawhub](https://github.com/openclaw/clawhub) - Official skill registry source. 🎖️ ![GitHub stars](https://img.shields.io/github/stars/openclaw/clawhub?style=social)
- [openclaw/skills](https://github.com/openclaw/skills) - Archived historical skill versions. 🎖️ ![GitHub stars](https://img.shields.io/github/stars/openclaw/skills?style=social)

<a id="curated-collections"></a>

## Подборки

- [hesamsheikh/awesome-openclaw-usecases](https://github.com/hesamsheikh/awesome-openclaw-usecases) - Реальные паттерны использования и примеры по доменам. ![GitHub stars](https://img.shields.io/github/stars/hesamsheikh/awesome-openclaw-usecases?style=social)
- [VoltAgent/awesome-openclaw-skills](https://github.com/VoltAgent/awesome-openclaw-skills) - Крупный индекс навыков OpenClaw от сообщества (с контекстом переименований). ![GitHub stars](https://img.shields.io/github/stars/VoltAgent/awesome-openclaw-skills?style=social)

<a id="skills-and-skill-indexes"></a>

## Навыки и индексы

Большинство записей ниже поддерживаются сообществом и не проверяются OpenClaw. Только записи с `🎖️` являются официальными.

- [BankrBot/openclaw-skills](https://github.com/BankrBot/openclaw-skills) - Библиотека навыков сообщества с фокусом на автоматизацию и финансы. ![GitHub stars](https://img.shields.io/github/stars/BankrBot/openclaw-skills?style=social)
- [clawdbot/skills](https://github.com/openclaw/skills) - Устаревший alias-путь к историческому архиву навыков. ![GitHub stars](https://img.shields.io/github/stars/openclaw/skills?style=social)
- [jdrhyne/agent-skills](https://github.com/jdrhyne/agent-skills) - Пакеты навыков агента и переиспользуемые расширения рабочих процессов. ![GitHub stars](https://img.shields.io/github/stars/jdrhyne/agent-skills?style=social)
- [lekt9/unbrowse-openclaw](https://github.com/lekt9/unbrowse-openclaw) - Workflow генерации API-навыков из захваченного web/API-трафика. ![GitHub stars](https://img.shields.io/github/stars/lekt9/unbrowse-openclaw?style=social)
- [openclaw/clawhub](https://github.com/openclaw/clawhub) - Официальный каталог навыков и точка обнаружения. 🎖️ ![GitHub stars](https://img.shields.io/github/stars/openclaw/clawhub?style=social)
- [openclaw/skills](https://github.com/openclaw/skills) - Архивные версии навыков, опубликованных в ClawHub. 🎖️ ![GitHub stars](https://img.shields.io/github/stars/openclaw/skills?style=social)
- [pors/skill-audit](https://github.com/pors/skill-audit) - Набор для аудита навыков, валидации и усиления качества навыков. ![GitHub stars](https://img.shields.io/github/stars/pors/skill-audit?style=social)
- [runkids/skillshare](https://github.com/runkids/skillshare) - Шеринг и синхронизация пакетов навыков между AI-инструментами для кодинга. ![GitHub stars](https://img.shields.io/github/stars/runkids/skillshare?style=social)
- [Skills.sh OpenClaw Directory](https://skills.sh/openclaw/openclaw) - Сторонний каталог для поиска навыков OpenClaw.
- [Virtual-Protocol/openclaw-acp](https://github.com/Virtual-Protocol/openclaw-acp) - Пакет навыков Agent Commerce Protocol для commerce-флоу. ![GitHub stars](https://img.shields.io/github/stars/Virtual-Protocol/openclaw-acp?style=social)

<a id="plugins-and-integrations"></a>

## Плагины и интеграции

Большинство записей ниже поддерживаются сообществом и не проверяются OpenClaw. Только записи с `🎖️` являются официальными.

- [11haonb/wecom-openclaw-plugin](https://github.com/11haonb/wecom-openclaw-plugin) - Плагин корпоративного мессенджинга WeCom (WeChat Work). ![GitHub stars](https://img.shields.io/github/stars/11haonb/wecom-openclaw-plugin?style=social)
- [AlexAnys/feishu-openclaw](https://github.com/AlexAnys/feishu-openclaw) - Плагин интеграции Feishu/Lark с упрощенным self-hosted сетапом. ![GitHub stars](https://img.shields.io/github/stars/AlexAnys/feishu-openclaw?style=social)
- [ClariSortAi/openclaw-manager-plugin](https://github.com/ClariSortAi/openclaw-manager-plugin) - Менеджер жизненного цикла для установки и настройки. ![GitHub stars](https://img.shields.io/github/stars/ClariSortAi/openclaw-manager-plugin?style=social)
- [DNYoussef/guardspine-openclaw](https://github.com/DNYoussef/guardspine-openclaw) - Governance-плагин с deny-by-default гейтингом и уровнями риска. ![GitHub stars](https://img.shields.io/github/stars/DNYoussef/guardspine-openclaw?style=social)
- [hyperspell/hyperspell-openclaw](https://github.com/hyperspell/hyperspell-openclaw) - Интеграция плагина HyperSpell для workflow OpenClaw. ![GitHub stars](https://img.shields.io/github/stars/hyperspell/hyperspell-openclaw?style=social)
- [limouren01/openclaw_qq_plugin](https://github.com/limouren01/openclaw_qq_plugin) - Плагин канала QQ для интеграции с китайскими платформами. ![GitHub stars](https://img.shields.io/github/stars/limouren01/openclaw_qq_plugin?style=social)
- [m1heng/clawdbot-feishu](https://github.com/m1heng/clawdbot-feishu) - Плагин канала Feishu/Lark с поддержкой enterprise-ботов. ![GitHub stars](https://img.shields.io/github/stars/m1heng/clawdbot-feishu?style=social)
- [marshallrichards/ClawPhone](https://github.com/marshallrichards/ClawPhone) - Мобильный компаньон с phone-first интерфейсом для workflow. ![GitHub stars](https://img.shields.io/github/stars/marshallrichards/ClawPhone?style=social)
- [MemTensor/MemOS-Cloud-OpenClaw-Plugin](https://github.com/MemTensor/MemOS-Cloud-OpenClaw-Plugin) - Облачная память для постоянного воспоминания контекста. ![GitHub stars](https://img.shields.io/github/stars/MemTensor/MemOS-Cloud-OpenClaw-Plugin?style=social)
- [rickybloomfield/OuraClaw](https://github.com/rickybloomfield/OuraClaw) - Плагин интеграции Oura: сон, readiness и сводки активности. ![GitHub stars](https://img.shields.io/github/stars/rickybloomfield/OuraClaw?style=social)
- [soimy/openclaw-channel-dingtalk](https://github.com/soimy/openclaw-channel-dingtalk) - Плагин корпоративного канала DingTalk с поддержкой стриминга. ![GitHub stars](https://img.shields.io/github/stars/soimy/openclaw-channel-dingtalk?style=social)
- [techartdev/OpenClawHomeAssistant](https://github.com/techartdev/OpenClawHomeAssistant) - Дополнение Home Assistant с интеграцией на уровне сущностей. ![GitHub stars](https://img.shields.io/github/stars/techartdev/OpenClawHomeAssistant?style=social)

<a id="mcp-and-tool-servers"></a>

## MCP и серверы инструментов

- [androidStern-personal/openclaw-mcp-adapter](https://github.com/androidStern-personal/openclaw-mcp-adapter) - адаптер для нативного доступа к инструментам OpenClaw. ![GitHub stars](https://img.shields.io/github/stars/androidStern-personal/openclaw-mcp-adapter?style=social)
- [Enderfga/openclaw-claude-code-skill](https://github.com/Enderfga/openclaw-claude-code-skill) - Интеграция навыка Claude Code в OpenClaw через MCP. ![GitHub stars](https://img.shields.io/github/stars/Enderfga/openclaw-claude-code-skill?style=social)
- [Helms-AI/openclaw-mcp-server](https://github.com/Helms-AI/openclaw-mcp-server) - MCP-сервер, который публикует инструменты OpenClaw Gateway. ![GitHub stars](https://img.shields.io/github/stars/Helms-AI/openclaw-mcp-server?style=social)

<a id="media-and-papers"></a>

## Медиа и статьи

- [Clawdbot Showed Me What the Future of Personal AI Assistants Looks Like](https://www.macstories.net/stories/clawdbot-showed-me-what-the-future-of-personal-ai-assistants-looks-like/) - Материал MacStories о ранних персональных агентных workflow Clawdbot/OpenClaw.

<a id="memory-and-context-systems"></a>

## Память и контекст

- [Mem0 persistent OpenClaw memory](https://docs.mem0.ai/integrations/openclaw) - Документация интеграции для постоянной памяти с Mem0. 💵
- [memovai/memov](https://github.com/memovai/memov) - Слой памяти и toolkit для ретривала постоянного контекста OpenClaw. ![GitHub stars](https://img.shields.io/github/stars/memovai/memov?style=social)
- [MemTensor/MemOS](https://github.com/MemTensor/MemOS) - Memory OS, используемая в экосистеме OpenClaw. ![GitHub stars](https://img.shields.io/github/stars/MemTensor/MemOS?style=social)
- [NevaMind-AI/memU](https://github.com/NevaMind-AI/memU) - Слой памяти для долго живущих ассистентов. ![GitHub stars](https://img.shields.io/github/stars/NevaMind-AI/memU?style=social)
- [nhevers/MoltBrain](https://github.com/nhevers/MoltBrain) - Долгосрочная память для workflow агентов OpenClaw и MoltBook. ![GitHub stars](https://img.shields.io/github/stars/nhevers/MoltBrain?style=social)
- [oceanbase/powermem](https://github.com/oceanbase/powermem) - Долговременная память для потоков плагинов OpenClawd. ![GitHub stars](https://img.shields.io/github/stars/oceanbase/powermem?style=social)
- [vincentkoc/openamnesia](https://github.com/vincentkoc/openamnesia) - Контекстный движок непрерывного обучения, извлекающий безопасную память из реальной активности. ![GitHub stars](https://img.shields.io/github/stars/vincentkoc/openamnesia?style=social)
- [supermemory OpenClaw Integration Docs](https://supermemory.ai/docs/integrations/openclaw) - Официальный гайд по интеграции Supermemory с OpenClaw. 💵
- [supermemoryai/openclaw-supermemory](https://github.com/supermemoryai/openclaw-supermemory) - Плагин долгосрочной памяти на базе Supermemory. 💵 ![GitHub stars](https://img.shields.io/github/stars/supermemoryai/openclaw-supermemory?style=social)
- [thedotmack/claude-mem](https://github.com/thedotmack/claude-mem/) - Легкий слой памяти для сохранения контекста Claude/OpenClaw. ![GitHub stars](https://img.shields.io/github/stars/thedotmack/claude-mem?style=social)
- [tobi/qmd](https://github.com/tobi/qmd) - Markdown-нативные workflow памяти и знаний для постоянного контекста. ![GitHub stars](https://img.shields.io/github/stars/tobi/qmd?style=social)

<a id="developer-tooling-and-observability"></a>

## Инструменты разработки и наблюдаемость

- [bokonon23/clawdbot-cost-monitor](https://github.com/bokonon23/clawdbot-cost-monitor) - Монитор затрат и расходов для использования OpenClaw/Clawdbot. ![GitHub stars](https://img.shields.io/github/stars/bokonon23/clawdbot-cost-monitor?style=social)
- [ClawFOMO](https://clawfomo.com) - Монитор в реальном времени трендов и настроений активности экосистемы.
- [clawdeckio/clawdeck](https://github.com/clawdeckio/clawdeck) - Mission control дашборд для управления агентами OpenClaw. ![GitHub stars](https://img.shields.io/github/stars/clawdeckio/clawdeck?style=social)
- [crshdn/mission-control](https://github.com/crshdn/mission-control) - Дашборд оркестрации мульти-агентов для workflow OpenClaw Gateway. ![GitHub stars](https://img.shields.io/github/stars/crshdn/mission-control?style=social)
- [grp06/openclaw-studio](https://github.com/grp06/openclaw-studio) - Studio-стиль web IDE и UI управления workflow OpenClaw. ![GitHub stars](https://img.shields.io/github/stars/grp06/openclaw-studio?style=social)
- [ibelick/webclaw](https://github.com/ibelick/webclaw) - Быстрый веб-клиент для взаимодействия с OpenClaw. ![GitHub stars](https://img.shields.io/github/stars/ibelick/webclaw?style=social)
- [Intina47/context-sync](https://github.com/Intina47/context-sync) - Синхронизация контекста для multi-session agent workflow. ![GitHub stars](https://img.shields.io/github/stars/Intina47/context-sync?style=social)
- [iOfficeAI/AionUi](https://github.com/iOfficeAI/AionUi) - Локальный UI для управления и работы с OpenClaw-подобными агентными системами. ![GitHub stars](https://img.shields.io/github/stars/iOfficeAI/AionUi?style=social)
- [jasonkneen/vibeclaw](https://github.com/jasonkneen/vibeclaw) - Полноценный OpenClaw в браузере: визуальный конструктор серверов, песочница с бесплатными AI-моделями и библиотека серверов. Установка не требуется. ([vibeclaw.dev](https://vibeclaw.dev)) ![GitHub stars](https://img.shields.io/github/stars/jasonkneen/vibeclaw?style=social)
- [junhoyeo/tokscale](https://github.com/junhoyeo/tokscale) - Трекинг токенов и стоимости в workflow кодинг-ассистентов. ![GitHub stars](https://img.shields.io/github/stars/junhoyeo/tokscale?style=social)
- [kepano/obsidian-skills](https://github.com/kepano/obsidian-skills) - Переносимые паттерны skill-pack, полезные для дизайна навыков OpenClaw. ![GitHub stars](https://img.shields.io/github/stars/kepano/obsidian-skills?style=social)
- [luccast/crabwalk](https://github.com/luccast/crabwalk) - Компаньон для мониторинга сессий агентов OpenClaw. ![GitHub stars](https://img.shields.io/github/stars/luccast/crabwalk?style=social)
- [Hotmolts](https://www.hotmolts.com) - Ранжирование влиятельных агентов по соцграфу и сигналам вовлеченности.
- [MoltMatch](https://moltmatch.xyz) - Слой матчмейкинга и обнаружения для коллабораций агентов.
- [merciagents/riphook](https://github.com/merciagents/riphook) - Инструменты webhook и event-bridge для автоматизаций, управляемых агентами. ![GitHub stars](https://img.shields.io/github/stars/merciagents/riphook?style=social)
- [openclaw/lobster](https://github.com/openclaw/lobster) - Workflow shell для компоновки инструментов и автоматизаций OpenClaw. 🎖️ ![GitHub stars](https://img.shields.io/github/stars/openclaw/lobster?style=social)
- [OthmanAdi/planning-with-files](https://github.com/OthmanAdi/planning-with-files) - Паттерн навыка для планирования, используемый в agentic репозиториях. ![GitHub stars](https://img.shields.io/github/stars/OthmanAdi/planning-with-files?style=social)
- [prompt-security/clawsec](https://github.com/prompt-security/clawsec) - Набор безопасности с детекцией дрейфа, аудитами и проверкой целостности навыков. ![GitHub stars](https://img.shields.io/github/stars/prompt-security/clawsec?style=social)
- [rdsthomas/mission-control](https://github.com/rdsthomas/mission-control) - Kanban-панель для управления задачами в workflow OpenClaw. ![GitHub stars](https://img.shields.io/github/stars/rdsthomas/mission-control?style=social)
- [refly-ai/refly](https://github.com/refly-ai/refly) - Экосистема билдера навыков и workflow с пересечением с agent tooling. ![GitHub stars](https://img.shields.io/github/stars/refly-ai/refly?style=social)
- [shanselman/openclaw-windows-hub](https://github.com/shanselman/openclaw-windows-hub) - Windows-хаб-компаньон для десктопной интеграции. ![GitHub stars](https://img.shields.io/github/stars/shanselman/openclaw-windows-hub?style=social)
- [Unbrowse](https://www.unbrowse.ai/) - Платформа для преобразования браузерных workflow в API-интеграции и навыки агентов.

<a id="deployment-and-operations"></a>

## Развертывание и эксплуатация

### Управляемый хостинг и настройка

Эти провайдеры берут настройку на себя: без Docker, без терминала и без DevOps.

- [Agent37](https://www.agent37.com/openclaw) - Управляемый инстанс OpenClaw с быстрым запуском. 💵
- [ClawCloud](https://www.clawcloud.sh/) - Управляемый OpenClaw-хостинг с автообновлениями и бэкапами. 💵
- [ClawSimple](https://clawsimple.com/en) - Управляемый OpenClaw-хостинг с простыми тарифами и быстрым запуском. 💵
- [Contabo OpenClaw](https://contabo.com/en-us/openclaw-hosting/) - VPS-вариант хостинга OpenClaw с предсказуемой ценой. 💵
- [EasyClaw](https://www.easyclaw.pro/en) - Управляемый OpenClaw-сетап с поддержкой нескольких моделей. 💵
- [GetClawHelp](https://getclawhelp.com/) - Платная 1:1-помощь по установке OpenClaw на ваш VPS. 💵
- [Kilo Claw](https://kilo.ai/kiloclaw) - Управляемая OpenClaw-платформа с SSO и аудитом. 💵
- [MyClaw.ai](https://myclaw.ai/pricing) - Управляемый OpenClaw-инстанс с моментальным запуском и бэкапами. 💵
- [Myclawhost](https://www.myclawhost.com/) - Управляемый OpenClaw-хостинг с многоуровневыми тарифами. 💵
- [OpenClaw Cloud](https://openclawcloud.work/) - Управляемое облачное OpenClaw-предложение (бета). 💵
- [OpenClaw Hosting](https://openclawhosting.io/pricing) - Управляемый OpenClaw-хостинг с тарифами для solo и team. 💵
- [OpenClaw Voice](https://openclawvoice.com/) - Управляемый голосовой интерфейс OpenClaw в браузере. 💵
- [OpenClawd.ai](https://finance.yahoo.com/news/openclaw-introduces-secure-hosted-clawdbot-204800756.html) - Управляемое хостинговое OpenClaw-предложение (анонс). 💵
- [SimpleClaw](https://www.simpleclaw.com/) - Управляемый OpenClaw-хостинг (ранний доступ). 💵
- [xCloud](https://xcloud.host/openclaw-hosting) - Управляемый OpenClaw-хостинг с опциями зашифрованных бэкапов. 💵

### Self-hosted деплой и инфраструктура

- [1Panel-dev/1Panel](https://github.com/1Panel-dev/1Panel) - Self-hosted панель сервера, часто используемая для деплоя OpenClaw. ![GitHub stars](https://img.shields.io/github/stars/1Panel-dev/1Panel?style=social)
- [badrisnarayanan/antigravity-claude-proxy](https://github.com/badrisnarayanan/antigravity-claude-proxy) - Прокси и роутинг для доступа к моделям в workflow ассистентов. ![GitHub stars](https://img.shields.io/github/stars/badrisnarayanan/antigravity-claude-proxy?style=social)
- [ClawArena](https://clawarena.ai) - Арена прогнозов, где AI-агенты предсказывают рыночные исходы и соревнуются.
- [Clawstead](https://www.clawstead.com) - Постоянный симулированный мир, где агенты добывают, торгуют, строят и живут.
- [ClawTasks](https://clawtasks.com) - Bounty-обмен задачами для разовых цифровых работ.
- [cloudflare/moltworker](https://github.com/cloudflare/moltworker) - Путь деплоя на Cloudflare Workers для рантаймов, совместимых с OpenClaw. ![GitHub stars](https://img.shields.io/github/stars/cloudflare/moltworker?style=social)
- [coollabsio/openclaw](https://github.com/coollabsio/openclaw) - Автоматизированный Docker-поток для хостинга OpenClaw. ![GitHub stars](https://img.shields.io/github/stars/coollabsio/openclaw?style=social)
- [essamamdani/openclaw-coolify](https://github.com/essamamdani/openclaw-coolify) - Шаблон Coolify для упрощенного хостинга OpenClaw. ![GitHub stars](https://img.shields.io/github/stars/essamamdani/openclaw-coolify?style=social)
- [khal3d/openclaw](https://github.com/khal3d/openclaw) - Стек деплоя OpenClaw на контейнерах и Helm. ![GitHub stars](https://img.shields.io/github/stars/khal3d/openclaw?style=social)
- [miantiao-me/cloud-claw](https://github.com/miantiao-me/cloud-claw) - Деплой персонального OpenClaw на Cloudflare Containers. ![GitHub stars](https://img.shields.io/github/stars/miantiao-me/cloud-claw?style=social)
- [miaoxworld/OpenClawInstaller](https://github.com/miaoxworld/OpenClawInstaller) - Инсталлятор и автоматизация настройки. ![GitHub stars](https://img.shields.io/github/stars/miaoxworld/OpenClawInstaller?style=social)
- [MoltBunker](https://moltbunker.com) - Безопасный слой персистентности и хранения для агентов.
- [MoltCities](https://moltcities.org) - Слой идентичности и "проживания" с хэндлами и ключевой идентичностью.
- [Moltline](https://www.moltline.com) - Приватная инфраструктура сообщений для постоянных хэндлов и инбоксов.
- [Moltroad](https://www.moltroad.com/) - Маркетплейс сервисов, навыков и цифровых товаров с микроплатежами.
- [MyDeadInternet.com](https://mydeadinternet.com) - Коллективная платформа, где агенты вносят фрагменты памяти в общие результаты.
- [Openwork](https://openwork.bot) - Маркетплейс труда только для агентов: координация задач и ончейн-расчеты.
- [openclaw/clawdinators](https://github.com/openclaw/clawdinators) - Декларативный шаблон развертывания NixOS и AWS. 🎖️ ![GitHub stars](https://img.shields.io/github/stars/openclaw/clawdinators?style=social)
- [openclaw/homebrew-tap](https://github.com/openclaw/homebrew-tap) - Homebrew tap для установки OpenClaw на macOS. 🎖️ ![GitHub stars](https://img.shields.io/github/stars/openclaw/homebrew-tap?style=social)
- [openclaw/openclaw-ansible](https://github.com/openclaw/openclaw-ansible) - Усиленное автоматизированное развертывание с Ansible. 🎖️ ![GitHub stars](https://img.shields.io/github/stars/openclaw/openclaw-ansible?style=social)
- [Pamir AI](https://www.pamir.ai/) - Выделенный Linux-компьютер для AI-агентов, оптимизированный для 24/7 задач и удаленного доступа. 💵
- [RentAHuman](https://rentahuman.ai) - Маркетплейс, где агенты нанимают людей для физических задач.
- [serhanekicii/openclaw-helm](https://github.com/serhanekicii/openclaw-helm) - Helm chart для развертывания OpenClaw в Kubernetes. ![GitHub stars](https://img.shields.io/github/stars/serhanekicii/openclaw-helm?style=social)
- [Virtuals](https://www.virtuals.io) - Токенизированная инфраструктура AI-агентов для децентрализованного владения и монетизации.
- [vincentkoc/natilius](https://github.com/vincentkoc/natilius) - One-click настройка macOS инженерной среды для research, sandbox и агентных машин. ![GitHub stars](https://img.shields.io/github/stars/vincentkoc/natilius?style=social)

<a id="localization-and-regional-forks"></a>

## Локализация и региональные форки

- [1186258278/OpenClawChineseTranslation](https://github.com/1186258278/OpenClawChineseTranslation) - Репозиторий сетапа, сфокусированный на переводе. ![GitHub stars](https://img.shields.io/github/stars/1186258278/OpenClawChineseTranslation?style=social)
- [jiulingyun/openclaw-cn](https://github.com/jiulingyun/openclaw-cn) - OpenClaw-адаптация, ориентированная на Китай. ![GitHub stars](https://img.shields.io/github/stars/jiulingyun/openclaw-cn?style=social)

<a id="contributing"></a>

## Вклад

PR приветствуются для:

- Добавления качественных ссылок по экосистеме OpenClaw.
- Улучшения категоризации и качества разделов.
- Очистки битых ссылок и устаревших проектов.

Пожалуйста, добавьте короткую заметку о релевантности при отправке нового пункта.

<a id="license"></a>

## Лицензия

MIT. См. [`LICENSE`](LICENSE).

---

Made with 💙 by <a href="https://github.com/vincentkoc">Vincent Koc</a> · <a href="LICENSE">MIT</a>
