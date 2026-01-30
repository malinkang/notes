# Agent Skills 文档更新

本次任务主要完善了关于 AI Agent Skills 的知识库文档。

## 变更内容

### 1. 新增与更新文档
*   **`tools/programming/skill.md`**: 
    *   新增了 Agent Skills 的详细介绍、官网及规范文档链接。
    *   添加了详细的安装指南，包括 CLI 工具 (`skills`) 的安装和插件的安装（强调了使用 `-a` 参数避免污染项目）。
    *   对比了 `skills.sh` 和 `openskills` 的区别。
    *   收录了常用的 Skill 推荐（如 `obsidian-skills`）及市场链接。
*   **`tools/programming/index.md`**: 进行了格式微调。
*   **`index.md`**: 移除了临时的 SQL 语句和无关链接。
*   **`tools/network/proxy.md`**: 增加了 ClashX.Meta 的相关链接。

### 2. 系统清理
*   清理了项目根目录下由 `skills` CLI 自动生成的多个冗余配置文件夹（如 `.cursor`, `.agent`, `.claude` 等），只建议按需生成。
