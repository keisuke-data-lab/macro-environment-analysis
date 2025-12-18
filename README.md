# Macro Environment Analysis & University Management Simulation
**マクロ環境分析と大学経営シミュレーション（2040年問題への対応）**

## 📌 Project Overview
日本の「18歳人口減少（2040年問題）」という不可逆的なマクロ環境の変化が、大学経営の財務基盤に与えるインパクトを定量化した分析プロジェクトです。
公開統計データに基づく人口予測と、損益分岐点分析（CVP分析）を組み合わせ、定員割れリスクと財務赤字の発生タイミングをシミュレーションしました。

## 📊 Key Visuals

### 1. 「2040年問題」の可視化 (The 2040 Problem)
18歳人口（青線）が大学収容力（赤点線）を下回り、「供給過剰（定員割れエリア）」が拡大していく様子を可視化。
市場縮小が確実な環境下での生存戦略の必要性を提示しています。
![Population Trend](images/macro_population_trend.png)

### 2. 財務インパクト・シミュレーション (Financial Projection)
学生数減少に伴う「授業料収入の減少」と「固定費の硬直性」による財務悪化を予測。
現状維持の経営を続けた場合、いつ「赤字（Red Bar）」に転落するかを特定し、早期のコスト構造改革（固定費削減・収益源多様化）を提言する根拠としています。
![Financial Impact](images/financial_impact_simulation.png)

## 🛠 Tech Stack
- **Language**: Python 3.12
- **Libraries**: NumPy, Pandas, Matplotlib, Seaborn
- **Data Source**: Synthetic Data based on Japanese Demographics (e-Stat trends)

## 📂 Directory Structure
```text
.
├── university_financial_loss_simulation.ipynb  # Main Analysis Notebook
├── generate_macro_visuals.py                   # Visualization Script
├── docs/                                       # Strategic Reports (PDF)
└── images/                                     # Output Charts
