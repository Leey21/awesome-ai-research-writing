# 学术写作资源库

整理自 [awesome-ai-research-writing](https://github.com/Leey21/awesome-ai-research-writing)，包含来自 MSRA、Seed、SH AI Lab 等顶尖研究机构及北大、中科大、上交硕博同学日常使用的写作技巧。

---

## 提示词（Prompts）

| 文件 | 适用场景 |
|------|----------|
| [中转英](./提示词/中转英.md) | 中文草稿 → 英文 LaTeX 学术片段 |
| [英转中](./提示词/英转中.md) | 英文 LaTeX → 中文直译（快速理解论文） |
| [中转中](./提示词/中转中.md) | 中文草稿重构为学术段落（Word 场景） |
| [缩写](./提示词/缩写.md) | 英文 LaTeX 微幅压缩（减少 5-15 词） |
| [扩写](./提示词/扩写.md) | 英文 LaTeX 微幅扩充（增加 5-15 词） |
| [表达润色（英文论文）](./提示词/表达润色（英文论文）.md) | 英文 LaTeX 深度润色，达到顶会发表水准 |
| [表达润色（中文论文）](./提示词/表达润色（中文论文）.md) | 中文论文克制润色，只改必要问题（Word 场景） |
| [逻辑检查](./提示词/逻辑检查.md) | 终稿前"红线审查"，仅报致命错误 |
| [去AI味](./提示词/去AI味.md) | 机械化英文文本自然化，去除 AI 写作特征 |
| [论文架构图](./提示词/论文架构图.md) | 根据方法描述生成学术架构图（含英文版） |
| [实验绘图推荐](./提示词/实验绘图推荐.md) | 根据数据推荐最适合的学术图表类型 |
| [生成图的标题](./提示词/生成图的标题.md) | 中文描述 → 规范英文 Figure Caption |
| [生成表的标题](./提示词/生成表的标题.md) | 中文描述 → 规范英文 Table Caption |
| [实验分析](./提示词/实验分析.md) | 实验数据 → LaTeX 分析段落（含 \paragraph 结构） |
| [Reviewer视角审稿](./提示词/Reviewer视角审稿.md) | 模拟顶会 Reviewer 对全文进行严格评审 |
| [模型选择参考](./提示词/模型选择参考.md) | 不同写作场景的 AI 模型推荐 |

---

## 内置 Skills（`.claude/skills/`，Claude.ai / Cursor 直接使用）

本仓库在 `.claude/skills/` 目录中预置了 15 个学术写作核心技能，对应 Part I 中全部 prompt 场景，**克隆仓库后开箱即用**，无需额外安装。在 Claude.ai 的 **Customize → Skills** 面板，或 Cursor Agent Chat 中输入 `/技能名` 即可调用。

| 技能名 | 对应场景 |
|--------|----------|
| `/中转英` | 中文草稿 → 英文 LaTeX 学术片段 |
| `/英转中` | 英文 LaTeX → 中文直译 |
| `/中转中` | 中文草稿重构为学术段落（Word 场景） |
| `/缩写` | 英文 LaTeX 微幅压缩（减少 5-15 词） |
| `/扩写` | 英文 LaTeX 微幅扩充（增加 5-15 词） |
| `/英文润色` | 英文 LaTeX 深度润色，达到顶会水准 |
| `/中文润色` | 中文论文克制润色，只改必要问题（Word 场景） |
| `/逻辑检查` | 终稿前"红线审查"，仅报致命错误 |
| `/去AI味` | 机械化英文文本自然化 |
| `/论文架构图` | 根据方法描述生成学术架构图 |
| `/实验绘图推荐` | 根据数据推荐最适合的学术图表类型 |
| `/生成图标题` | 中文描述 → 规范英文 Figure Caption |
| `/生成表标题` | 中文描述 → 规范英文 Table Caption |
| `/实验分析` | 实验数据 → LaTeX 分析段落 |
| `/审稿人视角` | 模拟顶会 Reviewer 对全文进行严格评审（需上传 PDF） |

---

## 外部 Skills（需 Cursor / Claude Code + OpenSkills 配置）

> 需要 Cursor / Claude Code 等 AI coding 工具配合使用，详见 [技能总览与配置](./技能/技能总览与配置.md)

| 文件 | Skill 名称 | 来源 |
|------|------------|------|
| [技能总览与配置](./技能/技能总览与配置.md) | 安装方法与所有 Skill 概览 | — |
| [论文写作技能](./技能/论文写作技能.md) | 20-ml-paper-writing | zechenzhangAGI/AI-research-SKILLs |
| [去AI味技能](./技能/去AI味技能.md) | humanizer | blader/humanizer |
| [Word文档技能](./技能/Word文档技能.md) | docx | anthropics/skills |
| [协作写作技能](./技能/协作写作技能.md) | doc-coauthoring | anthropics/skills |
| [概念图设计技能](./技能/概念图设计技能.md) | canvas-design | anthropics/skills |
