# Skill Inventory Usage Report

## 当前导航 · 2026-10-10

本文件只保存 2026-06-29 的库存扫描、使用定义和统计，不作为当前运行可用性或项目业务状态台账。当前技能治理目标、决定、证据层级、授权连续性、待核项及续接说明见 [Skills handoff](/Users/USER/Documents/skills/SKILLS_PMO_HANDOFF_2026-10-10.md:3)。

唯一 Owner、新旧身份与交接验收由 [全局映射](/Users/USER/Documents/Codex/2026-09-23/global-pmo-20260923/outputs/迁移6会话-20261010.json) 的 Skills 条目维护；历史准备导航已移入文末，不影响当前终态。本文件由 Skills Owner 保留原统计、必要时维护导航；各次安装/验证及项目业务进度分别引用 handoff 内的原入口，不在此重复同步。

## 历史扫描 · 2026-06-29

以下原始元数据、评级规则与表格保持原样；“使用证据”是当日读路径或声明使用，不能解释为今天已配置、可运行或业务验收通过。

- Generated: 2026-06-29T12:19:47+08:00
- Skill entries scanned: 57
- Session log files scanned: 233
- Scope counts: global-agents=39, global-codex=10, project-skills=8
- Usage rating counts: S=8, A=7, B=4, C=38

## Rating Rule

- S: evidence_count >= 10, high actual evidence.
- A: evidence_count 3-9, repeated actual evidence.
- B: evidence_count 1-2, limited actual evidence.
- C: no strict actual evidence found in parsed session logs.

Evidence means either the assistant read that exact `SKILL.md` path in a tool call, or explicitly announced using that skill. Generic words like `review` are not counted.

## Full Table

| Rating | Evidence | Skill | Scope | Install Date Estimate | Path Read | Explicit Use | Path |
|---|---:|---|---|---|---:|---:|---|
| S | 394 | `using-superpowers` | global-codex | 2026-05-30T19:13:40+08:00 | 272 | 122 | `/Users/USER/.codex/skills/superpowers` |
| S | 253 | `planning-with-files` | global-codex | 2026-05-30T19:15:20+08:00 | 174 | 79 | `/Users/USER/.codex/skills/planning-with-files` |
| S | 66 | `webapp-testing` | global-codex | 2026-05-30T19:15:14+08:00 | 64 | 2 | `/Users/USER/.codex/skills/webapp-testing` |
| S | 61 | `ai-supply-chain-bottleneck-hunter` | global-codex | 2026-06-02T18:30:58+08:00 | 44 | 17 | `/Users/USER/.codex/skills/ai-supply-chain-bottleneck-hunter` |
| S | 24 | `obsidian-vault` | global-agents | 2026-06-15T20:37:42+08:00 | 22 | 2 | `/Users/USER/.agents/skills/obsidian-vault` |
| S | 15 | `pdf` | global-codex | 2026-05-30T19:15:10+08:00 | 13 | 2 | `/Users/USER/.codex/skills/pdf` |
| S | 14 | `find-skills` | global-codex | 2026-05-30T18:50:35+08:00 | 12 | 2 | `/Users/USER/.codex/skills/find-skills` |
| S | 13 | `impeccable` | global-agents | 2026-06-25T23:56:28+08:00 | 9 | 4 | `/Users/USER/.agents/skills/impeccable` |
| A | 8 | `review` | global-agents | 2026-06-15T20:37:42+08:00 | 4 | 4 | `/Users/USER/.agents/skills/review` |
| A | 7 | `handoff` | global-agents | 2026-06-15T20:37:42+08:00 | 7 | 0 | `/Users/USER/.agents/skills/handoff` |
| A | 7 | `improve-codebase-architecture` | global-agents | 2026-06-15T20:37:42+08:00 | 5 | 2 | `/Users/USER/.agents/skills/improve-codebase-architecture` |
| A | 7 | `prototype` | global-agents | 2026-06-15T20:37:42+08:00 | 7 | 0 | `/Users/USER/.agents/skills/prototype` |
| A | 7 | `teach` | global-agents | 2026-06-15T20:37:42+08:00 | 7 | 0 | `/Users/USER/.agents/skills/teach` |
| A | 6 | `chronicle` | global-codex | 2026-06-10T18:14:23+08:00 | 6 | 0 | `/Users/USER/.codex/skills/chronicle` |
| A | 3 | `diagnose` | global-agents | 2026-06-15T20:37:42+08:00 | 3 | 0 | `/Users/USER/.agents/skills/diagnose` |
| B | 2 | `code-simplifier` | global-codex | 2026-05-30T19:13:38+08:00 | 2 | 0 | `/Users/USER/.codex/skills/code-simplifier` |
| B | 1 | `caveman` | global-agents | 2026-06-15T20:37:42+08:00 | 1 | 0 | `/Users/USER/.agents/skills/caveman` |
| B | 1 | `edit-article` | global-agents | 2026-06-15T20:37:42+08:00 | 1 | 0 | `/Users/USER/.agents/skills/edit-article` |
| B | 1 | `to-prd` | global-agents | 2026-06-15T20:37:42+08:00 | 1 | 0 | `/Users/USER/.agents/skills/to-prd` |
| C | 0 | `agent-reach` | global-agents | 2026-06-29T09:43:20+08:00 | 0 | 0 | `/Users/USER/.agents/skills/agent-reach` |
| C | 0 | `ai-video-gen` | global-agents | 2026-06-29T09:42:23+08:00 | 0 | 0 | `/Users/USER/.agents/skills/ai-video-gen` |
| C | 0 | `codebase-memory-mcp-intelligence` | global-agents | 2026-06-29T09:43:34+08:00 | 0 | 0 | `/Users/USER/.agents/skills/codebase-memory-mcp-intelligence` |
| C | 0 | `design-an-interface` | global-agents | 2026-06-15T20:37:42+08:00 | 0 | 0 | `/Users/USER/.agents/skills/design-an-interface` |
| C | 0 | `git-guardrails-claude-code` | global-agents | 2026-06-15T20:37:42+08:00 | 0 | 0 | `/Users/USER/.agents/skills/git-guardrails-claude-code` |
| C | 0 | `grill-me` | global-agents | 2026-06-15T20:37:42+08:00 | 0 | 0 | `/Users/USER/.agents/skills/grill-me` |
| C | 0 | `grill-with-docs` | global-agents | 2026-06-15T20:37:42+08:00 | 0 | 0 | `/Users/USER/.agents/skills/grill-with-docs` |
| C | 0 | `migrate-to-shoehorn` | global-agents | 2026-06-15T20:37:42+08:00 | 0 | 0 | `/Users/USER/.agents/skills/migrate-to-shoehorn` |
| C | 0 | `motion-design` | global-agents | 2026-06-29T09:41:44+08:00 | 0 | 0 | `/Users/USER/.agents/skills/motion-design` |
| C | 0 | `qa` | global-agents | 2026-06-15T20:37:42+08:00 | 0 | 0 | `/Users/USER/.agents/skills/qa` |
| C | 0 | `remotion` | global-agents | 2026-06-29T09:43:07+08:00 | 0 | 0 | `/Users/USER/.agents/skills/remotion` |
| C | 0 | `request-refactor-plan` | global-agents | 2026-06-15T20:37:42+08:00 | 0 | 0 | `/Users/USER/.agents/skills/request-refactor-plan` |
| C | 0 | `scaffold-exercises` | global-agents | 2026-06-15T20:37:42+08:00 | 0 | 0 | `/Users/USER/.agents/skills/scaffold-exercises` |
| C | 0 | `setup-matt-pocock-skills` | global-agents | 2026-06-15T20:37:42+08:00 | 0 | 0 | `/Users/USER/.agents/skills/setup-matt-pocock-skills` |
| C | 0 | `setup-pre-commit` | global-agents | 2026-06-15T20:37:42+08:00 | 0 | 0 | `/Users/USER/.agents/skills/setup-pre-commit` |
| C | 0 | `tdd` | global-agents | 2026-06-15T20:37:42+08:00 | 0 | 0 | `/Users/USER/.agents/skills/tdd` |
| C | 0 | `text-to-speech` | global-agents | 2026-06-29T09:42:58+08:00 | 0 | 0 | `/Users/USER/.agents/skills/text-to-speech` |
| C | 0 | `to-issues` | global-agents | 2026-06-15T20:37:42+08:00 | 0 | 0 | `/Users/USER/.agents/skills/to-issues` |
| C | 0 | `triage` | global-agents | 2026-06-15T20:37:42+08:00 | 0 | 0 | `/Users/USER/.agents/skills/triage` |
| C | 0 | `ubiquitous-language` | global-agents | 2026-06-15T20:37:42+08:00 | 0 | 0 | `/Users/USER/.agents/skills/ubiquitous-language` |
| C | 0 | `video-download` | global-agents | 2026-06-29T09:42:49+08:00 | 0 | 0 | `/Users/USER/.agents/skills/video-download` |
| C | 0 | `video-edit` | global-agents | 2026-06-29T09:42:16+08:00 | 0 | 0 | `/Users/USER/.agents/skills/video-edit` |
| C | 0 | `video-understand` | global-agents | 2026-06-29T09:42:35+08:00 | 0 | 0 | `/Users/USER/.agents/skills/video-understand` |
| C | 0 | `write-a-skill` | global-agents | 2026-06-15T20:37:42+08:00 | 0 | 0 | `/Users/USER/.agents/skills/write-a-skill` |
| C | 0 | `writing-beats` | global-agents | 2026-06-15T20:37:42+08:00 | 0 | 0 | `/Users/USER/.agents/skills/writing-beats` |
| C | 0 | `writing-fragments` | global-agents | 2026-06-15T20:37:42+08:00 | 0 | 0 | `/Users/USER/.agents/skills/writing-fragments` |
| C | 0 | `writing-shape` | global-agents | 2026-06-15T20:37:42+08:00 | 0 | 0 | `/Users/USER/.agents/skills/writing-shape` |
| C | 0 | `zoom-out` | global-agents | 2026-06-15T20:37:42+08:00 | 0 | 0 | `/Users/USER/.agents/skills/zoom-out` |
| C | 0 | `hatch-pet` | global-codex | 2026-06-01T12:04:20+08:00 | 0 | 0 | `/Users/USER/.codex/skills/hatch-pet` |
| C | 0 | `mcp-builder` | global-codex | 2026-05-30T19:15:12+08:00 | 0 | 0 | `/Users/USER/.codex/skills/mcp-builder` |
| C | 0 | `create-prd` | project-skills | 2026-06-15T20:34:08+08:00 | 0 | 0 | `/Users/USER/Documents/skills/.agents/skills/create-prd` |
| C | 0 | `design-taste-frontend` | project-skills | 2026-06-15T20:33:54+08:00 | 0 | 0 | `/Users/USER/Documents/skills/.agents/skills/design-taste-frontend` |
| C | 0 | `diagnose` | project-skills | 2026-06-15T20:33:44+08:00 | 0 | 0 | `/Users/USER/Documents/skills/.agents/skills/diagnose` |
| C | 0 | `handoff` | project-skills | 2026-06-15T20:33:44+08:00 | 0 | 0 | `/Users/USER/Documents/skills/.agents/skills/handoff` |
| C | 0 | `image-to-code` | project-skills | 2026-06-15T20:33:54+08:00 | 0 | 0 | `/Users/USER/Documents/skills/.agents/skills/image-to-code` |
| C | 0 | `strategy-red-team` | project-skills | 2026-06-15T20:34:08+08:00 | 0 | 0 | `/Users/USER/Documents/skills/.agents/skills/strategy-red-team` |
| C | 0 | `tdd` | project-skills | 2026-06-15T20:33:44+08:00 | 0 | 0 | `/Users/USER/Documents/skills/.agents/skills/tdd` |
| C | 0 | `write-a-skill` | project-skills | 2026-06-15T20:33:44+08:00 | 0 | 0 | `/Users/USER/Documents/skills/.agents/skills/write-a-skill` |

## 历史导航附录（非当前状态）

以下保留 2026-10-10 重构前顶部导航原文，所述“待验收”仅为准备阶段快照。

<details>
<summary>原顶部迁移导航（原文）</summary>

## 迁移终态更新 · 2026-10-10

唯一 Owner：0-1 PMO总控 | Skills下载治理，`01a123a7-1786-7291-9dbb-509251cd5c51`；身份及实质交接已由全局核验，原位置顶已替换。交接入口 `/Users/USER/Documents/skills/SKILLS_PMO_HANDOFF_2026-10-10.md`。下方旧迁移准备状态保留为历史；业务状态和授权边界不因迁移改变。

# Skill Inventory Usage Report

## 2026-10-10 交接状态同步

本表保留为 2026-06-29 的历史扫描，57 项、使用等级和日志数量均不是当前盘点，也不证明脚本或业务可用。当前技能管理交接入口为 [SKILLS_PMO_HANDOFF_2026-10-10.md](/Users/USER/Documents/skills/SKILLS_PMO_HANDOFF_2026-10-10.md)。最新已完成事项：2026-10-08 更新全局 impeccable 与 ui-ux-pro-max；App 项目盘点 35 个本地 Skill 入口；FDE 13 个、自媒体 17 个安装回执分别见交接索引。2026-10-10 只核文件与整理交接，没有重新运行测试、联网核上游或安装升级。原 CSV 与历史统计未重算。后续唯一 Owner 切换与实质交接仍待全局 PMO 验收。


</details>
