# 📊 Financial Health Prediction Challenge (Zindi)

## Overview
This repository contains my complete machine learning solution for the **data.org Financial Health Prediction Challenge**, hosted on **Zindi**.  
The challenge focuses on predicting the **Financial Health Index (FHI)** of Small and Medium-Sized Enterprises (SMEs) using socio-economic and business survey data from Southern Africa.

The **Financial Health Index (FHI)** is a composite indicator that classifies SMEs into:
- **Low**
- **Medium**
- **High**

financial health categories, capturing resilience, savings behavior, debt exposure, and access to financial services.

---

## 🏆 Competition Information

| Item | Details |
|-----|--------|
| Platform | Zindi |
| Challenge | data.org Financial Health Prediction Challenge |
| Countries | Eswatini, Lesotho, Malawi, Zimbabwe |
| Evaluation Metric | **F1 Score** |
| Prize Pool | $1,500 USD |
| Problem Type | Multi-class Classification |
| Status | Ongoing |

---

## 🎯 Problem Statement
Traditional financial metrics such as profit or revenue do not fully capture the financial well-being of SMEs.  
This challenge introduces a holistic **Financial Health Index (FHI)** that evaluates SME stability across multiple dimensions.

The goal is to **build a machine learning model** that accurately predicts the FHI category of an SME using structured tabular data.

---

## 📈 Model Performance

- **Public Leaderboard F1 Score:** **0.895**

The model was trained and evaluated using best practices to avoid data leakage and ensure reproducibility.

---

## 🧠 Solution Approach

### 1️⃣ Data Preprocessing
- Handled missing values appropriately
- Encoded categorical variables
- Normalized / scaled numerical features where necessary
- Applied stratified train-validation split

### 2️⃣ Feature Engineering
- Created derived indicators from financial variables
- Aggregated country-level and sector-level features
- Reduced noise from sparse categorical features

### 3️⃣ Modeling
- Trained multiple machine learning models suitable for tabular data
- Tuned hyperparameters using cross-validation
- Optimized performance using **F1 score**
- Ensured class balance handling

### 4️⃣ Evaluation
- Cross-validation F1 score
- Public leaderboard evaluation
- Fixed random seeds for reproducibility

---
## 📓 Notebook Description

### `Competition.ipynb`
The notebook contains:
- Exploratory Data Analysis (EDA)
- Feature engineering
- Model training and tuning
- Evaluation metrics
- Submission file generation

All steps are documented within the notebook for clarity and reproducibility.

---

## ⚙️ Requirements

This project uses **only open-source libraries**, in compliance with Zindi rules.

Typical dependencies include:
- Python 3.x
- NumPy
- Pandas
- Scikit-learn
- Matplotlib / Seaborn

Install dependencies using:
```bash
pip install -r requirements.txt
📤 Submission Format
The final submission file follows the required format:

ID	Target
ID_XXXXXX	Low
ID_YYYYYY	Medium
ID_ZZZZZZ	High

🔒 Competition Compliance
✔ Only competition-provided data used
✔ No automated machine learning tools
✔ No external or private datasets
✔ Fully reproducible solution
✔ Fixed random seeds

🌍 Social Impact
This project supports:

Financial inclusion

SME resilience assessment

Data-driven policy design

Responsible AI for social good

Accurate prediction of SME financial health helps financial institutions, governments, and development partners allocate resources more effectively.

✍️ Author
Harshal Kala
Machine Learning & Data Science Practitioner

📜 License
This project adheres to the competition data license:
Creative Commons Attribution-ShareAlike 4.0 (CC-BY-SA 4.0)

⭐ Acknowledgements
data.org

FinMark Trust

Zindi

If you find this repository useful, feel free to ⭐ star it.
















