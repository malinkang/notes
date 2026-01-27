---
title: Agent Skills 资源汇总
date: 2026-01-22
tags:
  - AI
  - skills
  - Claude
  - 资源整理
status: active
---

# Agent Skills 资源汇总

> [!abstract] 什么是 Agent Skills？
> **Skill = 结构化的长期记忆**，把你不想每次都重复说的话写成文件存起来，AI 自动加载使用。

---

## 1️⃣ Skill 官网

### 核心规范

| 名称 | 链接 | 说明 |
|------|------|------|
| **Agent Skills 官网** | https://agentskills.io | ⭐ 入门必看 |
| **规范文档** | https://agentskills.io/specification | SKILL.md 格式定义 |
| **什么是 Skills** | https://agentskills.io/what-are-skills | 概念介绍 |
| **如何集成** | https://agentskills.io/integrate-skills | 工具开发者指南 |

### 官方仓库

| 仓库 | 说明 |
|------|------|
| [agentskills/agentskills](https://github.com/agentskills/agentskills) | Agent Skills 标准源码 |
| [anthropics/skills](https://github.com/anthropics/skills) ⭐48.2k | Anthropic 官方示例 |

### 平台文档

| 平台 | 链接 |
|------|------|
| **Claude Code** | [Claude Skills Documentation](https://platform.claude.com/docs/en/agents-and-tools/agent-skills/overview) |
| **VS Code Copilot** | [Use Agent Skills in VS Code](https://code.visualstudio.com/docs/copilot/customization/agent-skills) |
| **Google Antigravity** | [Authoring Antigravity Skills](https://codelabs.developers.google.com/getting-started-with-antigravity-skills) |

### 学习资料

| 标题 | 作者 | 链接 |
|------|------|------|
| Agent Skills 介绍 | Simon Willison | [Blog](https://simonwillison.net/2025/Dec/19/agent-skills/) |
| Writing OpenCode Agent Skills | JP Caparas | [Medium](https://jpcaparas.medium.com/writing-opencode-agent-skills-a-practical-guide-with-examples-870ff24eec66) |
| Build Your First Claude Code Skill | Rick Hightower | [Medium](https://medium.com/@richardhightower/build-your-first-claude-code-skill-a-simple-project-memory-system-that-saves-hours-1d13f21aff9e) |
| Your Agent Skills Work in Antigravity | Alex McFarland | [YouTube](https://www.youtube.com/watch?v=mWpuvze9V0A) |

---

## 2️⃣ Skill 安装

### 安装方式

> [!tip] 三种安装方法
> 1. **Marketplace 命令** - 最简单
> 2. **手动复制** - 最灵活
> 3. **CLI 工具** - 通用跨平台

#### Marketplace（Claude Code）

```bash
/plugin marketplace add kepano/obsidian-skills
/plugin install obsidian@obsidian-skills
```

#### 手动安装

```bash
# 克隆仓库
git clone https://github.com/kepano/obsidian-skills /tmp/skill

# 复制到对应目录（见下方安装位置）
cp -r /tmp/skill/skills/* <安装路径>/
```

#### CLI 工具

```bash
# OpenSkills
npm i -g openskills
openskills install <skill-name>

# Agent Skills CLI（支持所有平台）
npm i -g agent-skills-cli
```

### 安装位置

| 工具                 | Skill 路径                         |
| ------------------ | -------------------------------- |
| **Antigravity**    | `.agent/skills/<skill-name>/`    |
| **Claude Code**    | `.claude/skills/<skill-name>/`   |
| **Codex**          | `.codex/skills/<skill-name>/`    |
| **GitHub Copilot** | `.github/skills/<skill-name>/`   |
| **Cursor**         | `.cursor/skills/<skill-name>/`   |
| **OpenCode**       | `.opencode/skills/<skill-name>/` |

> [!note] 说明
> 所有工具都使用相同的 SKILL.md 格式，只是目录位置不同。Skill 文件可以跨平台复用！

### SKILL.md 基本结构

```markdown
---
name: my-skill
description: 触发条件，告诉 AI 何时使用
license: MIT
---

# Skill 标题

（你想让 AI 记住的规则、模板、示例）
```

### 相关工具

| 名称 | 链接 | 说明 |
|------|------|------|
| **openskills** | [GitHub](https://github.com/numman-ali/openskills) ⭐6.6k | 通用加载器 |
| **agent-skills-cli** | [GitHub](https://github.com/Karanjot786/agent-skills-cli) | 跨平台 CLI，支持 40k+ skills |
| **skills-ref** | [GitHub](https://github.com/agentskills/agentskills/tree/main/skills-ref) | 验证工具 |

---

## 3️⃣ Skill 推荐

### 🛒 Skills 市场

| 名称 | 链接 | 说明 |
|------|------|------|
| **SkillsMP** | https://skillsmp.com | ⭐ 最大市场，80,000+ skills |
| **daymade/claude-code-skills** | [GitHub](https://github.com/daymade/claude-code-skills) ⭐422 | 生产级开发 skills |
| **mhattingpete/claude-skills-marketplace** | [GitHub](https://github.com/mhattingpete/claude-skills-marketplace) ⭐241 | Git、测试、代码审查 |

### 📝 Obsidian 专用

| 名称 | 链接 | 说明 |
|------|------|------|
| **kepano/obsidian-skills** | [GitHub](https://github.com/kepano/obsidian-skills) ⭐7.7k | Obsidian CEO 开发 |

包含 3 个 skill：
- `obsidian-markdown` - Wikilinks、Callouts、Properties 等
- `obsidian-bases` - .base 文件的 Filters、Formulas、Views
- `json-canvas` - .canvas 文件的 Nodes、Edges、Groups

### 🚀 开发相关

| 名称 | 链接 | 说明 |
|------|------|------|
| **vercel-labs/agent-skills** | [GitHub](https://github.com/vercel-labs/agent-skills) | Vercel 部署、设计审计 |
| **automata-network/agent-skills** | [GitHub](https://github.com/automata-network/agent-skills) | Claude/Codex 通用 |

### 🎯 精选合集

| 名称 | 链接 | 说明 |
|------|------|------|
| **Nymbo/Skills** | [GitHub](https://github.com/Nymbo/Skills) | 精选高质量 skills |

---

## 🔗 本地相关

- [[Skill Demo/项目笔记示例]] - Obsidian Markdown 示例
- [[Skill Demo/任务追踪.base]] - Obsidian Bases 示例  
- [[Skill Demo/项目规划.canvas]] - JSON Canvas 示例

---

*最后更新: 2026-01-22*
