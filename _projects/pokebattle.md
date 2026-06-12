---
title: "PokeBattle Insight / 宝可梦数据分析与对战评估"
collection: projects
date: 2026-05-27
url: "https://github.com/zzXavier/PokeBattle"
description: "A Pokemon analytics platform featuring data cleaning, statistical analysis, visualization, and machine-learning-based battle evaluation."
---

PokeBattle Insight is a full-stack Pokemon analytics and battle evaluation platform. I built a data workflow that transforms raw Pokemon records into structured, queryable features and presents the results through an interactive analytics dashboard.

PokeBattle Insight 是一个全栈宝可梦数据分析与对战评估平台。我参与构建了从原始数据清洗、结构化处理到统计分析和交互式展示的完整数据流程。

## Data Processing and Analysis / 数据处理与分析

- Cleaned and normalized Pokemon attributes with pandas and NumPy, including missing values, numeric fields, types, generations, and battle statistics.
- Performed grouped aggregation, ranking, distribution analysis, correlation analysis, and multidimensional stat comparison.
- Designed dashboard views for type strength, generation distribution, strongest Pokemon rankings, scatterplots, and six-stat correlation heatmaps.
- Built reusable FastAPI endpoints for filtering, querying, evaluating, and presenting analytical results.

- 使用 pandas 和 NumPy 清洗并标准化宝可梦属性，包括缺失值、数值字段、属性、世代和战斗数据。
- 完成分组聚合、排名、分布分析、相关性分析和多维能力值比较。
- 设计属性强度、世代分布、强度排名、散点图和六维能力相关性热力图等分析视图。
- 使用 FastAPI 封装筛选、查询、评估和分析结果接口。

## Modeling / 建模能力

- Trained a Random Forest classifier to estimate legendary potential from battle-stat profiles.
- Applied K-Means clustering to identify battle-role patterns.
- Implemented normalized Euclidean-distance matching to find Pokemon with similar stat structures.

- 使用随机森林根据能力值特征预测传说宝可梦潜力。
- 使用 K-Means 聚类识别不同战斗定位。
- 使用归一化欧氏距离匹配能力结构最相似的宝可梦。

## Tech Stack / 技术栈

- Python, pandas, NumPy, scikit-learn
- FastAPI, SQLite
- React, Vite
- Statistical analysis and data visualization

## Repository / 仓库

[View on GitHub](https://github.com/zzXavier/PokeBattle)
