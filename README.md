# workbuddy-skills

> 我的 WorkBuddy Skill 合集 —— 扩展 AI 助手能力的可复用工作流。

---

## 什么是 WorkBuddy Skill

WorkBuddy Skill 是一种给 AI 助手加装"专业模块"的方式。  
每个 Skill 是一个 `SKILL.md` 文件，告诉 AI 在特定场景下该如何行动、遵循什么流程、以什么角色来帮你。

**类比**：就像给手机安装 App，Skill 让 AI 在某个领域变得更专业、更有用。

---

## Skill 列表

| Skill | 一句话描述 | 触发方式 |
|-------|-----------|---------|
| [feynman-learning-partner](./feynman-learning-partner/) | AI 扮演零基础新人，追问直到你真讲清楚 | `用费曼学习法教我 [知识点]` |

---

## 如何安装使用

将任意 Skill 的文件夹复制到 WorkBuddy 的 skill 目录：

```bash
# macOS / Linux
~/.workbuddy/skills/

# Windows
C:\Users\你的用户名\.workbuddy\skills\
```

例如安装费曼学习伙伴：

```
~/.workbuddy/skills/
└── feynman-learning-partner/
    └── SKILL.md
```

重新打开 WorkBuddy，按照各 Skill 的触发方式使用即可。

---

## License

MIT
