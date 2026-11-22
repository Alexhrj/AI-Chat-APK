# 实测指南 | Testing Guide

[测试入口 / Testing index](README.md) · [应用目录 / App directory](../Apps/README.md) · [模板 / Template](../Templates/APP_TEMPLATE.md)

## 1. 记录单位 | Record Unit

独立应用档案是逐项观察的主要记录位置。每条观察使用稳定 ID，例如 miraimind-001；只在有实际记录时分配，不用测试日期生成假时间。总览和专题引用档案及记录 ID。
Individual profiles are the primary location for observations. Use stable IDs such as miraimind-001, allocated only to actual records without inventing dates. Overviews and topics reference the profile and record ID.

现有档案可渐进补 ID，不得为满足新模板而删除旧观察。原始观察与整理结果分开；翻译不得扩大结论。
Existing profiles may gain IDs incrementally; never delete observations to fit the new template. Separate original observations from normalized results; translations must not expand claims.

## 2. 来源 | Sources

| 标签 / Label | 含义 / Meaning |
|---|---|
| User Test | 维护者或明确署名测试者实际操作后的报告 / Report following actual use by the maintainer or an identified tester |
| Official | 开发者控制的页面或文档 / Developer-controlled pages or documents |
| Third-party | 独立第三方资料 / Independent third-party material |

“—”表示无可引用来源，不是新来源类别。第三方文章不能仅因描述测试就自动标为维护者 User Test；注明实际报告者及链接。
“—” means no attributable source, not a new source category. A third-party article is not automatically a maintainer User Test because it describes testing; identify the actual reporter and URL.

## 3. 核实状态 | Verification Status

| 状态 / Status | 使用条件 / Use |
|---|---|
| Tested | 该项存在实际操作观察，仅适用于记录场景 / An actual-use observation exists for the item, limited to its recorded scenario |
| Partially Tested | 仅覆盖该项部分子场景，或用于概括应用测试覆盖有限 / Only some sub-scenarios are tested, or overall application coverage is limited |
| Not Tested | 明确尚未进行该项实测 / The item is explicitly not hands-on tested |
| Needs Verification | 已有线索，但身份、依据或结论仍需核实 / A lead exists but identity, evidence, or conclusion requires verification |
| Unknown | 信息或测试情况不足，无法确定 / Information or testing circumstances are insufficient to determine |

Tested 不表示 AI 助手重新安装复测，也不保证截图齐全或环境可复现。分别标记报告者、缺失环境和证据位置。官方页面即使已阅读，也不能据此把应用行为标为 Tested；页面核查另记日期和范围。
Tested does not mean the AI assistant reinstalled and retested the app, nor guarantee complete screenshots or reproducibility. Identify the reporter, missing environment, and evidence location separately. Reading an official page does not make application behavior Tested; record page-check date and scope separately.

维护状态（如停止维护）与上述状态分开；没有消息不能推出停止维护。
Maintenance status, such as discontinued, is separate; lack of news does not establish discontinuation.

## 4. 测试流程 | Procedure

1. 核实应用身份、开发者、包名和官方渠道，未确认项保留未知。
   Identify the app, developer, package ID, and official channels; leave unconfirmed fields unknown.
2. 记录测试日期、应用及 Android 版本、地区、账号套餐和开关设置，不记录密码或令牌。
   Record test date, app and Android versions, region, account plan, and toggles, never passwords or tokens.
3. 预先说明测试场景和观察范围；比较设置时尽量只改变一个条件。
   Define the scenario and observation scope; change one condition at a time when comparing settings where feasible.
4. 保存原始观察、样本数、结果、来源及局限。可用非露骨摘要，不需要公开成人聊天全文。
   Preserve original observations, sample size, results, sources, and limitations. Non-graphic summaries suffice; full adult chats need not be public.
5. 用相同场景复查差异；无法复现或与官方冲突时并列保留，不覆盖历史。
   Recheck differences with the same scenario; preserve non-reproducible or conflicting records alongside history.

## 5. 独立测试维度 | Independent Dimensions

| 维度 / Dimension | 要求 / Requirement |
|---|---|
| 私人生成 / Private generation | 记录实际输出情况，不能从显示开关推断 / Observe output; do not infer from display toggles |
| 显示开关 / Display toggle | 区分存在、取值、默认值与影响；分别核实 / Verify existence, tested value, default, and effect separately |
| 警告和过滤 / Warning and filtering | 有警告不等于阻止，也不等于无过滤 / A warning implies neither blocking nor absence of filtering |
| 公开内容 / Public content | 记录浏览区域和样本；未见描写不证明过滤机制 / Record area and samples; absence does not establish filtering |
| 标签与搜索 / Tags and search | 保留标签原文、语境、查询及结果，不只凭词判断成人含义 / Preserve labels, context, queries, and results; do not infer adult meaning from words alone |
| 账号、版本、地区 / Account, version, region | 只有对照记录才能支持差异结论 / Comparative records are needed for claims of differences |
| 聊天与记忆 / Chat and memory | 分开记录响应、连贯性、角色一致性、短期上下文与跨会话记忆 / Separate response, coherence, persona consistency, short-term context, and cross-session memory |
| 模型和功能 / Models and features | 区分官方宣称、界面选项和实测效果 / Separate official claims, UI options, and tested effects |
| 收费 / Pricing | 记录地区、币种、套餐、额度、税费说明及页面日期；不未经授权购买 / Record region, currency, plan, limits, tax details, and page date; no unauthorized purchases |
| 隐私安全 / Privacy and security | 区分政策声明、权限观察与技术验证；不能凭政策证明加密 / Separate policy claims, permission observations, and technical verification; policy alone does not prove encryption |

## 6. 日期、证据与安全 | Dates, Evidence, and Safety

测试日期、官方页面核查日期和整理日期分别记录；不知道就写 Unknown。迁移旧记录不构成新测试。
Record test date, official-page check date, and documentation date separately; use Unknown when missing. Migrating a record is not a new test.

截图与引用应去除账号标识、私人对话、支付资料和认证信息。不公开涉及未成年人的性化内容，不提供绕过年龄核验或安全限制的教程。测试须遵守法律、年龄要求和服务条款。
Redact account identifiers, private conversations, payment information, and credentials from evidence. Do not publish sexualized content involving minors or instructions to bypass age checks or safety restrictions. Follow laws, age requirements, and service terms.

## 7. 提交检查 | Submission Checks

检查 Markdown 表格、相对链接、中英一致性、来源与状态、未知字段、历史保留、总览与档案一致性。没有实际运行的检查不得报告通过。
Check Markdown tables, relative links, bilingual consistency, sources and statuses, unknown fields, historical preservation, and overview/profile consistency. Never report an unrun check as passed.
