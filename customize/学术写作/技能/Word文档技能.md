# Word 文档技能（docx）

> 来源：[anthropics/skills](https://github.com/anthropics/skills)
> 安装：`npx openskills install anthropics/skills`

## 功能介绍

对 .docx 文件进行创建、编辑、分析，支持：
- 用 pandoc 转 Markdown 读正文
- 用 Document 库/OOXML 编辑已有文档
- Redlining 流程：做带修订痕迹的审稿式修改

**论文场景**：给定期刊/会议的 Word 投稿模板，在模板中替换标题、作者、摘要、正文等占位内容，生成符合格式的投稿稿；也可对他人文档做修订建议（tracked changes）。

---

## 使用场景与示例

### 用 Word 模板写投稿稿

**前置输入**：期刊/会议提供的 .docx 投稿模板；你的标题、作者、摘要、各节正文

**示例 Prompt**：
- 「这是某期刊的 Word 模板，帮我把我的标题、摘要和正文填进去」
- 「在模板里替换作者信息和 Section 1–4 的内容」

**产出**：符合模板格式的 .docx 稿（可先解包再脚本替换占位内容，或按 OOXML 编辑后重新打包）

---

### 对 Word 稿做修订建议

**前置输入**：已写好的 .docx 论文或审稿意见

**示例 Prompt**：
- 「按 redlining 流程，帮我在文档里标出需要改的几处」
- 「把这段改成 tracked changes：原文删除、新文插入」

**产出**：带修订痕迹的 .docx（仅标记改动处，便于作者接受/拒绝）
