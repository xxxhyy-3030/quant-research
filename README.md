# 量化研究作品集

本仓库整理了若干量化金融研究项目，覆盖资产定价、因子研究、时间序列建模和价值投资策略复现。项目主要以 Jupyter Notebook 形式呈现，重点展示数据清洗、模型构建、回测评估、统计检验和结果可视化能力。

## 项目列表

| 项目 | 主题 | 主要能力 |
|---|---|---|
| `beta-estimation` | CAPM Beta 估计与横截面 Beta 分析 | 回归建模、滚动估计、行业聚合、风险暴露分析 |
| `factor-research` | PE 单因子检验与 Fama-French 因子复现 | 分组回测、因子构建、多因子回归、Newey-West 检验 |
| `time-series` | 跨市场波动溢出与指数预测 | VECM、GARCH、ARIMA/SARIMA、IRF、FEVD、预测评估 |
| `value-investing` | Steve Loughran 价值选股策略复现 | 财务数据清洗、财报滞后处理、股票池构建、组合回测、可视化 |

## 目录结构

```text
.
├── beta-estimation/
├── factor-research/
├── time-series/
├── value-investing/
├── DATA.md
├── requirements.txt
└── README.md
```

## 数据说明

原始行情、财务、行业分类和研报文件未包含在仓库中。这些数据可能来自 CSMAR、Wind、iFinD、RESSET 等授权数据库，或来自有版权限制的研究报告。

Notebook 中保留了研究逻辑和部分结果展示。如需重新运行，请根据自己的本地数据路径进行调整。详细说明见 `DATA.md`。

## 环境依赖

项目使用 Python 及常见量化研究库，包括 pandas、numpy、statsmodels、scipy、plotnine、matplotlib、arch、pmdarima 等。可使用以下命令安装建议依赖：

```bash
pip install -r requirements.txt
```

## 作品集定位

这些项目是研究型 Notebook，不是生产级交易系统。它们主要用于展示：

- 金融数据清洗与时点处理；
- 因子构建与分组回测；
- 回归模型与统计检验；
- 时间序列建模与模型诊断；
- 策略回测与结果可视化；
- 复现结果与参考文献或研报结果的差异分析。
