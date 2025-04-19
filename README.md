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


## 📊 Visual Highlights

### Top 15 Players by Average Explosives Over Expected (XOE)
![Top 15 Players by Avg XOE](outputs/Step 14/top_15_xoe_with_headshots.png)

---

### Team-Level XOE Comparison
![Team XOE](outputs/Step 13 D/xoe_by_team_logos.png)

---

### Explosiveness by Offensive Personnel
![XOE by Offensive Personnel](outputs/Step 13 E/xoe_by_offensive_personnel.png)

---

### Explosiveness by Defensive Personnel
![XOE by Defensive Personnel](outputs/Step 13 E/xoe_by_defensive_personnel.png)
