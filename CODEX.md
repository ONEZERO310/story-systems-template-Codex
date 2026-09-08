# Codex 适配说明

本仓库是 story-systems-template-Codex，与原仓库分开维护。原有故事系统、Agent 角色、命令、Skill、模板和 CLI 约定保持不变；Codex 侧使用根目录 AGENTS.md 作为项目入口，并按本项目实际运行环境读取 codex/ 或 .codex/ 下的资源副本。

- 不修改剧本创作方法、质量门禁、Agent 分工和导出约定。
- 需要调用角色时，在 Codex 主线程中按 AGENTS.md 的角色说明组织任务；需要并行视角时使用 Codex 子Agent。
- 原 codex/、AGENTS.md 文件保留作历史/兼容参考，不作为本 Codex 版入口。
