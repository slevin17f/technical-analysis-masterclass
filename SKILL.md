---
name: technical-analysis-masterclass
description: |
  用 Schlotmann 与 Czubatinski《Trading: Technical Analysis Masterclass》的方法复盘历史 K 线或 OHLC，解释波段、图表形态、支撑阻力、供需区、突破陷阱及技术指标。适用于读图练习和已有图表分析的复核。
metadata:
  cangjie.generated-by: cangjie-tools v2.5.0
  cangjie.variant: single
  cangjie.bundle-id: bundle.technical-analysis-masterclass
  cangjie.capability-count: 9
  cangjie.entrypoint-count: 1
---
# Trading: Technical Analysis Masterclass — 全书能力入口

## 触发与不触发

**适用**：与本书能力域相关的咨询与任务（见下方路由表的意图列）。
**不适用**：
- 实时交易指令、盈利概率估计和账户仓位计算。

## 核心原则（常驻速览，概览类问题读到这里即可回答）

1. 按用户的问题读对应卡。整图复盘先记品种、周期和最后一根已收盘 K 线，再依次检查波段、关键位、局部形态和指标。
2. 逐项指出图中时点或价位。区分可见事实、作者框架下的解释及下一根或后续波段需要验证的条件。右侧价格只在回放到该时点后使用。
3. 第 7.1 节按动量、趋势、波动分组。先写指标要回答的具体问题。RSI 与随机指标同源，MACD 零轴与对应 EMA 交叉等价，重复证据只记一次。
4. 输出市场阶段与依据、候选解释、相反证据、确认或失效条件、尚缺输入。局部问题只输出相关字段。

## 能力路由（先读本表，按意图加载 1 张能力卡）

| 用户意图 | 先读 | 补读/备注 |
|---|---|---|
| 从 OHLC 比较实体、影线、比例和实体位置，判断拒绝的方向与背景 | references/capabilities/candle.md | references/capabilities/levels.md、references/capabilities/wave.md |
| 用推进、回撤和摆动高低点解释趋势是否仍完整 | references/capabilities/wave.md | references/capabilities/pattern.md |
| 用波段、颈线或整理边界检验头肩、杯柄、三角、楔形和多重顶底 | references/capabilities/pattern.md | references/capabilities/wave.md、references/capabilities/traps.md |
| 核对锚点、触碰反应和角色互换，标出水平区与斜线的有效边界 | references/capabilities/levels.md | references/capabilities/wave.md、references/capabilities/zones.md |
| 核对离开前的窄幅停顿、离开的力度及首次回访表现 | references/capabilities/zones.md | references/capabilities/levels.md、references/capabilities/traps.md |
| 逐根回放刺穿、收盘和后续结构，判断哪一侧的突破失去支持 | references/capabilities/traps.md | references/capabilities/levels.md、references/capabilities/candle.md |
| 选取 SMA 或 EMA 的周期，审阅斜率、交叉、动态支阻及价格偏离 | references/capabilities/averages.md | references/capabilities/wave.md、references/capabilities/bands-macd.md |
| 辨认极值、背离与区间收盘位置，追踪价格确认 | references/capabilities/oscillators.md | references/capabilities/wave.md、references/capabilities/levels.md |
| 区分沿轨、拒绝和动能衰减，核对零轴及信号线交叉的含义 | references/capabilities/bands-macd.md | references/capabilities/averages.md、references/capabilities/wave.md |

**非能力类查询**：
- 书名/作者/章节/整书概览 → references/overview.md
- 术语解释 → references/glossary.md
- 决策规则速查（不需要原文依据时） → references/cheatsheet.md
- 完整意图与关键词索引（本表未覆盖的意图先查这里） → references/capability-index.md

## 加载规则

- 每次任务先读本文件，再按路由表加载 **1** 张能力卡；任务明确跨域时最多加载 2 张。
- 概览/书名类问题不加载能力卡，用「核心原则」与 overview.md 回答。
- 路由表与 capability-index.md 都无法命中的意图，明确告知超出本书范围，不要硬套。

## 边界与判停

- 图表被截断或价格不可读时，写明仍可辨认的现象和需要补充的数据。涉及盘中 K 线时冻结收盘确认。
