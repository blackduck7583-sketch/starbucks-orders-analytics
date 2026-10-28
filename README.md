# 星巴克订单探索性数据分析

本项目分析 10 万条星巴克订单，重点探索订单特征、顾客特征与满意度之间的关系。Notebook 包含数据加载与初步认识、探索性数据分析，以及基于参考 Notebook 第三章的统计分析拓展（描述统计、异常值、相关性、统计检验）。不包含特征工程或预测建模。

## 文件

- `starbucks-orders-analytics.ipynb` — 中文分析 Notebook，包含已保存的图表和输出。

## 数据集

使用公开的 [Starbucks Customer Ordering Patterns 数据集](https://www.kaggle.com/datasets/likithagedipudi/starbucks-customer-ordering-patterns)。在 Kaggle 中将数据集添加为 Notebook 输入；在本地运行时，将 `starbucks_customer_ordering_patterns.csv` 放在 Notebook 同目录。

## 运行环境

Python 3，依赖 pandas、NumPy、Matplotlib、Seaborn 和 SciPy。可在 Kaggle 或 Jupyter 中打开并运行所有单元格。

## 参考

参考并改编自 [Starbucks Orders: What Your Coffee Says About You](https://www.kaggle.com/code/seki32/starbucks-orders-what-your-coffee-says-about-you)。

