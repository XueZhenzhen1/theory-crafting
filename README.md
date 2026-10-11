# 万物皆可理论 · Everything Can Become a Theory

> 把日常现象压缩成易传播的名字，再用机制、边界与证据把它解释清楚。

[简体中文](#中文) · [English](#english)

## 中文

### 这是什么？

「万物皆可理论」是一个可移植的 Agent Skill，用来把生活、职场、教育、婚恋、商业与互联网文化中的普通现象，提炼成兼具**传播力**和**解释力**的概念。

它不鼓励为了造词而造词，而是遵循：

**生活现象 → 反常识矛盾 → 体验提炼 → 口语命名 → 机制解释 → 边界与反例 → 可检验判断 → 跨场景迁移**

### 为什么使用它？

很多分析要么只有学术术语、难以传播；要么只有吸睛标签、没有解释。这个 Skill 把两件事分开处理：

- **传播名**：短、口语、有画面，方便记忆和转述。
- **机制解释**：解释为什么发生、何时成立、何时不成立，以及什么证据会削弱这个解释。

### 能做什么

- 为一个生活或社会现象提出多个口语化概念名并筛选首选项。
- 拆解职场、师生、婚恋、消费、商业模式和互联网趋势中的行为机制。
- 将一个候选概念发展成文章选题、短视频切口或系列内容。
- 区分观察、推断、假设与修辞，避免把新造词伪装成已被验证的学术理论。

### 快速开始

将 `theory-crafting/` 目录作为一个 Agent Skill 安装到兼容的客户端。至少需要保留 `SKILL.md`；其余文件用于理解、测试与贡献流程。

示例提示：

- “给职场里明明很忙却没推进重要工作的现象命名，至少比较 5 个名字。”
- “用这个方法分析师生关系里的提问恐惧，给出机制、边界和可检验预测。”
- “围绕‘熟人折扣’设计一组婚恋主题内容，但不要把推断写成事实。”

### 输出质量标准

一个合格的理论草案至少应该包含：

1. 可观察的现象与核心矛盾；
2. 多个候选名及命名理由；
3. 清楚的一句话定义；
4. 有因果链条的机制解释；
5. 适用边界和反例；
6. 能被观察或反驳的预测。

### 目录

```text
theory-crafting/
├── SKILL.md             # Skill 主指令
├── README.md            # 项目说明与安装提示
├── LICENSE              # MIT License
├── CONTRIBUTING.md      # 贡献指南
├── CHANGELOG.md         # 版本记录
├── evals/
│   └── evals.json       # 输出质量评测用例
├── examples/
│   └── sample-theory.md # 示例输出
└── references/
    └── naming-rubric.md # 命名评估速查表
```

### 许可

本项目采用 MIT License，详见 [LICENSE](LICENSE)。

## English

### What is this?

**Everything Can Become a Theory** is a portable Agent Skill for turning everyday observations into memorable concepts backed by mechanisms, boundaries, and testable predictions.

It is designed for topics such as work, education, relationships, consumer behavior, business models, and internet culture.

### Core workflow

**Observation → Tension → Lived experience → Memorable name → Mechanism → Boundaries and counterexamples → Testable predictions → Cross-context transfer**

### Why use it?

A catchy label is not automatically a good theory. This skill separates:

- **The shareable name** — short, concrete, conversational, and easy to repeat.
- **The explanatory model** — a plausible mechanism with scope conditions and ways it could be challenged.

### Example prompts

- “Name the pattern where people look busy but make little progress. Compare at least five candidate names.”
- “Analyze why students may avoid asking questions. Include mechanisms, counterexamples, and testable predictions.”
- “Turn this concept into a content series without presenting speculation as established fact.”

See `SKILL.md` for the complete workflow. Contributions and evaluation cases are welcome.
