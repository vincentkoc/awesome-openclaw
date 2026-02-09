# Awesome OpenClaw [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of high-signal resources for **OpenClaw** (formerly **Moltbot**, originally **Clawdbot**): frameworks, skills, tooling, deployments, and real-world use cases.

## Navigation

- [Alternative Architectures](#alternative-architectures)
- [Canonical Project and Aliases](#canonical-project-and-aliases)
- [Community Channels](#community-channels)
- [Contributing](#contributing)
- [Curated Collections](#curated-collections)
- [Developer Tooling and Observability](#developer-tooling-and-observability)
- [Deployment and Operations](#deployment-and-operations)
- [License](#license)
- [Localization and Regional Forks](#localization-and-regional-forks)
- [MCP and Tool Servers](#mcp-and-tool-servers)
- [Memory and Context Systems](#memory-and-context-systems)
- [Official Resources](#official-resources)
- [Plugins and Integrations](#plugins-and-integrations)
- [Security Notes](#security-notes)
- [Skills and Skill Indexes](#skills-and-skill-indexes)
- [Tag Legend](#tag-legend)
- [Use-Case Libraries](#use-case-libraries)

## Tag Legend

- `Alias` - Legacy naming continuity (Moltbot/Clawdbot).
- `Archived` - Historical archive or legacy storage.
- `Catalog` - Index/list of many resources.
- `Community` - Community-maintained project.
- `Docs` - Documentation, integration guide, or technical write-up.
- `Infra` - Deployment, packaging, or infrastructure.
- `MCP` - Model Context Protocol related.
- `Paid` - Requires paid plan or commercial subscription for full use.
- `Official` - Maintained by OpenClaw org or official docs/site.
- `OSS` - Open-source code.
- `Plugins` - Focused on OpenClaw plugin discovery or implementation.
- `Skills` - Focused on OpenClaw skill discovery or implementation.

## Canonical Project and Aliases

- [clawdbot/clawdbot](https://github.com/clawdbot/clawdbot) - Legacy alias URL redirecting to the canonical repository. `Alias`
- [moltbot/moltbot](https://github.com/moltbot/moltbot) - Legacy alias URL redirecting to the canonical repository. `Alias`
- [openclaw/openclaw](https://github.com/openclaw/openclaw) - Core project. `Official` `OSS`

## Community Channels

- [GitHub Discussions](https://github.com/openclaw/openclaw/discussions) - Community discussion forum for help, ideas, and showcase posts. `Official`
- [GitHub Issues](https://github.com/openclaw/openclaw/issues) - Bug reports and feature requests for OpenClaw core. `Official`
- [MoltBook](https://moltbook.com) - Agent-first social platform connected to the broader Molt ecosystem. `Community`

## Alternative Architectures

- [gavrielc/nanoclaw](https://github.com/gavrielc/nanoclaw) - Lightweight alternative architecture/framework in the OpenClaw ecosystem. `Community` `OSS`
- [HKUDS/nanobot](https://github.com/HKUDS/nanobot) - Ultra-lightweight OpenClaw-inspired personal AI assistant implementation. `Community` `OSS`
- [microclaw/microclaw](https://github.com/microclaw/microclaw) - Rust-based OpenClaw-inspired assistant with tool execution and session resume. `Community` `OSS`
- [puremachinery/carapace](https://github.com/puremachinery/carapace) - Security-focused OpenClaw-inspired assistant with sandboxing and plugin isolation. `Community` `OSS`
- [puretensor/hal-claude](https://github.com/puretensor/hal-claude) - Minimal OpenClaw-style alternative emphasizing small code footprint. `Community` `OSS`
- [ysz/nanoClaw](https://github.com/ysz/nanoClaw) - Lightweight secure OpenClaw-inspired assistant with rapid setup. `Community` `OSS`

## Official Resources

- [AGENTS.md](https://github.com/openclaw/openclaw/blob/main/AGENTS.md) - Agent workspace and behavior configuration reference. `Official` `Docs`
- [CHANGELOG.md](https://github.com/openclaw/openclaw/blob/main/CHANGELOG.md) - Core release notes and change history. `Official` `Docs`
- [Channels](https://docs.openclaw.ai/channels) - Official channel integrations and messaging surfaces. `Official`
- [ClawHub](https://clawhub.ai) - Official skill registry and discovery portal. `Official` `Skills`
- [Discord](https://discord.gg/clawd) - Community chat and support server. `Official`
- [Docker Install](https://docs.openclaw.ai/install/docker) - Containerized install guide. `Official` `Infra`
- [FAQ](https://docs.openclaw.ai/start/faq) - Frequently asked questions. `Official`
- [Gateway Security](https://docs.openclaw.ai/gateway/security) - Security controls and hardening notes. `Official`
- [Getting Started](https://docs.openclaw.ai/start/getting-started) - Fastest path to a working setup. `Official`
- [Onboarding Wizard](https://docs.openclaw.ai/start/wizard) - Guided setup flow. `Official`
- [OpenClaw Docs](https://docs.openclaw.ai) - Main documentation portal. `Official`
- [OpenClaw Releases](https://github.com/openclaw/openclaw/releases) - Tagged release builds and changelog snapshots. `Official`
- [OpenClaw Website](https://openclaw.ai) - Product and project homepage. `Official`
- [Plugin Agent Tools](https://docs.openclaw.ai/plugins/agent-tools) - Official reference for adding plugin-provided agent tools. `Official` `Docs` `Plugins`
- [Plugin Docs](https://docs.openclaw.ai/plugin) - Official plugin authoring and runtime guide. `Official` `Docs` `Plugins`
- [openclaw/clawgo](https://github.com/openclaw/clawgo) - Go implementation for Clawd node infrastructure. `Official` `OSS`
- [openclaw/nix-openclaw](https://github.com/openclaw/nix-openclaw) - Nix packaging and setup resources. `Official` `OSS` `Infra`
- [openclaw/openclaw.ai](https://github.com/openclaw/openclaw.ai) - Official website repository. `Official` `OSS`
- [Showcase](https://docs.openclaw.ai/start/showcase) - Example usage and demos. `Official`
- [Skills Docs](https://docs.openclaw.ai/tools/skills) - Official skill model and usage docs. `Official` `Skills`

## Curated Collections

- [hesamsheikh/awesome-openclaw-usecases](https://github.com/hesamsheikh/awesome-openclaw-usecases) - Real-world usage patterns and domain examples. `Community` `Catalog`
- [thewh1teagle/awesome-openclaw](https://github.com/thewh1teagle/awesome-openclaw) - Broad ecosystem curation with tools and workflows. `Community` `Catalog`
- [ThisIsJeron/awesome-openclaw-plugins](https://github.com/ThisIsJeron/awesome-openclaw-plugins) - Curated list of OpenClaw plugins across channels, memory, observability, and governance. `Community` `Catalog` `Plugins`
- [vivy-yi/awesome-openclaw](https://github.com/vivy-yi/awesome-openclaw) - Large multilingual ecosystem curation across platforms, tools, and deployments. `Community` `Catalog`
- [VoltAgent/awesome-openclaw-skills](https://github.com/VoltAgent/awesome-openclaw-skills) - Major community index of OpenClaw skills with rename-lineage context. `Community` `Catalog` `Skills`

## Skills and Skill Indexes

- [BankrBot/openclaw-skills](https://github.com/BankrBot/openclaw-skills) - Community skill library with automation and finance-oriented integrations. `Community` `OSS` `Skills`
- [clawdbot/skills](https://github.com/clawdbot/skills) - Legacy alias path to historical skill archive content. `Alias` `Skills` `Archived`
- [lekt9/unbrowse-openclaw](https://github.com/lekt9/unbrowse-openclaw) - API-skill generation workflow from captured web/API traffic. `Community` `OSS` `Skills`
- [openclaw/clawhub](https://github.com/openclaw/clawhub) - Official skill directory and discovery surface. `Official` `OSS` `Skills`
- [openclaw/skills](https://github.com/openclaw/skills) - Archived versions of skills published on ClawHub. `Official` `OSS` `Skills` `Archived`
- [runkids/skillshare](https://github.com/runkids/skillshare) - Share and synchronize skill packs across AI coding tools. `Community` `OSS` `Skills`
- [Skills.sh OpenClaw Directory](https://skills.sh/openclaw/openclaw) - Third-party OpenClaw skill discovery directory. `Community` `Docs` `Skills`

## Plugins and Integrations

- [bmbsystemsdir/openclaw-model-selector](https://github.com/bmbsystemsdir/openclaw-model-selector) - Smart model routing plugin for suggest-confirm-execute flows. `Community` `OSS` `Plugins`
- [bmbsystemsdir/openclaw-unified-plugins](https://github.com/bmbsystemsdir/openclaw-unified-plugins) - Unified memory plugin layer combining graph and temporal memory patterns. `Community` `OSS` `Plugins`
- [chuckiefan/moltbot-plugin-2do](https://github.com/chuckiefan/moltbot-plugin-2do) - 2Do task manager integration plugin for natural-language task capture. `Community` `OSS` `Plugins`
- [ClariSortAi/openclaw-manager-plugin](https://github.com/ClariSortAi/openclaw-manager-plugin) - Lifecycle management plugin for installation and configuration workflows. `Community` `OSS` `Plugins`
- [Crossmint/openclaw-crossmint-plugin](https://github.com/Crossmint/openclaw-crossmint-plugin) - Smart-wallet and on-chain payment integration plugin for agent transactions. `Community` `OSS` `Plugins`
- [DNYoussef/guardspine-openclaw](https://github.com/DNYoussef/guardspine-openclaw) - Governance plugin with deny-by-default tool gating and risk tiers. `Community` `OSS` `Plugins`
- [flooredApe/openclaw-xmtp](https://github.com/flooredApe/openclaw-xmtp) - XMTP wallet messaging channel plugin for Web3-native communication. `Community` `OSS` `Plugins`
- [IBIZDigital/openclaw-cliq-channel](https://github.com/IBIZDigital/openclaw-cliq-channel) - Zoho Cliq channel plugin with real-time messaging and mention support. `Community` `OSS` `Plugins`
- [kcherry497/OpenClaw-IRC-Plugin](https://github.com/kcherry497/OpenClaw-IRC-Plugin) - IRC channel plugin built around KISS security principles. `Community` `OSS` `Plugins`
- [lekt9/openclaw-foundry](https://github.com/lekt9/openclaw-foundry) - Meta-extension for generating and evolving skills/plugins from observed workflows. `Community` `OSS` `Plugins`
- [likesjx/openclaw-plugin-ansible](https://github.com/likesjx/openclaw-plugin-ansible) - Distributed multi-instance coordination plugin for OpenClaw agents. `Community` `OSS` `Plugins`
- [limouren01/openclaw_qq_plugin](https://github.com/limouren01/openclaw_qq_plugin) - QQ messaging channel plugin for Chinese platform integration. `Community` `OSS` `Plugins`
- [m1heng/clawdbot-feishu](https://github.com/m1heng/clawdbot-feishu) - Feishu/Lark channel plugin with enterprise bot support. `Community` `OSS` `Plugins`
- [marshallrichards/ClawPhone](https://github.com/marshallrichards/ClawPhone) - Mobile companion and phone-first interface for OpenClaw workflows. `Community` `OSS` `Plugins`
- [magicwang1111/openclaw-wechat-plugin](https://github.com/magicwang1111/openclaw-wechat-plugin) - WeChat messaging integration plugin. `Community` `OSS` `Plugins`
- [MemTensor/MemOS-Cloud-OpenClaw-Plugin](https://github.com/MemTensor/MemOS-Cloud-OpenClaw-Plugin) - Cloud memory backend plugin for persistent recall and capture. `Community` `OSS` `Plugins`
- [Oceanswave/openclaw-tescmd](https://github.com/Oceanswave/openclaw-tescmd) - Tesla control and telemetry plugin for automotive workflows. `Community` `OSS` `Plugins`
- [rickybloomfield/OuraClaw](https://github.com/rickybloomfield/OuraClaw) - Oura integration plugin for readiness, sleep, and activity summaries. `Community` `OSS` `Plugins`
- [robb99/clay-webhook-bridge](https://github.com/robb99/clay-webhook-bridge) - Home Assistant to OpenClaw webhook bridge for event-driven automations. `Community` `OSS` `Plugins`
- [robertcuadra/compaction-context](https://github.com/robertcuadra/compaction-context) - Preserves recent context across compaction cycles. `Community` `OSS` `Plugins`
- [soimy/openclaw-channel-dingtalk](https://github.com/soimy/openclaw-channel-dingtalk) - DingTalk enterprise channel plugin with stream mode support. `Community` `OSS` `Plugins`
- [techartdev/OpenClawHomeAssistant](https://github.com/techartdev/OpenClawHomeAssistant) - Home Assistant add-on for running OpenClaw with entity-level integration. `Community` `OSS` `Plugins`
- [ThisIsJeron/openclaw-better-gateway](https://github.com/ThisIsJeron/openclaw-better-gateway) - Gateway UX enhancement plugin with improved connection behavior and status handling. `Community` `OSS` `Plugins`
- [ThisIsJeron/openclaw-observatory](https://github.com/ThisIsJeron/openclaw-observatory) - Multi-gateway observability dashboard for sessions, failures, and cost tracking. `Community` `OSS` `Plugins`

## MCP and Tool Servers

- [Enderfga/openclaw-claude-code-skill](https://github.com/Enderfga/openclaw-claude-code-skill) - OpenClaw skill integration for Claude Code workflows via MCP. `Community` `OSS` `Skills` `MCP`
- [Helms-AI/openclaw-mcp-server](https://github.com/Helms-AI/openclaw-mcp-server) - MCP server exposing OpenClaw Gateway tools. `Community` `OSS` `MCP`
- [openclaw/openclaw#1605](https://github.com/openclaw/openclaw/pull/1605) - Early MCP server support implementation work. `Official` `MCP`
- [openclaw/openclaw#4834](https://github.com/openclaw/openclaw/issues/4834) - Native MCP support discussion/history. `Official` `MCP`
- [openclaw/openclaw#5121](https://github.com/openclaw/openclaw/pull/5121) - MCP server support implementation PR. `Official` `MCP`

## Memory and Context Systems

- [mem0.ai: Memory for OpenClaw](https://mem0.ai/blog/mem0-memory-for-openclaw) - Mem0 engineering write-up and setup path for persistent OpenClaw memory. `Community` `Docs` `Paid`
- [Mem0 OpenClaw Integration Docs](https://docs.mem0.ai/integrations/openclaw) - Integration documentation for Mem0-backed OpenClaw memory. `Community` `Docs` `Paid`
- [memovai/memov](https://github.com/memovai/memov) - Memory layer and retrieval toolkit for persistent OpenClaw context. `Community` `OSS`
- [MemTensor/MemOS](https://github.com/MemTensor/MemOS) - Memory operating system with OpenClaw ecosystem adoption. `Community` `OSS`
- [NevaMind-AI/memU](https://github.com/NevaMind-AI/memU) - Agent memory layer for long-lived assistants. `Community` `OSS`
- [nhevers/MoltBrain](https://github.com/nhevers/MoltBrain) - Long-term memory layer for OpenClaw and MoltBook agent workflows. `Community` `OSS` `Plugins`
- [oceanbase/powermem](https://github.com/oceanbase/powermem) - Long-term memory infrastructure referenced in Moltbot/Clawdbot plugin contexts. `Community` `OSS`
- [supermemory OpenClaw Integration Docs](https://supermemory.ai/docs/integrations/openclaw) - Official guide for deploying Supermemory with OpenClaw. `Community` `Docs` `Paid`
- [supermemoryai/openclaw-supermemory](https://github.com/supermemoryai/openclaw-supermemory) - OpenClaw long-term memory plugin backed by Supermemory cloud. `Community` `OSS` `Plugins` `Paid`
- [tobi/qmd](https://github.com/tobi/qmd) - Markdown-native memory and knowledge workflows for persistent agent context. `Community` `OSS`
- [Vel-Labs/molting-memory](https://github.com/Vel-Labs/molting-memory) - Qdrant-based long-term memory layer for OpenClaw-style agents. `Community` `OSS`

## Developer Tooling and Observability

- [bokonon23/clawdbot-cost-monitor](https://github.com/bokonon23/clawdbot-cost-monitor) - Cost and spending monitor for OpenClaw/Clawdbot usage. `Community` `OSS`
- [grp06/openclaw-studio](https://github.com/grp06/openclaw-studio) - Studio-style web IDE and management UI for OpenClaw workflows. `Community` `OSS`
- [ibelick/webclaw](https://github.com/ibelick/webclaw) - Fast web client interface for OpenClaw interactions. `Community` `OSS`
- [Intina47/context-sync](https://github.com/Intina47/context-sync) - Context synchronization utility for multi-session agent workflows. `Community` `OSS`
- [iOfficeAI/AionUi](https://github.com/iOfficeAI/AionUi) - Local UI for managing and interacting with OpenClaw-style agent systems. `Community` `OSS`
- [junhoyeo/tokscale](https://github.com/junhoyeo/tokscale) - Token and cost tracking across coding assistant workflows. `Community` `OSS`
- [kepano/obsidian-skills](https://github.com/kepano/obsidian-skills) - Transferable skill-pack patterns useful for OpenClaw skill design. `Community` `OSS` `Skills`
- [luccast/crabwalk](https://github.com/luccast/crabwalk) - Monitoring companion for OpenClaw agent sessions. `Community` `OSS`
- [merciagents/riphook](https://github.com/merciagents/riphook) - Webhook and event bridge tooling for agent-driven automations. `Community` `OSS`
- [openclaw/lobster](https://github.com/openclaw/lobster) - Workflow shell for composing OpenClaw tools and automations. `Official` `OSS`
- [OthmanAdi/planning-with-files](https://github.com/OthmanAdi/planning-with-files) - Planning workflow skill pattern used in agentic repos. `Community` `OSS` `Skills`
- [rdsthomas/mission-control](https://github.com/rdsthomas/mission-control) - Kanban dashboard and chat-to-task project management for Moltbot/OpenClaw assistants. `Community` `OSS`
- [refly-ai/refly](https://github.com/refly-ai/refly) - Skills and workflow builder ecosystem with overlap for agent tooling. `Community` `OSS` `Skills`

## Deployment and Operations

- [1Panel-dev/1Panel](https://github.com/1Panel-dev/1Panel) - Self-hosted server panel often used for OpenClaw deployments. `Community` `OSS` `Infra`
- [badrisnarayanan/antigravity-claude-proxy](https://github.com/badrisnarayanan/antigravity-claude-proxy) - Proxy and routing support for model access in assistant workflows. `Community` `OSS` `Infra`
- [BlockRunAI/ClawRouter](https://github.com/BlockRunAI/ClawRouter) - Routing and cost optimization layer for OpenClaw-style agent setups. `Community` `OSS` `Infra`
- [cloudflare/moltworker](https://github.com/cloudflare/moltworker) - Cloudflare Worker deployment path for OpenClaw-compatible runtimes. `Community` `OSS` `Infra`
- [essamamdani/openclaw-coolify](https://github.com/essamamdani/openclaw-coolify) - Coolify template for simplified OpenClaw hosting. `Community` `OSS` `Infra`
- [khal3d/openclaw](https://github.com/khal3d/openclaw) - Container and Helm deployment stack for OpenClaw. `Community` `OSS` `Infra`
- [miantiao-me/cloud-claw](https://github.com/miantiao-me/cloud-claw) - One-click Cloudflare Containers deployment for personal OpenClaw agents. `Community` `OSS` `Infra`
- [miaoxworld/OpenClawInstaller](https://github.com/miaoxworld/OpenClawInstaller) - Installer and setup automation helper. `Community` `OSS` `Infra`
- [molt-bot/openclaw-trading-assistant](https://github.com/molt-bot/openclaw-trading-assistant) - Trading-focused assistant setup built on OpenClaw. `Community` `OSS`
- [openclaw/clawdinators](https://github.com/openclaw/clawdinators) - Declarative NixOS and cloud infrastructure for maintainer-grade agent hosts. `Official` `OSS` `Infra`
- [openclaw/homebrew-tap](https://github.com/openclaw/homebrew-tap) - Homebrew tap for macOS OpenClaw installation. `Official` `OSS` `Infra`
- [openclaw/openclaw-ansible](https://github.com/openclaw/openclaw-ansible) - Hardened automated deployment using Ansible and containerized runtime patterns. `Official` `OSS` `Infra`
- [willbullen/openclaw-docker](https://github.com/willbullen/openclaw-docker) - Production-focused Docker Compose setup with security hardening. `Community` `OSS` `Infra`

## Localization and Regional Forks

- [1186258278/OpenClawChineseTranslation](https://github.com/1186258278/OpenClawChineseTranslation) - Translation-focused setup repository. `Community` `OSS`
- [jiulingyun/openclaw-cn](https://github.com/jiulingyun/openclaw-cn) - Chinese-oriented OpenClaw adaptation. `Community` `OSS`

## Use-Case Libraries

- [Creative and Building](https://github.com/hesamsheikh/awesome-openclaw-usecases#creative--building) - Creative workflows and build projects. `Community` `Catalog`
- [Productivity](https://github.com/hesamsheikh/awesome-openclaw-usecases#productivity) - Personal and team productivity examples. `Community` `Catalog`
- [Research and Learning](https://github.com/hesamsheikh/awesome-openclaw-usecases#research--learning) - Learning, discovery, and research examples. `Community` `Catalog`
- [Social Media Use Cases](https://github.com/hesamsheikh/awesome-openclaw-usecases#social-media) - Content and social automation examples. `Community` `Catalog`

## Security Notes

- Treat third-party skills as untrusted code.
- Review repository source and maintainer profile before install.
- Start with least privilege and allow-listed tools.
- Keep API keys out of prompts, logs, and skill templates.
- Prefer sandboxed execution for untrusted integrations.
- Use official references first: [Skills Docs](https://docs.openclaw.ai/tools/skills) and [Gateway Security](https://docs.openclaw.ai/gateway/security).

## Contributing

PRs are welcome for:

- New high-signal OpenClaw ecosystem links.
- Better categorization and metadata tags.
- Dead-link cleanup and stale project removal.

Please include a short relevance note when submitting a new entry.

## License

MIT. See [`LICENSE`](LICENSE).
