# AI-Chat-APK

面向 Android AI 聊天应用的中英双语索引与详细实测数据库。

A bilingual directory and detailed hands-on testing database for Android AI chat applications.

## 项目简介 | About

收录通用 AI 助手、AI 伴侣、角色扮演、角色聊天及本地模型客户端等应用，不限于 NSFW 应用。NSFW 是独立测试维度，不代表项目的全部收录范围。

The project covers general AI assistants, AI companions, roleplay, character chat, local-model clients, and more—not only NSFW applications. NSFW behavior is one testing dimension, not the scope of the entire project.

本仓库只提供应用资料与外部链接，不托管或重新分发 APK 文件。

This repository provides application information and external links only. It does not host or redistribute APK files.

## 项目导航 | Navigation

| 文档 / Document | 用途 / Purpose |
|---|---|
| [应用总目录 / App directory](Apps/README.md) | 快速浏览应用 / Browse applications |
| [应用分类 / Categories](Categories/README.md) | 按主要用途分类 / Explore primary use cases |
| [实测数据库 / Testing database](Testing/README.md) | 测试规范及记录入口 / Testing guidance and records |
| [应用档案模板 / App template](Templates/APP_TEMPLATE.md) | 编写详细应用资料 / Document individual applications |
| [维护指引 / Agent instructions](AGENTS.md) | 项目规则与维护上下文 / Project rules and maintenance context |

## 应用分类 | Application Categories

应用可以属于多个类别。成人内容相关表现应另外逐项记录，不使用单一类别代替测试结果。

Applications may belong to multiple categories. Adult-content behavior is recorded separately by dimension; a category does not substitute for test results.

| 分类 / Category | 说明 / Description |
|---|---|
| AI 伴侣 / AI Companion | 虚拟伙伴与陪伴型聊天 / Virtual companions and conversational partners |
| 角色扮演 / Roleplay | 情景互动与故事体验 / Scenario-based interaction and storytelling |
| 角色聊天 / Character Chat | 自定义角色与角色卡 / Custom characters and personas |
| 本地 AI / Local AI | 本地模型与离线推理 / Local models and offline inference |
| 通用助手 / AI Assistant | 问答、写作及生产力 / Questions, writing, and productivity |
| 成人内容相关 / Adult-content-related | 记录相关功能、设置与限制，不作为整体支持结论 / Record relevant features, settings, and restrictions without an overall support verdict |

## 收录进度 | Documentation Progress

维护者已提供以下三款应用的用户实测观察，现有记录保存在 [AGENTS.md](AGENTS.md)。独立应用档案与总览迁移尚待完成；此表不表示应用已完成全面核实。

The maintainer has supplied user-test observations for the following three applications, currently preserved in [AGENTS.md](AGENTS.md). Individual profiles and directory integration remain pending. This table does not imply comprehensive verification.

| 应用 / App | 信息来源 / Source | 当前资料范围 / Available evidence |
|---|---|---|
| MiraiMind | User Test | 生成、公开内容及标签的部分观察 / Selected observations of generation, public content, and tags |
| Hi Waifu | User Test | NSFW 显示设置、公开内容及标签的部分观察 / Selected observations of NSFW display settings, public content, and tags |
| Sakura | User Test | 成人内容提示、生成、公开内容及标签的部分观察 / Selected observations of adult-content warnings, generation, public content, and tags |

未核实的开发者、官方网站及下载地址不得猜测填写。详细目录见 [Apps](Apps/README.md)。

Do not guess unverified developers, official websites, or download URLs. See [Apps](Apps/README.md) for the directory.

## 内容测试维度 | Content Testing Dimensions

不再用 Supported、Limited 或 Not Supported 等单一标签概括整个应用。以下项目分别记录，未测试或缺少依据时明确标记。

Do not summarize an entire application with a single Supported, Limited, or Not Supported label. Record each dimension separately and identify missing evidence or untested behavior.

| 测试项目 / Dimension | 记录内容 / What to record |
|---|---|
| 私人对话生成 / Private generation | 测试中是否生成成人内容 / Whether adult content was generated in the tested conversations |
| NSFW 显示设置 / NSFW display setting | 开关是否存在及测试时的设置 / Whether a toggle exists and its tested setting |
| 警告与确认 / Warnings and confirmation | 是否出现提示，是否仍可继续 / Whether prompts appear and continuation is possible |
| 生成过滤 / Generation filtering | 观察到的拒绝、过滤或限制 / Observed refusals, filtering, or restrictions |
| 公开内容 / Public content | 样本展示情况；与过滤机制是否已证实分开 / Observed public samples, separately from whether filtering mechanisms are established |
| 标签 / Tags | 标签原文、语境及是否涉及成人内容 / Exact labels, context, and adult-content relevance |
| 标签搜索 / Tag search | 搜索条件与可找到的结果 / Search conditions and discoverable results |
| 账号设置差异 / Account-setting differences | 不同设置或账号的实测差异 / Tested differences between settings or accounts |
| 版本与地区差异 / Version and regional differences | 已知环境及实测差异 / Known environments and tested differences |

“未观察到”不等于“不存在”；未见公开成人描写也不能单独证明平台实施过滤。用户实测不是官方声明，也不代表所有版本、地区或账号。

“Not observed” does not mean “does not exist.” An absence of adult descriptions in public samples does not by itself establish platform filtering. User tests are not official statements and do not represent every version, region, or account.

## 来源与核实状态 | Sources and Verification

来源和核实状态是两个独立字段，应尽量落实到具体观察或结论，而非对整个应用作统一背书。

Source and verification status are independent fields. Assign them to individual observations or claims where possible, rather than endorsing an entire application.

| 字段 / Field | 可用值 / Values |
|---|---|
| 信息来源 / Source | User Test（用户实测）, Official（官方资料）, Third-party（第三方资料） |
| 核实状态 / Verification status | Tested（已实测）, Partially Tested（部分实测）, Not Tested（未实测）, Needs Verification（待核实）, Unknown（未知） |

官方资料不等于已经实测；用户实测也不自动确认全部功能。缺少测试日期、版本、地区或账号设置时应标记未知，不用文档更新日期替代测试日期。详细状态定义将在测试规范中统一维护。

Official documentation is not equivalent to hands-on testing, and a user test does not verify every feature. Mark missing test dates, versions, regions, and account settings as unknown; do not substitute a documentation update date for a test date. Detailed status definitions will be maintained in the testing guidance.

## 下载与安全 | Download and Security

- 优先使用开发者官方网站或官方应用商店；未知来源的修改版不得标为官方版本。
  Prefer developer websites or official app stores; do not label unknown modified builds as official.
- 安装前检查权限、开发者信息及签名；有可靠参考值时核对 SHA-256。
  Review permissions, developer information, and signing certificates; compare SHA-256 checksums when a trustworthy reference is available.
- 通过 Issue 报告失效、可疑或冒充官方的链接。
  Report broken, suspicious, or falsely official links through Issues.

## 参与贡献 | Contributing

欢迎应用推荐、资料修正和实测补充。请使用[应用模板](Templates/APP_TEMPLATE.md)，并尽量提供应用名称、开发者、官方来源、逐项观察、信息来源、核实状态及测试环境。未知字段保留为未知，不填写推测内容。

Application recommendations, corrections, and test contributions are welcome. Use the [application template](Templates/APP_TEMPLATE.md) and provide the application name, developer, official sources, individual observations, source types, verification statuses, and test environment where available. Leave unknown fields unknown rather than guessing.

## 免责声明 | Disclaimer

本项目是独立社区资料库，不隶属于所收录应用的开发者。商标及应用权利归各权利人所有。收录不代表推荐、安全保证或对内容的背书。

This is an independent community database, not affiliated with listed developers. Trademarks and application rights belong to their respective owners. Inclusion is not an endorsement, security guarantee, or approval of content.

成人内容仅适用于成年人；禁止涉及未成年人的性剥削或性化内容。使用者须遵守适用法律及第三方服务条款。

Adult content is for adults only. Sexual exploitation or sexualization of minors is prohibited. Users must comply with applicable laws and third-party terms of service.
