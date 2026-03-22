# A-Share Signal

`a-share-signal` 是一个用于分析A股交易机会的 Skill，默认优先使用 `mx-skills` 获取个股数据；如果当前环境没有相关 skills，则回退到 `AkShare/BaoShare`，再结合结构化交易框架对个股进行多维度研判并输出可执行结论。

## 功能简介

- 基于筹码分布、三周期共振、优化 KDJ、威科夫与缠论等框架分析 A 股
- 结合用户自定义评分规则，输出结构化判断、参与条件与应对方案
- 默认采用 `mx-skills -> AkShare/BaoShare` 的数据获取优先级
- 适合把近期行情数据快速转成更清晰的交易决策参考

## 数据源建议

推荐优先安装并配置 `mx-skills`，这样可以更方便地获取个股行情、财务、公告、研报等数据。

- 下载地址: [ai.eastmoney.com/mxClaw](https://ai.eastmoney.com/mxClaw)
- 使用顺序: `mx-skills` 优先，若未安装或无法覆盖所需字段，再回退到 `AkShare/BaoShare`

## 同步与开源

本仓库会随本人真实使用的 skills 库持续实时更新，并同步开源发布在：

- GitHub: [byronwang2005/a-share-signal](https://github.com/byronwang2005/a-share-signal)
- ClawHub: [clawhub.ai/byronwang2005/a-share-signal](https://clawhub.ai/byronwang2005/a-share-signal)

## 兼容性

本 Skill 兼容主流 Agent / Coding Agent 生态，包括但不限于：

- OpenClaw
- Claude Code
- Codex
- OpenCode

## 特色

本 Skill 中涉及的部分理论方法，完全来自一名作者线下真实认识的一线游资交易者，其在妖股捕捉方面有极强的实战经验。
>相关内容仅用于研究交流与策略参考，不构成任何投资建议。
