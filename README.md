# NFL Explosive Plays Classification with XGBoost

## 🎯 Project Summary

This project was completed as the final capstone for **SAL 613: Football Analytics Applications** at Syracuse University (Spring 2025). 

The goal was to **build a machine learning model to classify explosive plays** in the NFL — defined as pass plays gaining 13+ yards or rush plays gaining 10+ yards — using play-by-play data and Next Gen Stats (NGS) features.

Using a powerful gradient boosting classifier (XGBoost), we trained and evaluated a model to identify patterns behind explosiveness, optimize predictive performance, and analyze player-level, team-level, and personnel-level tendencies.

---

## 📁 Repository Structure

plaintext
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

## 📈 Visual Highlights

#### 🧨 Top 15 Players by Average Explosives Over Expected (XOE)  
![Top 15 Players by Avg XOE](outputs/Step%2014%20A/top_15_xoe_with_headshots.png)

---

#### 🧮 Team-Level Evaluation: Precision, Recall, and F1 Across Thresholds  
![Threshold Sensitivity Curve](outputs/Step%209/threshold_sensitivity_plot.png)

---

#### 🧠 XGBoost Feature Importance  
![Top 20 Feature Importances](outputs/Step%2010/xgb_top20_feature_importance.png)

---

#### 🚀 Player-Level Performance: Explosives vs Expected  
![Top 20 XOE Players](outputs/Step%2013%20A/top20_xoe_players.png)
