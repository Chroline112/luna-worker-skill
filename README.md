# Luna Worker Skill

一个用于在 Codex 中部署或更新 `luna_worker` 自定义子 Agent 的 Skill。部署提示词定义了子 Agent 的任务边界、主 Agent 的委派规则和验证步骤。默认配置为 `gpt-6.1-terra` / `medium`，请在部署前确认当前 Codex 版本和账户支持该配置。

## 安装与使用

1. 克隆或下载此仓库，将 `luna-worker` 子目录完整放入 `~/.agents/skills/`，或放入目标项目的 `.agents/skills/`。
2. 在 Codex 中调用 `$luna-worker`，明确说明要部署或更新个人级子 Agent。只想阅读部署流程时，可直接查看[部署提示词](luna-worker/references/luna-worker-prompt.md)。
3. 部署成功后，开一个新会话验证。可用一个小型只读任务试用，例如请 `luna_worker` 查找指定目录中的测试入口并返回文件路径。

部署涉及 Codex 个人配置和个人级 `AGENTS.md`。先阅读部署提示词并确认修改范围，再授权执行。
