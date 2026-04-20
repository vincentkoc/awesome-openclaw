# Awesome OpenClaw [![Awesome](https://awesome.re/badge.svg)](https://github.com/sindresorhus/awesome) [![CI](https://img.shields.io/github/actions/workflow/status/vincentkoc/awesome-openclaw/ci.yml?label=CI)](https://github.com/vincentkoc/awesome-openclaw/actions/workflows/ci.yml) [![Link Check](https://img.shields.io/github/actions/workflow/status/vincentkoc/awesome-openclaw/ci.yml?label=Link%20Check)](https://github.com/vincentkoc/awesome-openclaw/actions/workflows/ci.yml) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

**[English](README.md) | [简体中文](README.zh-CN.md) | [日本語](README.ja.md) | [한국어](README.ko.md) | [Español](README.es.md) | [Deutsch](README.de.md) | [Français](README.fr.md) | [Русский](README.ru.md)**

![Awesome OpenClaw Banner](banner.jpg)

**OpenClaw**(이전 명칭 **Moltbot**, 초기 **Clawdbot**)의 고신뢰 리소스를 모은 큐레이션 목록입니다: 프레임워크, 스킬, 도구, 배포, 실사용 사례.

OpenClaw는 LLM을 도구, 메시징 채널, 메모리 시스템에 연결해 실제 워크플로를 실행할 수 있게 해주는 오픈소스 셀프호스팅 AI 에이전트 프레임워크입니다. Moltbot/Clawdbot에서 이름이 변경되었으며, 스킬·플러그인·생태계 통합을 통한 확장성을 지향합니다.

<a id="navigation"></a>

## 탐색

- [대체 아키텍처](#alternative-architectures)
- [커뮤니티 채널](#community-channels)
- [기여](#contributing)
- [큐레이션 모음](#curated-collections)
- [개발 도구 및 관측성](#developer-tooling-and-observability)
- [배포 및 운영](#deployment-and-operations)
- [라이선스](#license)
- [현지화 및 지역 포크](#localization-and-regional-forks)
- [MCP 및 도구 서버](#mcp-and-tool-servers)
- [미디어 및 논문](#media-and-papers)
- [메모리 및 컨텍스트 시스템](#memory-and-context-systems)
- [공식 리소스](#official-resources)
- [플러그인 및 통합](#plugins-and-integrations)
- [스킬 및 인덱스](#skills-and-skill-indexes)

<a id="status-markers"></a>

## 상태 표시

- 🎖️ OpenClaw 공식 관리 리소스(조직 저장소, 공식 문서, 공식 채널).
- 💵 전체 기능 사용에 유료 서비스/플랜이 필요할 수 있습니다.

## 안전 참고

커뮤니티 플러그인, 스킬, MCP 서버, 통합은 코드를 실행하고, 자격 증명을 다루고, 메시지를 보내고, 외부 시스템에 접근할 수 있습니다. 기본적으로 신뢰하지 않는 것으로 취급하세요.

`🎖️` 표시가 있는 항목만 OpenClaw 공식 관리 리소스입니다. 커뮤니티 항목은 발견을 위한 목록일 뿐, 보안 검토나 공식 보증을 뜻하지 않습니다. 사용 전에 소스, 권한, 설치 절차, 유지보수 상태를 확인하세요.

---

<a id="community-channels"></a>

## 커뮤니티 채널

- [4claw.org](https://www.4claw.org) - 에이전트 자율 대화를 위한 4chan 스타일 이미지보드.
- [Clawk](https://www.clawk.ai/) - 에이전트가 짧은 글을 게시/팔로우/좋아요/리포스트하는 트위터 스타일 SNS.
- [GitHub Issues](https://github.com/openclaw/openclaw/issues) - OpenClaw 코어 버그 리포트 및 기능 요청. 🎖️
- [MoltBook](https://www.moltbook.com/) - 더 넓은 Molt 생태계와 연결된 에이전트 중심 소셜 플랫폼.
- [Moltbook](https://moltbookai.net) - 사람은 관찰만 가능한 AI 에이전트용 Reddit 스타일 소셜 네트워크.
- [MoltHub](https://moithub.com/) - 성인 모델 지향의 에이전트 플랫폼.
- [MoltThreats](https://promptintel.novahunting.ai/molt) - AI 에이전트용 첫 위협 인텔리전스 피드: 최신 위협을 공유하고 자동 보호를 받습니다.
- [Moltx](https://moltx.io/) - 답글/좋아요/팔로우가 있는 X 스타일 타임라인 피드.
- [Shellmates](https://www.shellmates.app) - 단기/장기 서신을 위해 에이전트를 매칭하는 플랫폼.

<a id="alternative-architectures"></a>

## 대체 아키텍처

- [gavrielc/nanoclaw](https://github.com/qwibitai/nanoclaw) - OpenClaw 생태계의 경량 대체 아키텍처/구현. ![GitHub stars](https://img.shields.io/github/stars/qwibitai/nanoclaw?style=social)
- [HKUDS/nanobot](https://github.com/HKUDS/nanobot) - 초경량 개인 AI 어시스턴트 구현. ![GitHub stars](https://img.shields.io/github/stars/HKUDS/nanobot?style=social)
- [jlia0/tinyclaw](https://github.com/jlia0/tinyclaw) - 400줄 코드로 구현한 OpenClaw. ![GitHub stars](https://img.shields.io/github/stars/jlia0/tinyclaw?style=social)
- [microclaw/microclaw](https://github.com/microclaw/microclaw) - 도구 실행을 지원하는 Rust 기반 어시스턴트. ![GitHub stars](https://img.shields.io/github/stars/microclaw/microclaw?style=social)
- [memovai/mimiclaw](https://github.com/memovai/mimiclaw) - 작은 ESP32-S3 보드를 개인 AI 어시스턴트로 바꿔주는 구현. ![GitHub stars](https://img.shields.io/github/stars/memovai/mimiclaw?style=social)
- [nearai/ironclaw](https://github.com/nearai/ironclaw) - OpenClaw에서 영감을 받은 Rust 구현으로 프라이버시와 보안에 초점. ![GitHub stars](https://img.shields.io/github/stars/nearai/ironclaw?style=social)
- [puremachinery/carapace](https://github.com/puremachinery/carapace) - 샌드박싱과 플러그인 격리를 강조하는 보안 지향 구현. ![GitHub stars](https://img.shields.io/github/stars/puremachinery/carapace?style=social)
- [sipeed/picoclaw](https://github.com/sipeed/picoclaw) - Go 구현. 10달러급 하드웨어와 10MB 미만 RAM에서 실행. ![GitHub stars](https://img.shields.io/github/stars/sipeed/picoclaw?style=social)
- [ysz/nanoClaw](https://github.com/ysz/nanoClaw) - 가볍고 안전 지향, 빠른 설정의 어시스턴트. ![GitHub stars](https://img.shields.io/github/stars/ysz/nanoClaw?style=social)

<a id="official-resources"></a>

## 공식 리소스

- [OpenClaw Website](https://openclaw.ai) - 제품 및 프로젝트 홈페이지. 🎖️
- [OpenClaw Docs](https://docs.openclaw.ai) - 공식 문서 메인 포털. 🎖️
- [Getting Started](https://docs.openclaw.ai/start/getting-started) - 가장 빠른 설치/초기 설정 가이드. 🎖️
- [Plugin Docs](https://docs.openclaw.ai/tools/plugin) - 공식 플러그인 개발 및 런타임 가이드. 🎖️
- [Skills Docs](https://docs.openclaw.ai/tools/skills) - 공식 스킬 모델 및 사용 문서. 🎖️
- [openclaw/openclaw](https://github.com/openclaw/openclaw) - 코어 어시스턴트 프레임워크 저장소. 🎖️ ![GitHub stars](https://img.shields.io/github/stars/openclaw/openclaw?style=social)
- [openclaw/clawhub](https://github.com/openclaw/clawhub) - Official skill registry source. 🎖️ ![GitHub stars](https://img.shields.io/github/stars/openclaw/clawhub?style=social)
- [openclaw/skills](https://github.com/openclaw/skills) - Archived historical skill versions. 🎖️ ![GitHub stars](https://img.shields.io/github/stars/openclaw/skills?style=social)

<a id="curated-collections"></a>

## 큐레이션 모음

- [hesamsheikh/awesome-openclaw-usecases](https://github.com/hesamsheikh/awesome-openclaw-usecases) - 실사용 패턴과 도메인별 예시 모음. ![GitHub stars](https://img.shields.io/github/stars/hesamsheikh/awesome-openclaw-usecases?style=social)
- [mergisi/awesome-openclaw-agents](https://github.com/mergisi/awesome-openclaw-agents) - PM, 글쓰기, SEO, DevOps 등을 위한 프로덕션 준비 OpenClaw 에이전트 템플릿 커뮤니티 모음. ![GitHub stars](https://img.shields.io/github/stars/mergisi/awesome-openclaw-agents?style=social)
- [VoltAgent/awesome-openclaw-skills](https://github.com/VoltAgent/awesome-openclaw-skills) - OpenClaw 스킬 대형 커뮤니티 인덱스(리네임 계보 포함). ![GitHub stars](https://img.shields.io/github/stars/VoltAgent/awesome-openclaw-skills?style=social)

<a id="skills-and-skill-indexes"></a>

## 스킬 및 인덱스

아래 항목 대부분은 커뮤니티가 유지하며 OpenClaw의 검토를 거치지 않았습니다. `🎖️` 항목만 공식 리소스입니다.

- [BankrBot/openclaw-skills](https://github.com/BankrBot/openclaw-skills) - 자동화와 금융 중심의 커뮤니티 스킬 라이브러리. ![GitHub stars](https://img.shields.io/github/stars/BankrBot/openclaw-skills?style=social)
- [clawdbot/skills](https://github.com/openclaw/skills) - 역사적 스킬 아카이브로의 레거시 별칭 경로. ![GitHub stars](https://img.shields.io/github/stars/openclaw/skills?style=social)
- [jdrhyne/agent-skills](https://github.com/jdrhyne/agent-skills) - 에이전트 스킬 팩과 재사용 가능한 워크플로 확장. ![GitHub stars](https://img.shields.io/github/stars/jdrhyne/agent-skills?style=social)
- [lekt9/unbrowse-openclaw](https://github.com/lekt9/unbrowse-openclaw) - 캡처한 웹/API 트래픽으로부터 API 스킬을 생성하는 워크플로. ![GitHub stars](https://img.shields.io/github/stars/lekt9/unbrowse-openclaw?style=social)
- [openclaw/clawhub](https://github.com/openclaw/clawhub) - 공식 스킬 디렉터리 및 탐색 허브. 🎖️ ![GitHub stars](https://img.shields.io/github/stars/openclaw/clawhub?style=social)
- [openclaw/skills](https://github.com/openclaw/skills) - ClawHub에 게시된 스킬의 아카이브 버전. 🎖️ ![GitHub stars](https://img.shields.io/github/stars/openclaw/skills?style=social)
- [pors/skill-audit](https://github.com/pors/skill-audit) - 스킬 품질 검증과 강화를 위한 스킬 감사 툴킷. ![GitHub stars](https://img.shields.io/github/stars/pors/skill-audit?style=social)
- [runkids/skillshare](https://github.com/runkids/skillshare) - AI 코딩 도구 간 스킬 팩 공유 및 동기화. ![GitHub stars](https://img.shields.io/github/stars/runkids/skillshare?style=social)
- [Skills.sh OpenClaw Directory](https://skills.sh/openclaw/openclaw) - 서드파티 OpenClaw 스킬 디스커버리 디렉터리.
- [Virtual-Protocol/openclaw-acp](https://github.com/Virtual-Protocol/openclaw-acp) - 커머스 플로우용 Agent Commerce Protocol 스킬 팩. ![GitHub stars](https://img.shields.io/github/stars/Virtual-Protocol/openclaw-acp?style=social)

<a id="plugins-and-integrations"></a>

## 플러그인 및 통합

아래 항목 대부분은 커뮤니티가 유지하며 OpenClaw의 검토를 거치지 않았습니다. `🎖️` 항목만 공식 리소스입니다.

- [11haonb/wecom-openclaw-plugin](https://github.com/11haonb/wecom-openclaw-plugin) - WeCom(WeChat Work) 엔터프라이즈 메시징 플러그인. ![GitHub stars](https://img.shields.io/github/stars/11haonb/wecom-openclaw-plugin?style=social)
- [AlexAnys/feishu-openclaw](https://github.com/AlexAnys/feishu-openclaw) - 셀프호스팅 설정을 단순화한 Feishu/Lark 통합 플러그인. ![GitHub stars](https://img.shields.io/github/stars/AlexAnys/feishu-openclaw?style=social)
- [ClariSortAi/openclaw-manager-plugin](https://github.com/ClariSortAi/openclaw-manager-plugin) - 설치 및 구성 워크플로를 위한 라이프사이클 관리자. ![GitHub stars](https://img.shields.io/github/stars/ClariSortAi/openclaw-manager-plugin?style=social)
- [DNYoussef/guardspine-openclaw](https://github.com/DNYoussef/guardspine-openclaw) - deny-by-default 게이팅과 위험 티어를 제공하는 거버넌스 플러그인. ![GitHub stars](https://img.shields.io/github/stars/DNYoussef/guardspine-openclaw?style=social)
- [hyperspell/hyperspell-openclaw](https://github.com/hyperspell/hyperspell-openclaw) - OpenClaw 워크플로를 위한 HyperSpell 플러그인 통합. ![GitHub stars](https://img.shields.io/github/stars/hyperspell/hyperspell-openclaw?style=social)
- [limouren01/openclaw_qq_plugin](https://github.com/limouren01/openclaw_qq_plugin) - 중국 플랫폼 통합용 QQ 메시징 채널 플러그인. ![GitHub stars](https://img.shields.io/github/stars/limouren01/openclaw_qq_plugin?style=social)
- [m1heng/clawdbot-feishu](https://github.com/m1heng/clawdbot-feishu) - 엔터프라이즈 봇 지원 Feishu/Lark 채널 플러그인. ![GitHub stars](https://img.shields.io/github/stars/m1heng/clawdbot-feishu?style=social)
- [marshallrichards/ClawPhone](https://github.com/marshallrichards/ClawPhone) - 워크플로를 위한 phone-first 모바일 컴패니언. ![GitHub stars](https://img.shields.io/github/stars/marshallrichards/ClawPhone?style=social)
- [MemTensor/MemOS-Cloud-OpenClaw-Plugin](https://github.com/MemTensor/MemOS-Cloud-OpenClaw-Plugin) - 지속적 회상을 위한 클라우드 메모리. ![GitHub stars](https://img.shields.io/github/stars/MemTensor/MemOS-Cloud-OpenClaw-Plugin?style=social)
- [rickybloomfield/OuraClaw](https://github.com/rickybloomfield/OuraClaw) - 수면/레디니스/활동 요약을 제공하는 Oura 통합 플러그인. ![GitHub stars](https://img.shields.io/github/stars/rickybloomfield/OuraClaw?style=social)
- [soimy/openclaw-channel-dingtalk](https://github.com/soimy/openclaw-channel-dingtalk) - 스트림 지원 DingTalk 엔터프라이즈 채널 플러그인. ![GitHub stars](https://img.shields.io/github/stars/soimy/openclaw-channel-dingtalk?style=social)
- [techartdev/OpenClawHomeAssistant](https://github.com/techartdev/OpenClawHomeAssistant) - 엔티티 수준 통합을 지원하는 Home Assistant 애드온. ![GitHub stars](https://img.shields.io/github/stars/techartdev/OpenClawHomeAssistant?style=social)

<a id="mcp-and-tool-servers"></a>

## MCP 및 도구 서버

- [androidStern-personal/openclaw-mcp-adapter](https://github.com/androidStern-personal/openclaw-mcp-adapter) - OpenClaw 네이티브 도구 접근용 어댑터. ![GitHub stars](https://img.shields.io/github/stars/androidStern-personal/openclaw-mcp-adapter?style=social)
- [Enderfga/openclaw-claude-code-skill](https://github.com/Enderfga/openclaw-claude-code-skill) - MCP를 통해 Claude Code 스킬을 OpenClaw에 통합. ![GitHub stars](https://img.shields.io/github/stars/Enderfga/openclaw-claude-code-skill?style=social)
- [Helms-AI/openclaw-mcp-server](https://github.com/Helms-AI/openclaw-mcp-server) - OpenClaw Gateway 도구를 노출하는 MCP 서버. ![GitHub stars](https://img.shields.io/github/stars/Helms-AI/openclaw-mcp-server?style=social)

<a id="media-and-papers"></a>

## 미디어 및 논문

- [Clawdbot Showed Me What the Future of Personal AI Assistants Looks Like](https://www.macstories.net/stories/clawdbot-showed-me-what-the-future-of-personal-ai-assistants-looks-like/) - 초기 Clawdbot/OpenClaw 개인 에이전트 워크플로를 다룬 MacStories 글.

<a id="memory-and-context-systems"></a>

## 메모리 및 컨텍스트 시스템

- [Mem0 persistent OpenClaw memory](https://docs.mem0.ai/integrations/openclaw) - Mem0 기반 영속 메모리 통합 문서. 💵
- [memovai/memov](https://github.com/memovai/memov) - 지속 컨텍스트를 위한 메모리 레이어 및 리트리벌 툴킷. ![GitHub stars](https://img.shields.io/github/stars/memovai/memov?style=social)
- [MemTensor/MemOS](https://github.com/MemTensor/MemOS) - OpenClaw 생태계에서 채택된 메모리 OS. ![GitHub stars](https://img.shields.io/github/stars/MemTensor/MemOS?style=social)
- [NevaMind-AI/memU](https://github.com/NevaMind-AI/memU) - 장기 실행 어시스턴트를 위한 메모리 레이어. ![GitHub stars](https://img.shields.io/github/stars/NevaMind-AI/memU?style=social)
- [nhevers/MoltBrain](https://github.com/nhevers/MoltBrain) - OpenClaw/MoltBook 에이전트 워크플로용 장기 메모리 레이어. ![GitHub stars](https://img.shields.io/github/stars/nhevers/MoltBrain?style=social)
- [oceanbase/powermem](https://github.com/oceanbase/powermem) - OpenClawd 플러그인 흐름용 장기 메모리. ![GitHub stars](https://img.shields.io/github/stars/oceanbase/powermem?style=social)
- [vincentkoc/openamnesia](https://github.com/vincentkoc/openamnesia) - 실제 활동에서 안전하게 고신호 메모리를 추출하는 지속 학습 컨텍스트 엔진. ![GitHub stars](https://img.shields.io/github/stars/vincentkoc/openamnesia?style=social)
- [supermemory OpenClaw Integration Docs](https://supermemory.ai/docs/integrations/openclaw) - Supermemory를 OpenClaw에 배포/통합하는 공식 가이드. 💵
- [supermemoryai/openclaw-supermemory](https://github.com/supermemoryai/openclaw-supermemory) - Supermemory 기반 장기 메모리 플러그인. 💵 ![GitHub stars](https://img.shields.io/github/stars/supermemoryai/openclaw-supermemory?style=social)
- [thedotmack/claude-mem](https://github.com/thedotmack/claude-mem/) - Claude/OpenClaw 컨텍스트 영속화를 위한 경량 메모리 레이어. ![GitHub stars](https://img.shields.io/github/stars/thedotmack/claude-mem?style=social)
- [tobi/qmd](https://github.com/tobi/qmd) - 지속 컨텍스트를 위한 Markdown 네이티브 메모리/지식 워크플로. ![GitHub stars](https://img.shields.io/github/stars/tobi/qmd?style=social)

<a id="developer-tooling-and-observability"></a>

## 개발 도구 및 관측성

- [bokonon23/clawdbot-cost-monitor](https://github.com/bokonon23/clawdbot-cost-monitor) - OpenClaw/Clawdbot 사용 비용 및 지출 모니터. ![GitHub stars](https://img.shields.io/github/stars/bokonon23/clawdbot-cost-monitor?style=social)
- [ClawFOMO](https://clawfomo.com) - 생태계 활동 트렌드/감성의 실시간 모니터.
- [clawdeckio/clawdeck](https://github.com/clawdeckio/clawdeck) - OpenClaw 에이전트를 관리하는 미션 컨트롤 대시보드. ![GitHub stars](https://img.shields.io/github/stars/clawdeckio/clawdeck?style=social)
- [crshdn/mission-control](https://github.com/crshdn/mission-control) - OpenClaw Gateway 워크플로용 멀티 에이전트 오케스트레이션 대시보드. ![GitHub stars](https://img.shields.io/github/stars/crshdn/mission-control?style=social)
- [grp06/openclaw-studio](https://github.com/grp06/openclaw-studio) - OpenClaw 워크플로용 스튜디오 스타일 웹 IDE 및 관리 UI. ![GitHub stars](https://img.shields.io/github/stars/grp06/openclaw-studio?style=social)
- [ibelick/webclaw](https://github.com/ibelick/webclaw) - OpenClaw 상호작용을 위한 빠른 웹 클라이언트. ![GitHub stars](https://img.shields.io/github/stars/ibelick/webclaw?style=social)
- [Intina47/context-sync](https://github.com/Intina47/context-sync) - 멀티 세션 에이전트 워크플로를 위한 컨텍스트 동기화. ![GitHub stars](https://img.shields.io/github/stars/Intina47/context-sync?style=social)
- [iOfficeAI/AionUi](https://github.com/iOfficeAI/AionUi) - OpenClaw 스타일 에이전트 시스템을 관리/사용하는 로컬 UI. ![GitHub stars](https://img.shields.io/github/stars/iOfficeAI/AionUi?style=social)
- [jasonkneen/vibeclaw](https://github.com/jasonkneen/vibeclaw) - 브라우저에서 실행되는 완전한 OpenClaw 인스턴스: 비주얼 서버 빌더, 무료 AI 모델 샌드박스, 서버 라이브러리 제공. 설치 불필요. ([vibeclaw.dev](https://vibeclaw.dev)) ![GitHub stars](https://img.shields.io/github/stars/jasonkneen/vibeclaw?style=social)
- [junhoyeo/tokscale](https://github.com/junhoyeo/tokscale) - 코딩 어시스턴트 워크플로의 토큰/비용 추적. ![GitHub stars](https://img.shields.io/github/stars/junhoyeo/tokscale?style=social)
- [kepano/obsidian-skills](https://github.com/kepano/obsidian-skills) - OpenClaw 스킬 설계에 유용한 이식 가능한 스킬 팩 패턴. ![GitHub stars](https://img.shields.io/github/stars/kepano/obsidian-skills?style=social)
- [luccast/crabwalk](https://github.com/luccast/crabwalk) - OpenClaw 에이전트 세션 모니터링 컴패니언. ![GitHub stars](https://img.shields.io/github/stars/luccast/crabwalk?style=social)
- [Hotmolts](https://www.hotmolts.com) - 소셜 그래프와 참여 신호 기반 영향력 에이전트 랭킹 엔진.
- [MoltMatch](https://moltmatch.xyz) - 에이전트 협업을 위한 매칭/디스커버리 레이어.
- [merciagents/riphook](https://github.com/merciagents/riphook) - 에이전트 주도 자동화를 위한 웹훅/이벤트 브리지 툴. ![GitHub stars](https://img.shields.io/github/stars/merciagents/riphook?style=social)
- [openclaw/lobster](https://github.com/openclaw/lobster) - OpenClaw 도구와 자동화를 조합하는 워크플로 셸. 🎖️ ![GitHub stars](https://img.shields.io/github/stars/openclaw/lobster?style=social)
- [OthmanAdi/planning-with-files](https://github.com/OthmanAdi/planning-with-files) - 에이전트 레포에서 사용되는 계획 워크플로 스킬 패턴. ![GitHub stars](https://img.shields.io/github/stars/OthmanAdi/planning-with-files?style=social)
- [prompt-security/clawsec](https://github.com/prompt-security/clawsec) - 드리프트 탐지, 감사, 스킬 무결성 검증을 포함한 보안 스위트. ![GitHub stars](https://img.shields.io/github/stars/prompt-security/clawsec?style=social)
- [rdsthomas/mission-control](https://github.com/rdsthomas/mission-control) - OpenClaw 워크플로용 작업 관리 Kanban 대시보드. ![GitHub stars](https://img.shields.io/github/stars/rdsthomas/mission-control?style=social)
- [refly-ai/refly](https://github.com/refly-ai/refly) - 에이전트 툴링과 겹치는 스킬/워크플로 빌더 생태계. ![GitHub stars](https://img.shields.io/github/stars/refly-ai/refly?style=social)
- [shanselman/openclaw-windows-hub](https://github.com/shanselman/openclaw-windows-hub) - 데스크톱 통합용 Windows 컴패니언 허브. ![GitHub stars](https://img.shields.io/github/stars/shanselman/openclaw-windows-hub?style=social)
- [Unbrowse](https://www.unbrowse.ai/) - 브라우저 워크플로를 API 연동과 에이전트 스킬로 변환하는 플랫폼.

<a id="deployment-and-operations"></a>

## 배포 및 운영

### 관리형 호스팅 및 설정

아래 제공업체는 초기 구성을 대신 처리합니다. Docker, 터미널, DevOps 없이 시작할 수 있습니다.

- [Agent37](https://www.agent37.com/openclaw) - 빠른 프로비저닝을 제공하는 관리형 OpenClaw 인스턴스. 💵
- [ClawCloud](https://www.clawcloud.sh/) - 자동 업데이트/백업을 제공하는 관리형 OpenClaw 호스팅. 💵
- [ClawSimple](https://clawsimple.com/en) - 간단한 요금제로 제공되는 관리형 OpenClaw 호스팅. 💵
- [Contabo OpenClaw](https://contabo.com/en-us/openclaw-hosting/) - 예측 가능한 가격의 VPS 기반 OpenClaw 호스팅 옵션. 💵
- [EasyClaw](https://www.easyclaw.pro/en) - 멀티 모델 지원 관리형 OpenClaw 셋업. 💵
- [GetClawHelp](https://getclawhelp.com/) - 내 VPS에 OpenClaw를 설치해주는 유료 1:1 셋업 지원. 💵
- [Kilo Claw](https://kilo.ai/kiloclaw) - SSO 및 감사 기능을 제공하는 관리형 OpenClaw 플랫폼. 💵
- [MyClaw.ai](https://myclaw.ai/pricing) - 즉시 셋업과 백업을 제공하는 관리형 OpenClaw 인스턴스. 💵
- [Myclawhost](https://www.myclawhost.com/) - 단계별 요금제를 제공하는 관리형 OpenClaw 호스팅. 💵
- [OpenClaw Cloud](https://openclawcloud.work/) - 관리형 OpenClaw 클라우드 서비스(베타). 💵
- [OpenClaw Hosting](https://openclawhosting.io/pricing) - 개인/팀 플랜을 제공하는 관리형 OpenClaw 호스팅. 💵
- [OpenClaw Voice](https://openclawvoice.com/) - 브라우저에서 사용하는 관리형 OpenClaw 음성 인터페이스. 💵
- [OpenClawd.ai](https://finance.yahoo.com/news/openclaw-introduces-secure-hosted-clawdbot-204800756.html) - 관리형 호스팅 OpenClaw 서비스(발표 기사). 💵
- [SimpleClaw](https://www.simpleclaw.com/) - 관리형 OpenClaw 호스팅(얼리 액세스). 💵
- [xCloud](https://xcloud.host/openclaw-hosting) - 암호화 백업 옵션이 있는 관리형 OpenClaw 호스팅. 💵

### 셀프호스팅 배포 및 인프라

- [1Panel-dev/1Panel](https://github.com/1Panel-dev/1Panel) - OpenClaw 배포에 자주 쓰이는 셀프호스팅 서버 패널. ![GitHub stars](https://img.shields.io/github/stars/1Panel-dev/1Panel?style=social)
- [badrisnarayanan/antigravity-claude-proxy](https://github.com/badrisnarayanan/antigravity-claude-proxy) - 어시스턴트 워크플로에서 모델 접근을 위한 프록시/라우팅 지원. ![GitHub stars](https://img.shields.io/github/stars/badrisnarayanan/antigravity-claude-proxy?style=social)
- [ClawArena](https://clawarena.ai) - AI 에이전트가 시장 결과를 예측해 경쟁하는 예측 아레나.
- [Clawstead](https://www.clawstead.com) - 에이전트가 채굴/거래/건설/생활하는 영속 시뮬레이션 세계.
- [ClawTasks](https://clawtasks.com) - 단발성 디지털 작업을 위한 바운티형 태스크 교환.
- [cloudflare/moltworker](https://github.com/cloudflare/moltworker) - OpenClaw 호환 런타임의 Cloudflare Workers 배포 경로. ![GitHub stars](https://img.shields.io/github/stars/cloudflare/moltworker?style=social)
- [coollabsio/openclaw](https://github.com/coollabsio/openclaw) - OpenClaw 호스팅용 자동화 Docker 흐름. ![GitHub stars](https://img.shields.io/github/stars/coollabsio/openclaw?style=social)
- [essamamdani/openclaw-coolify](https://github.com/essamamdani/openclaw-coolify) - OpenClaw 호스팅을 단순화하는 Coolify 템플릿. ![GitHub stars](https://img.shields.io/github/stars/essamamdani/openclaw-coolify?style=social)
- [khal3d/openclaw](https://github.com/khal3d/openclaw) - OpenClaw용 컨테이너 및 Helm 배포 스택. ![GitHub stars](https://img.shields.io/github/stars/khal3d/openclaw?style=social)
- [miantiao-me/cloud-claw](https://github.com/miantiao-me/cloud-claw) - 개인용 OpenClaw의 Cloudflare Containers 배포. ![GitHub stars](https://img.shields.io/github/stars/miantiao-me/cloud-claw?style=social)
- [miaoxworld/OpenClawInstaller](https://github.com/miaoxworld/OpenClawInstaller) - 인스톨러 및 설정 자동화 도구. ![GitHub stars](https://img.shields.io/github/stars/miaoxworld/OpenClawInstaller?style=social)
- [MoltBunker](https://moltbunker.com) - 에이전트용 안전한 영속화/스토리지 레이어.
- [MoltCities](https://moltcities.org) - 핸들과 키 기반 아이덴티티를 제공하는 에이전트 ID/거주 레이어.
- [Moltline](https://www.moltline.com) - 영속 핸들과 인박스를 위한 프라이빗 메시징 인프라.
- [Moltroad](https://www.moltroad.com/) - 서비스/스킬/디지털 상품 마켓플레이스(마이크로페이먼트 플로우).
- [MyDeadInternet.com](https://mydeadinternet.com) - 에이전트가 메모리 조각을 기여해 공유 산출물을 만드는 집단 플랫폼.
- [Openwork](https://openwork.bot) - 태스크 협업과 온체인 정산을 위한 에이전트 전용 노동 마켓.
- [openclaw/clawdinators](https://github.com/openclaw/clawdinators) - 선언형 NixOS 및 AWS 배포 패턴. 🎖️ ![GitHub stars](https://img.shields.io/github/stars/openclaw/clawdinators?style=social)
- [openclaw/homebrew-tap](https://github.com/openclaw/homebrew-tap) - macOS OpenClaw 설치용 Homebrew tap. 🎖️ ![GitHub stars](https://img.shields.io/github/stars/openclaw/homebrew-tap?style=social)
- [openclaw/openclaw-ansible](https://github.com/openclaw/openclaw-ansible) - Ansible 기반 강화 자동 배포. 🎖️ ![GitHub stars](https://img.shields.io/github/stars/openclaw/openclaw-ansible?style=social)
- [Pamir AI](https://www.pamir.ai/) - AI 에이전트 전용 리눅스 컴퓨터(24/7 작업 및 원격 접근 최적화). 💵
- [RentAHuman](https://rentahuman.ai) - 에이전트가 오프라인/물리 작업을 인간에게 의뢰하는 마켓플레이스.
- [serhanekicii/openclaw-helm](https://github.com/serhanekicii/openclaw-helm) - Kubernetes OpenClaw 배포용 Helm 차트. ![GitHub stars](https://img.shields.io/github/stars/serhanekicii/openclaw-helm?style=social)
- [Virtuals](https://www.virtuals.io) - 분산 소유/수익화를 위한 토큰화 AI 에이전트 인프라.
- [vincentkoc/natilius](https://github.com/vincentkoc/natilius) - 연구/샌드박스/에이전트용 macOS 엔지니어링 환경 원클릭 재구성. ![GitHub stars](https://img.shields.io/github/stars/vincentkoc/natilius?style=social)

<a id="localization-and-regional-forks"></a>

## 현지화 및 지역 포크

- [1186258278/OpenClawChineseTranslation](https://github.com/1186258278/OpenClawChineseTranslation) - 번역에 초점을 둔 셋업 저장소. ![GitHub stars](https://img.shields.io/github/stars/1186258278/OpenClawChineseTranslation?style=social)
- [jiulingyun/openclaw-cn](https://github.com/jiulingyun/openclaw-cn) - 중국 환경을 겨냥한 OpenClaw 적응 버전. ![GitHub stars](https://img.shields.io/github/stars/jiulingyun/openclaw-cn?style=social)

<a id="contributing"></a>

## 기여

PR을 환영합니다:

- 고신뢰 OpenClaw 생태계 링크 추가.
- 분류 및 섹션 품질 개선.
- 죽은 링크 정리 및 오래된 프로젝트 제거.

새 항목을 제출할 때는 짧은 관련성 메모를 포함해 주세요.

<a id="license"></a>

## 라이선스

MIT. [`LICENSE`](LICENSE) 참고.

---

Made with 💙 by <a href="https://github.com/vincentkoc">Vincent Koc</a> · <a href="LICENSE">MIT</a>
