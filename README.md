# feiman-learning-partner-skills

> 我的费曼学习法 AI 追问伙伴 —— 可复用、可移植的 AI 学习工作流与 Skill 集合。

---

## 什么是 Skill

Skill 是一种扩展 AI 助手能力的方式。

它通过一个 `SKILL.md` 文件，为 AI 提供特定领域的角色设定、执行流程、行为规范和交互策略，让 AI 在某个场景下表现得更加专业和稳定。

**类比：**

* 对 AI 来说，Skill 就像插件（Plugin）
* 对 Agent 来说，Skill 就像能力模块（Capability）
* 对开发者来说，Skill 就像可复用的 Prompt Workflow

一个设计良好的 Skill 可以在不同 AI 平台、Agent Framework 和智能体系统之间复用。

---

## Skill 列表

| Skill                                                   | 一句话描述                        | 触发方式             |
| ------------------------------------------------------- | ---------------------------- | ---------------- |
| [feynman-learning-partner](./feynman-learning-partner/) | AI 扮演零基础新人，通过持续追问帮助你真正讲清楚知识点 | `用费曼学习法教我 [知识点]` |

---

## 使用方式

将 Skill 导入到你使用的 AI Agent 平台、Prompt Framework 或智能体系统中。

典型方式包括：

* 放入 Agent 的 Skills 目录
* 导入 Prompt Library
* 注册为 Workflow
* 挂载到 MCP Agent
* 作为系统提示词（System Prompt）使用

目录结构示例：

```text
skills/
└── feynman-learning-partner/
    └── SKILL.md
```

加载后即可按照对应触发方式使用：

```text
用费曼学习法教我 JVM
```

```text
用费曼学习法教我 Redis 缓存穿透
```

```text
用费曼学习法教我 Transformer
```

---

## 设计目标

本仓库中的 Skill 遵循以下原则：

* 可复用（Reusable）
* 可移植（Portable）
* 平台无关（Platform Agnostic）
* Agent 友好（Agent Friendly）
* 人类可读（Human Readable）

目标是让同一个 Skill 能够在不同 AI 助手和 Agent 系统中复用，而无需修改核心逻辑。

---

## 适用场景

* AI 学习伙伴
* AI 导师
* 智能体工作流
* Prompt Engineering
* Agent Runtime
* MCP Agent
* 多智能体系统
* 企业级 AI 平台

---

## Contributing

欢迎提交新的 Skill、优化现有工作流，或分享你的 Agent 实践经验。

---

## License

MIT
