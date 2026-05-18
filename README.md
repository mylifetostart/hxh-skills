# Deep Research Analyst

一个用于 Claude Code 的战略分析 Skill，能够对公司、行业、产品或概念进行深度调研，输出专业的结构化分析报告。

## 功能

- 多理论框架交叉分析（PEST、波特五力、SWOT、S 曲线、JTBD、AARRR、Flywheel、护城河等）
- 识别核心系统变量与反馈循环
- 三情景未来推演（乐观 / 中性 / 悲观）
- 输出 Markdown 格式的战略级报告

## 使用方式

在 Claude Code 中调用：

```
使用 deep-research-analyst skill 分析 [目标]
```

示例：

```
使用 deep-research-analyst skill 分析 OpenAI 的商业模式
使用 deep-research-analyst skill 分析 AI 编程工具行业
使用 deep-research-analyst skill 分析 Notion 的增长逻辑
```

## 输出结构

| 章节 | 内容 |
|------|------|
| Executive Summary | 核心结论与战略建议摘要 |
| Industry Analysis | 行业宏观分析（PEST、波特五力、S 曲线） |
| Company/Product Analysis | 商业模式、护城河、竞争优势 |
| User Needs Analysis | 用户需求（JTBD）、痛点、行为 |
| System & Growth Analysis | 增长模型、系统反馈循环、核心变量 |
| Risk Analysis | 政策、技术、竞争、商业化风险 |
| Future Scenarios | 1 / 3 / 5 年三情景推演 |
| Strategic Recommendations | 可执行的战略建议 |

## 分析原则

- 强调因果关系，避免信息堆砌
- 多框架交叉验证，提升结论可信度
- 每次分析必须明确核心变量和战略结论
- 输出专业、结构化、可执行的报告
