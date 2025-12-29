Financial Health Prediction Challenge – Zindi
📌 Overview

This repository contains my solution for the data.org Financial Health Prediction Challenge hosted on Zindi.
The objective of the competition is to predict the Financial Health Index (FHI) of small and medium-sized enterprises (SMEs) across Southern Africa.

The Financial Health Index categorizes businesses into:

Low

Medium

High

based on a holistic assessment of:

Savings and assets

Debt and repayment capacity

Resilience to shocks

Access to credit and financial services

This solution uses machine learning techniques to model SME financial well-being using socio-economic and business-level survey data.

🏆 Competition Details

Platform: Zindi

Challenge: data.org Financial Health Prediction Challenge

Countries Covered: Eswatini, Lesotho, Malawi, Zimbabwe

Evaluation Metric: F1 Score

Prize Pool: $1,500 USD

Status: Active

🎯 Objective

Build a multi-class classification model to predict the Financial Health Index (FHI) of SMEs using structured tabular data such as:

Business size and demographics

Trade activity (imports/exports, commodities)

Financial access indicators

Geographic and country-level features

📊 Model Performance

Validation / Public Leaderboard Score:
F1 Score ≈ 0.895

This score was achieved without data leakage and using only the datasets provided by the competition, in compliance with Zindi rules.

🧠 Approach
1. Data Preprocessing

Handling missing values

Encoding categorical variables

Feature scaling (where required)

Train-validation split with stratification

2. Feature Engineering

Derived financial ratios and indicators

Country-level and sector-based aggregation features

Robust handling of categorical variables

3. Modeling

Traditional ML models suited for tabular data

Hyperparameter tuning using cross-validation

Class imbalance handling

Optimization for F1 score

4. Evaluation

Cross-validation F1 score

Public leaderboard validation

Consistent seed usage for reproducibility



📓 Notebook

The complete end-to-end solution is provided in the Jupyter Notebook:

Competition.ipynb


It includes:

Exploratory Data Analysis (EDA)

Feature engineering

Model training

Evaluation

Submission file generation

⚙️ Requirements

All tools and libraries used are open-source, as required by the competition rules.

Typical dependencies include:

Python 3.x

NumPy

Pandas

Scikit-learn

Matplotlib / Seaborn

(Exact versions can be added to requirements.txt if needed.)

📤 Submission Format

The final submission follows the required format:

ID	Target
ID_XXXXX	Low
ID_YYYYY	Medium
ID_ZZZZZ	High
🔒 Competition Compliance

✔ Used only competition-provided data
✔ No automated ML tools
✔ No external/private datasets
✔ Fully reproducible with fixed random seeds

🌍 Social Impact

This project contributes to:

Financial inclusion

Data-driven policymaking

SME resilience assessment

Responsible AI for social good

By predicting SME financial health, the model helps governments, financial institutions, and development partners better target support and financing.

✍️ Author

Harshal Kala
Data Science & Machine Learning Enthusiast

📜 License

This project follows the competition’s data license:
CC-BY-SA 4.0
