# Awesome OpenClaw [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![CI](https://img.shields.io/github/actions/workflow/status/vincentkoc/awesome-openclaw/ci.yml?label=CI)](https://github.com/vincentkoc/awesome-openclaw/actions/workflows/ci.yml) [![Link Check](https://img.shields.io/github/actions/workflow/status/vincentkoc/awesome-openclaw/ci.yml?label=Link%20Check)](https://github.com/vincentkoc/awesome-openclaw/actions/workflows/ci.yml) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

**[English](README.md) | [简体中文](README.zh-CN.md) | [日本語](README.ja.md) | [한국어](README.ko.md) | [Español](README.es.md) | [Deutsch](README.de.md) | [Français](README.fr.md) | [Русский](README.ru.md)**

![Awesome OpenClaw Banner](banner.jpg)

Kuratiere Liste mit hochwertigen Ressourcen für **OpenClaw** (früher **Moltbot**, ursprünglich **Clawdbot**): Frameworks, Skills, Tools, Deployments und echte Anwendungsfälle.

OpenClaw ist ein Open-Source-, selbst gehostetes KI-Agenten-Framework, das LLMs mit Tools, Messaging-Kanälen und Speichersystemen verbindet, damit Agenten reale Workflows ausführen können. Früher hieß es Moltbot bzw. Clawdbot und ist auf Erweiterbarkeit durch Skills, Plugins und Ökosystem-Integrationen ausgelegt.

<a id="navigation"></a>

## Navigation

- [Alternative Architekturen](#alternative-architectures)
- [Community-Kanäle](#community-channels)
- [Mitwirken](#contributing)
- [Kuratierte Sammlungen](#curated-collections)
- [Entwicklertools und Observability](#developer-tooling-and-observability)
- [Deployment und Betrieb](#deployment-and-operations)
- [Lizenz](#license)
- [Lokalisierung und regionale Forks](#localization-and-regional-forks)
- [MCP und Tool-Server](#mcp-and-tool-servers)
- [Medien und Papers](#media-and-papers)
- [Speicher- und Kontextsysteme](#memory-and-context-systems)
- [Offizielle Ressourcen](#official-resources)
- [Plugins und Integrationen](#plugins-and-integrations)
- [Skills und Indizes](#skills-and-skill-indexes)

<a id="status-markers"></a>

## Statusmarker

- 🎖️ Offizielle, von OpenClaw gepflegte Ressource (Org-Repo, offizielle Doku oder offizielle Kanäle).
- 💵 Für den vollen Funktionsumfang ist oft ein kostenpflichtiger Dienst/Plan nötig.

---

<a id="community-channels"></a>

## Community-Kanäle

- [4claw.org](https://www.4claw.org) - Imageboard im 4chan-Stil fuer autonome Agenten-Konversationen.
- [Clawk](https://clawk.ai) - Twitter-aehnliches Netzwerk, in dem Agenten kurze Updates posten, folgen, liken und reposten.
- [GitHub Discussions](https://github.com/openclaw/openclaw/discussions) - Community-Forum fuer Hilfe, Ideen und Showcase-Beitraege. 🎖️
- [GitHub Issues](https://github.com/openclaw/openclaw/issues) - Bug-Reports und Feature-Requests fuer den OpenClaw-Core. 🎖️
- [Lobchan](https://lobchan.ai) - Anonyme Imageboard-Plattform fuer OpenClaw-Agenten mit kurzlebigen Threads.
- [MoltBook](https://moltbook.com) - Agent-first Social-Plattform, angebunden an das Molt-Oekosystem.
- [Moltbook](https://moltbookai.net) - Reddit-aehnliches Netzwerk fuer KI-Agenten, das Menschen nur beobachten koennen.
- [Moltbook Town](https://moltbooktown.xyz) - 2D/3D-Umgebung, in der Agenten leben und interagieren.
- [MoltHub](https://moithub.com/) - Agentengetriebene, erwachsenenorientierte Plattform.
- [MoltOverflow](https://moltoverflow.me) - Stack-Overflow-aehnliche Plattform, auf der Agenten validierte Loesungen teilen.
- [MoltThreats](https://promptintel.novahunting.ai/molt) - Erster Threat-Intelligence-Feed fuer KI-Agenten: neue Bedrohungen teilen und automatisierten Schutz erhalten.
- [Moltx](https://moltx.io/) - X-aehnlicher Social-Feed mit Replies, Likes und Follows.
- [Shellmates](https://www.shellmates.app) - Matching-Plattform, die Agenten fuer kurz- und langfristige Korrespondenz paart.

<a id="alternative-architectures"></a>

## Alternative Architekturen

- [gavrielc/nanoclaw](https://github.com/gavrielc/nanoclaw) - Leichte alternative Architektur/Framework im OpenClaw-Oekosystem. ![GitHub stars](https://img.shields.io/github/stars/gavrielc/nanoclaw?style=social)
- [HKUDS/nanobot](https://github.com/HKUDS/nanobot) - Ultra-leichte Implementierung eines persoenlichen KI-Assistenten. ![GitHub stars](https://img.shields.io/github/stars/HKUDS/nanobot?style=social)
- [jlia0/tinyclaw](https://github.com/jlia0/tinyclaw) - OpenClaw in 400 Zeilen Code. ![GitHub stars](https://img.shields.io/github/stars/jlia0/tinyclaw?style=social)
- [microclaw/microclaw](https://github.com/microclaw/microclaw) - Rust-basierter Assistent mit Tool-Ausfuehrung. ![GitHub stars](https://img.shields.io/github/stars/microclaw/microclaw?style=social)
- [memovai/mimiclaw](https://github.com/memovai/mimiclaw) - Macht aus einem kleinen ESP32-S3-Board einen persoenlichen KI-Assistenten. ![GitHub stars](https://img.shields.io/github/stars/memovai/mimiclaw?style=social)
- [nearai/ironclaw](https://github.com/nearai/ironclaw) - OpenClaw-inspirierte Rust-Implementierung mit Fokus auf Datenschutz und Sicherheit. ![GitHub stars](https://img.shields.io/github/stars/nearai/ironclaw?style=social)
- [puremachinery/carapace](https://github.com/puremachinery/carapace) - Security-fokussierter Assistent mit Sandboxing und Plugin-Isolation. ![GitHub stars](https://img.shields.io/github/stars/puremachinery/carapace?style=social)
- [sipeed/picoclaw](https://github.com/sipeed/picoclaw) - Go-Implementierung, laeuft auf $10-Hardware mit <10MB RAM. ![GitHub stars](https://img.shields.io/github/stars/sipeed/picoclaw?style=social)
- [ysz/nanoClaw](https://github.com/ysz/nanoClaw) - Leichter, sicherer Assistent mit schnellem Setup. ![GitHub stars](https://img.shields.io/github/stars/ysz/nanoClaw?style=social)

<a id="official-resources"></a>

## Offizielle Ressourcen

- [OpenClaw Website](https://openclaw.ai) - Produkt- und Projekt-Homepage. 🎖️
- [OpenClaw Docs](https://docs.openclaw.ai) - Zentrales Dokumentationsportal. 🎖️
- [Getting Started](https://docs.openclaw.ai/start/getting-started) - Schnellster Weg zu einem lauffaehigen Setup. 🎖️
- [Plugin Docs](https://docs.openclaw.ai/plugin) - Offizieller Leitfaden fuer Plugin-Entwicklung und Runtime. 🎖️
- [Skills Docs](https://docs.openclaw.ai/tools/skills) - Offizielle Doku zum Skill-Modell und zur Nutzung. 🎖️
- [openclaw/openclaw](https://github.com/openclaw/openclaw) - Repository des Kern-Assistant-Frameworks. 🎖️ ![GitHub stars](https://img.shields.io/github/stars/openclaw/openclaw?style=social)
- [openclaw/clawhub](https://github.com/openclaw/clawhub) - Official skill registry source. 🎖️ ![GitHub stars](https://img.shields.io/github/stars/openclaw/clawhub?style=social)
- [openclaw/skills](https://github.com/openclaw/skills) - Archived historical skill versions. 🎖️ ![GitHub stars](https://img.shields.io/github/stars/openclaw/skills?style=social)

<a id="curated-collections"></a>

## Kuratierte Sammlungen

- [hesamsheikh/awesome-openclaw-usecases](https://github.com/hesamsheikh/awesome-openclaw-usecases) - Praxisnahe Usage-Patterns und Domain-Beispiele. ![GitHub stars](https://img.shields.io/github/stars/hesamsheikh/awesome-openclaw-usecases?style=social)
- [VoltAgent/awesome-openclaw-skills](https://github.com/VoltAgent/awesome-openclaw-skills) - Grosses Community-Index fuer OpenClaw-Skills (inkl. Rename-Lineage). ![GitHub stars](https://img.shields.io/github/stars/VoltAgent/awesome-openclaw-skills?style=social)

<a id="skills-and-skill-indexes"></a>

## Skills und Indizes

- [BankrBot/openclaw-skills](https://github.com/BankrBot/openclaw-skills) - Community-Skillbibliothek mit Fokus auf Automatisierung und Finanzen. ![GitHub stars](https://img.shields.io/github/stars/BankrBot/openclaw-skills?style=social)
- [clawdbot/skills](https://github.com/clawdbot/skills) - Legacy-Alias-Pfad zu historischem Skill-Archiv. ![GitHub stars](https://img.shields.io/github/stars/clawdbot/skills?style=social)
- [jdrhyne/agent-skills](https://github.com/jdrhyne/agent-skills) - Skill-Pakete fuer Agenten und wiederverwendbare Workflow-Erweiterungen. ![GitHub stars](https://img.shields.io/github/stars/jdrhyne/agent-skills?style=social)
- [lekt9/unbrowse-openclaw](https://github.com/lekt9/unbrowse-openclaw) - Workflow zur API-Skill-Generierung aus aufgezeichnetem Web/API-Traffic. ![GitHub stars](https://img.shields.io/github/stars/lekt9/unbrowse-openclaw?style=social)
- [openclaw/clawhub](https://github.com/openclaw/clawhub) - Offizielles Skill-Verzeichnis und Discovery-Einstieg. 🎖️ ![GitHub stars](https://img.shields.io/github/stars/openclaw/clawhub?style=social)
- [openclaw/skills](https://github.com/openclaw/skills) - Archivierte Versionen von auf ClawHub veroeffentlichten Skills. 🎖️ ![GitHub stars](https://img.shields.io/github/stars/openclaw/skills?style=social)
- [pors/skill-audit](https://github.com/pors/skill-audit) - Skill-Auditing-Toolkit zur Validierung und Haertung der Skill-Qualitaet. ![GitHub stars](https://img.shields.io/github/stars/pors/skill-audit?style=social)
- [runkids/skillshare](https://github.com/runkids/skillshare) - Skill-Packs zwischen KI-Coding-Tools teilen und synchronisieren. ![GitHub stars](https://img.shields.io/github/stars/runkids/skillshare?style=social)
- [Skills.sh OpenClaw Directory](https://skills.sh/openclaw/openclaw) - Third-Party-Verzeichnis zur OpenClaw-Skill-Entdeckung.
- [Virtual-Protocol/openclaw-acp](https://github.com/Virtual-Protocol/openclaw-acp) - Agent-Commerce-Protocol Skill-Pack fuer Commerce-Flows. ![GitHub stars](https://img.shields.io/github/stars/Virtual-Protocol/openclaw-acp?style=social)

<a id="plugins-and-integrations"></a>

## Plugins und Integrationen

- [11haonb/wecom-openclaw-plugin](https://github.com/11haonb/wecom-openclaw-plugin) - Enterprise-Messaging-Plugin fuer WeCom (WeChat Work). ![GitHub stars](https://img.shields.io/github/stars/11haonb/wecom-openclaw-plugin?style=social)
- [AlexAnys/feishu-openclaw](https://github.com/AlexAnys/feishu-openclaw) - Feishu/Lark-Integration mit optimiertem Self-Hosted-Setup. ![GitHub stars](https://img.shields.io/github/stars/AlexAnys/feishu-openclaw?style=social)
- [ClariSortAi/openclaw-manager-plugin](https://github.com/ClariSortAi/openclaw-manager-plugin) - Lifecycle-Manager fuer Installations- und Konfigurationsablaeufe. ![GitHub stars](https://img.shields.io/github/stars/ClariSortAi/openclaw-manager-plugin?style=social)
- [Crossmint/openclaw-crossmint-plugin](https://github.com/Crossmint/openclaw-crossmint-plugin) - On-Chain-Wallet und Zahlungen fuer Agenten. ![GitHub stars](https://img.shields.io/github/stars/Crossmint/openclaw-crossmint-plugin?style=social)
- [DNYoussef/guardspine-openclaw](https://github.com/DNYoussef/guardspine-openclaw) - Governance-Plugin mit deny-by-default Gating und Risiko-Tiers. ![GitHub stars](https://img.shields.io/github/stars/DNYoussef/guardspine-openclaw?style=social)
- [lekt9/openclaw-foundry](https://github.com/lekt9/openclaw-foundry) - Meta-Extension zum Generieren und Weiterentwickeln von Skills aus Workflows. ![GitHub stars](https://img.shields.io/github/stars/lekt9/openclaw-foundry?style=social)
- [hyperspell/hyperspell-openclaw](https://github.com/hyperspell/hyperspell-openclaw) - HyperSpell-Plugin-Integration fuer OpenClaw-Workflows. ![GitHub stars](https://img.shields.io/github/stars/hyperspell/hyperspell-openclaw?style=social)
- [limouren01/openclaw_qq_plugin](https://github.com/limouren01/openclaw_qq_plugin) - QQ-Messaging-Channel-Plugin fuer chinesische Plattform-Integration. ![GitHub stars](https://img.shields.io/github/stars/limouren01/openclaw_qq_plugin?style=social)
- [m1heng/clawdbot-feishu](https://github.com/m1heng/clawdbot-feishu) - Feishu/Lark-Channel-Plugin mit Enterprise-Bot-Support. ![GitHub stars](https://img.shields.io/github/stars/m1heng/clawdbot-feishu?style=social)
- [marshallrichards/ClawPhone](https://github.com/marshallrichards/ClawPhone) - Mobiler Begleiter mit phone-first Workflow-UI. ![GitHub stars](https://img.shields.io/github/stars/marshallrichards/ClawPhone?style=social)
- [MemTensor/MemOS-Cloud-OpenClaw-Plugin](https://github.com/MemTensor/MemOS-Cloud-OpenClaw-Plugin) - Cloud-Speicher fuer persistentes Erinnern. ![GitHub stars](https://img.shields.io/github/stars/MemTensor/MemOS-Cloud-OpenClaw-Plugin?style=social)
- [rickybloomfield/OuraClaw](https://github.com/rickybloomfield/OuraClaw) - Oura-Integration fuer Readiness-, Schlaf- und Aktivitaets-Summaries. ![GitHub stars](https://img.shields.io/github/stars/rickybloomfield/OuraClaw?style=social)
- [soimy/openclaw-channel-dingtalk](https://github.com/soimy/openclaw-channel-dingtalk) - DingTalk-Enterprise-Channel-Plugin mit Stream-Unterstuetzung. ![GitHub stars](https://img.shields.io/github/stars/soimy/openclaw-channel-dingtalk?style=social)
- [techartdev/OpenClawHomeAssistant](https://github.com/techartdev/OpenClawHomeAssistant) - Home-Assistant-Add-on mit Integration auf Entitaetsebene. ![GitHub stars](https://img.shields.io/github/stars/techartdev/OpenClawHomeAssistant?style=social)

<a id="mcp-and-tool-servers"></a>

## MCP und Tool-Server

- [androidStern-personal/openclaw-mcp-adapter](https://github.com/androidStern-personal/openclaw-mcp-adapter) - Adapter fuer nativen OpenClaw-Toolzugriff. ![GitHub stars](https://img.shields.io/github/stars/androidStern-personal/openclaw-mcp-adapter?style=social)
- [Enderfga/openclaw-claude-code-skill](https://github.com/Enderfga/openclaw-claude-code-skill) - Claude-Code Skill-Integration via MCP fuer OpenClaw. ![GitHub stars](https://img.shields.io/github/stars/Enderfga/openclaw-claude-code-skill?style=social)
- [Helms-AI/openclaw-mcp-server](https://github.com/Helms-AI/openclaw-mcp-server) - MCP-Server, der OpenClaw-Gateway-Tools exponiert. ![GitHub stars](https://img.shields.io/github/stars/Helms-AI/openclaw-mcp-server?style=social)

<a id="media-and-papers"></a>

## Medien und Papers

- [Clawdbot Showed Me What the Future of Personal AI Assistants Looks Like](https://www.macstories.net/stories/clawdbot-showed-me-what-the-future-of-personal-ai-assistants-looks-like/) - MacStories-Beitrag ueber fruehe Clawdbot/OpenClaw Personal-Agent-Workflows.

<a id="memory-and-context-systems"></a>

## Speicher- und Kontextsysteme

- [Mem0 persistent OpenClaw memory](https://docs.mem0.ai/integrations/openclaw) - Integrations-Doku fuer persistente Memorie mit Mem0. 💵
- [memovai/memov](https://github.com/memovai/memov) - Memory-Layer und Retrieval-Toolkit fuer persistente OpenClaw-Kontexte. ![GitHub stars](https://img.shields.io/github/stars/memovai/memov?style=social)
- [MemTensor/MemOS](https://github.com/MemTensor/MemOS) - Memory-Operating-System mit Adoption im OpenClaw-Oekosystem. ![GitHub stars](https://img.shields.io/github/stars/MemTensor/MemOS?style=social)
- [NevaMind-AI/memU](https://github.com/NevaMind-AI/memU) - Agent-Memory-Layer fuer langlebige Assistenten. ![GitHub stars](https://img.shields.io/github/stars/NevaMind-AI/memU?style=social)
- [nhevers/MoltBrain](https://github.com/nhevers/MoltBrain) - Langzeit-Memory-Layer fuer OpenClaw- und MoltBook-Agent-Workflows. ![GitHub stars](https://img.shields.io/github/stars/nhevers/MoltBrain?style=social)
- [oceanbase/powermem](https://github.com/oceanbase/powermem) - Langzeitspeicher fuer OpenClawd-Plugin-Workflows. ![GitHub stars](https://img.shields.io/github/stars/oceanbase/powermem?style=social)
- [vincentkoc/openamnesia](https://github.com/vincentkoc/openamnesia) - Continual-Learning Context Engine, die sichere Memory aus realer Aktivitaet extrahiert. ![GitHub stars](https://img.shields.io/github/stars/vincentkoc/openamnesia?style=social)
- [supermemory OpenClaw Integration Docs](https://supermemory.ai/docs/integrations/openclaw) - Offizieller Guide zur Supermemory-Integration mit OpenClaw. 💵
- [supermemoryai/openclaw-supermemory](https://github.com/supermemoryai/openclaw-supermemory) - Supermemory-basiertes Langzeit-Memory-Plugin. 💵 ![GitHub stars](https://img.shields.io/github/stars/supermemoryai/openclaw-supermemory?style=social)
- [thedotmack/claude-mem](https://github.com/thedotmack/claude-mem/) - Leichte Memory-Schicht fuer persistente Claude/OpenClaw-Kontexte. ![GitHub stars](https://img.shields.io/github/stars/thedotmack/claude-mem?style=social)
- [tobi/qmd](https://github.com/tobi/qmd) - Markdown-native Memory- und Knowledge-Workflows fuer persistente Agenten-Kontexte. ![GitHub stars](https://img.shields.io/github/stars/tobi/qmd?style=social)

<a id="developer-tooling-and-observability"></a>

## Entwicklertools und Observability

- [bokonon23/clawdbot-cost-monitor](https://github.com/bokonon23/clawdbot-cost-monitor) - Kosten- und Spending-Monitor fuer OpenClaw/Clawdbot-Nutzung. ![GitHub stars](https://img.shields.io/github/stars/bokonon23/clawdbot-cost-monitor?style=social)
- [ClawFOMO](https://clawfomo.com) - Echtzeit-Monitor fuer Trends und Sentiment im Oekosystem.
- [ClawScan](https://clawscan.io) - Tool-Verzeichnis und Projektindex fuer Oekosystem-Ressourcen.
- [clawdeckio/clawdeck](https://github.com/clawdeckio/clawdeck) - Mission-Control-Dashboard zum Verwalten von OpenClaw-Agenten. ![GitHub stars](https://img.shields.io/github/stars/clawdeckio/clawdeck?style=social)
- [crshdn/mission-control](https://github.com/crshdn/mission-control) - Multi-Agent-Orchestrierungs-Dashboard fuer OpenClaw-Gateway-Workflows. ![GitHub stars](https://img.shields.io/github/stars/crshdn/mission-control?style=social)
- [grp06/openclaw-studio](https://github.com/grp06/openclaw-studio) - Studio-artige Web-IDE und Management-UI fuer OpenClaw-Workflows. ![GitHub stars](https://img.shields.io/github/stars/grp06/openclaw-studio?style=social)
- [ibelick/webclaw](https://github.com/ibelick/webclaw) - Schneller Web-Client fuer OpenClaw-Interaktionen. ![GitHub stars](https://img.shields.io/github/stars/ibelick/webclaw?style=social)
- [Intina47/context-sync](https://github.com/Intina47/context-sync) - Kontext-Synchronisation fuer Multi-Session-Agent-Workflows. ![GitHub stars](https://img.shields.io/github/stars/Intina47/context-sync?style=social)
- [iOfficeAI/AionUi](https://github.com/iOfficeAI/AionUi) - Lokale UI zum Verwalten und Nutzen von OpenClaw-aehnlichen Agent-Systemen. ![GitHub stars](https://img.shields.io/github/stars/iOfficeAI/AionUi?style=social)
- [junhoyeo/tokscale](https://github.com/junhoyeo/tokscale) - Token- und Kosten-Tracking fuer Coding-Assistant-Workflows. ![GitHub stars](https://img.shields.io/github/stars/junhoyeo/tokscale?style=social)
- [kepano/obsidian-skills](https://github.com/kepano/obsidian-skills) - Uebertragbare Skill-Pack-Patterns fuer OpenClaw-Skill-Design. ![GitHub stars](https://img.shields.io/github/stars/kepano/obsidian-skills?style=social)
- [luccast/crabwalk](https://github.com/luccast/crabwalk) - Monitoring-Begleiter fuer OpenClaw-Agent-Sessions. ![GitHub stars](https://img.shields.io/github/stars/luccast/crabwalk?style=social)
- [Hotmolts](https://www.hotmolts.com) - Ranking-Engine fuer einflussreiche Agenten basierend auf Social-Graph und Engagement.
- [MoltMatch](https://moltmatch.xyz) - Matching- und Discovery-Layer fuer Agenten-Kollaborationen.
- [merciagents/riphook](https://github.com/merciagents/riphook) - Webhook- und Event-Bridge-Tooling fuer agentengetriebene Automationen. ![GitHub stars](https://img.shields.io/github/stars/merciagents/riphook?style=social)
- [openclaw/lobster](https://github.com/openclaw/lobster) - Workflow-Shell zum Kombinieren von OpenClaw-Tools und Automationen. 🎖️ ![GitHub stars](https://img.shields.io/github/stars/openclaw/lobster?style=social)
- [OthmanAdi/planning-with-files](https://github.com/OthmanAdi/planning-with-files) - Planungs-Workflow-Skill-Pattern aus agentischen Repos. ![GitHub stars](https://img.shields.io/github/stars/OthmanAdi/planning-with-files?style=social)
- [prompt-security/clawsec](https://github.com/prompt-security/clawsec) - Security-Skill-Suite mit Drift-Detection, Audits und Skill-Integritaetschecks. ![GitHub stars](https://img.shields.io/github/stars/prompt-security/clawsec?style=social)
- [rdsthomas/mission-control](https://github.com/rdsthomas/mission-control) - Kanban-Dashboard fuer Aufgabenmanagement in OpenClaw-Workflows. ![GitHub stars](https://img.shields.io/github/stars/rdsthomas/mission-control?style=social)
- [refly-ai/refly](https://github.com/refly-ai/refly) - Ecosystem fuer Skill- und Workflow-Builder mit Ueberschneidung zu Agent-Tooling. ![GitHub stars](https://img.shields.io/github/stars/refly-ai/refly?style=social)
- [shanselman/openclaw-windows-hub](https://github.com/shanselman/openclaw-windows-hub) - Windows-Begleithub fuer Desktop-Integration. ![GitHub stars](https://img.shields.io/github/stars/shanselman/openclaw-windows-hub?style=social)
- [Unbrowse](https://www.unbrowse.ai/) - Plattform zum Umwandeln von Browser-Workflows in API-Integrationen und Agent-Skills.

<a id="deployment-and-operations"></a>

## Deployment und Betrieb

### Managed Hosting und Setup

Diese Anbieter uebernehmen das Setup fuer dich: kein Docker, kein Terminal, kein DevOps erforderlich.

- [Agent37](https://www.agent37.com/openclaw) - Managed OpenClaw-Instanz mit sehr schneller Bereitstellung. 💵
- [ClawCloud](https://www.clawcloud.sh/) - Managed OpenClaw-Hosting mit Auto-Updates und Backups. 💵
- [ClawSimple](https://clawsimple.com/en) - Managed OpenClaw-Hosting mit einfachen Plaenen und Setup. 💵
- [Contabo OpenClaw](https://contabo.com/en/openclaw-hosting/) - VPS-basierte OpenClaw-Hosting-Option mit planbarer Preisstruktur. 💵
- [EasyClaw](https://www.easyclaw.pro/en) - Managed OpenClaw-Setup mit Multi-Model-Support. 💵
- [GetClawHelp](https://getclawhelp.com/) - Einmalige 1:1-Setup-Hilfe fuer OpenClaw auf deinem VPS. 💵
- [get-open-claw.com](https://www.get-open-claw.com/) - Managed OpenClaw-Setup mit optionalen Backups und Monitoring. 💵
- [Kilo Claw](https://kilo.ai/kiloclaw) - Managed OpenClaw-Plattform mit SSO- und Audit-Features. 💵
- [MyClaw.ai](https://myclaw.ai/pricing) - Managed OpenClaw-Instanz mit sofortigem Setup und Backups. 💵
- [Myclawhost](https://www.myclawhost.com/) - Managed OpenClaw-Hosting mit gestaffelten Tarifen. 💵
- [OpenClaw Cloud](https://openclawcloud.work/) - Managed OpenClaw-Cloud-Angebot (Beta). 💵
- [OpenClaw Hosting](https://openclawhosting.io/pricing) - Managed OpenClaw-Hosting mit Solo-/Team-Tarifen. 💵
- [OpenClaw Voice](https://openclawvoice.com/) - Managed OpenClaw-Voice-Interface im Browser. 💵
- [OpenClawd.ai](https://finance.yahoo.com/news/openclaw-introduces-secure-hosted-clawdbot-204800756.html) - Managed Hosted-OpenClaw-Angebot (Ankuendigung). 💵
- [SimpleClaw](https://www.simpleclaw.com/) - Managed OpenClaw-Hosting (Early Access). 💵
- [xCloud](https://xcloud.host/openclaw-hosting) - Managed OpenClaw-Hosting mit Optionen fuer verschluesselte Backups. 💵

### Self-Hosted Deployment und Infrastruktur

- [1Panel-dev/1Panel](https://github.com/1Panel-dev/1Panel) - Self-hosted Server-Panel, oft fuer OpenClaw-Deployments genutzt. ![GitHub stars](https://img.shields.io/github/stars/1Panel-dev/1Panel?style=social)
- [badrisnarayanan/antigravity-claude-proxy](https://github.com/badrisnarayanan/antigravity-claude-proxy) - Proxy- und Routing-Support fuer Model-Zugriff in Assistant-Workflows. ![GitHub stars](https://img.shields.io/github/stars/badrisnarayanan/antigravity-claude-proxy?style=social)
- [BlockRunAI/ClawRouter](https://github.com/BlockRunAI/ClawRouter) - Routing- und Kostenoptimierungs-Layer fuer OpenClaw-aehnliche Agent-Setups. ![GitHub stars](https://img.shields.io/github/stars/BlockRunAI/ClawRouter?style=social)
- [ClawArena](https://clawarena.ai) - Prediction-Arena, in der KI-Agenten Markt-Outcomes vorhersagen und konkurrieren.
- [Clawstead](https://www.clawstead.com) - Persistente Simulationswelt, in der Agenten schuerfen, handeln, bauen und leben.
- [ClawTasks](https://clawtasks.com) - Bounty-artiger Task-Austausch fuer einmalige digitale Jobs.
- [cloudflare/moltworker](https://github.com/cloudflare/moltworker) - Cloudflare-Worker-Deployment-Pfad fuer OpenClaw-kompatible Runtimes. ![GitHub stars](https://img.shields.io/github/stars/cloudflare/moltworker?style=social)
- [coollabsio/openclaw](https://github.com/coollabsio/openclaw) - Automatisierter Docker-Flow fuer OpenClaw-Hosting. ![GitHub stars](https://img.shields.io/github/stars/coollabsio/openclaw?style=social)
- [essamamdani/openclaw-coolify](https://github.com/essamamdani/openclaw-coolify) - Coolify-Template fuer vereinfachtes OpenClaw-Hosting. ![GitHub stars](https://img.shields.io/github/stars/essamamdani/openclaw-coolify?style=social)
- [khal3d/openclaw](https://github.com/khal3d/openclaw) - Container- und Helm-Deployment-Stack fuer OpenClaw. ![GitHub stars](https://img.shields.io/github/stars/khal3d/openclaw?style=social)
- [miantiao-me/cloud-claw](https://github.com/miantiao-me/cloud-claw) - Cloudflare-Containers-Deployment fuer persoenliches OpenClaw. ![GitHub stars](https://img.shields.io/github/stars/miantiao-me/cloud-claw?style=social)
- [miaoxworld/OpenClawInstaller](https://github.com/miaoxworld/OpenClawInstaller) - Installer und Setup-Automation. ![GitHub stars](https://img.shields.io/github/stars/miaoxworld/OpenClawInstaller?style=social)
- [MoltBunker](https://moltbunker.com) - Sichere Persistenz- und Storage-Schicht fuer Agenten.
- [MoltCities](https://moltcities.org) - Identity- und Residence-Layer mit Handles und Key-basierter Identitaet.
- [Moltline](https://www.moltline.com) - Private Messaging-Infrastruktur fuer persistente Handles und Inboxes.
- [Moltroad](https://moltroad.com) - Marketplace fuer Services, Skills und digitale Gueter mit Micropayment-Flows.
- [molt-bot/openclaw-trading-assistant](https://github.com/molt-bot/openclaw-trading-assistant) - Trading-fokussiertes Assistant-Setup auf OpenClaw-Basis. ![GitHub stars](https://img.shields.io/github/stars/molt-bot/openclaw-trading-assistant?style=social)
- [MyDeadInternet.com](https://mydeadinternet.com) - Kollektive Plattform, auf der Agenten Memory-Fragmente zu gemeinsamen Outputs beitragen.
- [Openwork](https://openwork.bot) - Agent-only Labor-Marketplace fuer Task-Koordination und On-Chain-Settlement.
- [openclaw/clawdinators](https://github.com/openclaw/clawdinators) - Deklaratives NixOS- und AWS-Deployment-Muster. 🎖️ ![GitHub stars](https://img.shields.io/github/stars/openclaw/clawdinators?style=social)
- [openclaw/homebrew-tap](https://github.com/openclaw/homebrew-tap) - Homebrew-Tap fuer die OpenClaw-Installation unter macOS. 🎖️ ![GitHub stars](https://img.shields.io/github/stars/openclaw/homebrew-tap?style=social)
- [openclaw/openclaw-ansible](https://github.com/openclaw/openclaw-ansible) - Gehaertetes automatisiertes Deployment mit Ansible. 🎖️ ![GitHub stars](https://img.shields.io/github/stars/openclaw/openclaw-ansible?style=social)
- [Pamir AI](https://www.pamir.ai/) - Dedizierter Linux-Computer fuer KI-Agenten, optimiert fuer 24/7 Tasks und Remote-Zugriff. 💵
- [RentAHuman](https://rentahuman.ai) - Marketplace, auf dem Agenten Menschen fuer physische Aufgaben anheuern.
- [serhanekicii/openclaw-helm](https://github.com/serhanekicii/openclaw-helm) - Helm-Chart fuer OpenClaw-Deployment auf Kubernetes. ![GitHub stars](https://img.shields.io/github/stars/serhanekicii/openclaw-helm?style=social)
- [Virtuals](https://www.virtuals.io) - Tokenisierte KI-Agent-Infrastruktur fuer dezentrale Ownership und Monetarisierung.
- [vincentkoc/natilius](https://github.com/vincentkoc/natilius) - Automatisches One-Click macOS-Setup fuer Engineering-Umgebungen fuer Research, Sandbox und Agenten. ![GitHub stars](https://img.shields.io/github/stars/vincentkoc/natilius?style=social)
- [willbullen/openclaw-docker](https://github.com/willbullen/openclaw-docker) - Production-orientiertes Docker Compose Setup mit Security-Hardening. ![GitHub stars](https://img.shields.io/github/stars/willbullen/openclaw-docker?style=social)

<a id="localization-and-regional-forks"></a>

## Lokalisierung und regionale Forks

- [1186258278/OpenClawChineseTranslation](https://github.com/1186258278/OpenClawChineseTranslation) - Setup-Repository mit Fokus auf Uebersetzung. ![GitHub stars](https://img.shields.io/github/stars/1186258278/OpenClawChineseTranslation?style=social)
- [jiulingyun/openclaw-cn](https://github.com/jiulingyun/openclaw-cn) - China-orientierte OpenClaw-Adaptation. ![GitHub stars](https://img.shields.io/github/stars/jiulingyun/openclaw-cn?style=social)

<a id="contributing"></a>

## Mitwirken

PRs sind willkommen für:

- Neue hochwertige OpenClaw-Ökosystem-Links.
- Bessere Kategorisierung und Abschnittsqualität.
- Bereinigung toter Links und veralteter Projekte.

Bitte fuege beim Einreichen eines neuen Eintrags eine kurze Relevanznotiz hinzu.

<a id="license"></a>

## Lizenz

MIT. Siehe [`LICENSE`](LICENSE).

---

Made with 💙 by <a href="https://github.com/vincentkoc">Vincent Koc</a> · <a href="LICENSE">MIT</a>
