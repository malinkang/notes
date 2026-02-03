---
title: Skills
---

> [!abstract] 什么是 Agent Skills？
> **Skill = 结构化的长期记忆**，把你不想每次都重复说的话写成文件存起来，AI 自动加载使用。

---

## 官网

* [官网](https://agentskills.io)
* [规范文档](https://agentskills.io/specification)
* [什么是 Skills](https://agentskills.io/what-are-skills)
* [如何集成](https://agentskills.io/integrate-skills)
* [anthropics/skills](https://github.com/anthropics/skills)
* [agentskills/agentskills](https://github.com/agentskills/agentskills)


## 安装

### 1. [vercel-labs/skills](https://github.com/vercel-labs/skills)

```bash
npm install -g skills
```

### 2. 安装 Skill (插件)

使用 `add` 命令安装 Skill。

**基本语法：**
```bash
npx skills add <repository> [options]
```

**常用参数：**
*   `-a, --agent <names>`: 指定为哪些 AI 工具安装 (如 `cursor`, `gemini`, `claude-code`)。**强烈建议指定**，否则会默认为几十个 Agent 安装，生成大量垃圾文件。
*   `-g, --global`: 安装到全局范围 (默认是当前项目)。
*   `-y, --yes`: 自动确认所有提示。

**示例：**

```bash
# 只为 Cursor 安装 Obsidian Skill
npx skills add kepano/obsidian-skills --agent cursor

# 为 Cursor 和 Gemini 安装 Vercel 推荐 Skill
npx skills add vercel-labs/agent-skills --agent cursor,gemini-cli
```

### 3. 其他常用命令

*   **查看已安装**：`npx skills list`
*   **搜索 Skill**：`npx skills find [keywords]`
*   **移除 Skill**：`npx skills remove [name]`



## Skill 推荐

### [obsidian-skills](https://github.com/kepano/obsidian-skills)

```bash
npx skills add kepano/obsidian-skills --agent antigravity gemini-cli codex opencode
```


### [ui-ux-pro-max-skill](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill)
