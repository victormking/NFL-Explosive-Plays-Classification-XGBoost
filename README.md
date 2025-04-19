# NFL Explosive Plays Classification with XGBoost

## 🎯 Project Summary

This project was completed as the final capstone for **SAL 613: Football Analytics Applications** at Syracuse University (Spring 2025). 

The goal was to **build a machine learning model to classify explosive plays** in the NFL — defined as pass plays gaining 13+ yards or rush plays gaining 10+ yards — using play-by-play data and Next Gen Stats (NGS) features.

Using a powerful gradient boosting classifier (XGBoost), we trained and evaluated a model to identify patterns behind explosiveness, optimize predictive performance, and analyze player-level, team-level, and personnel-level tendencies.

---

## 📁 Repository Structure

```plaintext
📦 NFL-Explosive-Plays-Classification-XGBoost
│
├── data/
│   ├── Step 1 to Step 14 folders
│   └── Raw + Cleaned datasets, engineered features, modeling inputs
│
├── outputs/
│   ├── Step 8 – Tuning Results
│   ├── Step 9 – Evaluation Metrics & Threshold Curves
│   ├── Step 10 – Feature Importance Bar Charts
│   ├── Step 13 – All XOE Visuals (Player, Team, Personnel, Logos)
│   └── Step 14 – GT Tables by Avg XOE
│
├── scripts/
│   └── Xboost_NFL_Explosive_Plays.Rmd – Fully commented final source code
│
└── README.md – This file
