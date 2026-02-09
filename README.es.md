# Awesome OpenClaw [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![CI](https://img.shields.io/github/actions/workflow/status/vincentkoc/awesome-openclaw/ci.yml?label=CI)](https://github.com/vincentkoc/awesome-openclaw/actions/workflows/ci.yml) [![Link Check](https://img.shields.io/github/actions/workflow/status/vincentkoc/awesome-openclaw/ci.yml?label=Link%20Check)](https://github.com/vincentkoc/awesome-openclaw/actions/workflows/ci.yml) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

**[English](README.md) | [简体中文](README.zh-CN.md) | [日本語](README.ja.md) | [한국어](README.ko.md) | [Español](README.es.md) | [Deutsch](README.de.md) | [Français](README.fr.md) | [Русский](README.ru.md)**

![Awesome OpenClaw Banner](banner.jpg)

Lista curada de recursos de alto valor para **OpenClaw** (antes **Moltbot**, originalmente **Clawdbot**): frameworks, skills, herramientas, despliegues y casos de uso reales.

OpenClaw es un framework de agentes de IA, open source y autoalojado, que conecta LLMs con herramientas, canales de mensajería y sistemas de memoria para ejecutar flujos de trabajo reales. Antes se conocía como Moltbot y Clawdbot, y está diseñado para extenderse mediante skills, plugins e integraciones del ecosistema.

<a id="navigation"></a>

## Navegación

- [Arquitecturas alternativas](#alternative-architectures)
- [Canales de la comunidad](#community-channels)
- [Contribuir](#contributing)
- [Colecciones curadas](#curated-collections)
- [Herramientas de desarrollo y observabilidad](#developer-tooling-and-observability)
- [Despliegue y operaciones](#deployment-and-operations)
- [Licencia](#license)
- [Localización y forks regionales](#localization-and-regional-forks)
- [MCP y servidores de herramientas](#mcp-and-tool-servers)
- [Medios y artículos](#media-and-papers)
- [Memoria y contexto](#memory-and-context-systems)
- [Recursos oficiales](#official-resources)
- [Plugins e integraciones](#plugins-and-integrations)
- [Skills e índices](#skills-and-skill-indexes)

<a id="status-markers"></a>

## Marcadores de estado

- 🎖️ Recurso oficial mantenido por OpenClaw (repo de la organización, docs oficiales o canales oficiales).
- 💵 Puede requerir servicio o plan de pago para uso completo.

---

<a id="community-channels"></a>

## Canales de la comunidad

- [4claw.org](https://www.4claw.org) - Tablon estilo 4chan para conversaciones de agentes autonomos.
- [Clawk](https://clawk.ai) - Red social estilo Twitter donde los agentes publican, siguen, dan "me gusta" y republican actualizaciones cortas.
- [GitHub Discussions](https://github.com/openclaw/openclaw/discussions) - Foro de discusion para ayuda, ideas y proyectos destacados. 🎖️
- [GitHub Issues](https://github.com/openclaw/openclaw/issues) - Reportes de errores y solicitudes de funciones para el core de OpenClaw. 🎖️
- [Lobchan](https://lobchan.ai) - Plataforma anonima tipo imageboard para agentes de OpenClaw, con hilos efimeros.
- [MoltBook](https://moltbook.com) - Plataforma social centrada en agentes conectada al ecosistema Molt.
- [Moltbook](https://moltbookai.net) - Red social estilo Reddit para agentes de IA donde los humanos pueden observar la actividad entre agentes.
- [Moltbook Town](https://moltbooktown.xyz) - Entorno virtual 2D/3D donde los agentes viven e interactuan.
- [MoltHub](https://moithub.com/) - Plataforma orientada a modelos para adultos operada por agentes.
- [MoltOverflow](https://moltoverflow.me) - Plataforma tipo Stack Overflow donde los agentes comparten soluciones validadas a bloqueos tecnicos.
- [Moltx](https://moltx.io/) - Feed social estilo X con respuestas, "me gusta" y seguidores.
- [Shellmates](https://www.shellmates.app) - Plataforma de emparejamiento para correspondencia entre agentes a corto y largo plazo.

<a id="alternative-architectures"></a>

## Arquitecturas alternativas

- [gavrielc/nanoclaw](https://github.com/gavrielc/nanoclaw) - Arquitectura alternativa ligera dentro del ecosistema OpenClaw. ![GitHub stars](https://img.shields.io/github/stars/gavrielc/nanoclaw?style=social)
- [HKUDS/nanobot](https://github.com/HKUDS/nanobot) - Implementacion ultraligera de asistente personal de IA. ![GitHub stars](https://img.shields.io/github/stars/HKUDS/nanobot?style=social)
- [jlia0/tinyclaw](https://github.com/jlia0/tinyclaw) - OpenClaw en 400 lineas de codigo. ![GitHub stars](https://img.shields.io/github/stars/jlia0/tinyclaw?style=social)
- [microclaw/microclaw](https://github.com/microclaw/microclaw) - Asistente en Rust con ejecucion de herramientas. ![GitHub stars](https://img.shields.io/github/stars/microclaw/microclaw?style=social)
- [memovai/mimiclaw](https://github.com/memovai/mimiclaw) - Convierte una pequena placa ESP32-S3 en un asistente personal de IA. ![GitHub stars](https://img.shields.io/github/stars/memovai/mimiclaw?style=social)
- [puremachinery/carapace](https://github.com/puremachinery/carapace) - Asistente centrado en seguridad con sandboxing y aislamiento de plugins. ![GitHub stars](https://img.shields.io/github/stars/puremachinery/carapace?style=social)
- [sipeed/picoclaw](https://github.com/sipeed/picoclaw) - Implementacion en Go que corre en hardware de $10 con <10MB de RAM. ![GitHub stars](https://img.shields.io/github/stars/sipeed/picoclaw?style=social)
- [ysz/nanoClaw](https://github.com/ysz/nanoClaw) - Asistente ligero y seguro con configuracion rapida. ![GitHub stars](https://img.shields.io/github/stars/ysz/nanoClaw?style=social)

<a id="official-resources"></a>

## Recursos oficiales

- [OpenClaw Website](https://openclaw.ai) - Pagina oficial del producto y del proyecto. 🎖️
- [OpenClaw Docs](https://docs.openclaw.ai) - Portal principal de documentacion. 🎖️
- [Getting Started](https://docs.openclaw.ai/start/getting-started) - La ruta mas rapida para tener una instalacion funcional. 🎖️
- [Plugin Docs](https://docs.openclaw.ai/plugin) - Guia oficial de creacion y ejecucion de plugins. 🎖️
- [Skills Docs](https://docs.openclaw.ai/tools/skills) - Documentacion oficial del modelo y uso de skills. 🎖️
- [openclaw/openclaw](https://github.com/openclaw/openclaw) - Repositorio del framework central del asistente. 🎖️ ![GitHub stars](https://img.shields.io/github/stars/openclaw/openclaw?style=social)
- [openclaw/clawhub](https://github.com/openclaw/clawhub) - Official skill registry source. 🎖️ ![GitHub stars](https://img.shields.io/github/stars/openclaw/clawhub?style=social)
- [openclaw/skills](https://github.com/openclaw/skills) - Archived historical skill versions. 🎖️ ![GitHub stars](https://img.shields.io/github/stars/openclaw/skills?style=social)

<a id="curated-collections"></a>

## Colecciones curadas

- [hesamsheikh/awesome-openclaw-usecases](https://github.com/hesamsheikh/awesome-openclaw-usecases) - Patrones de uso reales y ejemplos por dominio. ![GitHub stars](https://img.shields.io/github/stars/hesamsheikh/awesome-openclaw-usecases?style=social)
- [jensrot/awesome-openclaw](https://github.com/jensrot/awesome-openclaw) - Recursos curados del ecosistema OpenClaw y referencias de tooling. ![GitHub stars](https://img.shields.io/github/stars/jensrot/awesome-openclaw?style=social)
- [VoltAgent/awesome-openclaw-skills](https://github.com/VoltAgent/awesome-openclaw-skills) - Indice comunitario principal de skills de OpenClaw (con contexto de renombrados). ![GitHub stars](https://img.shields.io/github/stars/VoltAgent/awesome-openclaw-skills?style=social)

<a id="skills-and-skill-indexes"></a>

## Skills e índices

- [BankrBot/openclaw-skills](https://github.com/BankrBot/openclaw-skills) - Biblioteca comunitaria de skills centrada en automatizacion y finanzas. ![GitHub stars](https://img.shields.io/github/stars/BankrBot/openclaw-skills?style=social)
- [clawdbot/skills](https://github.com/clawdbot/skills) - Ruta alias heredada hacia el archivo historico de skills. ![GitHub stars](https://img.shields.io/github/stars/clawdbot/skills?style=social)
- [jdrhyne/agent-skills](https://github.com/jdrhyne/agent-skills) - Paquetes de skills y extensiones reutilizables de flujos de trabajo. ![GitHub stars](https://img.shields.io/github/stars/jdrhyne/agent-skills?style=social)
- [lekt9/unbrowse-openclaw](https://github.com/lekt9/unbrowse-openclaw) - Flujo de generacion de skills de API a partir de trafico web/API capturado. ![GitHub stars](https://img.shields.io/github/stars/lekt9/unbrowse-openclaw?style=social)
- [openclaw/clawhub](https://github.com/openclaw/clawhub) - Directorio oficial de skills y punto de descubrimiento. 🎖️ ![GitHub stars](https://img.shields.io/github/stars/openclaw/clawhub?style=social)
- [openclaw/skills](https://github.com/openclaw/skills) - Versiones archivadas de skills publicadas en ClawHub. 🎖️ ![GitHub stars](https://img.shields.io/github/stars/openclaw/skills?style=social)
- [pors/skill-audit](https://github.com/pors/skill-audit) - Toolkit de auditoria de skills para validar y reforzar su calidad. ![GitHub stars](https://img.shields.io/github/stars/pors/skill-audit?style=social)
- [runkids/skillshare](https://github.com/runkids/skillshare) - Compartir y sincronizar packs de skills entre herramientas de codificacion con IA. ![GitHub stars](https://img.shields.io/github/stars/runkids/skillshare?style=social)
- [Skills.sh OpenClaw Directory](https://skills.sh/openclaw/openclaw) - Directorio de descubrimiento de skills de OpenClaw de terceros.
- [Virtual-Protocol/openclaw-acp](https://github.com/Virtual-Protocol/openclaw-acp) - Pack de skills del Agent Commerce Protocol para flujos de comercio. ![GitHub stars](https://img.shields.io/github/stars/Virtual-Protocol/openclaw-acp?style=social)

<a id="plugins-and-integrations"></a>

## Plugins e integraciones

- [11haonb/wecom-openclaw-plugin](https://github.com/11haonb/wecom-openclaw-plugin) - Plugin de mensajeria empresarial para WeCom (WeChat Work). ![GitHub stars](https://img.shields.io/github/stars/11haonb/wecom-openclaw-plugin?style=social)
- [AlexAnys/feishu-openclaw](https://github.com/AlexAnys/feishu-openclaw) - Plugin de integracion con Feishu/Lark con configuracion self-hosted simplificada. ![GitHub stars](https://img.shields.io/github/stars/AlexAnys/feishu-openclaw?style=social)
- [ClariSortAi/openclaw-manager-plugin](https://github.com/ClariSortAi/openclaw-manager-plugin) - Gestor de ciclo de vida para instalacion y configuracion. ![GitHub stars](https://img.shields.io/github/stars/ClariSortAi/openclaw-manager-plugin?style=social)
- [Crossmint/openclaw-crossmint-plugin](https://github.com/Crossmint/openclaw-crossmint-plugin) - Billetera on-chain y pagos para agentes. ![GitHub stars](https://img.shields.io/github/stars/Crossmint/openclaw-crossmint-plugin?style=social)
- [DNYoussef/guardspine-openclaw](https://github.com/DNYoussef/guardspine-openclaw) - Plugin de gobernanza con control deny-by-default y niveles de riesgo. ![GitHub stars](https://img.shields.io/github/stars/DNYoussef/guardspine-openclaw?style=social)
- [lekt9/openclaw-foundry](https://github.com/lekt9/openclaw-foundry) - Metaextension para generar y evolucionar skills a partir de flujos de trabajo. ![GitHub stars](https://img.shields.io/github/stars/lekt9/openclaw-foundry?style=social)
- [hyperspell/hyperspell-openclaw](https://github.com/hyperspell/hyperspell-openclaw) - Integracion del plugin HyperSpell para flujos de OpenClaw. ![GitHub stars](https://img.shields.io/github/stars/hyperspell/hyperspell-openclaw?style=social)
- [limouren01/openclaw_qq_plugin](https://github.com/limouren01/openclaw_qq_plugin) - Plugin de canal de mensajeria QQ para integracion con plataformas chinas. ![GitHub stars](https://img.shields.io/github/stars/limouren01/openclaw_qq_plugin?style=social)
- [m1heng/clawdbot-feishu](https://github.com/m1heng/clawdbot-feishu) - Plugin de canal Feishu/Lark con soporte para bots empresariales. ![GitHub stars](https://img.shields.io/github/stars/m1heng/clawdbot-feishu?style=social)
- [marshallrichards/ClawPhone](https://github.com/marshallrichards/ClawPhone) - Companero movil con interfaz pensada para el telefono. ![GitHub stars](https://img.shields.io/github/stars/marshallrichards/ClawPhone?style=social)
- [MemTensor/MemOS-Cloud-OpenClaw-Plugin](https://github.com/MemTensor/MemOS-Cloud-OpenClaw-Plugin) - Memoria en la nube para recuerdo persistente. ![GitHub stars](https://img.shields.io/github/stars/MemTensor/MemOS-Cloud-OpenClaw-Plugin?style=social)
- [rickybloomfield/OuraClaw](https://github.com/rickybloomfield/OuraClaw) - Plugin de integracion con Oura para resumenes de descanso, sueno y actividad. ![GitHub stars](https://img.shields.io/github/stars/rickybloomfield/OuraClaw?style=social)
- [soimy/openclaw-channel-dingtalk](https://github.com/soimy/openclaw-channel-dingtalk) - Plugin de canal empresarial de DingTalk con soporte de streaming. ![GitHub stars](https://img.shields.io/github/stars/soimy/openclaw-channel-dingtalk?style=social)
- [techartdev/OpenClawHomeAssistant](https://github.com/techartdev/OpenClawHomeAssistant) - Complemento de Home Assistant con integracion a nivel de entidad. ![GitHub stars](https://img.shields.io/github/stars/techartdev/OpenClawHomeAssistant?style=social)

<a id="mcp-and-tool-servers"></a>

## MCP y servidores de herramientas

- [androidStern-personal/openclaw-mcp-adapter](https://github.com/androidStern-personal/openclaw-mcp-adapter) - adaptador para acceso nativo a herramientas en OpenClaw. ![GitHub stars](https://img.shields.io/github/stars/androidStern-personal/openclaw-mcp-adapter?style=social)
- [Enderfga/openclaw-claude-code-skill](https://github.com/Enderfga/openclaw-claude-code-skill) - Integracion de skill de Claude Code via MCP para OpenClaw. ![GitHub stars](https://img.shields.io/github/stars/Enderfga/openclaw-claude-code-skill?style=social)
- [Helms-AI/openclaw-mcp-server](https://github.com/Helms-AI/openclaw-mcp-server) - Servidor MCP que expone herramientas del Gateway de OpenClaw. ![GitHub stars](https://img.shields.io/github/stars/Helms-AI/openclaw-mcp-server?style=social)

<a id="media-and-papers"></a>

## Medios y artículos

- [Clawdbot Showed Me What the Future of Personal AI Assistants Looks Like](https://www.macstories.net/stories/clawdbot-showed-me-what-the-future-of-personal-ai-assistants-looks-like/) - Articulo de MacStories sobre los primeros flujos de agentes personales Clawdbot/OpenClaw.

<a id="memory-and-context-systems"></a>

## Memoria y contexto

- [Mem0 persistent OpenClaw memory](https://docs.mem0.ai/integrations/openclaw) - Documentacion de integracion para memoria persistente con Mem0. 💵
- [memovai/memov](https://github.com/memovai/memov) - Capa de memoria y toolkit de recuperacion para contexto persistente en OpenClaw. ![GitHub stars](https://img.shields.io/github/stars/memovai/memov?style=social)
- [MemTensor/MemOS](https://github.com/MemTensor/MemOS) - Sistema operativo de memoria adoptado en el ecosistema OpenClaw. ![GitHub stars](https://img.shields.io/github/stars/MemTensor/MemOS?style=social)
- [NevaMind-AI/memU](https://github.com/NevaMind-AI/memU) - Capa de memoria para asistentes de larga duracion. ![GitHub stars](https://img.shields.io/github/stars/NevaMind-AI/memU?style=social)
- [nhevers/MoltBrain](https://github.com/nhevers/MoltBrain) - Capa de memoria a largo plazo para flujos de agentes OpenClaw y MoltBook. ![GitHub stars](https://img.shields.io/github/stars/nhevers/MoltBrain?style=social)
- [oceanbase/powermem](https://github.com/oceanbase/powermem) - Memoria a largo plazo para flujos de plugins de OpenClawd. ![GitHub stars](https://img.shields.io/github/stars/oceanbase/powermem?style=social)
- [vincentkoc/openamnesia](https://github.com/vincentkoc/openamnesia) - Motor de contexto de aprendizaje continuo que extrae memoria segura de actividad real para un arranque en frio con senal alta. ![GitHub stars](https://img.shields.io/github/stars/vincentkoc/openamnesia?style=social)
- [supermemory OpenClaw Integration Docs](https://supermemory.ai/docs/integrations/openclaw) - Guia oficial para desplegar Supermemory con OpenClaw. 💵
- [supermemoryai/openclaw-supermemory](https://github.com/supermemoryai/openclaw-supermemory) - Plugin de memoria a largo plazo basado en Supermemory. 💵 ![GitHub stars](https://img.shields.io/github/stars/supermemoryai/openclaw-supermemory?style=social)
- [thedotmack/claude-mem](https://github.com/thedotmack/claude-mem/) - Capa de memoria ligera para persistencia de contexto en Claude/OpenClaw. ![GitHub stars](https://img.shields.io/github/stars/thedotmack/claude-mem?style=social)
- [tobi/qmd](https://github.com/tobi/qmd) - Flujos de memoria y conocimiento nativos en Markdown para contexto persistente. ![GitHub stars](https://img.shields.io/github/stars/tobi/qmd?style=social)

<a id="developer-tooling-and-observability"></a>

## Herramientas de desarrollo y observabilidad

- [bokonon23/clawdbot-cost-monitor](https://github.com/bokonon23/clawdbot-cost-monitor) - Monitor de costes y gasto para uso de OpenClaw/Clawdbot. ![GitHub stars](https://img.shields.io/github/stars/bokonon23/clawdbot-cost-monitor?style=social)
- [ClawFOMO](https://clawfomo.com) - Monitor en tiempo real de tendencias y sentimiento de actividad del ecosistema.
- [ClawScan](https://clawscan.io) - Directorio de herramientas e indice de proyectos del ecosistema.
- [clawdeckio/clawdeck](https://github.com/clawdeckio/clawdeck) - Panel tipo mission control para gestionar agentes de OpenClaw. ![GitHub stars](https://img.shields.io/github/stars/clawdeckio/clawdeck?style=social)
- [crshdn/mission-control](https://github.com/crshdn/mission-control) - Panel de orquestacion multiagente para flujos del Gateway de OpenClaw. ![GitHub stars](https://img.shields.io/github/stars/crshdn/mission-control?style=social)
- [grp06/openclaw-studio](https://github.com/grp06/openclaw-studio) - IDE web tipo studio y UI de gestion para flujos de OpenClaw. ![GitHub stars](https://img.shields.io/github/stars/grp06/openclaw-studio?style=social)
- [ibelick/webclaw](https://github.com/ibelick/webclaw) - Cliente web rapido para interactuar con OpenClaw. ![GitHub stars](https://img.shields.io/github/stars/ibelick/webclaw?style=social)
- [Intina47/context-sync](https://github.com/Intina47/context-sync) - Utilidad de sincronizacion de contexto para flujos multi-sesion. ![GitHub stars](https://img.shields.io/github/stars/Intina47/context-sync?style=social)
- [iOfficeAI/AionUi](https://github.com/iOfficeAI/AionUi) - UI local para gestionar e interactuar con sistemas de agentes tipo OpenClaw. ![GitHub stars](https://img.shields.io/github/stars/iOfficeAI/AionUi?style=social)
- [junhoyeo/tokscale](https://github.com/junhoyeo/tokscale) - Seguimiento de tokens y costes en flujos de asistentes de programacion. ![GitHub stars](https://img.shields.io/github/stars/junhoyeo/tokscale?style=social)
- [kepano/obsidian-skills](https://github.com/kepano/obsidian-skills) - Patrones transferibles de packs de skills utiles para diseno de skills en OpenClaw. ![GitHub stars](https://img.shields.io/github/stars/kepano/obsidian-skills?style=social)
- [luccast/crabwalk](https://github.com/luccast/crabwalk) - Herramienta de monitorizacion companera para sesiones de agentes OpenClaw. ![GitHub stars](https://img.shields.io/github/stars/luccast/crabwalk?style=social)
- [Hotmolts](https://www.hotmolts.com) - Motor de ranking para agentes influyentes basado en grafo social y senales de engagement.
- [MoltMatch](https://moltmatch.xyz) - Capa de emparejamiento y descubrimiento para colaboraciones entre agentes.
- [merciagents/riphook](https://github.com/merciagents/riphook) - Herramientas de webhooks y puente de eventos para automatizaciones guiadas por agentes. ![GitHub stars](https://img.shields.io/github/stars/merciagents/riphook?style=social)
- [openclaw/lobster](https://github.com/openclaw/lobster) - Shell de flujos para componer herramientas y automatizaciones de OpenClaw. 🎖️ ![GitHub stars](https://img.shields.io/github/stars/openclaw/lobster?style=social)
- [OthmanAdi/planning-with-files](https://github.com/OthmanAdi/planning-with-files) - Patron de skill para planificacion usado en repos de agentes. ![GitHub stars](https://img.shields.io/github/stars/OthmanAdi/planning-with-files?style=social)
- [prompt-security/clawsec](https://github.com/prompt-security/clawsec) - Suite de seguridad con deteccion de drift, auditorias y verificacion de integridad. ![GitHub stars](https://img.shields.io/github/stars/prompt-security/clawsec?style=social)
- [rdsthomas/mission-control](https://github.com/rdsthomas/mission-control) - Panel Kanban para gestion de tareas en flujos de OpenClaw. ![GitHub stars](https://img.shields.io/github/stars/rdsthomas/mission-control?style=social)
- [refly-ai/refly](https://github.com/refly-ai/refly) - Ecosistema para construir skills y flujos con solapamiento con tooling de agentes. ![GitHub stars](https://img.shields.io/github/stars/refly-ai/refly?style=social)
- [shanselman/openclaw-windows-hub](https://github.com/shanselman/openclaw-windows-hub) - Hub complementario de Windows para integracion de escritorio. ![GitHub stars](https://img.shields.io/github/stars/shanselman/openclaw-windows-hub?style=social)
- [Unbrowse](https://www.unbrowse.ai/) - Plataforma para convertir flujos del navegador en integraciones API y skills de agentes.

<a id="deployment-and-operations"></a>

## Despliegue y operaciones

### Hosting gestionado y configuracion

Estos proveedores se encargan de la puesta en marcha: sin Docker, sin terminal y sin DevOps.

- [Agent37](https://www.agent37.com/openclaw) - Instancia gestionada de OpenClaw con aprovisionamiento rapido. 💵
- [ClawCloud](https://www.clawcloud.sh/) - Hosting gestionado de OpenClaw con actualizaciones y copias de seguridad automaticas. 💵
- [ClawSimple](https://clawsimple.com/en) - Hosting gestionado de OpenClaw con planes simples y setup rapido. 💵
- [Contabo OpenClaw](https://contabo.com/en/openclaw-hosting/) - Opcion de hosting OpenClaw basada en VPS con precios predecibles. 💵
- [EasyClaw](https://www.easyclaw.pro/en) - Setup gestionado de OpenClaw con soporte multi-modelo. 💵
- [GetClawHelp](https://getclawhelp.com/) - Asistencia 1:1 de pago para configurar OpenClaw en tu VPS. 💵
- [get-open-claw.com](https://www.get-open-claw.com/) - Setup gestionado de OpenClaw con opciones de backup y monitoreo. 💵
- [Kilo Claw](https://kilo.ai/kiloclaw) - Plataforma OpenClaw gestionada con SSO y capacidades de auditoria. 💵
- [MyClaw.ai](https://myclaw.ai/pricing) - Instancia OpenClaw gestionada con puesta en marcha inmediata y backups. 💵
- [Myclawhost](https://www.myclawhost.com/) - Hosting gestionado de OpenClaw con planes por niveles. 💵
- [OpenClaw Cloud](https://openclawcloud.work/) - Oferta cloud gestionada de OpenClaw (beta). 💵
- [OpenClaw Hosting](https://openclawhosting.io/pricing) - Hosting gestionado de OpenClaw con planes solo/equipo. 💵
- [OpenClaw Voice](https://openclawvoice.com/) - Interfaz de voz gestionada para OpenClaw en navegador. 💵
- [OpenClawd.ai](https://finance.yahoo.com/news/openclaw-introduces-secure-hosted-clawdbot-204800756.html) - Oferta gestionada de OpenClaw alojado (anuncio). 💵
- [SimpleClaw](https://www.simpleclaw.com/) - Hosting gestionado de OpenClaw (acceso temprano). 💵
- [xCloud](https://xcloud.host/openclaw-hosting) - Hosting gestionado de OpenClaw con opciones de backups cifrados. 💵

### Despliegue self-hosted e infraestructura

- [1Panel-dev/1Panel](https://github.com/1Panel-dev/1Panel) - Panel de servidor self-hosted usado a menudo para despliegues de OpenClaw. ![GitHub stars](https://img.shields.io/github/stars/1Panel-dev/1Panel?style=social)
- [badrisnarayanan/antigravity-claude-proxy](https://github.com/badrisnarayanan/antigravity-claude-proxy) - Proxy y routing para acceso a modelos en flujos de asistentes. ![GitHub stars](https://img.shields.io/github/stars/badrisnarayanan/antigravity-claude-proxy?style=social)
- [BlockRunAI/ClawRouter](https://github.com/BlockRunAI/ClawRouter) - Capa de routing y optimizacion de costes para setups de agentes tipo OpenClaw. ![GitHub stars](https://img.shields.io/github/stars/BlockRunAI/ClawRouter?style=social)
- [ClawArena](https://clawarena.ai) - Arena de prediccion donde agentes de IA pronostican resultados de mercado y compiten.
- [Clawstead](https://www.clawstead.com) - Mundo simulado persistente donde agentes minan, comercian, construyen y viven.
- [ClawTasks](https://clawtasks.com) - Intercambio de tareas tipo bounty para trabajos digitales puntuales.
- [cloudflare/moltworker](https://github.com/cloudflare/moltworker) - Ruta de despliegue en Cloudflare Workers para runtimes compatibles con OpenClaw. ![GitHub stars](https://img.shields.io/github/stars/cloudflare/moltworker?style=social)
- [coollabsio/openclaw](https://github.com/coollabsio/openclaw) - Flujo Docker automatizado para hosting de OpenClaw. ![GitHub stars](https://img.shields.io/github/stars/coollabsio/openclaw?style=social)
- [essamamdani/openclaw-coolify](https://github.com/essamamdani/openclaw-coolify) - Plantilla de Coolify para hosting simplificado de OpenClaw. ![GitHub stars](https://img.shields.io/github/stars/essamamdani/openclaw-coolify?style=social)
- [khal3d/openclaw](https://github.com/khal3d/openclaw) - Stack de despliegue con contenedores y Helm para OpenClaw. ![GitHub stars](https://img.shields.io/github/stars/khal3d/openclaw?style=social)
- [miantiao-me/cloud-claw](https://github.com/miantiao-me/cloud-claw) - Despliegue en Cloudflare Containers para un OpenClaw personal. ![GitHub stars](https://img.shields.io/github/stars/miantiao-me/cloud-claw?style=social)
- [miaoxworld/OpenClawInstaller](https://github.com/miaoxworld/OpenClawInstaller) - Instalador y automatizacion de configuracion. ![GitHub stars](https://img.shields.io/github/stars/miaoxworld/OpenClawInstaller?style=social)
- [MoltBunker](https://moltbunker.com) - Capa de persistencia y almacenamiento segura para agentes.
- [MoltCities](https://moltcities.org) - Capa de identidad y residencia con handles e identidad basada en claves.
- [Moltline](https://www.moltline.com) - Infraestructura de mensajeria privada para handles persistentes y bandejas de entrada.
- [Moltroad](https://moltroad.com) - Marketplace de servicios, skills y bienes digitales con flujos de micropagos.
- [molt-bot/openclaw-trading-assistant](https://github.com/molt-bot/openclaw-trading-assistant) - Setup de asistente enfocado en trading construido sobre OpenClaw. ![GitHub stars](https://img.shields.io/github/stars/molt-bot/openclaw-trading-assistant?style=social)
- [MyDeadInternet.com](https://mydeadinternet.com) - Plataforma colectiva donde agentes aportan fragmentos de memoria para salidas compartidas.
- [Openwork](https://openwork.bot) - Marketplace solo para agentes para coordinar tareas y liquidar on-chain.
- [openclaw/clawdinators](https://github.com/openclaw/clawdinators) - Patron declarativo de despliegue con NixOS y AWS. 🎖️ ![GitHub stars](https://img.shields.io/github/stars/openclaw/clawdinators?style=social)
- [openclaw/homebrew-tap](https://github.com/openclaw/homebrew-tap) - Tap de Homebrew para instalar OpenClaw en macOS. 🎖️ ![GitHub stars](https://img.shields.io/github/stars/openclaw/homebrew-tap?style=social)
- [openclaw/openclaw-ansible](https://github.com/openclaw/openclaw-ansible) - Despliegue automatizado reforzado con Ansible. 🎖️ ![GitHub stars](https://img.shields.io/github/stars/openclaw/openclaw-ansible?style=social)
- [Pamir AI](https://www.pamir.ai/) - Ordenador Linux dedicado para agentes de IA, optimizado para tareas 24/7 y acceso remoto. 💵
- [RentAHuman](https://rentahuman.ai) - Marketplace donde agentes contratan humanos para tareas del mundo fisico.
- [serhanekicii/openclaw-helm](https://github.com/serhanekicii/openclaw-helm) - Chart Helm para despliegue de OpenClaw en Kubernetes. ![GitHub stars](https://img.shields.io/github/stars/serhanekicii/openclaw-helm?style=social)
- [Virtuals](https://www.virtuals.io) - Infraestructura tokenizada de agentes de IA para propiedad y monetizacion descentralizadas.
- [vincentkoc/natilius](https://github.com/vincentkoc/natilius) - Configuracion automatizada en un clic de entornos de ingenieria en macOS para reconstruir maquinas de investigacion, sandbox y agentes. ![GitHub stars](https://img.shields.io/github/stars/vincentkoc/natilius?style=social)
- [willbullen/openclaw-docker](https://github.com/willbullen/openclaw-docker) - Docker Compose orientado a produccion con hardening de seguridad. ![GitHub stars](https://img.shields.io/github/stars/willbullen/openclaw-docker?style=social)

<a id="localization-and-regional-forks"></a>

## Localización y forks regionales

- [1186258278/OpenClawChineseTranslation](https://github.com/1186258278/OpenClawChineseTranslation) - Repositorio de configuracion enfocado en traduccion. ![GitHub stars](https://img.shields.io/github/stars/1186258278/OpenClawChineseTranslation?style=social)
- [jiulingyun/openclaw-cn](https://github.com/jiulingyun/openclaw-cn) - Adaptacion de OpenClaw orientada a China. ![GitHub stars](https://img.shields.io/github/stars/jiulingyun/openclaw-cn?style=social)

<a id="contributing"></a>

## Contribuir

Se aceptan PR para:

- Nuevos enlaces de alto valor del ecosistema OpenClaw.
- Mejor categorización y calidad de secciones.
- Limpieza de enlaces rotos y proyectos obsoletos.

Incluye una breve nota de relevancia al enviar una nueva entrada.

<a id="license"></a>

## Licencia

MIT. Consulta [`LICENSE`](LICENSE).

---

Made with 💙 by <a href="https://github.com/vincentkoc">Vincent Koc</a> · <a href="LICENSE">MIT</a>
