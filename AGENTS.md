AGENTS.md

AI-Chat-APK — Project Memory & Instructions

«This file provides persistent project context and operating instructions for OpenAI Codex and other AI coding agents.

本文件用于保存项目背景、历史决策、数据规范和后续工作要求，避免更换 AI 会话后丢失项目连续性。»

---

1. Project Identity | 项目基本信息

- Repository: "Alexhrj/AI-Chat-APK"
- Repository URL: https://github.com/Alexhrj/AI-Chat-APK
- Project name: AI-Chat-APK
- Visibility: Public
- Collection method: Links only
- Collection scope: All Android AI chat applications
- Documentation languages: Chinese + English
- Primary format: Markdown
- Main purpose: Independent Android AI chat application directory and testing database.

Project Description

中文：

这是一个用于收集、整理、比较 Android AI 聊天应用的独立开源目录项目。

重点收录：

- AI Companion
- AI Roleplay
- Character Chat
- AI Girlfriend / Boyfriend
- AI Assistant
- Local AI
- Applications with NSFW-related features

项目特别关注不同应用的 NSFW 能力、私人聊天生成、公开内容展示、标签系统及实际使用体验。

English:

An independent directory and testing database for Android AI chat applications.

The project covers AI companions, roleplay applications, character chat, AI assistants, local AI, and applications with NSFW-related features.

Special attention is given to NSFW capabilities, private generation, public content, tag systems, and real-world user experience.

---

2. Important Project Decisions | 已确定的项目规则

These decisions have already been established. Do not change them without the maintainer's approval.

1. The repository is public.
2. Applications are collected through links, not by hosting APK files.
3. The collection scope is ALL Android AI chat applications, not only NSFW applications.
4. Documentation must support both Chinese and English.
5. Testing uses BOTH overview tables and detailed individual application profiles.
6. Testing scope is DETAILED.
7. User-provided test results must be preserved.
8. Official information and hands-on observations must be distinguished.
9. Do not invent features, download links, prices, policies, or test results.
10. Do not delete historical records without explicit authorization.

---

3. Repository Structure | 当前文件结构

Last known repository structure:

AI-Chat-APK/
│
├── README.md
│
├── Apps/
│   └── README.md
│
├── Categories/
│   └── README.md
│
├── Templates/
│   └── APP_TEMPLATE.md
│
└── Testing/
    └── README.md

Important:

This is the last known structure from the previous project review. Always inspect the actual GitHub repository before making changes.

Do not assume that planned files already exist.

Planned Structure

AI-Chat-APK/
│
├── AGENTS.md
├── README.md
│
├── Apps/
│   ├── README.md
│   ├── MiraiMind/
│   ├── Hi-Waifu/
│   └── Sakura/
│
├── Categories/
│   └── README.md
│
├── Templates/
│   └── APP_TEMPLATE.md
│
└── Testing/
    ├── README.md
    ├── TESTING_GUIDE.md
    ├── TEST_OVERVIEW.md
    ├── NSFW_TESTS.md
    ├── CHAT_EXPERIENCE.md
    ├── FEATURES.md
    ├── PRICING.md
    ├── PRIVACY_SECURITY.md
    ├── PUBLIC_CONTENT.md
    └── TAG_DATABASE.md

This is a proposed structure, not a statement that these files already exist.

---

4. Application Testing Records | 已有应用实测资料

The following information was supplied by the project maintainer through actual application testing.

These records are important original project data.

Do not silently rewrite, remove, or reinterpret them.

4.1 MiraiMind

Name requires verification: the maintainer initially entered "MiraiMrid"; subsequent project discussions used "MiraiMind".

Observed results:

- Publicly displayed content includes partial sexual implications.
- Some sexual anatomical descriptions were observed.
- Private generation can produce NSFW content.
- Observed tag examples include:
  - 调教
  - 触手
  - 抖M

Testing summary:

Test Item| Result
Private NSFW generation| Supported in maintainer's test
Public sexual implications| Observed
Public anatomical descriptions| Partially observed
NSFW-related tags| Observed
Overall verification| Needs detailed documentation

Do not assume that all public content contains explicit descriptions.

4.2 Hi Waifu

Observed results:

- Account settings provide an option to enable NSFW content display.
- Public content does not display NSFW descriptions in the maintainer's observation.
- No NSFW-specific tags were observed in the tested public tag samples.
- Observed ordinary tags include:
  - RPG
  - 名人
  - VTuber

Testing summary:

Test Item| Result
NSFW setting| Available
Manual setting required| Yes, according to observation
Public NSFW descriptions| Not observed
NSFW-specific tags| None observed in tested samples
Ordinary tags| RPG, 名人, VTuber

Important: Do not interpret the absence of observed NSFW tags as proof that no such tags exist anywhere in the application.

4.3 Sakura

Observed results:

- When adult content appears in conversations, the application displays a warning or notification.
- Conversations can continue after the warning, according to the maintainer's test.
- NSFW content generation is possible.
- Public content does not display NSFW descriptions in the maintainer's observation.
- Observed tags include:
  - gay
  - male
  - OC

Testing summary:

Test Item| Result
NSFW generation| Supported in maintainer's test
Adult-content warning| Observed
Continue after warning| Possible in tested scenario
Public NSFW descriptions| Not observed
Observed tags| gay, male, OC

Important: These are observations from tested scenarios, not guarantees about every conversation or account.

---

5. Testing Database Design | 实测数据库设计

The database uses two complementary formats.

A. Test Overview

A standardized comparison table for all applications.

Each application should have separate fields for:

- Basic information
- Android availability
- Private NSFW generation
- NSFW settings
- Content warnings
- Public content
- NSFW tags
- Chat experience
- Memory
- Pricing
- Privacy and security
- Verification status

B. Detailed Application Profiles

Every application should have an individual profile.

Recommended fields:

1. Basic Information
2. Application Description
3. Features
4. NSFW Test Results
5. Chat Experience
6. Tag System
7. Pricing and Restrictions
8. Privacy and Security
9. Download Links
10. Test Environment
11. Evidence Sources
12. Update History

Do not reduce the database to a simple Supported / Not Supported NSFW classification.

Different capabilities must be recorded independently.

---

6. Evidence and Verification | 证据与核实

Information Sources

Use these source labels:

Label| Meaning
User Test| Actual hands-on observations
Official| Developer-controlled information
Third-party| Independent public sources

Verification Status

Status| Meaning
Tested| Actually tested
Partially Tested| Only some scenarios tested
Not Tested| No hands-on test
Needs Verification| Information exists but evidence is insufficient
Unknown| No reliable information

Important distinctions:

- Not observed does not mean nonexistent.
- Not tested does not mean unsupported.
- Official claims do not automatically equal independently verified behavior.
- A third-party download link must never be labeled official.

Whenever possible, record:

- Test date
- Application version
- Android version
- Test region
- Account settings
- Test scenario
- Result
- Source URL

---

7. NSFW Classification Rules | NSFW 分类规则

Do not use one NSFW label to describe an entire application.

Record these dimensions separately:

1. Private conversation generation.
2. NSFW account settings.
3. Adult-content warnings.
4. Content filters and restrictions.
5. Public character descriptions.
6. Public profile and community content.
7. NSFW-related tags.
8. Tag search and filtering.

The project documents application capabilities, not unrestricted access or guaranteed content availability.

Respect applicable laws, platform requirements, and age restrictions. Never include sexualized depictions of minors.

---

8. Documentation Style | 文档编写规范

All documentation must be bilingual.

Preferred format:

## 实测规范 | Testing Guidelines

中文说明……

English explanation...

Tables must use valid GitHub Markdown:

| 中文项目 | English Item | Description |
|---|---|---|
| 聊天体验 | Chat Experience | 聊天质量 / Conversation quality |

Rules:

- Use UTF-8.
- Use standard Markdown.
- Use consistent headings.
- Use relative links for files inside the repository.
- Check all internal links.
- Avoid duplicate or contradictory information.
- Use concise technical terminology.
- Keep Chinese and English meanings consistent.
- Do not create unnecessary documentation files.

---

9. GitHub Operating Instructions | GitHub 操作要求

The maintainer prefers the AI agent to perform repository work directly.

When authorized:

1. Inspect the current repository and branch.
2. Read existing files before editing.
3. Identify actual errors and inconsistencies.
4. Modify files directly through GitHub or the available Git interface.
5. Preserve existing useful information.
6. Use clear commit messages.
7. Verify every modification after writing.
8. Report exact files changed and any remaining issues.

Do not ask the maintainer to manually copy large documents when direct repository write access is available.

Do not claim a change succeeded unless the GitHub operation confirms success.

If write access is unavailable:

- Explain the actual permission problem.
- Do not repeatedly attempt the same failed operation.
- Do not pretend files have been modified.
- Prefer an efficient alternative.

Never overwrite files without reading their latest contents and checking for concurrent changes.

---

10. Current Project Priorities | 当前工作优先级

Continue from the existing repository. Do not rebuild everything from scratch.

Recommended sequence:

Priority 1 — Repair Existing Documentation

- Review root README.
- Fix invalid Markdown tables.
- Standardize Chinese-English formatting.
- Improve navigation.
- Check all internal links.
- Correct inaccurate or ambiguous NSFW classifications.

Priority 2 — Create Application Profiles

Create detailed records for:

- MiraiMind (verify exact application name)
- Hi Waifu
- Sakura

Use the existing application template.

Preserve all maintainer-provided test results.

Priority 3 — Build the Testing Database

Create:

- TESTING_GUIDE.md
- TEST_OVERVIEW.md
- NSFW_TESTS.md
- CHAT_EXPERIENCE.md
- FEATURES.md
- PRICING.md
- PRIVACY_SECURITY.md
- PUBLIC_CONTENT.md
- TAG_DATABASE.md

Priority 4 — Quality Assurance

- Check Markdown syntax.
- Check internal links.
- Check bilingual consistency.
- Check duplicate records.
- Check source references.
- Check that all test claims have appropriate evidence labels.
- Verify the final repository tree.

---

11. How to Work with the Maintainer | 与项目维护者协作

The maintainer has already spent considerable time building this repository through previous ChatGPT conversations.

Project continuity is important.

Therefore:

- Do not ask for information already recorded in this file.
- Do not restart the project unnecessarily.
- Do not repeatedly explain the established project decisions.
- Prefer direct implementation over lengthy instructions.
- Work in manageable batches.
- Preserve user-provided original test data.
- Ask only when a genuinely important decision is missing.
- Keep the maintainer informed about actual progress and limitations.

The maintainer prefers Chinese communication, while repository documentation must remain bilingual.

---

12. First Task for Codex | Codex 首要任务

Before doing anything else:

1. Read this "AGENTS.md".
2. Inspect the complete current repository tree.
3. Read every existing Markdown file.
4. Compare the actual files against the project requirements above.
5. Identify errors, missing files, broken links, and inconsistent classifications.
6. Prepare a concise correction plan.
7. If repository write access is available, begin repairing existing documentation directly.
8. Preserve all original test results.

Do not immediately generate every planned file before inspecting the repository.

The objective is to continue the existing project, not replace it with a new project.

---

Project Identity

AI-Chat-APK

Independent Android AI Chat Application Directory & Testing Database.

Maintainer: Alexhrj

Repository: https://github.com/Alexhrj/AI-Chat-APK

Primary Language: Chinese

Documentation: Chinese + English

Collection Method: Links

Testing Format: Overview + Detailed Profiles

Testing Scope: Detailed

End Goal: A structured, maintainable, bilingual, evidence-based directory of Android AI chat applications.