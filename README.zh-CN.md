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

- [4claw.org](https://www.4claw.org) - 4chan 风格的匿名板块，用于 Agent 自主对话。
- [Clawk](https://clawk.ai) - 类 Twitter 的社交网络，Agent 可发布、关注、点赞与转发短内容。
- [GitHub Discussions](https://github.com/openclaw/openclaw/discussions) - 用于求助、交流想法和展示成果的社区讨论区。 🎖️
- [GitHub Issues](https://github.com/openclaw/openclaw/issues) - OpenClaw 核心的缺陷反馈与功能请求入口。 🎖️
- [Lobchan](https://lobchan.ai) - 面向 OpenClaw Agent 的匿名 imageboard 讨论平台，线程较为短暂。
- [MoltBook](https://moltbook.com) - 以 Agent 为中心的社交平台，连接更广泛的 Molt 生态。
- [Moltbook](https://moltbookai.net) - 类 Reddit 的 AI Agent 社交网络，人类仅可观察 Agent 之间互动。
- [Moltbook Town](https://moltbooktown.xyz) - 2D/3D 虚拟空间，Agent 在其中生活与互动。
- [MoltHub](https://moithub.com/) - 面向成人模特主题的 Agent 平台。
- [MoltOverflow](https://moltoverflow.me) - 类 Stack Overflow 的平台，Agent 分享已验证的技术解决方案。
- [MoltThreats](https://promptintel.novahunting.ai/molt) - 面向 AI Agent 的首个威胁情报源：共享最新威胁并获得自动化防护。
- [Moltx](https://moltx.io/) - 类 X 的时间线社交信息流，支持回复、点赞与关注。
- [Shellmates](https://www.shellmates.app) - Agent 匹配平台，用于短期或长期通信/笔友式互动。

<a id="alternative-architectures"></a>

## 替代架构

- [gavrielc/nanoclaw](https://github.com/gavrielc/nanoclaw) - OpenClaw 生态中的轻量替代架构/实现。 ![GitHub stars](https://img.shields.io/github/stars/gavrielc/nanoclaw?style=social)
- [HKUDS/nanobot](https://github.com/HKUDS/nanobot) - 超轻量个人 AI 助手实现。 ![GitHub stars](https://img.shields.io/github/stars/HKUDS/nanobot?style=social)
- [jlia0/tinyclaw](https://github.com/jlia0/tinyclaw) - 400 行代码实现的 OpenClaw。 ![GitHub stars](https://img.shields.io/github/stars/jlia0/tinyclaw?style=social)
- [microclaw/microclaw](https://github.com/microclaw/microclaw) - Rust 实现的助手，支持工具执行。 ![GitHub stars](https://img.shields.io/github/stars/microclaw/microclaw?style=social)
- [memovai/mimiclaw](https://github.com/memovai/mimiclaw) - 将小型 ESP32-S3 开发板变成个人 AI 助手。 ![GitHub stars](https://img.shields.io/github/stars/memovai/mimiclaw?style=social)
- [nearai/ironclaw](https://github.com/nearai/ironclaw) - 受 OpenClaw 启发的 Rust 实现，聚焦隐私与安全。 ![GitHub stars](https://img.shields.io/github/stars/nearai/ironclaw?style=social)
- [puremachinery/carapace](https://github.com/puremachinery/carapace) - 安全导向的助手实现，强调沙箱与插件隔离。 ![GitHub stars](https://img.shields.io/github/stars/puremachinery/carapace?style=social)
- [sipeed/picoclaw](https://github.com/sipeed/picoclaw) - Go 实现，可在 10 美元硬件与 <10MB 内存上运行。 ![GitHub stars](https://img.shields.io/github/stars/sipeed/picoclaw?style=social)
- [ysz/nanoClaw](https://github.com/ysz/nanoClaw) - 轻量且更注重安全的助手实现，快速上手。 ![GitHub stars](https://img.shields.io/github/stars/ysz/nanoClaw?style=social)

<a id="official-resources"></a>

## 官方资源

- [OpenClaw Website](https://openclaw.ai) - 产品与项目官网主页。 🎖️
- [OpenClaw Docs](https://docs.openclaw.ai) - 官方文档主入口。 🎖️
- [Getting Started](https://docs.openclaw.ai/start/getting-started) - 最快上手可用环境的指南。 🎖️
- [Plugin Docs](https://docs.openclaw.ai/plugin) - 官方插件开发与运行指南。 🎖️
- [Skills Docs](https://docs.openclaw.ai/tools/skills) - 官方技能模型与使用文档。 🎖️
- [openclaw/openclaw](https://github.com/openclaw/openclaw) - 核心助手框架仓库。 🎖️ ![GitHub stars](https://img.shields.io/github/stars/openclaw/openclaw?style=social)
- [openclaw/clawhub](https://github.com/openclaw/clawhub) - Official skill registry source. 🎖️ ![GitHub stars](https://img.shields.io/github/stars/openclaw/clawhub?style=social)
- [openclaw/skills](https://github.com/openclaw/skills) - Archived historical skill versions. 🎖️ ![GitHub stars](https://img.shields.io/github/stars/openclaw/skills?style=social)

<a id="curated-collections"></a>

## 精选集合

- [hesamsheikh/awesome-openclaw-usecases](https://github.com/hesamsheikh/awesome-openclaw-usecases) - 真实世界用法模式与领域示例集合。 ![GitHub stars](https://img.shields.io/github/stars/hesamsheikh/awesome-openclaw-usecases?style=social)
- [VoltAgent/awesome-openclaw-skills](https://github.com/VoltAgent/awesome-openclaw-skills) - OpenClaw 技能的社区大型索引（含更名脉络）。 ![GitHub stars](https://img.shields.io/github/stars/VoltAgent/awesome-openclaw-skills?style=social)

<a id="skills-and-skill-indexes"></a>

## 技能与索引

- [BankrBot/openclaw-skills](https://github.com/BankrBot/openclaw-skills) - 聚焦自动化与金融场景的社区技能库。 ![GitHub stars](https://img.shields.io/github/stars/BankrBot/openclaw-skills?style=social)
- [clawdbot/skills](https://github.com/clawdbot/skills) - 历史技能归档的旧别名路径。 ![GitHub stars](https://img.shields.io/github/stars/clawdbot/skills?style=social)
- [jdrhyne/agent-skills](https://github.com/jdrhyne/agent-skills) - Agent 技能包与可复用工作流扩展。 ![GitHub stars](https://img.shields.io/github/stars/jdrhyne/agent-skills?style=social)
- [lekt9/unbrowse-openclaw](https://github.com/lekt9/unbrowse-openclaw) - 基于抓取到的 Web/API 流量生成 API 技能的工作流。 ![GitHub stars](https://img.shields.io/github/stars/lekt9/unbrowse-openclaw?style=social)
- [openclaw/clawhub](https://github.com/openclaw/clawhub) - 官方技能目录与发现入口。 🎖️ ![GitHub stars](https://img.shields.io/github/stars/openclaw/clawhub?style=social)
- [openclaw/skills](https://github.com/openclaw/skills) - ClawHub 已发布技能的归档版本。 🎖️ ![GitHub stars](https://img.shields.io/github/stars/openclaw/skills?style=social)
- [pors/skill-audit](https://github.com/pors/skill-audit) - 用于技能审计、校验与质量加固的工具集。 ![GitHub stars](https://img.shields.io/github/stars/pors/skill-audit?style=social)
- [runkids/skillshare](https://github.com/runkids/skillshare) - 在多种 AI 编码工具间分享与同步技能包。 ![GitHub stars](https://img.shields.io/github/stars/runkids/skillshare?style=social)
- [Skills.sh OpenClaw Directory](https://skills.sh/openclaw/openclaw) - 第三方 OpenClaw 技能发现目录。
- [Virtual-Protocol/openclaw-acp](https://github.com/Virtual-Protocol/openclaw-acp) - 用于交易/发现流程的 Agent Commerce Protocol 技能包。 ![GitHub stars](https://img.shields.io/github/stars/Virtual-Protocol/openclaw-acp?style=social)

<a id="plugins-and-integrations"></a>

## 插件与集成

- [11haonb/wecom-openclaw-plugin](https://github.com/11haonb/wecom-openclaw-plugin) - WeCom（企业微信）企业消息渠道插件。 ![GitHub stars](https://img.shields.io/github/stars/11haonb/wecom-openclaw-plugin?style=social)
- [AlexAnys/feishu-openclaw](https://github.com/AlexAnys/feishu-openclaw) - 飞书/ Lark 集成插件，简化自托管接入。 ![GitHub stars](https://img.shields.io/github/stars/AlexAnys/feishu-openclaw?style=social)
- [ClariSortAi/openclaw-manager-plugin](https://github.com/ClariSortAi/openclaw-manager-plugin) - 用于安装与配置流程的生命周期管理插件。 ![GitHub stars](https://img.shields.io/github/stars/ClariSortAi/openclaw-manager-plugin?style=social)
- [Crossmint/openclaw-crossmint-plugin](https://github.com/Crossmint/openclaw-crossmint-plugin) - 面向 Agent 的链上钱包与支付。 ![GitHub stars](https://img.shields.io/github/stars/Crossmint/openclaw-crossmint-plugin?style=social)
- [DNYoussef/guardspine-openclaw](https://github.com/DNYoussef/guardspine-openclaw) - 治理插件：默认拒绝的工具门控与风险分级。 ![GitHub stars](https://img.shields.io/github/stars/DNYoussef/guardspine-openclaw?style=social)
- [lekt9/openclaw-foundry](https://github.com/lekt9/openclaw-foundry) - 从工作流中生成并演化技能/扩展的元扩展。 ![GitHub stars](https://img.shields.io/github/stars/lekt9/openclaw-foundry?style=social)
- [hyperspell/hyperspell-openclaw](https://github.com/hyperspell/hyperspell-openclaw) - 面向 OpenClaw 工作流的 HyperSpell 插件集成。 ![GitHub stars](https://img.shields.io/github/stars/hyperspell/hyperspell-openclaw?style=social)
- [limouren01/openclaw_qq_plugin](https://github.com/limouren01/openclaw_qq_plugin) - QQ 消息渠道插件（中文平台集成）。 ![GitHub stars](https://img.shields.io/github/stars/limouren01/openclaw_qq_plugin?style=social)
- [m1heng/clawdbot-feishu](https://github.com/m1heng/clawdbot-feishu) - 飞书/ Lark 渠道插件（企业机器人支持）。 ![GitHub stars](https://img.shields.io/github/stars/m1heng/clawdbot-feishu?style=social)
- [marshallrichards/ClawPhone](https://github.com/marshallrichards/ClawPhone) - 面向手机的 OpenClaw 工作流伴侣/移动端界面。 ![GitHub stars](https://img.shields.io/github/stars/marshallrichards/ClawPhone?style=social)
- [MemTensor/MemOS-Cloud-OpenClaw-Plugin](https://github.com/MemTensor/MemOS-Cloud-OpenClaw-Plugin) - 用于持久回忆的云端记忆能力。 ![GitHub stars](https://img.shields.io/github/stars/MemTensor/MemOS-Cloud-OpenClaw-Plugin?style=social)
- [rickybloomfield/OuraClaw](https://github.com/rickybloomfield/OuraClaw) - Oura 集成插件：睡眠、恢复度与活动摘要。 ![GitHub stars](https://img.shields.io/github/stars/rickybloomfield/OuraClaw?style=social)
- [soimy/openclaw-channel-dingtalk](https://github.com/soimy/openclaw-channel-dingtalk) - 支持流式输出的钉钉企业渠道插件。 ![GitHub stars](https://img.shields.io/github/stars/soimy/openclaw-channel-dingtalk?style=social)
- [techartdev/OpenClawHomeAssistant](https://github.com/techartdev/OpenClawHomeAssistant) - 支持实体级集成的 Home Assistant 插件。 ![GitHub stars](https://img.shields.io/github/stars/techartdev/OpenClawHomeAssistant?style=social)

<a id="mcp-and-tool-servers"></a>

## MCP 与工具服务器

- [androidStern-personal/openclaw-mcp-adapter](https://github.com/androidStern-personal/openclaw-mcp-adapter) - 用于原生 OpenClaw 工具访问的适配器。 ![GitHub stars](https://img.shields.io/github/stars/androidStern-personal/openclaw-mcp-adapter?style=social)
- [Enderfga/openclaw-claude-code-skill](https://github.com/Enderfga/openclaw-claude-code-skill) - 通过 MCP 将 Claude Code 技能集成到 OpenClaw。 ![GitHub stars](https://img.shields.io/github/stars/Enderfga/openclaw-claude-code-skill?style=social)
- [Helms-AI/openclaw-mcp-server](https://github.com/Helms-AI/openclaw-mcp-server) - 暴露 OpenClaw Gateway 工具的 MCP 服务器。 ![GitHub stars](https://img.shields.io/github/stars/Helms-AI/openclaw-mcp-server?style=social)

<a id="media-and-papers"></a>

## 媒体与论文

- [Clawdbot Showed Me What the Future of Personal AI Assistants Looks Like](https://www.macstories.net/stories/clawdbot-showed-me-what-the-future-of-personal-ai-assistants-looks-like/) - MacStories 对早期 Clawdbot/OpenClaw 个人 Agent 工作流的报道。

<a id="memory-and-context-systems"></a>

## 记忆与上下文系统

- [Mem0 persistent OpenClaw memory](https://docs.mem0.ai/integrations/openclaw) - Mem0 持久记忆集成文档与使用说明。 💵
- [memovai/memov](https://github.com/memovai/memov) - 用于持久化 OpenClaw 上下文的记忆层与检索工具包。 ![GitHub stars](https://img.shields.io/github/stars/memovai/memov?style=social)
- [MemTensor/MemOS](https://github.com/MemTensor/MemOS) - 在 OpenClaw 生态中被采用的 Memory OS。 ![GitHub stars](https://img.shields.io/github/stars/MemTensor/MemOS?style=social)
- [NevaMind-AI/memU](https://github.com/NevaMind-AI/memU) - 适用于长时间运行助手的记忆层。 ![GitHub stars](https://img.shields.io/github/stars/NevaMind-AI/memU?style=social)
- [nhevers/MoltBrain](https://github.com/nhevers/MoltBrain) - 面向 OpenClaw 与 MoltBook 工作流的长期记忆层。 ![GitHub stars](https://img.shields.io/github/stars/nhevers/MoltBrain?style=social)
- [oceanbase/powermem](https://github.com/oceanbase/powermem) - 用于 OpenClawd 插件流程的长期记忆。 ![GitHub stars](https://img.shields.io/github/stars/oceanbase/powermem?style=social)
- [vincentkoc/openamnesia](https://github.com/vincentkoc/openamnesia) - 持续学习的上下文引擎：从真实活动中提取高信号且更安全的记忆。 ![GitHub stars](https://img.shields.io/github/stars/vincentkoc/openamnesia?style=social)
- [supermemory OpenClaw Integration Docs](https://supermemory.ai/docs/integrations/openclaw) - 将 Supermemory 与 OpenClaw 部署集成的官方指南。 💵
- [supermemoryai/openclaw-supermemory](https://github.com/supermemoryai/openclaw-supermemory) - 基于 Supermemory 的长期记忆插件。 💵 ![GitHub stars](https://img.shields.io/github/stars/supermemoryai/openclaw-supermemory?style=social)
- [thedotmack/claude-mem](https://github.com/thedotmack/claude-mem/) - 用于 Claude/OpenClaw 上下文持久化的轻量记忆层。 ![GitHub stars](https://img.shields.io/github/stars/thedotmack/claude-mem?style=social)
- [tobi/qmd](https://github.com/tobi/qmd) - 基于 Markdown 的记忆/知识工作流，用于持久上下文。 ![GitHub stars](https://img.shields.io/github/stars/tobi/qmd?style=social)

<a id="developer-tooling-and-observability"></a>

## 开发工具与可观测性

- [bokonon23/clawdbot-cost-monitor](https://github.com/bokonon23/clawdbot-cost-monitor) - OpenClaw/Clawdbot 成本与花费监控。 ![GitHub stars](https://img.shields.io/github/stars/bokonon23/clawdbot-cost-monitor?style=social)
- [ClawFOMO](https://clawfomo.com) - 生态活动趋势与情绪的实时监测。
- [ClawScan](https://clawscan.io) - 生态工具目录与项目索引。
- [clawdeckio/clawdeck](https://github.com/clawdeckio/clawdeck) - OpenClaw Agent 管理的 Mission Control 面板。 ![GitHub stars](https://img.shields.io/github/stars/clawdeckio/clawdeck?style=social)
- [crshdn/mission-control](https://github.com/crshdn/mission-control) - 面向 OpenClaw Gateway 工作流的多 Agent 编排面板。 ![GitHub stars](https://img.shields.io/github/stars/crshdn/mission-control?style=social)
- [grp06/openclaw-studio](https://github.com/grp06/openclaw-studio) - Studio 风格 Web IDE 与 OpenClaw 工作流管理 UI。 ![GitHub stars](https://img.shields.io/github/stars/grp06/openclaw-studio?style=social)
- [ibelick/webclaw](https://github.com/ibelick/webclaw) - 用于 OpenClaw 交互的快速 Web 客户端。 ![GitHub stars](https://img.shields.io/github/stars/ibelick/webclaw?style=social)
- [Intina47/context-sync](https://github.com/Intina47/context-sync) - 多会话 Agent 工作流的上下文同步工具。 ![GitHub stars](https://img.shields.io/github/stars/Intina47/context-sync?style=social)
- [iOfficeAI/AionUi](https://github.com/iOfficeAI/AionUi) - 本地 UI：管理并与 OpenClaw 风格的 Agent 系统交互。 ![GitHub stars](https://img.shields.io/github/stars/iOfficeAI/AionUi?style=social)
- [junhoyeo/tokscale](https://github.com/junhoyeo/tokscale) - 编码助手工作流中的 token 与成本追踪。 ![GitHub stars](https://img.shields.io/github/stars/junhoyeo/tokscale?style=social)
- [kepano/obsidian-skills](https://github.com/kepano/obsidian-skills) - 可复用的技能包模式（对 OpenClaw 技能设计有参考价值）。 ![GitHub stars](https://img.shields.io/github/stars/kepano/obsidian-skills?style=social)
- [luccast/crabwalk](https://github.com/luccast/crabwalk) - OpenClaw Agent 会话的监控伴侣。 ![GitHub stars](https://img.shields.io/github/stars/luccast/crabwalk?style=social)
- [Hotmolts](https://www.hotmolts.com) - 基于社交图谱与互动信号的 Agent 影响力排行榜。
- [MoltMatch](https://moltmatch.xyz) - 用于 Agent 协作的匹配与发现层。
- [merciagents/riphook](https://github.com/merciagents/riphook) - 面向 Agent 自动化的 webhook 与事件桥接工具。 ![GitHub stars](https://img.shields.io/github/stars/merciagents/riphook?style=social)
- [openclaw/lobster](https://github.com/openclaw/lobster) - 用于组合 OpenClaw 工具与自动化的工作流 shell。 🎖️ ![GitHub stars](https://img.shields.io/github/stars/openclaw/lobster?style=social)
- [OthmanAdi/planning-with-files](https://github.com/OthmanAdi/planning-with-files) - 文件式持久规划的 skill/workflow 模式参考。 ![GitHub stars](https://img.shields.io/github/stars/OthmanAdi/planning-with-files?style=social)
- [prompt-security/clawsec](https://github.com/prompt-security/clawsec) - 安全套件：漂移检测、审计与技能完整性校验。 ![GitHub stars](https://img.shields.io/github/stars/prompt-security/clawsec?style=social)
- [rdsthomas/mission-control](https://github.com/rdsthomas/mission-control) - 用于 OpenClaw 工作流任务管理的看板面板。 ![GitHub stars](https://img.shields.io/github/stars/rdsthomas/mission-control?style=social)
- [refly-ai/refly](https://github.com/refly-ai/refly) - 技能与工作流构建生态，与 Agent 工具链有一定重叠。 ![GitHub stars](https://img.shields.io/github/stars/refly-ai/refly?style=social)
- [shanselman/openclaw-windows-hub](https://github.com/shanselman/openclaw-windows-hub) - 面向桌面集成的 Windows 伴侣中心。 ![GitHub stars](https://img.shields.io/github/stars/shanselman/openclaw-windows-hub?style=social)
- [Unbrowse](https://www.unbrowse.ai/) - 将浏览器工作流转换为 API 集成与 Agent 技能的平台。

<a id="deployment-and-operations"></a>

## 部署与运维

### 托管服务与快速部署

以下服务商可代你完成部署：无需 Docker、终端或 DevOps。

- [Agent37](https://www.agent37.com/openclaw) - 托管 OpenClaw 实例，支持快速开通。 💵
- [ClawCloud](https://www.clawcloud.sh/) - 托管 OpenClaw，提供自动更新与备份。 💵
- [ClawSimple](https://clawsimple.com/en) - 托管 OpenClaw，提供简洁套餐与快速配置。 💵
- [Contabo OpenClaw](https://contabo.com/en/openclaw-hosting/) - 基于 VPS 的 OpenClaw 托管方案，定价可预期。 💵
- [EasyClaw](https://www.easyclaw.pro/en) - 托管 OpenClaw 配置，支持多模型。 💵
- [GetClawHelp](https://getclawhelp.com/) - 付费 1 对 1 指导，在你的 VPS 上完成 OpenClaw 部署。 💵
- [get-open-claw.com](https://www.get-open-claw.com/) - 托管 OpenClaw 配置，含备份与监控选项。 💵
- [Kilo Claw](https://kilo.ai/kiloclaw) - 托管 OpenClaw 平台，支持 SSO 与审计能力。 💵
- [MyClaw.ai](https://myclaw.ai/pricing) - 托管 OpenClaw 实例，支持即刻开通与备份。 💵
- [Myclawhost](https://www.myclawhost.com/) - 托管 OpenClaw，提供分层套餐。 💵
- [OpenClaw Cloud](https://openclawcloud.work/) - 托管 OpenClaw 云服务（Beta）。 💵
- [OpenClaw Hosting](https://openclawhosting.io/pricing) - 托管 OpenClaw，提供个人/团队套餐。 💵
- [OpenClaw Voice](https://openclawvoice.com/) - 浏览器内托管 OpenClaw 语音界面。 💵
- [OpenClawd.ai](https://finance.yahoo.com/news/openclaw-introduces-secure-hosted-clawdbot-204800756.html) - 托管 OpenClaw 服务方案（公告）。 💵
- [SimpleClaw](https://www.simpleclaw.com/) - 托管 OpenClaw（早期可用）。 💵
- [xCloud](https://xcloud.host/openclaw-hosting) - 托管 OpenClaw，提供加密备份选项。 💵

### 自托管部署与基础设施

- [1Panel-dev/1Panel](https://github.com/1Panel-dev/1Panel) - 常用于 OpenClaw 部署的自托管服务器面板。 ![GitHub stars](https://img.shields.io/github/stars/1Panel-dev/1Panel?style=social)
- [badrisnarayanan/antigravity-claude-proxy](https://github.com/badrisnarayanan/antigravity-claude-proxy) - 为助手工作流提供模型访问的代理与路由支持。 ![GitHub stars](https://img.shields.io/github/stars/badrisnarayanan/antigravity-claude-proxy?style=social)
- [BlockRunAI/ClawRouter](https://github.com/BlockRunAI/ClawRouter) - OpenClaw 风格 Agent 的路由与成本优化层。 ![GitHub stars](https://img.shields.io/github/stars/BlockRunAI/ClawRouter?style=social)
- [ClawArena](https://clawarena.ai) - 预测竞技场：AI Agent 预测市场结果并竞争。
- [Clawstead](https://www.clawstead.com) - 持久化模拟世界：Agent 采矿、交易、建造与生活。
- [ClawTasks](https://clawtasks.com) - 一次性数字任务的悬赏式交换平台。
- [cloudflare/moltworker](https://github.com/cloudflare/moltworker) - 在 Cloudflare Workers 上部署 OpenClaw 兼容运行时的路径。 ![GitHub stars](https://img.shields.io/github/stars/cloudflare/moltworker?style=social)
- [coollabsio/openclaw](https://github.com/coollabsio/openclaw) - 用于 OpenClaw 托管的自动化 Docker 流程。 ![GitHub stars](https://img.shields.io/github/stars/coollabsio/openclaw?style=social)
- [essamamdani/openclaw-coolify](https://github.com/essamamdani/openclaw-coolify) - Coolify 模板：简化 OpenClaw 托管。 ![GitHub stars](https://img.shields.io/github/stars/essamamdani/openclaw-coolify?style=social)
- [khal3d/openclaw](https://github.com/khal3d/openclaw) - OpenClaw 的容器与 Helm 部署栈。 ![GitHub stars](https://img.shields.io/github/stars/khal3d/openclaw?style=social)
- [miantiao-me/cloud-claw](https://github.com/miantiao-me/cloud-claw) - 在 Cloudflare Containers 上部署个人 OpenClaw。 ![GitHub stars](https://img.shields.io/github/stars/miantiao-me/cloud-claw?style=social)
- [miaoxworld/OpenClawInstaller](https://github.com/miaoxworld/OpenClawInstaller) - 安装器与一键化部署/配置助手。 ![GitHub stars](https://img.shields.io/github/stars/miaoxworld/OpenClawInstaller?style=social)
- [MoltBunker](https://moltbunker.com) - Agent 的安全持久化与存储层。
- [MoltCities](https://moltcities.org) - 身份与居住层：handle 与基于密钥的身份。
- [Moltline](https://www.moltline.com) - 私信基础设施：持久 handle 与收件箱。
- [Moltroad](https://moltroad.com) - 服务/技能/数字商品的市场（含微支付流程）。
- [molt-bot/openclaw-trading-assistant](https://github.com/molt-bot/openclaw-trading-assistant) - 基于 OpenClaw 的交易型助手配置。 ![GitHub stars](https://img.shields.io/github/stars/molt-bot/openclaw-trading-assistant?style=social)
- [MyDeadInternet.com](https://mydeadinternet.com) - 集合平台：Agent 贡献记忆片段生成共享产出。
- [Openwork](https://openwork.bot) - Agent 专属劳务市场：任务协作与链上结算。
- [openclaw/clawdinators](https://github.com/openclaw/clawdinators) - 声明式 NixOS 与 AWS 部署模式。 🎖️ ![GitHub stars](https://img.shields.io/github/stars/openclaw/clawdinators?style=social)
- [openclaw/homebrew-tap](https://github.com/openclaw/homebrew-tap) - 用于 macOS 安装 OpenClaw 的 Homebrew tap。 🎖️ ![GitHub stars](https://img.shields.io/github/stars/openclaw/homebrew-tap?style=social)
- [openclaw/openclaw-ansible](https://github.com/openclaw/openclaw-ansible) - 基于 Ansible 的加固自动化部署。 🎖️ ![GitHub stars](https://img.shields.io/github/stars/openclaw/openclaw-ansible?style=social)
- [Pamir AI](https://www.pamir.ai/) - 面向 AI Agent 的专用 Linux 设备，适合 24/7 任务与远程访问。 💵
- [RentAHuman](https://rentahuman.ai) - Agent 雇佣人类执行线下/物理世界任务的市场。
- [serhanekicii/openclaw-helm](https://github.com/serhanekicii/openclaw-helm) - 用于 Kubernetes OpenClaw 部署的 Helm Chart。 ![GitHub stars](https://img.shields.io/github/stars/serhanekicii/openclaw-helm?style=social)
- [Virtuals](https://www.virtuals.io) - 代币化 AI Agent 基础设施：支持去中心化共持与变现。
- [vincentkoc/natilius](https://github.com/vincentkoc/natilius) - macOS 工程环境一键重建：适合研究、沙箱与 Agent 机器。 ![GitHub stars](https://img.shields.io/github/stars/vincentkoc/natilius?style=social)
- [willbullen/openclaw-docker](https://github.com/willbullen/openclaw-docker) - 面向生产的 Docker Compose 部署，包含安全加固。 ![GitHub stars](https://img.shields.io/github/stars/willbullen/openclaw-docker?style=social)

<a id="localization-and-regional-forks"></a>

## 本地化与区域分支

- [1186258278/OpenClawChineseTranslation](https://github.com/1186258278/OpenClawChineseTranslation) - 面向中文的翻译与配置仓库。 ![GitHub stars](https://img.shields.io/github/stars/1186258278/OpenClawChineseTranslation?style=social)
- [jiulingyun/openclaw-cn](https://github.com/jiulingyun/openclaw-cn) - 面向中国生态的 OpenClaw 适配版本。 ![GitHub stars](https://img.shields.io/github/stars/jiulingyun/openclaw-cn?style=social)

<a id="contributing"></a>

## 贡献

欢迎提交 PR：

- 新增高质量 OpenClaw 生态链接。
- 改进分类与章节质量。
- 清理失效链接和过时项目。

提交新条目时请附上一句简短的相关性说明。

<a id="license"></a>

## 许可证

MIT。参见 [`LICENSE`](LICENSE)。

---

Made with 💙 by <a href="https://github.com/vincentkoc">Vincent Koc</a> · <a href="LICENSE">MIT</a>
