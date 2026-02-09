# Awesome OpenClaw [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of high-signal resources for **OpenClaw** (formerly **Moltbot**, originally **Clawdbot**): frameworks, skills, tooling, deployments, and real-world use cases.

## Navigation

- [Alternative Architectures](#alternative-architectures)
- [Canonical Project and Aliases](#canonical-project-and-aliases)
- [Contributing](#contributing)
- [Curated Collections](#curated-collections)
- [Developer Tooling and Observability](#developer-tooling-and-observability)
- [Deployment and Operations](#deployment-and-operations)
- [License](#license)
- [Localization and Regional Forks](#localization-and-regional-forks)
- [MCP and Tool Servers](#mcp-and-tool-servers)
- [Memory and Context Systems](#memory-and-context-systems)
- [Official Resources](#official-resources)
- [Security Notes](#security-notes)
- [Skills and Skill Indexes](#skills-and-skill-indexes)
- [Tag Legend](#tag-legend)
- [Use-Case Libraries](#use-case-libraries)

## Tag Legend

- `Alias` - Legacy naming continuity (Moltbot/Clawdbot).
- `Archived` - Historical archive or legacy storage.
- `Catalog` - Index/list of many resources.
- `Community` - Community-maintained project.
- `Infra` - Deployment, packaging, or infrastructure.
- `MCP` - Model Context Protocol related.
- `Official` - Maintained by OpenClaw org or official docs/site.
- `OSS` - Open-source code.
- `Skills` - Focused on OpenClaw skill discovery or implementation.

## Canonical Project and Aliases

- [clawdbot/clawdbot](https://github.com/clawdbot/clawdbot) - Legacy alias URL redirecting to the canonical repository. `Alias`
- [moltbot/moltbot](https://github.com/moltbot/moltbot) - Legacy alias URL redirecting to the canonical repository. `Alias`
- [openclaw/openclaw](https://github.com/openclaw/openclaw) - Core project. `Official` `OSS`

## Alternative Architectures

- [gavrielc/nanoclaw](https://github.com/gavrielc/nanoclaw) - Lightweight alternative architecture/framework in the OpenClaw ecosystem. `Community` `OSS`

## Official Resources

- [Channels](https://docs.openclaw.ai/channels) - Official channel integrations and messaging surfaces. `Official`
- [Discord](https://discord.gg/clawd) - Community chat and support server. `Official`
- [Docker Install](https://docs.openclaw.ai/install/docker) - Containerized install guide. `Official` `Infra`
- [FAQ](https://docs.openclaw.ai/start/faq) - Frequently asked questions. `Official`
- [Gateway Security](https://docs.openclaw.ai/gateway/security) - Security controls and hardening notes. `Official`
- [Getting Started](https://docs.openclaw.ai/start/getting-started) - Fastest path to a working setup. `Official`
- [Onboarding Wizard](https://docs.openclaw.ai/start/wizard) - Guided setup flow. `Official`
- [OpenClaw Docs](https://docs.openclaw.ai) - Main documentation portal. `Official`
- [OpenClaw Website](https://openclaw.ai) - Product and project homepage. `Official`
- [openclaw/nix-openclaw](https://github.com/openclaw/nix-openclaw) - Nix packaging and setup resources. `Official` `OSS` `Infra`
- [Showcase](https://docs.openclaw.ai/start/showcase) - Example usage and demos. `Official`
- [Skills Docs](https://docs.openclaw.ai/tools/skills) - Official skill model and usage docs. `Official` `Skills`

## Curated Collections

- [hesamsheikh/awesome-openclaw-usecases](https://github.com/hesamsheikh/awesome-openclaw-usecases) - Real-world usage patterns and domain examples. `Community` `Catalog`
- [thewh1teagle/awesome-openclaw](https://github.com/thewh1teagle/awesome-openclaw) - Broad ecosystem curation with tools and workflows. `Community` `Catalog`
- [VoltAgent/awesome-openclaw-skills](https://github.com/VoltAgent/awesome-openclaw-skills) - Major community index of OpenClaw skills with rename-lineage context. `Community` `Catalog` `Skills`

## Skills and Skill Indexes

- [BankrBot/openclaw-skills](https://github.com/BankrBot/openclaw-skills) - Community skill library with automation and finance-oriented integrations. `Community` `OSS` `Skills`
- [clawdbot/skills](https://github.com/clawdbot/skills) - Legacy alias path to historical skill archive content. `Alias` `Skills` `Archived`
- [lekt9/unbrowse-openclaw](https://github.com/lekt9/unbrowse-openclaw) - API-skill generation workflow from captured web/API traffic. `Community` `OSS` `Skills`
- [openclaw/clawhub](https://github.com/openclaw/clawhub) - Official skill directory and discovery surface. `Official` `OSS` `Skills`
- [openclaw/skills](https://github.com/openclaw/skills) - Archived versions of skills published on ClawHub. `Official` `OSS` `Skills` `Archived`

## MCP and Tool Servers

- [Enderfga/openclaw-claude-code-skill](https://github.com/Enderfga/openclaw-claude-code-skill) - OpenClaw skill integration for Claude Code workflows via MCP. `Community` `OSS` `Skills` `MCP`
- [Helms-AI/openclaw-mcp-server](https://github.com/Helms-AI/openclaw-mcp-server) - MCP server exposing OpenClaw Gateway tools. `Community` `OSS` `MCP`
- [openclaw/openclaw#4834](https://github.com/openclaw/openclaw/issues/4834) - Native MCP support discussion/history. `Official` `MCP`
- [openclaw/openclaw#5121](https://github.com/openclaw/openclaw/pull/5121) - MCP server support implementation PR. `Official` `MCP`

## Memory and Context Systems

- [MemTensor/MemOS](https://github.com/MemTensor/MemOS) - Memory operating system with OpenClaw ecosystem adoption. `Community` `OSS`
- [NevaMind-AI/memU](https://github.com/NevaMind-AI/memU) - Agent memory layer for long-lived assistants. `Community` `OSS`
- [oceanbase/powermem](https://github.com/oceanbase/powermem) - Long-term memory infrastructure referenced in Moltbot/Clawdbot plugin contexts. `Community` `OSS`
- [tobi/qmd](https://github.com/tobi/qmd) - Markdown-native memory and knowledge workflows for persistent agent context. `Community` `OSS`

## Developer Tooling and Observability

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
- [miantiao-me/cloud-claw](https://github.com/miantiao-me/cloud-claw) - One-click Cloudflare Containers deployment for personal OpenClaw agents. `Community` `OSS` `Infra`
- [miaoxworld/OpenClawInstaller](https://github.com/miaoxworld/OpenClawInstaller) - Installer and setup automation helper. `Community` `OSS` `Infra`
- [molt-bot/openclaw-trading-assistant](https://github.com/molt-bot/openclaw-trading-assistant) - Trading-focused assistant setup built on OpenClaw. `Community` `OSS`
- [openclaw/clawdinators](https://github.com/openclaw/clawdinators) - Declarative NixOS and cloud infrastructure for maintainer-grade agent hosts. `Official` `OSS` `Infra`
- [openclaw/openclaw-ansible](https://github.com/openclaw/openclaw-ansible) - Hardened automated deployment using Ansible and containerized runtime patterns. `Official` `OSS` `Infra`

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
