# Falconi Method

基于 Vicente Falconi Campos 所著《True Power》（中文版《法尔科尼管理方法：引领企业成长的真正力量》，华夏出版社 2018）的管理方法论 Skill，适用于 [Claude Code](https://docs.anthropic.com/en/docs/claude-code)。

## 核心理念

管理的本质只有一件事：**持续识别并缩小现状与目标之间的差距**。

## 功能覆盖

| 场景 | 参考文件 | 对应章节 |
|---|---|---|
| 管理体系、组织设计、目标分解、战略部署 | `references/management-system.md` | Ch1, Ch3, Ch4, Ch7 |
| 领导力、人才发展、知识获取、激励 | `references/leadership-knowledge.md` | Ch2, Ch10 |
| 业务问题诊断、根因分析、系统思维 | `references/analysis-framework.md` | Ch5, Ch6 |
| 改进计划、PDCA 执行、成本/收入优化 | `references/improvement-execution.md` | Ch8 |
| 稳定化、日常管理、SDCA、标准化 | `references/stabilization-daily.md` | Ch9, 结语 |

## 方法论要点

- **差距分析** — Gap = 理想状态 - 当前状态
- **SDCA/PDCA 循环** — 先稳定，再改进
- **四因分析** — 目标缺失、分析不足、执行不力、不可控因素
- **成功三角** — 领导力 × 专业知识 × 方法论

## 核心能力

| 场景 | 我能做什么 |
|---|---|
| **诊断业务问题** | 用差距分析、根因分析（四大失败原因框架）、Rummler 3x3 矩阵等工具，帮你定位绩效下滑、质量问题、成本超支的根本原因 |
| **制定改善计划** | 用 PDCA 循环设计行动方案——降本、增收、战略部署，附带可执行的具体步骤 |
| **管理咨询 / 组织设计** | 分析领导力、组织架构、目标分解、战略展开等问题，提供系统性建议 |
| **标准化与稳定** | 用 SDCA 循环巩固成果、建立日常管理例程、防止问题反弹 |

### 核心方法论

- **差距思维**：管理的本质 = 持续缩小「现状」与「目标」之间的差距
- **SDCA → PDCA**：先稳定（标准化），再改善
- **成功三角**：领导力 × 专业知识 × 方法，三者缺一不可
- **四大利益相关方**：股东、客户、员工、社会

### 使用示例

直接在 Claude Code 中描述你的业务问题或管理挑战即可：

- "我们部门客户投诉率上升了 30%，帮我分析"
- "帮我制定一个降低生产成本 15% 的改善计划"
- "我们的战略目标总是落不了地，怎么改进管理体系"
- "团队刚完成一轮改善，如何防止成果回退"

## 安装

```bash
# 符号链接到 Claude Code skills 目录
ln -s /path/to/falconi-method ~/.claude/skills/falconi-method
```

## 使用

在 Claude Code 中输入 `/falconi-method` 即可激活。适用于业务差距分析、PDCA 改进、目标分解、日常管理等场景。

## 许可

MIT
