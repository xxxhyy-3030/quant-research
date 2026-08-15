# 因子研究

本目录包含两个因子研究项目：PE 单因子检验和 Fama-French 因子复现。

## Notebook

- `pe-factor-single-factor-test.ipynb`
- `replicating-fama-french-factors.ipynb`

## PE 单因子检验

该 Notebook 检验低 PE 股票相对于高 PE 股票是否具有更高收益表现，并构造低 PE 减高 PE 的零成本组合。

主要内容包括：

- 样本市值和 PE 分布概览；
- PE 分位数组合构建；
- 2001-2024 年年度分组收益检验；
- 低 PE 减高 PE 零成本组合；
- 等权和市值加权稳健性检验；
- CAPM 和 Fama-French 调整后的 Alpha 检验；
- Newey-West t 值计算。

## Fama-French 因子复现

该 Notebook 基于组合排序方法复现 Fama-French 核心因子。

主要内容包括：

- 三因子和五因子的排序变量构造；
- 股票组合划分；
- SMB、HML、盈利能力因子和投资因子构建；
- 因子复现效果检验；
- 研究结论总结。

## 展示能力

- 因子构建；
- 分组回测；
- 多空组合评估；
- 回归 Alpha 检验；
- 稳健标准误和统计显著性分析。

## 数据说明

原始财务、收益率和因子数据未包含在仓库中。
