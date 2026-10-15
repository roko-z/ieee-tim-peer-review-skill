# 可复用审稿输出模板

## 中文审前核查稿（用于解释/内部讨论）

```markdown
# [编号] 审稿分析

**研究对象：** [实际测量对象]
**主要贡献：** [原文可证实的两项]
**初步建议：** Major Revision / Minor Revision / Reject（待核查）
**判断理由：** [一句话说明影响中心主张的证据缺口]

### 主要问题 1：[核心名词]
**原文依据：** [章节/公式/图/表、简短原句或关键数据]
**问题性质：** 已证实 / 需澄清 / 尚未验证
**审稿判断：** [为什么影响结论，不超出证据范围]
**建议修改：** [一至两项可执行动作；或收缩结论]
```

若用户希望最通俗的解释，再添加“基础原理”和“举例”，不加入正式英文投稿稿件。

## 正式英文 Reviewer Comments（默认 6–9 条）

```markdown
Reviewer Comments

This manuscript investigates [measurement objective] using [core approach] and reports [two verified strengths].
The study is relevant to instrumentation and measurement; however, [two-to-three central evidence gaps] should be addressed before the claims can be adequately assessed.

Comment #1
[Specific text/equation/table claim]. [Reason this is insufficient, ambiguous, or condition-dependent]. Please [one focused, implementable action]. [If appropriate: otherwise qualify the claim].

Comment #2
...
```

**英文写作要求**：平实自然、可直接发给作者、避免冗长自我表述和高强度命令；每条尽量 3–5 句，技术复杂者酌情延长。整体评价肯定已完成的工作。审稿决定如果系统有单独框可不在面向作者的段落直接写，私下编辑意见另述。

## R1/R2 答复有效性矩阵

| 旧评论 | 作者回应及新增数据 | 原文新位置 | 解决状态 | 本轮必要问题 |
|---|---|---|---|---|
| 例：要求交叉验证 | 增加分层五折 CV | 方法和结果章节 | 部分解决 | 仍缺跨批次验证，不再说“没做 CV” |

## 审稿意见精简准则

把“一个主张的多个侧面”整合成一条；例如：
- 零截距系数、留一工况、跨平台部署 → 标定独立性与适用范围；
- 参考标准、重复样本、置信区间 → 测量不确定度与统计可靠性；
- 基线调参、比较口径、某些工况不佳 → 比较公平性与结论限定。

不为缩减数量而把完全不相关的要求硬拼成一条。
