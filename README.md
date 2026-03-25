# A股信号 `a-share-signal`

`a-share-signal`是一个用于分析A股交易机会的Skill，聚焦结构化判断与可执行结论输出。本Skill中涉及的理论方法，来自一名作者线下认识的游资，其在妖股捕捉方面有极强的实战经验。

> 相关内容仅用于研究交流与策略参考，不构成任何投资建议。

## 功能简介

- 基于筹码分布、三周期共振、优化KDJ、威科夫与缠论等框架分析A股
- 适合将近期行情数据快速整理为更清晰的交易决策参考

## 适用场景

- 判断当前是否具备参与条件
- 检查多周期结构是否共振
- 评估突破、放量、金叉等信号质量
- 识别筹码结构、主力洗盘 / 出货倾向与阶段状态
- 在结构成立前提下给出条件性目标价参考

## 数据来源

推荐优先安装并配置`mx-skills`，以便更方便地获取个股行情、财务、公告、研报等数据；如没有配置，会回退其他开源数据源如`akshare`或`baoshare`；必要时也能结合本地数据接口完成分析。

> [`mx-skills`官网](https://ai.eastmoney.com/mxClaw)

## 兼容性

本Skill兼容主流Agent生态，包括但不限于：

- OpenClaw
 > ClawHub: [byronwang2005/a-share-signal](https://clawhub.ai/byronwang2005/a-share-signal)（同步可能滞后）
- Claude Code
- Codex
- OpenCode
