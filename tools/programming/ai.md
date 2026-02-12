---
title: AI 编程工具整理
---

## Antigravity

Google 推出的 AI IDE，基于 Gemini 3。

- [官网](https://developers.google.com/idx/antigravity)[]()

### 安装

```bash
brew install --cask antigravity
```

---

### [Antigravity kit](https://github.com/vudovn/antigravity-kit/)



## OpenCode

- [官网](https://opencode.ai/)
- [GitHub](https://github.com/anomalyco/opencode)

### 安装

```bash
curl -fsSL https://opencode.ai/install | bash
```


## Oh My OpenCode

基于 OpenCode 的“编排层”插件：多 Agent 调度、Hooks、MCP、LSP 等。

- [官网](https://ohmyopencode.com/)
- [安装说明](https://ohmyopencode.com/installation/)
- [GitHub](https://github.com/code-yeongyu/oh-my-opencode)

### 安装方式

```bash
bunx oh-my-opencode install
```


##  opencode-antigravity-auth

作用：让 OpenCode 通过 OAuth 使用 **Google Antigravity** 的额度，白嫖 Gemini 3 / Claude 等模型。

- [GitHub](https://github.com/NoeFabris/opencode-antigravity-auth)  

### 执行 OAuth 登录

```bash
opencode auth login
```

---

##  Antigravity-Manager

作用：专业的 Antigravity 账号管理与一键切换 + 协议中转（OpenAI / Anthropic / Gemini），做本地 AI 网关。

- [GitHub](https://github.com/lbjlaq/Antigravity-Manager)：  

### 安装

```bash
# 1. 添加 Tap
brew tap lbjlaq/antigravity-manager https://github.com/lbjlaq/Antigravity-Manager

# 2. 安装应用
brew install --cask antigravity-tools
# 如遇安全限制可用：
# brew install --cask --no-quarantine antigravity-tools
```

##  quotio

- [Github](https://github.com/nguyenphutrong/quotio)

## HAPI

* [Github](https://github.com/tiann/hapi)

## happy

* [Github](https://github.com/slopus/happy)

## CodexBar

- [GitHub](https://github.com/steipete/CodexBar)

## agmente

- [GitHub](https://github.com/rebornix/agmente)
