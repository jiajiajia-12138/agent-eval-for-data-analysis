# agent-eval-for-data-analysis
An executable evaluation framework for data-analysis agents
# Agent Eval for Data Analysis

本项目面向“数据分析场景下的 Agent”，设计一套可执行的评测框架，用于比较不同 Agent 在真实数据分析任务上的表现。

框架包含四个部分：
1. 题集：覆盖取数、清洗、指标计算、归因分析等典型任务；
2. 可执行验证器：用确定性检查判断 Agent 输出是否正确；
3. 复杂度分层：按任务难度分层，避免只测简单题；
4. 多 Agent 对比：引入 cost-of-pass 与失败模式分析。

目标：让“Agent 能不能做数据分析”这件事，从主观感受变成可复现的评测结果。
