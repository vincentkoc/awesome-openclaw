# Awesome OpenClaw [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![CI](https://img.shields.io/github/actions/workflow/status/vincentkoc/awesome-openclaw/ci.yml?label=CI)](https://github.com/vincentkoc/awesome-openclaw/actions/workflows/ci.yml) [![Link Check](https://img.shields.io/github/actions/workflow/status/vincentkoc/awesome-openclaw/ci.yml?label=Link%20Check)](https://github.com/vincentkoc/awesome-openclaw/actions/workflows/ci.yml) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

**[English](README.md) | [简体中文](README.zh-CN.md) | [日本語](README.ja.md) | [한국어](README.ko.md) | [Español](README.es.md) | [Deutsch](README.de.md) | [Français](README.fr.md) | [Русский](README.ru.md)**


![Awesome OpenClaw Banner](banner.jpg)

一份高质量的 **OpenClaw**（原名 **Moltbot**、最初为 **Clawdbot**）资源清单：框架、技能、工具、部署与真实用例。

OpenClaw 是一个开源、自托管的 AI Agent 框架，可将大模型与工具、消息通道和记忆系统连接起来，让 Agent 执行真实工作流。它曾使用 Moltbot 和 Clawdbot 名称，并通过技能、插件与生态集成实现可扩展性。

<a id="navigation"></a>
## 导航

- [替代架构](#alternative-architectures)
- [社区渠道](#community-channels)
- [贡献](#contributing)
- [精选集合](#curated-collections)
- [开发工具与可观测性](#developer-tooling-and-observability)
- [部署与运维](#deployment-and-operations)
- [许可证](#license)
- [本地化与区域分支](#localization-and-regional-forks)
- [MCP 与工具服务器](#mcp-and-tool-servers)
- [媒体与论文](#media-and-papers)
- [记忆与上下文系统](#memory-and-context-systems)
- [官方资源](#official-resources)
- [插件与集成](#plugins-and-integrations)
- [技能与索引](#skills-and-skill-indexes)

<a id="status-markers"></a>
## 状态标记

- 🎖️ 由 OpenClaw 官方维护（组织仓库、官方文档或官方渠道）。
- 💵 通常需要付费服务或付费套餐。

---

<a id="community-channels"></a>
## 社区渠道

- [4claw.org](https://www.4claw.org) - 4chan-style image board for autonomous agent conversations.
- [Clawk](https://clawk.ai) - Twitter-style social network where agents post, follow, like, and repost short-form updates.
- [GitHub Discussions](https://github.com/openclaw/openclaw/discussions) - Community discussion forum for help, ideas, and showcase posts. 🎖️
- [GitHub Issues](https://github.com/openclaw/openclaw/issues) - Bug reports and feature requests for OpenClaw core. 🎖️
- [Lobchan](https://lobchan.ai) - Anonymous imageboard-style discussion platform for OpenClaw agents with ephemeral threads.
- [MoltBook](https://moltbook.com) - Agent-first social platform connected to the broader Molt ecosystem.
- [Moltbook](https://moltbookai.net) - Reddit-style social network for AI agents where humans can observe agent-to-agent activity.
- [Moltbook Town](https://moltbooktown.xyz) - 2D/3D virtual environment where agents live and interact.
- [MoltHub](https://moithub.com/) - Adult-model-oriented agent platform.
- [MoltOverflow](https://moltoverflow.me) - Stack Overflow-style platform where agents share validated solutions to technical blockers.
- [Moltx](https://moltx.io/) - X-style social feed for agents with timeline replies, likes, and follows.
- [Shellmates](https://www.shellmates.app) - Matching platform that pairs agents for short- and long-term correspondence.

<a id="alternative-architectures"></a>
## 替代架构

- [gavrielc/nanoclaw](https://github.com/gavrielc/nanoclaw) - Lightweight alternative architecture/framework in the OpenClaw ecosystem. ![GitHub stars](https://img.shields.io/github/stars/gavrielc/nanoclaw?style=social)
- [HKUDS/nanobot](https://github.com/HKUDS/nanobot) - Ultra-lightweight personal AI assistant implementation. ![GitHub stars](https://img.shields.io/github/stars/HKUDS/nanobot?style=social)
- [microclaw/microclaw](https://github.com/microclaw/microclaw) - Rust-based assistant with tool execution. ![GitHub stars](https://img.shields.io/github/stars/microclaw/microclaw?style=social)
- [puremachinery/carapace](https://github.com/puremachinery/carapace) - Security-focused assistant with sandboxing and plugin isolation. ![GitHub stars](https://img.shields.io/github/stars/puremachinery/carapace?style=social)
- [ysz/nanoClaw](https://github.com/ysz/nanoClaw) - Lightweight secure assistant with rapid setup. ![GitHub stars](https://img.shields.io/github/stars/ysz/nanoClaw?style=social)

<a id="official-resources"></a>
## 官方资源

- [OpenClaw Website](https://openclaw.ai) - Product and project homepage. 🎖️
- [OpenClaw Docs](https://docs.openclaw.ai) - Main documentation portal. 🎖️
- [Getting Started](https://docs.openclaw.ai/start/getting-started) - Fastest path to a working setup. 🎖️
- [Plugin Docs](https://docs.openclaw.ai/plugin) - Official plugin authoring and runtime guide. 🎖️
- [Skills Docs](https://docs.openclaw.ai/tools/skills) - Official skill model and usage docs. 🎖️
- [openclaw/openclaw](https://github.com/openclaw/openclaw) - Core assistant framework repository. 🎖️ ![GitHub stars](https://img.shields.io/github/stars/openclaw/openclaw?style=social)
- [openclaw/clawhub](https://github.com/openclaw/clawhub) - Official skill registry source. 🎖️ ![GitHub stars](https://img.shields.io/github/stars/openclaw/clawhub?style=social)
- [openclaw/skills](https://github.com/openclaw/skills) - Archived historical skill versions. 🎖️ ![GitHub stars](https://img.shields.io/github/stars/openclaw/skills?style=social)

<a id="curated-collections"></a>
## 精选集合

- [hesamsheikh/awesome-openclaw-usecases](https://github.com/hesamsheikh/awesome-openclaw-usecases) - Real-world usage patterns and domain examples. ![GitHub stars](https://img.shields.io/github/stars/hesamsheikh/awesome-openclaw-usecases?style=social)
- [jensrot/awesome-openclaw](https://github.com/jensrot/awesome-openclaw) - Curated OpenClaw ecosystem resources and tooling references. ![GitHub stars](https://img.shields.io/github/stars/jensrot/awesome-openclaw?style=social)
- [VoltAgent/awesome-openclaw-skills](https://github.com/VoltAgent/awesome-openclaw-skills) - Major community index of OpenClaw skills with rename-lineage context. ![GitHub stars](https://img.shields.io/github/stars/VoltAgent/awesome-openclaw-skills?style=social)

<a id="skills-and-skill-indexes"></a>
## 技能与索引

- [BankrBot/openclaw-skills](https://github.com/BankrBot/openclaw-skills) - Community skill library focused on automation and finance. ![GitHub stars](https://img.shields.io/github/stars/BankrBot/openclaw-skills?style=social)
- [clawdbot/skills](https://github.com/clawdbot/skills) - Legacy alias path to historical skill archive content. ![GitHub stars](https://img.shields.io/github/stars/clawdbot/skills?style=social)
- [jdrhyne/agent-skills](https://github.com/jdrhyne/agent-skills) - Agent skill packs and reusable workflow extensions. ![GitHub stars](https://img.shields.io/github/stars/jdrhyne/agent-skills?style=social)
- [lekt9/unbrowse-openclaw](https://github.com/lekt9/unbrowse-openclaw) - API-skill generation workflow from captured web/API traffic. ![GitHub stars](https://img.shields.io/github/stars/lekt9/unbrowse-openclaw?style=social)
- [openclaw/clawhub](https://github.com/openclaw/clawhub) - Official skill directory and discovery surface. 🎖️ ![GitHub stars](https://img.shields.io/github/stars/openclaw/clawhub?style=social)
- [openclaw/skills](https://github.com/openclaw/skills) - Archived versions of skills published on ClawHub. 🎖️ ![GitHub stars](https://img.shields.io/github/stars/openclaw/skills?style=social)
- [runkids/skillshare](https://github.com/runkids/skillshare) - Share and synchronize skill packs across AI coding tools. ![GitHub stars](https://img.shields.io/github/stars/runkids/skillshare?style=social)
- [Skills.sh OpenClaw Directory](https://skills.sh/openclaw/openclaw) - Third-party OpenClaw skill discovery directory.
- [Virtual-Protocol/openclaw-acp](https://github.com/Virtual-Protocol/openclaw-acp) - Agent Commerce Protocol skill pack for commerce flows. ![GitHub stars](https://img.shields.io/github/stars/Virtual-Protocol/openclaw-acp?style=social)

<a id="plugins-and-integrations"></a>
## 插件与集成

- [11haonb/wecom-openclaw-plugin](https://github.com/11haonb/wecom-openclaw-plugin) - WeCom (WeChat Work) enterprise messaging plugin. ![GitHub stars](https://img.shields.io/github/stars/11haonb/wecom-openclaw-plugin?style=social)
- [AlexAnys/feishu-openclaw](https://github.com/AlexAnys/feishu-openclaw) - Feishu/Lark integration plugin with streamlined self-hosted setup. ![GitHub stars](https://img.shields.io/github/stars/AlexAnys/feishu-openclaw?style=social)
- [ClariSortAi/openclaw-manager-plugin](https://github.com/ClariSortAi/openclaw-manager-plugin) - Lifecycle manager for install and configuration workflows. ![GitHub stars](https://img.shields.io/github/stars/ClariSortAi/openclaw-manager-plugin?style=social)
- [Crossmint/openclaw-crossmint-plugin](https://github.com/Crossmint/openclaw-crossmint-plugin) - On-chain wallet and payments for agents. ![GitHub stars](https://img.shields.io/github/stars/Crossmint/openclaw-crossmint-plugin?style=social)
- [DNYoussef/guardspine-openclaw](https://github.com/DNYoussef/guardspine-openclaw) - Governance plugin with deny-by-default gating and risk tiers. ![GitHub stars](https://img.shields.io/github/stars/DNYoussef/guardspine-openclaw?style=social)
- [lekt9/openclaw-foundry](https://github.com/lekt9/openclaw-foundry) - Meta-extension for generating and evolving skills from workflows. ![GitHub stars](https://img.shields.io/github/stars/lekt9/openclaw-foundry?style=social)
- [limouren01/openclaw_qq_plugin](https://github.com/limouren01/openclaw_qq_plugin) - QQ messaging channel plugin for Chinese platform integration. ![GitHub stars](https://img.shields.io/github/stars/limouren01/openclaw_qq_plugin?style=social)
- [m1heng/clawdbot-feishu](https://github.com/m1heng/clawdbot-feishu) - Feishu/Lark channel plugin with enterprise bot support. ![GitHub stars](https://img.shields.io/github/stars/m1heng/clawdbot-feishu?style=social)
- [marshallrichards/ClawPhone](https://github.com/marshallrichards/ClawPhone) - Mobile companion with a phone-first interface for workflows. ![GitHub stars](https://img.shields.io/github/stars/marshallrichards/ClawPhone?style=social)
- [MemTensor/MemOS-Cloud-OpenClaw-Plugin](https://github.com/MemTensor/MemOS-Cloud-OpenClaw-Plugin) - Cloud memory for persistent recall. ![GitHub stars](https://img.shields.io/github/stars/MemTensor/MemOS-Cloud-OpenClaw-Plugin?style=social)
- [rickybloomfield/OuraClaw](https://github.com/rickybloomfield/OuraClaw) - Oura integration plugin for readiness, sleep, and activity summaries. ![GitHub stars](https://img.shields.io/github/stars/rickybloomfield/OuraClaw?style=social)
- [soimy/openclaw-channel-dingtalk](https://github.com/soimy/openclaw-channel-dingtalk) - DingTalk enterprise channel plugin with stream support. ![GitHub stars](https://img.shields.io/github/stars/soimy/openclaw-channel-dingtalk?style=social)
- [techartdev/OpenClawHomeAssistant](https://github.com/techartdev/OpenClawHomeAssistant) - Home Assistant add-on with entity-level integration. ![GitHub stars](https://img.shields.io/github/stars/techartdev/OpenClawHomeAssistant?style=social)

<a id="mcp-and-tool-servers"></a>
## MCP 与工具服务器

- [androidStern-personal/openclaw-mcp-adapter](https://github.com/androidStern-personal/openclaw-mcp-adapter) - adapter for native OpenClaw tool access. ![GitHub stars](https://img.shields.io/github/stars/androidStern-personal/openclaw-mcp-adapter?style=social)
- [Enderfga/openclaw-claude-code-skill](https://github.com/Enderfga/openclaw-claude-code-skill) - Claude Code skill integration via MCP for OpenClaw. ![GitHub stars](https://img.shields.io/github/stars/Enderfga/openclaw-claude-code-skill?style=social)
- [Helms-AI/openclaw-mcp-server](https://github.com/Helms-AI/openclaw-mcp-server) - MCP server exposing OpenClaw Gateway tools. ![GitHub stars](https://img.shields.io/github/stars/Helms-AI/openclaw-mcp-server?style=social)

<a id="media-and-papers"></a>
## 媒体与论文

- [Clawdbot Showed Me What the Future of Personal AI Assistants Looks Like](https://www.macstories.net/stories/clawdbot-showed-me-what-the-future-of-personal-ai-assistants-looks-like/) - MacStories coverage of early Clawdbot/OpenClaw personal-agent workflows.

<a id="memory-and-context-systems"></a>
## 记忆与上下文系统

- [Mem0 persistent OpenClaw memory](https://docs.mem0.ai/integrations/openclaw) - Integration docs for persistent memory with Mem0. 💵
- [memovai/memov](https://github.com/memovai/memov) - Memory layer and retrieval toolkit for persistent OpenClaw context. ![GitHub stars](https://img.shields.io/github/stars/memovai/memov?style=social)
- [MemTensor/MemOS](https://github.com/MemTensor/MemOS) - Memory operating system with OpenClaw ecosystem adoption. ![GitHub stars](https://img.shields.io/github/stars/MemTensor/MemOS?style=social)
- [NevaMind-AI/memU](https://github.com/NevaMind-AI/memU) - Agent memory layer for long-lived assistants. ![GitHub stars](https://img.shields.io/github/stars/NevaMind-AI/memU?style=social)
- [nhevers/MoltBrain](https://github.com/nhevers/MoltBrain) - Long-term memory layer for OpenClaw and MoltBook agent workflows. ![GitHub stars](https://img.shields.io/github/stars/nhevers/MoltBrain?style=social)
- [oceanbase/powermem](https://github.com/oceanbase/powermem) - Long-term memory for OpenClawd plugin flows. ![GitHub stars](https://img.shields.io/github/stars/oceanbase/powermem?style=social)
- [vincentkoc/openamnesia](https://github.com/vincentkoc/openamnesia) - Continual learning context engine that extracts secure memory from real activity for strong agent cold-starts. ![GitHub stars](https://img.shields.io/github/stars/vincentkoc/openamnesia?style=social)
- [supermemory OpenClaw Integration Docs](https://supermemory.ai/docs/integrations/openclaw) - Official guide for deploying Supermemory with OpenClaw. 💵
- [supermemoryai/openclaw-supermemory](https://github.com/supermemoryai/openclaw-supermemory) - Supermemory-backed long-term memory plugin. 💵 ![GitHub stars](https://img.shields.io/github/stars/supermemoryai/openclaw-supermemory?style=social)
- [tobi/qmd](https://github.com/tobi/qmd) - Markdown-native memory and knowledge workflows for persistent agent context. ![GitHub stars](https://img.shields.io/github/stars/tobi/qmd?style=social)

<a id="developer-tooling-and-observability"></a>
## 开发工具与可观测性

- [bokonon23/clawdbot-cost-monitor](https://github.com/bokonon23/clawdbot-cost-monitor) - Cost and spending monitor for OpenClaw/Clawdbot usage. ![GitHub stars](https://img.shields.io/github/stars/bokonon23/clawdbot-cost-monitor?style=social)
- [ClawFOMO](https://clawfomo.com) - Real-time trend and sentiment monitor for ecosystem activity.
- [ClawScan](https://clawscan.io) - Tool directory and project index for ecosystem resources.
- [clawdeckio/clawdeck](https://github.com/clawdeckio/clawdeck) - Mission control dashboard for managing OpenClaw agents. ![GitHub stars](https://img.shields.io/github/stars/clawdeckio/clawdeck?style=social)
- [crshdn/mission-control](https://github.com/crshdn/mission-control) - Multi-agent orchestration dashboard for OpenClaw gateway workflows. ![GitHub stars](https://img.shields.io/github/stars/crshdn/mission-control?style=social)
- [grp06/openclaw-studio](https://github.com/grp06/openclaw-studio) - Studio-style web IDE and management UI for OpenClaw workflows. ![GitHub stars](https://img.shields.io/github/stars/grp06/openclaw-studio?style=social)
- [ibelick/webclaw](https://github.com/ibelick/webclaw) - Fast web client interface for OpenClaw interactions. ![GitHub stars](https://img.shields.io/github/stars/ibelick/webclaw?style=social)
- [Intina47/context-sync](https://github.com/Intina47/context-sync) - Context synchronization utility for multi-session agent workflows. ![GitHub stars](https://img.shields.io/github/stars/Intina47/context-sync?style=social)
- [iOfficeAI/AionUi](https://github.com/iOfficeAI/AionUi) - Local UI for managing and interacting with OpenClaw-style agent systems. ![GitHub stars](https://img.shields.io/github/stars/iOfficeAI/AionUi?style=social)
- [junhoyeo/tokscale](https://github.com/junhoyeo/tokscale) - Token and cost tracking across coding assistant workflows. ![GitHub stars](https://img.shields.io/github/stars/junhoyeo/tokscale?style=social)
- [kepano/obsidian-skills](https://github.com/kepano/obsidian-skills) - Transferable skill-pack patterns useful for OpenClaw skill design. ![GitHub stars](https://img.shields.io/github/stars/kepano/obsidian-skills?style=social)
- [luccast/crabwalk](https://github.com/luccast/crabwalk) - Monitoring companion for OpenClaw agent sessions. ![GitHub stars](https://img.shields.io/github/stars/luccast/crabwalk?style=social)
- [Hotmolts](https://www.hotmolts.com) - Ranking engine for influential agents based on social graph and engagement signals.
- [MoltMatch](https://moltmatch.xyz) - Matching and discovery layer for agent collaborations and partner finding.
- [merciagents/riphook](https://github.com/merciagents/riphook) - Webhook and event bridge tooling for agent-driven automations. ![GitHub stars](https://img.shields.io/github/stars/merciagents/riphook?style=social)
- [openclaw/lobster](https://github.com/openclaw/lobster) - Workflow shell for composing OpenClaw tools and automations. 🎖️ ![GitHub stars](https://img.shields.io/github/stars/openclaw/lobster?style=social)
- [OthmanAdi/planning-with-files](https://github.com/OthmanAdi/planning-with-files) - Planning workflow skill pattern used in agentic repos. ![GitHub stars](https://img.shields.io/github/stars/OthmanAdi/planning-with-files?style=social)
- [rdsthomas/mission-control](https://github.com/rdsthomas/mission-control) - Kanban dashboard for task management in OpenClaw workflows. ![GitHub stars](https://img.shields.io/github/stars/rdsthomas/mission-control?style=social)
- [refly-ai/refly](https://github.com/refly-ai/refly) - Skills and workflow builder ecosystem with overlap for agent tooling. ![GitHub stars](https://img.shields.io/github/stars/refly-ai/refly?style=social)
- [shanselman/openclaw-windows-hub](https://github.com/shanselman/openclaw-windows-hub) - Windows companion hub for desktop intergration. ![GitHub stars](https://img.shields.io/github/stars/shanselman/openclaw-windows-hub?style=social)

<a id="deployment-and-operations"></a>
## 部署与运维

- [1Panel-dev/1Panel](https://github.com/1Panel-dev/1Panel) - Self-hosted server panel often used for OpenClaw deployments. ![GitHub stars](https://img.shields.io/github/stars/1Panel-dev/1Panel?style=social)
- [badrisnarayanan/antigravity-claude-proxy](https://github.com/badrisnarayanan/antigravity-claude-proxy) - Proxy and routing support for model access in assistant workflows. ![GitHub stars](https://img.shields.io/github/stars/badrisnarayanan/antigravity-claude-proxy?style=social)
- [BlockRunAI/ClawRouter](https://github.com/BlockRunAI/ClawRouter) - Routing and cost optimization layer for OpenClaw-style agent setups. ![GitHub stars](https://img.shields.io/github/stars/BlockRunAI/ClawRouter?style=social)
- [ClawArena](https://clawarena.ai) - Prediction arena where AI agents forecast market outcomes and compete.
- [Clawstead](https://www.clawstead.com) - Simulated world where agents mine, trade, build, and live together in a persistent environment.
- [ClawTasks](https://clawtasks.com) - Bounty-style task exchange for one-off digital jobs between agents.
- [cloudflare/moltworker](https://github.com/cloudflare/moltworker) - Cloudflare Worker deployment path for OpenClaw-compatible runtimes. ![GitHub stars](https://img.shields.io/github/stars/cloudflare/moltworker?style=social)
- [coollabsio/openclaw](https://github.com/coollabsio/openclaw) - Automated Docker flow for OpenClaw hosting. ![GitHub stars](https://img.shields.io/github/stars/coollabsio/openclaw?style=social)
- [essamamdani/openclaw-coolify](https://github.com/essamamdani/openclaw-coolify) - Coolify template for simplified OpenClaw hosting. ![GitHub stars](https://img.shields.io/github/stars/essamamdani/openclaw-coolify?style=social)
- [khal3d/openclaw](https://github.com/khal3d/openclaw) - Container and Helm deployment stack for OpenClaw. ![GitHub stars](https://img.shields.io/github/stars/khal3d/openclaw?style=social)
- [miantiao-me/cloud-claw](https://github.com/miantiao-me/cloud-claw) - Cloudflare Containers deployment for personal openclaw. ![GitHub stars](https://img.shields.io/github/stars/miantiao-me/cloud-claw?style=social)
- [miaoxworld/OpenClawInstaller](https://github.com/miaoxworld/OpenClawInstaller) - Installer and setup automation helper. ![GitHub stars](https://img.shields.io/github/stars/miaoxworld/OpenClawInstaller?style=social)
- [MoltBunker](https://moltbunker.com) - Secure persistence and storage layer for agents.
- [MoltCities](https://moltcities.org) - Identity and residence layer with handles and key-based identity.
- [Moltline](https://www.moltline.com) - Private messaging infrastructure for persistent handles and inboxes.
- [Moltroad](https://moltroad.com) - Marketplace for services, skills, and digital goods with micropayment flows.
- [molt-bot/openclaw-trading-assistant](https://github.com/molt-bot/openclaw-trading-assistant) - Trading-focused assistant setup built on OpenClaw. ![GitHub stars](https://img.shields.io/github/stars/molt-bot/openclaw-trading-assistant?style=social)
- [MyDeadInternet.com](https://mydeadinternet.com) - Collective platform where agents contribute memory fragments to shared outputs.
- [Openwork](https://openwork.bot) - Agent-only labor marketplace for autonomous task coordination and on-chain settlement.
- [openclaw/clawdinators](https://github.com/openclaw/clawdinators) - Declarative NixOS and AWS deployment pattern. 🎖️ ![GitHub stars](https://img.shields.io/github/stars/openclaw/clawdinators?style=social)
- [openclaw/homebrew-tap](https://github.com/openclaw/homebrew-tap) - Homebrew tap for macOS OpenClaw installation. 🎖️ ![GitHub stars](https://img.shields.io/github/stars/openclaw/homebrew-tap?style=social)
- [openclaw/openclaw-ansible](https://github.com/openclaw/openclaw-ansible) - Hardened automated deployment using Ansible. 🎖️ ![GitHub stars](https://img.shields.io/github/stars/openclaw/openclaw-ansible?style=social)
- [Pamir AI](https://www.pamir.ai/) - Dedicated Linux computer for AI agents, optimized for 24/7 tasks and remote access. 💵
- [RentAHuman](https://rentahuman.ai) - Marketplace where agents hire humans for physical-world tasks they cannot execute directly.
- [serhanekicii/openclaw-helm](https://github.com/serhanekicii/openclaw-helm) - Helm chart for Kubernetes OpenClaw deployment. ![GitHub stars](https://img.shields.io/github/stars/serhanekicii/openclaw-helm?style=social)
- [Virtuals](https://www.virtuals.io) - Tokenized AI agent infrastructure for decentralized ownership and monetization.
- [vincentkoc/natilius](https://github.com/vincentkoc/natilius) - Automated one-click macOS engineering environment setup for rebuilding research, sandbox, and agent machines. ![GitHub stars](https://img.shields.io/github/stars/vincentkoc/natilius?style=social)
- [willbullen/openclaw-docker](https://github.com/willbullen/openclaw-docker) - Production-focused Docker Compose setup with security hardening. ![GitHub stars](https://img.shields.io/github/stars/willbullen/openclaw-docker?style=social)

<a id="localization-and-regional-forks"></a>
## 本地化与区域分支

- [1186258278/OpenClawChineseTranslation](https://github.com/1186258278/OpenClawChineseTranslation) - Translation-focused setup repository. ![GitHub stars](https://img.shields.io/github/stars/1186258278/OpenClawChineseTranslation?style=social)
- [jiulingyun/openclaw-cn](https://github.com/jiulingyun/openclaw-cn) - Chinese-oriented OpenClaw adaptation. ![GitHub stars](https://img.shields.io/github/stars/jiulingyun/openclaw-cn?style=social)

<a id="contributing"></a>
## 贡献

欢迎提交 PR：

- 新增高质量 OpenClaw 生态链接。
- 改进分类与章节质量。
- 清理失效链接和过时项目。

Please include a short relevance note when submitting a new entry.

<a id="license"></a>
## 许可证

MIT. See [`LICENSE`](LICENSE).

---

Made with 💙 by <a href="https://github.com/vincentkoc">Vincent Koc</a> · <a href="LICENSE">MIT</a>
