# 去 AI 味技能（humanizer）

> 来源：[blader/humanizer](https://github.com/blader/humanizer)
> 安装：`npx openskills install anthropics/skills`（或直接从 blader/humanizer 安装）

## 功能介绍

识别并去除 AI 写作痕迹，使文本更自然、像人写。

基于 Wikipedia「Signs of AI writing」的规则，针对以下 AI 写作特征进行处理：
- 过度强调意义
- 促销腔
- 空洞的 -ing 分析
- 模糊归因
- 破折号滥用
- 三点式堆砌
- AI 高频词（leverage, delve, tapestry 等）
- 否定式平行结构

同时注入「人味」特征：有观点、节奏变化、承认不确定性、适当用「我」。

---

## 适用场景

- 润色后终稿的语言风格检查
- 投稿前 Abstract 和 Introduction 的去 AI 味处理
- 任何大模型生成内容的自然化处理

---

## 使用示例

**前置输入**：待检查的段落或全文（LaTeX 片段、Word 正文、Markdown 等）

**示例 Prompt**：
- 「这段读起来像 AI 写的，帮我 humanize」
- 「投稿前帮我把 Abstract 和 Introduction 去一下 AI 味」

**产出**：重写后的自然文本 + 可选修改说明；保留原意与语气，减少显著性堆砌、破折号滥用、三点式、AI 高频词等
