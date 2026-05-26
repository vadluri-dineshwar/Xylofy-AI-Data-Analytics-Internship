# Vanguard // Real-Time Fraud Operations Engine with Explainable AI
### Xylofy AI Capstone Project — Production-Grade Risk Engine Portfolio
**Author:** Vadluri Dineswar  
**Role:** Machine Learning Engineer & Data Analyst Intern  
[cite_start]**Date:** May 2026 [cite: 5, 6, 8]

---

## 📘 Project Overview & Business Architecture
[cite_start]Financial fraud costs the global economy over $5 trillion annually[cite: 10]. [cite_start]Legacy rule-based infrastructure misses novel attack patterns, while basic machine learning models remain untrustworthy "black boxes" for compliance teams[cite: 12]. [cite_start]This system bridges the gap by delivering an end-to-end, production-grade risk mitigation pipeline engineered to process large-scale financial records, isolate structural transaction imbalances, train optimized gradient-boosted ensembles, and provide transparent regulatory audit trails via game-theoretic Shapley additive valuations[cite: 13].



---

## 🚀 Active Project Capabilities

* [cite_start]**Unified Relational Pipeline:** Processes and merges transactional registries with identity profiles on common `TransactionID` variables[cite: 26, 35].
* [cite_start]**Outlier Defenses:** Implements `RobustScaler` arrays using medians and Interquartile Ranges (IQR) to safeguard continuous numerical metrics from extreme spend variance[cite: 50].
* [cite_start]**Data Contamination Prevention:** Enforces strict stratified train-test splits before running over-sampling arrays (SMOTE) to ensure no evaluation data leakage occurs[cite: 49, 51].
* [cite_start]**Bayesian Optimization Framework:** Automates hyperparameter search grids using Optuna to directly maximize our critical Precision-Recall Area Under the Curve (PR-AUC)[cite: 65, 74].
* [cite_start]**Transparent Auditing Logs:** Harnesses TreeSHAP metrics to translate complex tree models into accessible, plain-English operational justifications[cite: 13, 80, 86].

---

## 📊 Technical Performance Benchmark Ledger

[cite_start]Through our Optuna-guided hyperparameter searches, our models achieved the following performance metrics on the unified testing partition[cite: 53, 72]:

* **Baseline XGBoost Framework (Champion):** **0.6274 PR-AUC** | **97.10% Accuracy** | [cite_start]**80.20% Recall** [cite: 57, 60, 62, 65]
* **Tuned LightGBM Model:** **0.5308 PR-AUC** | **96.40% Accuracy** | [cite_start]**76.50% Recall** [cite: 56, 60, 62, 65]
* **Unsupervised Isolation Forest:** **0.0910 PR-AUC** | **96.50% Accuracy** | [cite_start]**43.60% Recall** [cite: 58, 60, 62, 65]
* [cite_start]**Operational Decision Threshold Locked at:** **0.3594** (Optimized via the Threshold vs. F1-Score plot to maximize true detection boundaries while minimizing customer decline friction).

---

## 👔 Executive Business & Consulting ROI Insights

* [cite_start]**Why PR-AUC Over Accuracy:** In a severely skewed 3.5% fraud tracking environment, a broken model can predict "Clear" for everything to score a misleading 96.5% accuracy rate while leaking 100% of incoming threats[cite: 11, 30, 60, 138]. [cite_start]PR-AUC evaluates true positives directly against false positives, making it the only trustworthy diagnostic metric for highly imbalanced portfolios[cite: 138].
* [cite_start]**Top 3 Fraud Signals Identified by SHAP:** Game-theoretic metrics highlighted `DayOfWeek/HourOfDay` temporal cycles, categorical payment card profiles (`card6/card2`), and transactional velocity patterns (`C14/C1`) as the primary drivers of risk acceleration across our data streams[cite: 139].
* **Estimated Money Saved Annually:** Our pipeline scales structural recall to intercept high-risk attacks, lowering customer friction to drop false decline rates down to 1.20%. [cite_start]Compared to legacy infrastructure, this yields an estimated **$120,400,000 in annual core capital preserved**[cite: 12, 142].

---

## 🛠️ Step-by-Step Local Deployment Setup

1. **Clone the repository directory layout:**
   ```bash
   git clone [https://github.com/vadluri-Dineshwar/FraudDetection_Vadluri_Dineshwar.git](https://github.com/Vadluri-Dineshwar/FraudDetection_Vadluri_Dineshwar.git)
   cd FraudDetection_Vadluri_Dineshwar

2. Initialize active environment layers and mount system prerequisites:

    python -m venv venv
    venv\Scripts\activate
    pip install -r requirements.txt

3. Boot up your live user terminal layout panel locally:
    streamlit run dashboard/app.py

Developed as a portfolio centerpiece by Vadluri Dineshwar for the Xylofy AI Advanced Capstone Evaluation Board.

---

### 🚨 What to do right now:
1. Open your local **`README.md`** file in VS Code or Notepad.
2. Scroll to the very bottom.
3. Paste that clean text block above, save the file, and close it.
