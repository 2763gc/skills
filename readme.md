# Shared Skills

跨工具共享的 AI Skills 库。AutoClaw、Claude Code、Codex 等工具共用。

## 使用方式

### AutoClaw
将本仓库 clone 到 skills 目录，或在配置中指向本仓库路径。

### Claude Code
在 `.claude/CLAUDE.md` 中添加：
```
参考 shared-skills 目录下的 SKILL.md 文件获取可用技能。
```

### Codex
在 `AGENTS.md` 中引用本仓库路径。

## Skills 列表

| Skill | 说明 | 路径 |
|---|---|---|
| security-auditor | 安全审计 | `security-auditor/SKILL.md` |
| code | 编程辅助 | `code/SKILL.md` |
| seo | SEO 优化 | `seo/SKILL.md` |
| ui-ux-pro-max | UI/UX 设计 | `ui-ux-pro-max/SKILL.md` |

## 添加新 Skill

1. 在根目录创建新文件夹
2. 添加 `SKILL.md`（核心指令，给 AI 看的）
3. 可选：添加 `manifest.yaml` 声明元数据
4. 更新本 README 的列表

## Skill 目录结构

```
skill-name/
├── SKILL.md          # 核心指令（必须）
├── manifest.yaml     # 元数据（可选）
├── templates/        # 模板文件（可选）
└── examples/         # 示例（可选）
```
