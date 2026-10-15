# Evidence-Driven Peer Review Skill for Instrumentation & Measurement

一套面向仪器测量、传感器和信号处理论文的证据驱动审稿 Skill。适用于论文初审、返修稿核查、Reviewer Comments 起草、中文讲解和现有 Word 审稿意见的保格式修订。

> **非 IEEE 官方项目，亦不代表 IEEE 或任何期刊的审稿政策。**

## 文件结构

- `SKILL.md` — 主规则与分步审稿流程
- `references/decision-rubric.md` — 大修、小修及证据强度判定
- `references/domain-checklists.md` — 通用计量、阵列流量、电化学检测、可穿戴监测等专项清单
- `references/output-templates.md` — 中英文审稿及返修核查模板
- `references/sample-evidence-ledger.md` — 完全虚构的证据卡示例

## 安装与使用

将整个仓库复制到支持 Agent Skills 的工具的技能目录。例如在兼容 `.agents/skills/` 约定的项目中：

```text
.agents/skills/ieee-tim-peer-review/
  SKILL.md
  references/
```

然后提供有权处理的论文材料，并要求助手“按照 evidence-driven peer review skill，先核查证据，再提出审稿意见”。不同工具的技能安装步骤可能有所不同。

## 核心原则

- 核实原文证据，不把未经验证的推测当成事实。
- 承认作者已经完成的实验、交叉验证及返修工作。
- 重视校准、量纲、不确定度、独立验证和对照公平性。
- 不机械追求评论数量，优先提供可执行、符合论文定位的建议。
- 尊重审稿保密义务与各期刊的 AI 使用政策。**请勿公开上传未获授权的投稿稿件、审稿回复或审稿意见。**

## License

MIT License，详见 [LICENSE](LICENSE)。
