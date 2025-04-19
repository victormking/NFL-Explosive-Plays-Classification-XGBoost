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
<img src="https://github.com/victormking/NFL-Explosive-Plays-Classification-XGBoost/raw/main/Outputs/Step%2014%20A/top_15_xoe_with_headshots.png" width="700"/>

---

#### 🧪 Team-Level Evaluation: Precision, Recall, and F1 Across Thresholds  
<img src="https://github.com/victormking/NFL-Explosive-Plays-Classification-XGBoost/raw/main/Outputs/Step%209/threshold_sensitivity_plot.png" width="700"/>

---

#### 🧠 XGBoost Feature Importance  
<img src="https://github.com/victormking/NFL-Explosive-Plays-Classification-XGBoost/raw/main/Outputs/Step%2010/xgb_top20_feature_importance.png" width="700"/>

---

#### 👤 Player-Level Performance: Explosives vs Expected  
<img src="https://github.com/victormking/NFL-Explosive-Plays-Classification-XGBoost/raw/main/Outputs/Step%2013%20A/top20_xoe_players.png" width="700"/>

### 🔍 Model Performance Summary

- Accuracy: **68.3%**
- ROC AUC: **0.681**
- Brier Score: **0.1926**
- Cross-validation: **10-fold, stratified**
- Algorithm: **XGBoost (Grid + Latin Hypercube Tuned)**
