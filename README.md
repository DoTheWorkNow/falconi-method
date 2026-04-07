# Falconi Method

基于 Vicente Falconi《True Power》的管理方法论 Skill，适用于 [Claude Code](https://docs.anthropic.com/en/docs/claude-code)。

## 核心理念

管理的本质只有一件事：**持续识别并缩小现状与目标之间的差距**。

## 功能覆盖

| 场景 | 参考文件 |
|---|---|
| 业务问题诊断 | `references/analysis-framework.md` |
| 改进计划制定 | `references/improvement-execution.md` |
| 管理咨询与组织设计 | `references/management-system.md` |
| 稳定化与知识管理 | `references/stabilization-knowledge.md` |

## 方法论要点

- **差距分析** — Gap = 理想状态 - 当前状态
- **SDCA/PDCA 循环** — 先稳定，再改进
- **四因分析** — 目标缺失、分析不足、执行不力、不可控因素
- **成功三角** — 领导力 × 专业知识 × 方法论

## 安装

```bash
# 符号链接到 Claude Code skills 目录
ln -s /path/to/falconi-method ~/.claude/skills/falconi-method
```

## 使用

在 Claude Code 中输入 `/falconi-method` 即可激活。适用于业务差距分析、PDCA 改进、目标分解、日常管理等场景。

## 许可

MIT
