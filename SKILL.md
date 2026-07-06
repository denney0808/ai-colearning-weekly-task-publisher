---
name: ai-colearning-checkin-2026h2w1
description: Create and facilitate the 2026H2W1 AI co-learning group check-in task for practicing Codex on a real messy-folder cleanup workflow. Use when drafting the week 1 assignment, group announcement, participant instructions, submission template, acceptance criteria, recap, or facilitator guidance for a Codex co-learning community.
---

# AI共学群打卡任务 - 2026H2W1

## Goal

Turn the first Codex co-learning week into a practical check-in task: participants use Codex to safely organize one messy local folder copy, then submit evidence of the workflow, not just a polished final folder.

The core lesson is safe delegation: copy first, set rules, read-only inventory, plan before execution, confirm changes, and leave an audit trail.

## Assignment

Use this task title:

```text
2026H2W1｜用 Codex 安全整理一个混乱文件夹
```

Use this short group announcement:

```text
本周任务：找一个真实但不重要的混乱文件夹，先复制副本，再让 Codex 按“只读盘点 -> 出整理方案 -> 确认执行 -> 生成索引和日志”的流程整理一次。

重点不是整理得多漂亮，而是练会把本地电脑任务安全交给 Codex：有副本、有规则、有计划、有确认、有记录。
```

## Participant Workflow

Ask participants to complete these steps:

1. Pick a messy folder
   - Use a real folder such as downloads, project materials, event assets, meeting notes, course materials, customer资料, or image collections.
   - Copy it first. Work only inside the copy.
   - Do not use sensitive folders containing secrets, certificates, contracts, private IDs, API keys, passwords, or unreleasable customer data.

2. Add a project rule file
   - Ask Codex to create `AGENTS.md` in the folder copy.
   - Require Chinese replies, current-folder-only operations, no deletion, no overwrite, first pass read-only, ask before uncertain actions, and update the cleanup log after execution.

3. Run read-only inventory
   - Ask Codex to list file types, counts, likely usage, duplicate/version conflicts, unclear files, and confirmation questions.
   - It must not move, rename, modify, or delete files in this step.

4. Ask for a plan only
   - Ask Codex to propose folder structure, placement rules, naming rules, unclear-file handling, and generated documents.
   - It must not execute before the participant confirms.

5. Execute after confirmation
   - Let Codex create folders, move files, and generate documentation.
   - Expected docs: README or project notes, file index, pending-confirmation list, cleanup log, and version notes when old/final versions conflict.

6. Make one follow-up adjustment
   - Ask Codex to revise one part of the result, such as merging guest materials, moving old versions to pending confirmation, changing folder names, or updating the index.
   - Require a small plan before the second execution.

## Prompts

Use this prompt for `AGENTS.md`:

```text
我现在需要在这个项目文件夹里新建一个 AGENTS.md 规则文件。
规则文件内容包括：默认使用中文回复；只允许操作当前项目文件夹。
第一轮只读盘点，不移动、不重命名、不修改、不删除任何文件。
禁止删除任何文件；需要确认的操作先问我。
无法判断的文件放入待确认清单，不要强行处理。
每次执行后要更新整理日志。
如果已经存在 AGENTS.md，请先读取并说明差异，不要覆盖。
```

Use this prompt for read-only inventory:

```text
请先只读盘点当前文件夹。
不移动、不重命名、不修改、不删除任何文件。
列出当前文件夹里的文件类型、数量和可能用途。
找出疑似重复、旧版本、不明用途的文件。
给出你对这个项目的初步理解。
用一个简洁表格输出，最后列出我需要确认的问题。
```

Use this prompt for planning:

```text
请进入计划模式。
基于刚才的盘点结果，给出整理方案，但不要执行。
方案需要包括：建议创建哪些文件夹；哪些文件放入哪些位置；命名规则是什么。
哪些文件不能判断，应该进入待确认。
需要生成哪些说明文档和整理日志。
```

Use this prompt for a follow-up adjustment:

```text
请基于已经整理好的结果做一次二次调整。
调整需求是：[写下你的具体调整需求]。
请先列出调整计划，说明会移动哪些文件、会更新哪些说明文档，等待我确认后再执行。
```

## Submission Template

Ask participants to submit:

```text
2026H2W1 打卡：

1. 我整理的文件夹类型：
2. 原始文件数量：
3. Codex 盘点出的主要文件类型：
4. Codex 建议的分类结构：
5. 我确认后执行了哪些整理：
6. Codex 生成了哪些说明文档：
7. 待确认清单里有哪些典型问题：
8. 我做的二次调整是什么：
9. 这次我学到的一个安全使用 Codex 的经验：
```

## Acceptance Criteria

Treat a submission as complete when it shows:

- It used a copied folder, not the only original.
- It created or used `AGENTS.md` rules before execution.
- It includes a read-only inventory result.
- It includes a plan-before-execution step.
- It includes final folder categories and generated docs.
- It includes at least one pending-confirmation item or explains why none existed.
- It includes one follow-up adjustment.
- It states one safety lesson learned.

Do not require screenshots if the participant can provide a clear text summary. Encourage screenshots only when useful and safe.

## Facilitator Review

When reviewing submissions, focus on process quality:

- Good: clear safety boundary, no deletion, no overwrite, uncertainty preserved, logs updated.
- Needs improvement: direct execution without inventory, working on originals, deleting files, forcing unclear files into categories, or no record of changes.
- Best discussion question: "哪一步让你第一次觉得 Codex 是在帮你做真实电脑任务，而不是只给建议？"

For weekly recap, summarize three things:

1. Common folder types participants chose.
2. Common uncertainty patterns, such as final-version conflicts, unnamed files, duplicate images, or unclear meeting notes.
3. One practical rule to carry into the next week.

