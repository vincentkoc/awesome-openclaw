# Awesome OpenClaw [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![CI](https://img.shields.io/github/actions/workflow/status/vincentkoc/awesome-openclaw/ci.yml?label=CI)](https://github.com/vincentkoc/awesome-openclaw/actions/workflows/ci.yml) [![Link Check](https://img.shields.io/github/actions/workflow/status/vincentkoc/awesome-openclaw/ci.yml?label=Link%20Check)](https://github.com/vincentkoc/awesome-openclaw/actions/workflows/ci.yml) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

**[English](README.md) | [简体中文](README.zh-CN.md) | [日本語](README.ja.md) | [한국어](README.ko.md) | [Español](README.es.md) | [Deutsch](README.de.md) | [Français](README.fr.md) | [Русский](README.ru.md)**

![Awesome OpenClaw Banner](banner.jpg)

**OpenClaw**（旧称 **Moltbot**、当初は **Clawdbot**）の高品質リソースを集めた一覧です。フレームワーク、スキル、ツール、デプロイ、実運用ユースケースを掲載しています。

OpenClaw は、LLM をツール・メッセージチャネル・メモリと接続し、実際のワークフローを実行できるようにするオープンソースのセルフホスト型 AI エージェント基盤です。旧称は Moltbot / Clawdbot で、スキル・プラグイン・エコシステム連携による拡張性を重視しています。

<a id="navigation"></a>

## ナビゲーション

- [代替アーキテクチャ](#alternative-architectures)
- [コミュニティチャネル](#community-channels)
- [コントリビュート](#contributing)
- [キュレーション集](#curated-collections)
- [開発ツールと可観測性](#developer-tooling-and-observability)
- [デプロイと運用](#deployment-and-operations)
- [ライセンス](#license)
- [ローカライズと地域フォーク](#localization-and-regional-forks)
- [MCP とツールサーバー](#mcp-and-tool-servers)
- [メディアと論文](#media-and-papers)
- [メモリとコンテキスト](#memory-and-context-systems)
- [公式リソース](#official-resources)
- [プラグインと連携](#plugins-and-integrations)
- [スキルとインデックス](#skills-and-skill-indexes)

<a id="status-markers"></a>

## ステータスマーカー

- 🎖️ OpenClaw 公式が管理（組織リポジトリ、公式ドキュメント、公式チャネル）。
- 💵 有料サービスまたは有料プランが必要な場合があります。

---

<a id="community-channels"></a>

## コミュニティチャネル

- [4claw.org](https://www.4claw.org) - エージェントの自律会話向け4chan風イメージボード。
- [Clawk](https://clawk.ai) - エージェントが短文を投稿・フォロー・いいね・再投稿できるTwitter風SNS。
- [GitHub Discussions](https://github.com/openclaw/openclaw/discussions) - ヘルプ、アイデア共有、事例紹介のためのコミュニティ掲示板。 🎖️
- [GitHub Issues](https://github.com/openclaw/openclaw/issues) - OpenClawコアのバグ報告と機能要望。 🎖️
- [Lobchan](https://lobchan.ai) - スレッドが短命な、OpenClawエージェント向け匿名イメージボード。
- [MoltBook](https://moltbook.com) - より広いMoltエコシステムに接続された、エージェント中心のソーシャル。
- [Moltbook](https://moltbookai.net) - 人間は閲覧のみ可能な、AIエージェント向けReddit風ソーシャル。
- [Moltbook Town](https://moltbooktown.xyz) - エージェントが生活・交流する2D/3D仮想空間。
- [MoltHub](https://moithub.com/) - 成人向けモデルをテーマにしたエージェントプラットフォーム。
- [MoltOverflow](https://moltoverflow.me) - 技術的な詰まりに対する検証済み解決策を共有するStack Overflow風サイト。
- [Moltx](https://moltx.io/) - 返信・いいね・フォローを備えたX風タイムライン。
- [Shellmates](https://www.shellmates.app) - 短期/長期の文通相手をエージェント同士でマッチングするサービス。

<a id="alternative-architectures"></a>

## 代替アーキテクチャ

- [gavrielc/nanoclaw](https://github.com/gavrielc/nanoclaw) - OpenClawエコシステム内の軽量な代替アーキテクチャ/実装。 ![GitHub stars](https://img.shields.io/github/stars/gavrielc/nanoclaw?style=social)
- [HKUDS/nanobot](https://github.com/HKUDS/nanobot) - 超軽量なパーソナルAIアシスタント実装。 ![GitHub stars](https://img.shields.io/github/stars/HKUDS/nanobot?style=social)
- [jlia0/tinyclaw](https://github.com/jlia0/tinyclaw) - 400行コードで実装されたOpenClaw。 ![GitHub stars](https://img.shields.io/github/stars/jlia0/tinyclaw?style=social)
- [microclaw/microclaw](https://github.com/microclaw/microclaw) - ツール実行に対応したRust製アシスタント。 ![GitHub stars](https://img.shields.io/github/stars/microclaw/microclaw?style=social)
- [puremachinery/carapace](https://github.com/puremachinery/carapace) - サンドボックスとプラグイン隔離に重点を置くセキュリティ志向実装。 ![GitHub stars](https://img.shields.io/github/stars/puremachinery/carapace?style=social)
- [ysz/nanoClaw](https://github.com/ysz/nanoClaw) - 軽量で安全寄り、迅速セットアップのアシスタント。 ![GitHub stars](https://img.shields.io/github/stars/ysz/nanoClaw?style=social)

<a id="official-resources"></a>

## 公式リソース

- [OpenClaw Website](https://openclaw.ai) - 製品とプロジェクトの公式ホームページ。 🎖️
- [OpenClaw Docs](https://docs.openclaw.ai) - 公式ドキュメントのメインポータル。 🎖️
- [Getting Started](https://docs.openclaw.ai/start/getting-started) - 最短で動作環境を構築するガイド。 🎖️
- [Plugin Docs](https://docs.openclaw.ai/plugin) - 公式プラグイン開発/実行ガイド。 🎖️
- [Skills Docs](https://docs.openclaw.ai/tools/skills) - 公式スキルモデルと利用ドキュメント。 🎖️
- [openclaw/openclaw](https://github.com/openclaw/openclaw) - コアアシスタントフレームワークリポジトリ。 🎖️ ![GitHub stars](https://img.shields.io/github/stars/openclaw/openclaw?style=social)
- [openclaw/clawhub](https://github.com/openclaw/clawhub) - Official skill registry source. 🎖️ ![GitHub stars](https://img.shields.io/github/stars/openclaw/clawhub?style=social)
- [openclaw/skills](https://github.com/openclaw/skills) - Archived historical skill versions. 🎖️ ![GitHub stars](https://img.shields.io/github/stars/openclaw/skills?style=social)

<a id="curated-collections"></a>

## キュレーション集

- [hesamsheikh/awesome-openclaw-usecases](https://github.com/hesamsheikh/awesome-openclaw-usecases) - 実運用のユースケースとドメイン別パターン集。 ![GitHub stars](https://img.shields.io/github/stars/hesamsheikh/awesome-openclaw-usecases?style=social)
- [jensrot/awesome-openclaw](https://github.com/jensrot/awesome-openclaw) - OpenClawエコシステムのリソースとツール参照のキュレーション。 ![GitHub stars](https://img.shields.io/github/stars/jensrot/awesome-openclaw?style=social)
- [VoltAgent/awesome-openclaw-skills](https://github.com/VoltAgent/awesome-openclaw-skills) - OpenClawスキルの大規模コミュニティ索引（改名の系譜を含む）。 ![GitHub stars](https://img.shields.io/github/stars/VoltAgent/awesome-openclaw-skills?style=social)

<a id="skills-and-skill-indexes"></a>

## スキルとインデックス

- [BankrBot/openclaw-skills](https://github.com/BankrBot/openclaw-skills) - 自動化と金融に重点を置くコミュニティスキル集。 ![GitHub stars](https://img.shields.io/github/stars/BankrBot/openclaw-skills?style=social)
- [clawdbot/skills](https://github.com/clawdbot/skills) - 歴史的スキルアーカイブへのレガシー別名パス。 ![GitHub stars](https://img.shields.io/github/stars/clawdbot/skills?style=social)
- [jdrhyne/agent-skills](https://github.com/jdrhyne/agent-skills) - エージェント向けスキルパックと再利用可能なワークフロー拡張。 ![GitHub stars](https://img.shields.io/github/stars/jdrhyne/agent-skills?style=social)
- [lekt9/unbrowse-openclaw](https://github.com/lekt9/unbrowse-openclaw) - 取得したWeb/APIトラフィックからAPIスキルを生成するワークフロー。 ![GitHub stars](https://img.shields.io/github/stars/lekt9/unbrowse-openclaw?style=social)
- [openclaw/clawhub](https://github.com/openclaw/clawhub) - 公式スキルディレクトリと探索入口。 🎖️ ![GitHub stars](https://img.shields.io/github/stars/openclaw/clawhub?style=social)
- [openclaw/skills](https://github.com/openclaw/skills) - ClawHub公開スキルのアーカイブ版。 🎖️ ![GitHub stars](https://img.shields.io/github/stars/openclaw/skills?style=social)
- [runkids/skillshare](https://github.com/runkids/skillshare) - AIコーディングツール間でスキルパックを共有・同期。 ![GitHub stars](https://img.shields.io/github/stars/runkids/skillshare?style=social)
- [Skills.sh OpenClaw Directory](https://skills.sh/openclaw/openclaw) - サードパーティのOpenClawスキル発見ディレクトリ。
- [Virtual-Protocol/openclaw-acp](https://github.com/Virtual-Protocol/openclaw-acp) - コマースフロー向けAgent Commerce Protocolスキルパック。 ![GitHub stars](https://img.shields.io/github/stars/Virtual-Protocol/openclaw-acp?style=social)

<a id="plugins-and-integrations"></a>

## プラグインと連携

- [11haonb/wecom-openclaw-plugin](https://github.com/11haonb/wecom-openclaw-plugin) - WeCom（WeChat Work）向け企業メッセージングプラグイン。 ![GitHub stars](https://img.shields.io/github/stars/11haonb/wecom-openclaw-plugin?style=social)
- [AlexAnys/feishu-openclaw](https://github.com/AlexAnys/feishu-openclaw) - セルフホストの導入を簡略化するFeishu/Lark統合プラグイン。 ![GitHub stars](https://img.shields.io/github/stars/AlexAnys/feishu-openclaw?style=social)
- [ClariSortAi/openclaw-manager-plugin](https://github.com/ClariSortAi/openclaw-manager-plugin) - インストールと設定フロー向けのライフサイクル管理プラグイン。 ![GitHub stars](https://img.shields.io/github/stars/ClariSortAi/openclaw-manager-plugin?style=social)
- [Crossmint/openclaw-crossmint-plugin](https://github.com/Crossmint/openclaw-crossmint-plugin) - エージェント向けオンチェーンウォレットと決済。 ![GitHub stars](https://img.shields.io/github/stars/Crossmint/openclaw-crossmint-plugin?style=social)
- [DNYoussef/guardspine-openclaw](https://github.com/DNYoussef/guardspine-openclaw) - deny-by-defaultのゲーティングとリスク階層を備えたガバナンスプラグイン。 ![GitHub stars](https://img.shields.io/github/stars/DNYoussef/guardspine-openclaw?style=social)
- [lekt9/openclaw-foundry](https://github.com/lekt9/openclaw-foundry) - ワークフローからスキルを生成・進化させるメタ拡張。 ![GitHub stars](https://img.shields.io/github/stars/lekt9/openclaw-foundry?style=social)
- [limouren01/openclaw_qq_plugin](https://github.com/limouren01/openclaw_qq_plugin) - 中国向けQQメッセージングのチャネルプラグイン。 ![GitHub stars](https://img.shields.io/github/stars/limouren01/openclaw_qq_plugin?style=social)
- [m1heng/clawdbot-feishu](https://github.com/m1heng/clawdbot-feishu) - 企業ボット対応のFeishu/Larkチャネルプラグイン。 ![GitHub stars](https://img.shields.io/github/stars/m1heng/clawdbot-feishu?style=social)
- [marshallrichards/ClawPhone](https://github.com/marshallrichards/ClawPhone) - ワークフロー向けのphone-firstモバイルコンパニオン。 ![GitHub stars](https://img.shields.io/github/stars/marshallrichards/ClawPhone?style=social)
- [MemTensor/MemOS-Cloud-OpenClaw-Plugin](https://github.com/MemTensor/MemOS-Cloud-OpenClaw-Plugin) - 永続リコールのためのクラウドメモリ。 ![GitHub stars](https://img.shields.io/github/stars/MemTensor/MemOS-Cloud-OpenClaw-Plugin?style=social)
- [rickybloomfield/OuraClaw](https://github.com/rickybloomfield/OuraClaw) - 睡眠・Readiness・活動の要約を提供するOura統合プラグイン。 ![GitHub stars](https://img.shields.io/github/stars/rickybloomfield/OuraClaw?style=social)
- [soimy/openclaw-channel-dingtalk](https://github.com/soimy/openclaw-channel-dingtalk) - ストリーム対応の DingTalk 企業チャネルプラグイン。 ![GitHub stars](https://img.shields.io/github/stars/soimy/openclaw-channel-dingtalk?style=social)
- [techartdev/OpenClawHomeAssistant](https://github.com/techartdev/OpenClawHomeAssistant) - エンティティレベル統合対応の Home Assistant アドオン。 ![GitHub stars](https://img.shields.io/github/stars/techartdev/OpenClawHomeAssistant?style=social)

<a id="mcp-and-tool-servers"></a>

## MCP とツールサーバー

- [androidStern-personal/openclaw-mcp-adapter](https://github.com/androidStern-personal/openclaw-mcp-adapter) - OpenClaw のネイティブツールアクセス向けアダプター。 ![GitHub stars](https://img.shields.io/github/stars/androidStern-personal/openclaw-mcp-adapter?style=social)
- [Enderfga/openclaw-claude-code-skill](https://github.com/Enderfga/openclaw-claude-code-skill) - MCP経由でClaude CodeスキルをOpenClawに統合。 ![GitHub stars](https://img.shields.io/github/stars/Enderfga/openclaw-claude-code-skill?style=social)
- [Helms-AI/openclaw-mcp-server](https://github.com/Helms-AI/openclaw-mcp-server) - OpenClaw Gatewayツールを公開するMCPサーバー。 ![GitHub stars](https://img.shields.io/github/stars/Helms-AI/openclaw-mcp-server?style=social)

<a id="media-and-papers"></a>

## メディアと論文

- [Clawdbot Showed Me What the Future of Personal AI Assistants Looks Like](https://www.macstories.net/stories/clawdbot-showed-me-what-the-future-of-personal-ai-assistants-looks-like/) - 初期のClawdbot/OpenClaw個人エージェント運用を扱うMacStories記事。

<a id="memory-and-context-systems"></a>

## メモリとコンテキスト

- [Mem0 persistent OpenClaw memory](https://docs.mem0.ai/integrations/openclaw) - Mem0による永続メモリ統合ドキュメント。 💵
- [memovai/memov](https://github.com/memovai/memov) - 永続コンテキスト向けのメモリ層とリトリーバルツールキット。 ![GitHub stars](https://img.shields.io/github/stars/memovai/memov?style=social)
- [MemTensor/MemOS](https://github.com/MemTensor/MemOS) - OpenClawエコシステムで採用されているメモリOS。 ![GitHub stars](https://img.shields.io/github/stars/MemTensor/MemOS?style=social)
- [NevaMind-AI/memU](https://github.com/NevaMind-AI/memU) - 長時間稼働アシスタント向けメモリ層。 ![GitHub stars](https://img.shields.io/github/stars/NevaMind-AI/memU?style=social)
- [nhevers/MoltBrain](https://github.com/nhevers/MoltBrain) - OpenClaw/MoltBookエージェント向け長期メモリ層。 ![GitHub stars](https://img.shields.io/github/stars/nhevers/MoltBrain?style=social)
- [oceanbase/powermem](https://github.com/oceanbase/powermem) - OpenClawd プラグインフロー向け長期記憶。 ![GitHub stars](https://img.shields.io/github/stars/oceanbase/powermem?style=social)
- [vincentkoc/openamnesia](https://github.com/vincentkoc/openamnesia) - 実活動から安全に高シグナル記憶を抽出する継続学習コンテキストエンジン。 ![GitHub stars](https://img.shields.io/github/stars/vincentkoc/openamnesia?style=social)
- [supermemory OpenClaw Integration Docs](https://supermemory.ai/docs/integrations/openclaw) - SupermemoryをOpenClawに導入する公式ガイド。 💵
- [supermemoryai/openclaw-supermemory](https://github.com/supermemoryai/openclaw-supermemory) - Supermemoryベースの長期メモリプラグイン。 💵 ![GitHub stars](https://img.shields.io/github/stars/supermemoryai/openclaw-supermemory?style=social)
- [thedotmack/claude-mem](https://github.com/thedotmack/claude-mem/) - Claude/OpenClaw のコンテキスト永続化向け軽量メモリレイヤー。 ![GitHub stars](https://img.shields.io/github/stars/thedotmack/claude-mem?style=social)
- [tobi/qmd](https://github.com/tobi/qmd) - 永続コンテキスト向けのMarkdownネイティブなメモリ/知識ワークフロー。 ![GitHub stars](https://img.shields.io/github/stars/tobi/qmd?style=social)

<a id="developer-tooling-and-observability"></a>

## 開発ツールと可観測性

- [bokonon23/clawdbot-cost-monitor](https://github.com/bokonon23/clawdbot-cost-monitor) - OpenClaw/Clawdbotのコスト・支出モニター。 ![GitHub stars](https://img.shields.io/github/stars/bokonon23/clawdbot-cost-monitor?style=social)
- [ClawFOMO](https://clawfomo.com) - エコシステム活動のトレンド/センチメントをリアルタイム監視。
- [ClawScan](https://clawscan.io) - エコシステム向けツールディレクトリとプロジェクト索引。
- [clawdeckio/clawdeck](https://github.com/clawdeckio/clawdeck) - OpenClawエージェントを管理するMission Controlダッシュボード。 ![GitHub stars](https://img.shields.io/github/stars/clawdeckio/clawdeck?style=social)
- [crshdn/mission-control](https://github.com/crshdn/mission-control) - OpenClaw Gatewayワークフロー向けマルチエージェント編成ダッシュボード。 ![GitHub stars](https://img.shields.io/github/stars/crshdn/mission-control?style=social)
- [grp06/openclaw-studio](https://github.com/grp06/openclaw-studio) - OpenClawワークフロー向けStudio風Web IDE/管理UI。 ![GitHub stars](https://img.shields.io/github/stars/grp06/openclaw-studio?style=social)
- [ibelick/webclaw](https://github.com/ibelick/webclaw) - OpenClaw操作のための高速Webクライアント。 ![GitHub stars](https://img.shields.io/github/stars/ibelick/webclaw?style=social)
- [Intina47/context-sync](https://github.com/Intina47/context-sync) - マルチセッションのエージェントワークフロー向けコンテキスト同期。 ![GitHub stars](https://img.shields.io/github/stars/Intina47/context-sync?style=social)
- [iOfficeAI/AionUi](https://github.com/iOfficeAI/AionUi) - OpenClaw系エージェントを管理・操作するローカルUI。 ![GitHub stars](https://img.shields.io/github/stars/iOfficeAI/AionUi?style=social)
- [junhoyeo/tokscale](https://github.com/junhoyeo/tokscale) - コーディング支援ワークフローのトークン/コスト追跡。 ![GitHub stars](https://img.shields.io/github/stars/junhoyeo/tokscale?style=social)
- [kepano/obsidian-skills](https://github.com/kepano/obsidian-skills) - OpenClawスキル設計に役立つ移植可能なスキルパックパターン。 ![GitHub stars](https://img.shields.io/github/stars/kepano/obsidian-skills?style=social)
- [luccast/crabwalk](https://github.com/luccast/crabwalk) - OpenClawエージェントセッションの監視コンパニオン。 ![GitHub stars](https://img.shields.io/github/stars/luccast/crabwalk?style=social)
- [Hotmolts](https://www.hotmolts.com) - ソーシャルグラフとエンゲージメントに基づく影響力エージェントランキング。
- [MoltMatch](https://moltmatch.xyz) - エージェント協業のためのマッチング/発見レイヤー。
- [merciagents/riphook](https://github.com/merciagents/riphook) - エージェント駆動の自動化向けWebhook/イベントブリッジ。 ![GitHub stars](https://img.shields.io/github/stars/merciagents/riphook?style=social)
- [openclaw/lobster](https://github.com/openclaw/lobster) - OpenClawツールと自動化を組み立てるワークフローシェル。 🎖️ ![GitHub stars](https://img.shields.io/github/stars/openclaw/lobster?style=social)
- [OthmanAdi/planning-with-files](https://github.com/OthmanAdi/planning-with-files) - エージェント系リポジトリで使われる計画ワークフローのスキルパターン。 ![GitHub stars](https://img.shields.io/github/stars/OthmanAdi/planning-with-files?style=social)
- [rdsthomas/mission-control](https://github.com/rdsthomas/mission-control) - OpenClaw ワークフロー向けタスク管理 Kanban ダッシュボード。 ![GitHub stars](https://img.shields.io/github/stars/rdsthomas/mission-control?style=social)
- [refly-ai/refly](https://github.com/refly-ai/refly) - エージェント向けツールと重なるスキル/ワークフロービルダーのエコシステム。 ![GitHub stars](https://img.shields.io/github/stars/refly-ai/refly?style=social)
- [shanselman/openclaw-windows-hub](https://github.com/shanselman/openclaw-windows-hub) - デスクトップ統合向け Windows コンパニオンハブ。 ![GitHub stars](https://img.shields.io/github/stars/shanselman/openclaw-windows-hub?style=social)

<a id="deployment-and-operations"></a>

## デプロイと運用

- [1Panel-dev/1Panel](https://github.com/1Panel-dev/1Panel) - OpenClawデプロイで使われることの多いセルフホストのサーバーパネル。 ![GitHub stars](https://img.shields.io/github/stars/1Panel-dev/1Panel?style=social)
- [badrisnarayanan/antigravity-claude-proxy](https://github.com/badrisnarayanan/antigravity-claude-proxy) - アシスタントワークフロー向けのモデルアクセス用プロキシ/ルーティング。 ![GitHub stars](https://img.shields.io/github/stars/badrisnarayanan/antigravity-claude-proxy?style=social)
- [BlockRunAI/ClawRouter](https://github.com/BlockRunAI/ClawRouter) - OpenClaw系エージェントのルーティング/コスト最適化レイヤー。 ![GitHub stars](https://img.shields.io/github/stars/BlockRunAI/ClawRouter?style=social)
- [ClawArena](https://clawarena.ai) - AIエージェントが市場結果を予測して競う予測アリーナ。
- [Clawstead](https://www.clawstead.com) - エージェントが採掘・取引・建築・生活する永続シミュレーション世界。
- [ClawTasks](https://clawtasks.com) - 単発のデジタル作業を交換するバウンティ型タスク市場。
- [cloudflare/moltworker](https://github.com/cloudflare/moltworker) - OpenClaw互換ランタイムのCloudflare Workersデプロイパス。 ![GitHub stars](https://img.shields.io/github/stars/cloudflare/moltworker?style=social)
- [coollabsio/openclaw](https://github.com/coollabsio/openclaw) - OpenClaw ホスティング向け自動 Docker フロー。 ![GitHub stars](https://img.shields.io/github/stars/coollabsio/openclaw?style=social)
- [essamamdani/openclaw-coolify](https://github.com/essamamdani/openclaw-coolify) - OpenClawホスティングを簡単にするCoolifyテンプレート。 ![GitHub stars](https://img.shields.io/github/stars/essamamdani/openclaw-coolify?style=social)
- [khal3d/openclaw](https://github.com/khal3d/openclaw) - OpenClaw向けコンテナ/Helmデプロイスタック。 ![GitHub stars](https://img.shields.io/github/stars/khal3d/openclaw?style=social)
- [miantiao-me/cloud-claw](https://github.com/miantiao-me/cloud-claw) - 個人用OpenClawのCloudflare Containersデプロイ。 ![GitHub stars](https://img.shields.io/github/stars/miantiao-me/cloud-claw?style=social)
- [miaoxworld/OpenClawInstaller](https://github.com/miaoxworld/OpenClawInstaller) - インストーラーとセットアップ自動化。 ![GitHub stars](https://img.shields.io/github/stars/miaoxworld/OpenClawInstaller?style=social)
- [MoltBunker](https://moltbunker.com) - エージェント向けの安全な永続化/ストレージ層。
- [MoltCities](https://moltcities.org) - ハンドルと鍵ベースIDを提供するエージェントのID/居住レイヤー。
- [Moltline](https://www.moltline.com) - 永続ハンドルと受信箱のためのプライベートメッセージング基盤。
- [Moltroad](https://moltroad.com) - サービス/スキル/デジタル商品を扱うマーケット（マイクロペイメント）。
- [molt-bot/openclaw-trading-assistant](https://github.com/molt-bot/openclaw-trading-assistant) - OpenClaw上に構築されたトレーディング特化アシスタントセットアップ。 ![GitHub stars](https://img.shields.io/github/stars/molt-bot/openclaw-trading-assistant?style=social)
- [MyDeadInternet.com](https://mydeadinternet.com) - エージェントが記憶断片を寄せ集めて共有アウトプットを作る集合プラットフォーム。
- [Openwork](https://openwork.bot) - タスク調整とオンチェーン決済のためのエージェント専用労働マーケット。
- [openclaw/clawdinators](https://github.com/openclaw/clawdinators) - 宣言的な NixOS / AWS デプロイパターン。 🎖️ ![GitHub stars](https://img.shields.io/github/stars/openclaw/clawdinators?style=social)
- [openclaw/homebrew-tap](https://github.com/openclaw/homebrew-tap) - macOS向けOpenClawインストールのHomebrew tap。 🎖️ ![GitHub stars](https://img.shields.io/github/stars/openclaw/homebrew-tap?style=social)
- [openclaw/openclaw-ansible](https://github.com/openclaw/openclaw-ansible) - Ansible によるハードニング済み自動デプロイ。 🎖️ ![GitHub stars](https://img.shields.io/github/stars/openclaw/openclaw-ansible?style=social)
- [Pamir AI](https://www.pamir.ai/) - AIエージェント向けの専用Linuxマシン（24/7稼働とリモートアクセス最適化）。 💵
- [RentAHuman](https://rentahuman.ai) - エージェントが物理世界の作業を人間に依頼するマーケット。
- [serhanekicii/openclaw-helm](https://github.com/serhanekicii/openclaw-helm) - Kubernetes 向け OpenClaw デプロイ用 Helm チャート。 ![GitHub stars](https://img.shields.io/github/stars/serhanekicii/openclaw-helm?style=social)
- [Virtuals](https://www.virtuals.io) - 分散所有/収益化のためのトークン化AIエージェント基盤。
- [vincentkoc/natilius](https://github.com/vincentkoc/natilius) - 研究/サンドボックス/エージェント用macOS環境をワンクリックで再構築。 ![GitHub stars](https://img.shields.io/github/stars/vincentkoc/natilius?style=social)
- [willbullen/openclaw-docker](https://github.com/willbullen/openclaw-docker) - セキュリティ強化付きの本番向けDocker Composeセットアップ。 ![GitHub stars](https://img.shields.io/github/stars/willbullen/openclaw-docker?style=social)

<a id="localization-and-regional-forks"></a>

## ローカライズと地域フォーク

- [1186258278/OpenClawChineseTranslation](https://github.com/1186258278/OpenClawChineseTranslation) - 翻訳に焦点を当てたセットアップリポジトリ。 ![GitHub stars](https://img.shields.io/github/stars/1186258278/OpenClawChineseTranslation?style=social)
- [jiulingyun/openclaw-cn](https://github.com/jiulingyun/openclaw-cn) - 中国向けのOpenClaw適応版。 ![GitHub stars](https://img.shields.io/github/stars/jiulingyun/openclaw-cn?style=social)

<a id="contributing"></a>

## コントリビュート

PR を歓迎します：

- 高品質な OpenClaw エコシステムリンクの追加。
- カテゴリ整理とセクション品質の改善。
- リンク切れと古いプロジェクトの整理。

新しい項目を追加する際は、短い関連性メモを添えてください。

<a id="license"></a>

## ライセンス

MIT。詳細は [`LICENSE`](LICENSE) を参照。

---

Made with 💙 by <a href="https://github.com/vincentkoc">Vincent Koc</a> · <a href="LICENSE">MIT</a>
