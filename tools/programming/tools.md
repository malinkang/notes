# AI 编程工具整理


## OpenCode

- [官网](https://opencode.ai/)
- [GitHub](https://github.com/anomalyco/opencode)

### 安装

```bash
curl -fsSL https://opencode.ai/install | bash
```


---

## Oh My OpenCode

基于 OpenCode 的“编排层”插件：多 Agent 调度、Hooks、MCP、LSP 等。

- [官网](https://ohmyopencode.com/)
- [安装说明](https://ohmyopencode.com/installation/)
- GitHub：从官网 “View on GitHub” 进入（保持以官网为主入口）

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
