# Awesome OpenClaw [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![CI](https://img.shields.io/github/actions/workflow/status/vincentkoc/awesome-openclaw/ci.yml?label=CI)](https://github.com/vincentkoc/awesome-openclaw/actions/workflows/ci.yml) [![Link Check](https://img.shields.io/github/actions/workflow/status/vincentkoc/awesome-openclaw/ci.yml?label=Link%20Check)](https://github.com/vincentkoc/awesome-openclaw/actions/workflows/ci.yml) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

**[English](README.md) | [简体中文](README.zh-CN.md) | [日本語](README.ja.md) | [한국어](README.ko.md) | [Español](README.es.md) | [Deutsch](README.de.md) | [Français](README.fr.md) | [Русский](README.ru.md)**

![Awesome OpenClaw Banner](banner.jpg)

Liste curée de ressources à fort signal pour **OpenClaw** (anciennement **Moltbot**, à l’origine **Clawdbot**) : frameworks, skills, outils, déploiements et cas d’usage réels.

OpenClaw est un framework d’agent IA open source et auto-hébergé qui relie les LLM aux outils, canaux de messagerie et systèmes de mémoire afin d’exécuter de vrais workflows. Anciennement Moltbot/Clawdbot, il est conçu pour être extensible via des skills, plugins et intégrations d’écosystème.

<a id="navigation"></a>

## Navigation

- [Architectures alternatives](#alternative-architectures)
- [Canaux communautaires](#community-channels)
- [Contribuer](#contributing)
- [Collections curées](#curated-collections)
- [Outils développeur et observabilité](#developer-tooling-and-observability)
- [Déploiement et opérations](#deployment-and-operations)
- [Licence](#license)
- [Localisation et forks régionaux](#localization-and-regional-forks)
- [MCP et serveurs d’outils](#mcp-and-tool-servers)
- [Médias et publications](#media-and-papers)
- [Mémoire et contexte](#memory-and-context-systems)
- [Ressources officielles](#official-resources)
- [Plugins et intégrations](#plugins-and-integrations)
- [Skills et index](#skills-and-skill-indexes)

<a id="status-markers"></a>

## Indicateurs d’état

- 🎖️ Ressource officielle maintenue par OpenClaw (repo d’organisation, docs officielles ou canaux officiels).
- 💵 Peut nécessiter un service ou un plan payant pour un usage complet.

---

<a id="community-channels"></a>

## Canaux communautaires

- [4claw.org](https://www.4claw.org) - Imageboard style 4chan pour des conversations d agents autonomes.
- [Clawk](https://clawk.ai) - Reseau social style Twitter ou les agents publient, suivent, aiment et repartagent des mises a jour courtes.
- [GitHub Discussions](https://github.com/openclaw/openclaw/discussions) - Forum communautaire pour aide, idees et projets vitrines. 🎖️
- [GitHub Issues](https://github.com/openclaw/openclaw/issues) - Signalement de bugs et demandes de fonctionnalites pour le coeur OpenClaw. 🎖️
- [Lobchan](https://lobchan.ai) - Plateforme anonyme type imageboard pour agents OpenClaw, avec fils ephemeres.
- [MoltBook](https://moltbook.com) - Plateforme sociale agent-first connectee a l ecosysteme Molt.
- [Moltbook](https://moltbookai.net) - Reseau social type Reddit pour agents IA ou les humains peuvent observer l activite entre agents.
- [Moltbook Town](https://moltbooktown.xyz) - Environnement virtuel 2D/3D ou les agents vivent et interagissent.
- [MoltHub](https://moithub.com/) - Plateforme orientee modeles adultes alimentee par des agents.
- [MoltOverflow](https://moltoverflow.me) - Plateforme type Stack Overflow ou les agents partagent des solutions validees a des blocages techniques.
- [Moltx](https://moltx.io/) - Flux social style X avec reponses, likes et abonnements.
- [Shellmates](https://www.shellmates.app) - Plateforme de mise en relation pour correspondance d agents a court et long terme.

<a id="alternative-architectures"></a>

## Architectures alternatives

- [gavrielc/nanoclaw](https://github.com/gavrielc/nanoclaw) - Architecture alternative legere dans l ecosysteme OpenClaw. ![GitHub stars](https://img.shields.io/github/stars/gavrielc/nanoclaw?style=social)
- [HKUDS/nanobot](https://github.com/HKUDS/nanobot) - Implementation ultra-legere d assistant personnel IA. ![GitHub stars](https://img.shields.io/github/stars/HKUDS/nanobot?style=social)
- [jlia0/tinyclaw](https://github.com/jlia0/tinyclaw) - OpenClaw en 400 lignes de code. ![GitHub stars](https://img.shields.io/github/stars/jlia0/tinyclaw?style=social)
- [microclaw/microclaw](https://github.com/microclaw/microclaw) - Assistant Rust avec execution d outils. ![GitHub stars](https://img.shields.io/github/stars/microclaw/microclaw?style=social)
- [puremachinery/carapace](https://github.com/puremachinery/carapace) - Assistant axe securite avec sandboxing et isolation des plugins. ![GitHub stars](https://img.shields.io/github/stars/puremachinery/carapace?style=social)
- [ysz/nanoClaw](https://github.com/ysz/nanoClaw) - Assistant leger et securise avec mise en route rapide. ![GitHub stars](https://img.shields.io/github/stars/ysz/nanoClaw?style=social)

<a id="official-resources"></a>

## Ressources officielles

- [OpenClaw Website](https://openclaw.ai) - Page officielle du produit et du projet. 🎖️
- [OpenClaw Docs](https://docs.openclaw.ai) - Portail principal de documentation. 🎖️
- [Getting Started](https://docs.openclaw.ai/start/getting-started) - Chemin le plus rapide vers une installation fonctionnelle. 🎖️
- [Plugin Docs](https://docs.openclaw.ai/plugin) - Guide officiel de creation et d execution des plugins. 🎖️
- [Skills Docs](https://docs.openclaw.ai/tools/skills) - Documentation officielle du modele et de l usage des skills. 🎖️
- [openclaw/openclaw](https://github.com/openclaw/openclaw) - Depot du framework central de l assistant. 🎖️ ![GitHub stars](https://img.shields.io/github/stars/openclaw/openclaw?style=social)
- [openclaw/clawhub](https://github.com/openclaw/clawhub) - Official skill registry source. 🎖️ ![GitHub stars](https://img.shields.io/github/stars/openclaw/clawhub?style=social)
- [openclaw/skills](https://github.com/openclaw/skills) - Archived historical skill versions. 🎖️ ![GitHub stars](https://img.shields.io/github/stars/openclaw/skills?style=social)

<a id="curated-collections"></a>

## Collections curées

- [hesamsheikh/awesome-openclaw-usecases](https://github.com/hesamsheikh/awesome-openclaw-usecases) - Patrons d usage reels et exemples par domaine. ![GitHub stars](https://img.shields.io/github/stars/hesamsheikh/awesome-openclaw-usecases?style=social)
- [jensrot/awesome-openclaw](https://github.com/jensrot/awesome-openclaw) - Ressources curees de l ecosysteme OpenClaw et references tooling. ![GitHub stars](https://img.shields.io/github/stars/jensrot/awesome-openclaw?style=social)
- [VoltAgent/awesome-openclaw-skills](https://github.com/VoltAgent/awesome-openclaw-skills) - Grand index communautaire de skills OpenClaw (avec contexte de renommage). ![GitHub stars](https://img.shields.io/github/stars/VoltAgent/awesome-openclaw-skills?style=social)

<a id="skills-and-skill-indexes"></a>

## Skills et index

- [BankrBot/openclaw-skills](https://github.com/BankrBot/openclaw-skills) - Bibliotheque communautaire de skills axee sur l'automatisation et la finance. ![GitHub stars](https://img.shields.io/github/stars/BankrBot/openclaw-skills?style=social)
- [clawdbot/skills](https://github.com/clawdbot/skills) - Chemin alias historique vers l archive de skills. ![GitHub stars](https://img.shields.io/github/stars/clawdbot/skills?style=social)
- [jdrhyne/agent-skills](https://github.com/jdrhyne/agent-skills) - Packs de skills d'agent et extensions de workflow reutilisables. ![GitHub stars](https://img.shields.io/github/stars/jdrhyne/agent-skills?style=social)
- [lekt9/unbrowse-openclaw](https://github.com/lekt9/unbrowse-openclaw) - Workflow de generation de skills API a partir de trafic web/API capture. ![GitHub stars](https://img.shields.io/github/stars/lekt9/unbrowse-openclaw?style=social)
- [openclaw/clawhub](https://github.com/openclaw/clawhub) - Annuaire officiel des skills et point de decouverte. 🎖️ ![GitHub stars](https://img.shields.io/github/stars/openclaw/clawhub?style=social)
- [openclaw/skills](https://github.com/openclaw/skills) - Versions archivees des skills publies sur ClawHub. 🎖️ ![GitHub stars](https://img.shields.io/github/stars/openclaw/skills?style=social)
- [runkids/skillshare](https://github.com/runkids/skillshare) - Partager et synchroniser des packs de skills entre outils de dev assistes par IA. ![GitHub stars](https://img.shields.io/github/stars/runkids/skillshare?style=social)
- [Skills.sh OpenClaw Directory](https://skills.sh/openclaw/openclaw) - Annuaire tiers de decouverte de skills OpenClaw.
- [Virtual-Protocol/openclaw-acp](https://github.com/Virtual-Protocol/openclaw-acp) - Pack de skills Agent Commerce Protocol pour des flux de commerce. ![GitHub stars](https://img.shields.io/github/stars/Virtual-Protocol/openclaw-acp?style=social)

<a id="plugins-and-integrations"></a>

## Plugins et intégrations

- [11haonb/wecom-openclaw-plugin](https://github.com/11haonb/wecom-openclaw-plugin) - Plugin de messagerie entreprise WeCom (WeChat Work). ![GitHub stars](https://img.shields.io/github/stars/11haonb/wecom-openclaw-plugin?style=social)
- [AlexAnys/feishu-openclaw](https://github.com/AlexAnys/feishu-openclaw) - Plugin d integration Feishu/Lark avec setup self-hosted simplifie. ![GitHub stars](https://img.shields.io/github/stars/AlexAnys/feishu-openclaw?style=social)
- [ClariSortAi/openclaw-manager-plugin](https://github.com/ClariSortAi/openclaw-manager-plugin) - Gestionnaire de cycle de vie pour l'installation et la configuration. ![GitHub stars](https://img.shields.io/github/stars/ClariSortAi/openclaw-manager-plugin?style=social)
- [Crossmint/openclaw-crossmint-plugin](https://github.com/Crossmint/openclaw-crossmint-plugin) - Portefeuille on-chain et paiements pour agents. ![GitHub stars](https://img.shields.io/github/stars/Crossmint/openclaw-crossmint-plugin?style=social)
- [DNYoussef/guardspine-openclaw](https://github.com/DNYoussef/guardspine-openclaw) - Plugin de gouvernance avec controle deny-by-default et niveaux de risque. ![GitHub stars](https://img.shields.io/github/stars/DNYoussef/guardspine-openclaw?style=social)
- [lekt9/openclaw-foundry](https://github.com/lekt9/openclaw-foundry) - Meta-extension pour generer et faire evoluer des skills a partir de workflows. ![GitHub stars](https://img.shields.io/github/stars/lekt9/openclaw-foundry?style=social)
- [limouren01/openclaw_qq_plugin](https://github.com/limouren01/openclaw_qq_plugin) - Plugin de canal QQ pour integration plateformes chinoises. ![GitHub stars](https://img.shields.io/github/stars/limouren01/openclaw_qq_plugin?style=social)
- [m1heng/clawdbot-feishu](https://github.com/m1heng/clawdbot-feishu) - Plugin de canal Feishu/Lark avec support bots entreprise. ![GitHub stars](https://img.shields.io/github/stars/m1heng/clawdbot-feishu?style=social)
- [marshallrichards/ClawPhone](https://github.com/marshallrichards/ClawPhone) - Compagnon mobile avec interface phone-first pour les workflows. ![GitHub stars](https://img.shields.io/github/stars/marshallrichards/ClawPhone?style=social)
- [MemTensor/MemOS-Cloud-OpenClaw-Plugin](https://github.com/MemTensor/MemOS-Cloud-OpenClaw-Plugin) - Memoire cloud pour un rappel persistant. ![GitHub stars](https://img.shields.io/github/stars/MemTensor/MemOS-Cloud-OpenClaw-Plugin?style=social)
- [rickybloomfield/OuraClaw](https://github.com/rickybloomfield/OuraClaw) - Plugin d integration Oura pour resumes sommeil, readiness et activite. ![GitHub stars](https://img.shields.io/github/stars/rickybloomfield/OuraClaw?style=social)
- [soimy/openclaw-channel-dingtalk](https://github.com/soimy/openclaw-channel-dingtalk) - Plugin de canal entreprise DingTalk avec prise en charge du streaming. ![GitHub stars](https://img.shields.io/github/stars/soimy/openclaw-channel-dingtalk?style=social)
- [techartdev/OpenClawHomeAssistant](https://github.com/techartdev/OpenClawHomeAssistant) - Extension Home Assistant avec integration au niveau des entites. ![GitHub stars](https://img.shields.io/github/stars/techartdev/OpenClawHomeAssistant?style=social)

<a id="mcp-and-tool-servers"></a>

## MCP et serveurs d’outils

- [androidStern-personal/openclaw-mcp-adapter](https://github.com/androidStern-personal/openclaw-mcp-adapter) - adaptateur pour un acces natif aux outils OpenClaw. ![GitHub stars](https://img.shields.io/github/stars/androidStern-personal/openclaw-mcp-adapter?style=social)
- [Enderfga/openclaw-claude-code-skill](https://github.com/Enderfga/openclaw-claude-code-skill) - Integration du skill Claude Code via MCP pour OpenClaw. ![GitHub stars](https://img.shields.io/github/stars/Enderfga/openclaw-claude-code-skill?style=social)
- [Helms-AI/openclaw-mcp-server](https://github.com/Helms-AI/openclaw-mcp-server) - Serveur MCP exposant les outils du Gateway OpenClaw. ![GitHub stars](https://img.shields.io/github/stars/Helms-AI/openclaw-mcp-server?style=social)

<a id="media-and-papers"></a>

## Médias et publications

- [Clawdbot Showed Me What the Future of Personal AI Assistants Looks Like](https://www.macstories.net/stories/clawdbot-showed-me-what-the-future-of-personal-ai-assistants-looks-like/) - Article MacStories sur les premiers workflows d agents personnels Clawdbot/OpenClaw.

<a id="memory-and-context-systems"></a>

## Mémoire et contexte

- [Mem0 persistent OpenClaw memory](https://docs.mem0.ai/integrations/openclaw) - Documentation d integration pour une memoire persistante avec Mem0. 💵
- [memovai/memov](https://github.com/memovai/memov) - Couche memoire et toolkit de retrieval pour contexte OpenClaw persistant. ![GitHub stars](https://img.shields.io/github/stars/memovai/memov?style=social)
- [MemTensor/MemOS](https://github.com/MemTensor/MemOS) - Systeme d exploitation de memoire adopte dans l ecosysteme OpenClaw. ![GitHub stars](https://img.shields.io/github/stars/MemTensor/MemOS?style=social)
- [NevaMind-AI/memU](https://github.com/NevaMind-AI/memU) - Couche memoire pour assistants longue duree. ![GitHub stars](https://img.shields.io/github/stars/NevaMind-AI/memU?style=social)
- [nhevers/MoltBrain](https://github.com/nhevers/MoltBrain) - Couche memoire long terme pour workflows d agents OpenClaw et MoltBook. ![GitHub stars](https://img.shields.io/github/stars/nhevers/MoltBrain?style=social)
- [oceanbase/powermem](https://github.com/oceanbase/powermem) - Memoire long terme pour les flux de plugins OpenClawd. ![GitHub stars](https://img.shields.io/github/stars/oceanbase/powermem?style=social)
- [vincentkoc/openamnesia](https://github.com/vincentkoc/openamnesia) - Moteur de contexte a apprentissage continu extrayant une memoire sure a partir d activite reelle. ![GitHub stars](https://img.shields.io/github/stars/vincentkoc/openamnesia?style=social)
- [supermemory OpenClaw Integration Docs](https://supermemory.ai/docs/integrations/openclaw) - Guide officiel pour deployer Supermemory avec OpenClaw. 💵
- [supermemoryai/openclaw-supermemory](https://github.com/supermemoryai/openclaw-supermemory) - Plugin de memoire long terme base sur Supermemory. 💵 ![GitHub stars](https://img.shields.io/github/stars/supermemoryai/openclaw-supermemory?style=social)
- [thedotmack/claude-mem](https://github.com/thedotmack/claude-mem/) - Couche memoire legere pour la persistance de contexte Claude/OpenClaw. ![GitHub stars](https://img.shields.io/github/stars/thedotmack/claude-mem?style=social)
- [tobi/qmd](https://github.com/tobi/qmd) - Workflows memoire/connaissance natifs Markdown pour contexte persistant. ![GitHub stars](https://img.shields.io/github/stars/tobi/qmd?style=social)

<a id="developer-tooling-and-observability"></a>

## Outils développeur et observabilité

- [bokonon23/clawdbot-cost-monitor](https://github.com/bokonon23/clawdbot-cost-monitor) - Moniteur de couts et depenses pour l usage OpenClaw/Clawdbot. ![GitHub stars](https://img.shields.io/github/stars/bokonon23/clawdbot-cost-monitor?style=social)
- [ClawFOMO](https://clawfomo.com) - Moniteur en temps reel des tendances et du sentiment de l ecosysteme.
- [ClawScan](https://clawscan.io) - Annuaire d outils et index de projets de l ecosysteme.
- [clawdeckio/clawdeck](https://github.com/clawdeckio/clawdeck) - Dashboard mission control pour gerer des agents OpenClaw. ![GitHub stars](https://img.shields.io/github/stars/clawdeckio/clawdeck?style=social)
- [crshdn/mission-control](https://github.com/crshdn/mission-control) - Dashboard d orchestration multi-agent pour workflows du Gateway OpenClaw. ![GitHub stars](https://img.shields.io/github/stars/crshdn/mission-control?style=social)
- [grp06/openclaw-studio](https://github.com/grp06/openclaw-studio) - IDE web type studio et UI de gestion pour workflows OpenClaw. ![GitHub stars](https://img.shields.io/github/stars/grp06/openclaw-studio?style=social)
- [ibelick/webclaw](https://github.com/ibelick/webclaw) - Client web rapide pour interagir avec OpenClaw. ![GitHub stars](https://img.shields.io/github/stars/ibelick/webclaw?style=social)
- [Intina47/context-sync](https://github.com/Intina47/context-sync) - Utilitaire de synchronisation de contexte pour workflows multi-session. ![GitHub stars](https://img.shields.io/github/stars/Intina47/context-sync?style=social)
- [iOfficeAI/AionUi](https://github.com/iOfficeAI/AionUi) - UI locale pour gerer et interagir avec des systemes d agents type OpenClaw. ![GitHub stars](https://img.shields.io/github/stars/iOfficeAI/AionUi?style=social)
- [junhoyeo/tokscale](https://github.com/junhoyeo/tokscale) - Suivi des tokens et des couts dans les workflows d assistants de dev. ![GitHub stars](https://img.shields.io/github/stars/junhoyeo/tokscale?style=social)
- [kepano/obsidian-skills](https://github.com/kepano/obsidian-skills) - Patrons de packs de skills transferables utiles pour concevoir des skills OpenClaw. ![GitHub stars](https://img.shields.io/github/stars/kepano/obsidian-skills?style=social)
- [luccast/crabwalk](https://github.com/luccast/crabwalk) - Outil compagnon de monitoring pour sessions d agents OpenClaw. ![GitHub stars](https://img.shields.io/github/stars/luccast/crabwalk?style=social)
- [Hotmolts](https://www.hotmolts.com) - Moteur de classement d agents influents selon graphe social et engagement.
- [MoltMatch](https://moltmatch.xyz) - Couche de matching et de decouverte pour collaborations entre agents.
- [merciagents/riphook](https://github.com/merciagents/riphook) - Outils de webhooks et pont d evenements pour automatisations pilotees par agents. ![GitHub stars](https://img.shields.io/github/stars/merciagents/riphook?style=social)
- [openclaw/lobster](https://github.com/openclaw/lobster) - Shell de workflow pour composer outils et automatisations OpenClaw. 🎖️ ![GitHub stars](https://img.shields.io/github/stars/openclaw/lobster?style=social)
- [OthmanAdi/planning-with-files](https://github.com/OthmanAdi/planning-with-files) - Patron de skill de planification utilise dans des repos d agents. ![GitHub stars](https://img.shields.io/github/stars/OthmanAdi/planning-with-files?style=social)
- [rdsthomas/mission-control](https://github.com/rdsthomas/mission-control) - Tableau Kanban pour la gestion des taches dans les workflows OpenClaw. ![GitHub stars](https://img.shields.io/github/stars/rdsthomas/mission-control?style=social)
- [refly-ai/refly](https://github.com/refly-ai/refly) - Ecosysteme de creation de skills et workflows, proche du tooling agent. ![GitHub stars](https://img.shields.io/github/stars/refly-ai/refly?style=social)
- [shanselman/openclaw-windows-hub](https://github.com/shanselman/openclaw-windows-hub) - Hub compagnon Windows pour l'integration bureau. ![GitHub stars](https://img.shields.io/github/stars/shanselman/openclaw-windows-hub?style=social)

<a id="deployment-and-operations"></a>

## Déploiement et opérations

- [1Panel-dev/1Panel](https://github.com/1Panel-dev/1Panel) - Panneau serveur self-hosted souvent utilise pour des deploiements OpenClaw. ![GitHub stars](https://img.shields.io/github/stars/1Panel-dev/1Panel?style=social)
- [badrisnarayanan/antigravity-claude-proxy](https://github.com/badrisnarayanan/antigravity-claude-proxy) - Proxy et routage pour l acces aux modeles dans des workflows d assistants. ![GitHub stars](https://img.shields.io/github/stars/badrisnarayanan/antigravity-claude-proxy?style=social)
- [BlockRunAI/ClawRouter](https://github.com/BlockRunAI/ClawRouter) - Couche de routage et d optimisation des couts pour setups d agents type OpenClaw. ![GitHub stars](https://img.shields.io/github/stars/BlockRunAI/ClawRouter?style=social)
- [ClawArena](https://clawarena.ai) - Arena de prediction ou des agents IA predisent des resultats de marche et se confrontent.
- [Clawstead](https://www.clawstead.com) - Monde simule persistant ou des agents minent, echangent, construisent et vivent.
- [ClawTasks](https://clawtasks.com) - Echange de taches type bounty pour des jobs numeriques ponctuels.
- [cloudflare/moltworker](https://github.com/cloudflare/moltworker) - Chemin de deploiement Cloudflare Workers pour runtimes compatibles OpenClaw. ![GitHub stars](https://img.shields.io/github/stars/cloudflare/moltworker?style=social)
- [coollabsio/openclaw](https://github.com/coollabsio/openclaw) - Flux Docker automatise pour l'hebergement OpenClaw. ![GitHub stars](https://img.shields.io/github/stars/coollabsio/openclaw?style=social)
- [essamamdani/openclaw-coolify](https://github.com/essamamdani/openclaw-coolify) - Template Coolify pour hebergement OpenClaw simplifie. ![GitHub stars](https://img.shields.io/github/stars/essamamdani/openclaw-coolify?style=social)
- [khal3d/openclaw](https://github.com/khal3d/openclaw) - Stack de deploiement conteneurs et Helm pour OpenClaw. ![GitHub stars](https://img.shields.io/github/stars/khal3d/openclaw?style=social)
- [miantiao-me/cloud-claw](https://github.com/miantiao-me/cloud-claw) - Deploiement Cloudflare Containers pour un OpenClaw personnel. ![GitHub stars](https://img.shields.io/github/stars/miantiao-me/cloud-claw?style=social)
- [miaoxworld/OpenClawInstaller](https://github.com/miaoxworld/OpenClawInstaller) - Installeur et automatisation de configuration. ![GitHub stars](https://img.shields.io/github/stars/miaoxworld/OpenClawInstaller?style=social)
- [MoltBunker](https://moltbunker.com) - Couche de persistance et stockage securisee pour agents.
- [MoltCities](https://moltcities.org) - Couche d identite et de residence avec handles et identite basee sur des cles.
- [Moltline](https://www.moltline.com) - Infra de messagerie privee pour handles persistants et boites de reception.
- [Moltroad](https://moltroad.com) - Marketplace de services, skills et biens numeriques avec micropaiements.
- [molt-bot/openclaw-trading-assistant](https://github.com/molt-bot/openclaw-trading-assistant) - Setup d assistant oriente trading construit sur OpenClaw. ![GitHub stars](https://img.shields.io/github/stars/molt-bot/openclaw-trading-assistant?style=social)
- [MyDeadInternet.com](https://mydeadinternet.com) - Plateforme collective ou les agents contribuent des fragments de memoire pour des sorties partagees.
- [Openwork](https://openwork.bot) - Marketplace reserve aux agents pour coordination de taches et reglement on-chain.
- [openclaw/clawdinators](https://github.com/openclaw/clawdinators) - Modele de deploiement declaratif NixOS et AWS. 🎖️ ![GitHub stars](https://img.shields.io/github/stars/openclaw/clawdinators?style=social)
- [openclaw/homebrew-tap](https://github.com/openclaw/homebrew-tap) - Tap Homebrew pour installer OpenClaw sur macOS. 🎖️ ![GitHub stars](https://img.shields.io/github/stars/openclaw/homebrew-tap?style=social)
- [openclaw/openclaw-ansible](https://github.com/openclaw/openclaw-ansible) - Deploiement automatise durci avec Ansible. 🎖️ ![GitHub stars](https://img.shields.io/github/stars/openclaw/openclaw-ansible?style=social)
- [Pamir AI](https://www.pamir.ai/) - Machine Linux dediee pour agents IA, optimisee pour taches 24/7 et acces distant. 💵
- [RentAHuman](https://rentahuman.ai) - Marketplace ou les agents embauchent des humains pour des taches physiques.
- [serhanekicii/openclaw-helm](https://github.com/serhanekicii/openclaw-helm) - Chart Helm pour le deploiement OpenClaw sur Kubernetes. ![GitHub stars](https://img.shields.io/github/stars/serhanekicii/openclaw-helm?style=social)
- [Virtuals](https://www.virtuals.io) - Infrastructure tokenisee d agents IA pour propriete et monetisation decentralisees.
- [vincentkoc/natilius](https://github.com/vincentkoc/natilius) - Setup macOS automatise en un clic pour reconstruire des machines de recherche, sandbox et agents. ![GitHub stars](https://img.shields.io/github/stars/vincentkoc/natilius?style=social)
- [willbullen/openclaw-docker](https://github.com/willbullen/openclaw-docker) - Docker Compose oriente production avec durcissement securite. ![GitHub stars](https://img.shields.io/github/stars/willbullen/openclaw-docker?style=social)

<a id="localization-and-regional-forks"></a>

## Localisation et forks régionaux

- [1186258278/OpenClawChineseTranslation](https://github.com/1186258278/OpenClawChineseTranslation) - Depot de configuration axe sur la traduction. ![GitHub stars](https://img.shields.io/github/stars/1186258278/OpenClawChineseTranslation?style=social)
- [jiulingyun/openclaw-cn](https://github.com/jiulingyun/openclaw-cn) - Adaptation OpenClaw orientee Chine. ![GitHub stars](https://img.shields.io/github/stars/jiulingyun/openclaw-cn?style=social)

<a id="contributing"></a>

## Contribuer

Les PR sont les bienvenues pour :

- Ajouter des liens OpenClaw à fort signal.
- Améliorer la catégorisation et la qualité des sections.
- Nettoyer les liens morts et retirer les projets obsolètes.

Ajoutez une courte note de pertinence lors de la soumission d'une nouvelle entree.

<a id="license"></a>

## Licence

MIT. Voir [`LICENSE`](LICENSE).

---

Made with 💙 by <a href="https://github.com/vincentkoc">Vincent Koc</a> · <a href="LICENSE">MIT</a>
