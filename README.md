# End-to-End-Insurance-Risk-Analytics-Predictive-Modeling-w3
Overview

This project analyzes an automotive insurance dataset to understand portfolio behavior, assess risk, and establish a reproducible data pipeline.
It includes:
Task 1: Exploratory Data Analysis (EDA)
Task 2: Data Version Control (DVC) setup

Task 1 — Exploratory Data Analysis
Key Steps
- Data cleaning (duplicates, missing values, type checks)
- Summary statistics of key financial features
- Loss Ratio analysis:
- Overall portfolio LR ≈ 1.05
- Segmented by Province, Gender, VehicleType
- Outlier detection for claims/premiums
- Trend checks across TransactionMonth

Generated Visuals
- Loss Ratio by Province
- Loss Ratio by Gender

Insights (Brief)
- Gauteng, KZN, and Western Cape show the highest risk.
- Female policyholders have lower loss ratios.
- Certain commercial/mobility vehicle types drive higher claims.

Task 2 — Data Version Control (DVC) Setup

- Initialized DVC in project directory
- Configured local remote storage
- Tracked dataset with dvc add
- Version metadata committed to Git
- Data pushed to remote via dvc push

Reproducibility

git clone <repo-url>
dvc pull
Restores the exact dataset used for the analysis.

 Tech Stack

- Python (Pandas, NumPy, Matplotlib/Seaborn)
- Git & GitHub
- DVC (local remote storage)

Next Steps

- Feature engineering
- Risk modeling
- Prediction

✔ Status

Tasks 1 and 2 completed.
