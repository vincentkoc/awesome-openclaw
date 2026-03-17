# Awesome OpenClaw [![Awesome](https://awesome.re/badge.svg)](https://github.com/sindresorhus/awesome) [![CI](https://img.shields.io/github/actions/workflow/status/vincentkoc/awesome-openclaw/ci.yml?label=CI)](https://github.com/vincentkoc/awesome-openclaw/actions/workflows/ci.yml) [![Link Check](https://img.shields.io/github/actions/workflow/status/vincentkoc/awesome-openclaw/ci.yml?label=Link%20Check)](https://github.com/vincentkoc/awesome-openclaw/actions/workflows/ci.yml) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md) [![Skills](https://img.shields.io/badge/Skills-5495+-blue)](./skills) [![中文](https://img.shields.io/badge/中文-文档-red)](./README.zh-CN.md)

**[English](README.md) | [简体中文](README.zh-CN.md) | [日本語](README.ja.md) | [한국어](README.ko.md) | [Español](README.es.md) | [Deutsch](README.de.md) | [Français](README.fr.md) | [Русский](README.ru.md)**

![Awesome OpenClaw Banner](banner.jpg)

A curated list of high-signal resources for **OpenClaw** (formerly **Moltbot**, originally **Clawdbot**): frameworks, skills, tooling, deployments, and real-world use cases.

OpenClaw is an open-source, self-hosted AI agent framework that connects LLMs to tools, messaging channels, and memory systems so agents can execute real workflows. Formerly known as Moltbot and Clawdbot, it is designed for extensibility through skills, plugins, and ecosystem integrations.

## 📊 Repository Statistics

- 🛠️ **5,495+ Skills** - Curated from ClawHub registry
- 🌍 **8 Languages** - Multi-language documentation
- 🏗️ **30+ Categories** - Organized skill collections
- 🔄 **Active Maintenance** - Daily updates from community

## 📁 Repository Structure

```
awesome-openclaw/
├── 📁 skills/              # 5,495+ curated skills by category
│   ├── coding-agents-and-ides.md
│   ├── devops-and-cloud.md
│   ├── communication.md
│   └── ... (30 categories)
├── 📁 skills-zh/           # 中文技能文档
│   └── README.md
├── 📁 tools/               # Development tools & utilities
├── 📁 resources/           # Learning resources & guides
├── 📁 tutorials/           # Step-by-step tutorials
├── 📁 use-cases/           # Real-world use case examples
├── 📄 README.md            # This file (English)
└── 📄 README.zh-CN.md      # 简体中文版本
```

## 🚀 Quick Start

### Installation

```bash
# Install OpenClaw
npm install -g openclaw

# Or use npx
npx openclaw
```

### Install Skills

```bash
# Via ClawHub CLI
clawhub install <skill-slug>

# Manual installation
cp -r skill-folder ~/.openclaw/skills/
```

## 📚 Navigation

- [🛠️ Skills Library](#️-skills-library)
- [🔌 Official Resources](#-official-resources)
- [🏛️ Alternative Architectures](#️-alternative-architectures)
- [💬 Community Channels](#-community-channels)
- [🛠️ Developer Tooling](#-developer-tooling)
- [📦 Deployment](#-deployment)
- [🔌 Plugins & Integrations](#-plugins--integrations)
- [🧠 Memory Systems](#-memory-systems)
- [📝 Contributing](#-contributing)

## 🛠️ Skills Library

Browse our curated collection of **5,495+ skills** organized by category:

| Category | Description | Count |
|----------|-------------|-------|
| [Coding Agents & IDEs](./skills/coding-agents-and-ides.md) | AI coding assistants, IDE integrations | 1000+ |
| [DevOps & Cloud](./skills/devops-and-cloud.md) | Infrastructure, deployment, monitoring | 500+ |
| [Communication](./skills/communication.md) | Email, chat, messaging platforms | 400+ |
| [Browser & Automation](./skills/browser-and-automation.md) | Web scraping, browser control | 800+ |
| [Git & GitHub](./skills/git-and-github.md) | Version control, PR management | 300+ |
| [Web & Frontend](./skills/web-and-frontend-development.md) | Web development tools | 900+ |
| [Search & Research](./skills/search-and-research.md) | Information retrieval, analysis | 600+ |
| [Media & Streaming](./skills/media-and-streaming.md) | Audio, video, content creation | 300+ |
| [Security & Passwords](./skills/security-and-passwords.md) | Security tools, vault management | 200+ |
| [Calendar & Scheduling](./skills/calendar-and-scheduling.md) | Time management, calendar tools | 200+ |

👉 [View All Categories](./skills)

### 🔥 Featured Skills

```markdown
# Coding & Development
- [codex](https://clawdhub.com/skills/codex) - OpenAI Codex integration
- [claude-code](https://clawdhub.com/skills/claude-code) - Claude Code CLI
- [github](https://clawdhub.com/skills/github) - GitHub API integration

# Productivity
- [slack](https://clawdhub.com/skills/slack) - Slack workspace management
- [gmail](https://clawdhub.com/skills/gmail) - Gmail automation
- [notion](https://clawdhub.com/skills/notion) - Notion workspace sync

# AI & Media
- [elevenlabs](https://clawdhub.com/skills/elevenlabs) - Text-to-speech
- [fal-ai](https://clawdhub.com/skills/fal-ai) - Image/video generation
- [perplexity](https://clawdhub.com/skills/perplexity) - AI search
```

## 🔌 Official Resources

- [OpenClaw Website](https://openclaw.ai) - Product and project homepage 🎖️
- [OpenClaw Docs](https://docs.openclaw.ai) - Main documentation portal 🎖️
- [Getting Started](https://docs.openclaw.ai/start/getting-started) - Fastest path to a working setup 🎖️
- [Plugin Docs](https://docs.openclaw.ai/tools/plugin) - Official plugin authoring guide 🎖️
- [Skills Docs](https://docs.openclaw.ai/tools/skills) - Official skill model docs 🎖️
- [openclaw/openclaw](https://github.com/openclaw/openclaw) - Core framework repository 🎖️
- [openclaw/clawhub](https://github.com/openclaw/clawhub) - Official skill registry 🎖️

## 🏛️ Alternative Architectures

- [nanoclaw](https://github.com/qwibitai/nanoclaw) - Lightweight alternative framework
- [nanobot](https://github.com/HKUDS/nanobot) - Ultra-lightweight personal AI assistant
- [tinyclaw](https://github.com/jlia0/tinyclaw) - OpenClaw in 400 lines
- [microclaw](https://github.com/microclaw/microclaw) - Rust-based assistant
- [ironclaw](https://github.com/nearai/ironclaw) - Security-focused Rust implementation
- [picoclaw](https://github.com/sipeed/picoclaw) - Runs on $10 hardware

## 💬 Community Channels

- [GitHub Discussions](https://github.com/openclaw/openclaw/discussions) - Community forum 🎖️
- [Discord](https://discord.gg/openclaw) - Real-time chat
- [Moltbook](https://www.moltbook.com/) - Agent-first social platform
- [Clawk](https://www.clawk.ai/) - Twitter-style agent network
- [MoltOverflow](https://moltoverflow.me) - Stack Overflow for agents

## 🛠️ Developer Tooling

- [ClawHub CLI](https://github.com/openclaw/clawhub) - Skill management
- [Skill Audit](https://github.com/pors/skill-audit) - Security auditing
- [Unbrowse OpenClaw](https://github.com/lekt9/unbrowse-openclaw) - API generation
- [OpenClaw Foundry](https://github.com/lekt9/openclaw-foundry) - Skill generation

## 📦 Deployment

- [Docker](https://docs.openclaw.ai/start/docker) - Containerized deployment
- [Railway](https://railway.app/template/openclaw) - One-click deploy
- [Render](https://render.com/deploy?repo=openclaw/openclaw) - Cloud hosting
- [Fly.io](https://fly.io/docs/app-guides/openclaw/) - Edge deployment

## 🔌 Plugins & Integrations

- [feishu-openclaw](https://github.com/AlexAnys/feishu-openclaw) - Feishu/Lark integration
- [wecom-openclaw-plugin](https://github.com/11haonb/wecom-openclaw-plugin) - WeChat Work
- [openclaw-crossmint-plugin](https://github.com/Crossmint/openclaw-crossmint-plugin) - Web3 payments
- [guardspine-openclaw](https://github.com/DNYoussef/guardspine-openclaw) - Governance

## 🧠 Memory Systems

- [ClawDB](https://github.com/openclaw/clawdb) - Knowledge graph memory
- [Mem0](https://github.com/mem0ai/mem0) - Self-improving memory
- [Chroma](https://github.com/chroma-core/chroma) - Vector database

## 📝 Contributing

Contributions are welcome! Please see [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

### Skill Submission

1. Publish your skill to [openclaw/skills](https://github.com/openclaw/skills)
2. Include ClawHub link in PR description
3. Follow the category structure

## 📜 License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](LICENSE)

To the extent possible under law, the contributors have waived all copyright and related or neighboring rights to this work.

## 🙏 Acknowledgments

- [VoltAgent](https://github.com/VoltAgent/awesome-openclaw-skills) - Original skills curation
- [clawdbot-ai](https://github.com/clawdbot-ai/awesome-openclaw-skills-zh) - Chinese translation
- All [contributors](https://github.com/vincentkoc/awesome-openclaw/graphs/contributors) who make this possible

---

<p align="center">
  <a href="https://openclaw.ai">🦞 OpenClaw</a> |
  <a href="https://clawdhub.com">ClawHub</a> |
  <a href="https://docs.openclaw.ai">Documentation</a>
</p>
