# 📊 Trader Behavior Insights

![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![ML](https://img.shields.io/badge/Model-XGBoost-orange)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

## Overview
This project analyzes how **trader behavior and performance** change under different **market sentiment regimes (Fear vs Greed)** using the Bitcoin Fear & Greed Index and historical trading data from Hyperliquid.

The goal is to understand how **profitability, risk exposure, and leverage behavior** vary with market sentiment and to identify signals for smarter trading strategies.

---

## Datasets
- **Bitcoin Fear & Greed Index** – daily market sentiment (Fear / Greed)
- **Hyperliquid Trade Data** – 211k+ executed trades with realized PnL

---

## Methodology
- Data cleaning and preprocessing
- Feature engineering (sentiment encoding, implied leverage)
- Exploratory data analysis
- Statistical testing (Welch’s t-test, ANOVA)
- Machine learning using **XGBoost**:
  - Classification: Profit vs Loss
  - Regression: Trade PnL
- 5-fold cross-validation for robustness

---

## Key Insights
- Greed markets increase leverage and exposure, not guaranteed profitability
- Fear regimes reward disciplined, low-risk trading
- High implied leverage is a leading indicator of drawdowns
- Market sentiment affects behavior more than returns

---

## Repository Structure
ds_Shanmukha_guggilam/
├── Trader_Behavior_Insights.ipynb

├── sentiment_vs_trading.ipynb

├── merged_trader_sentiment_data.csv

├── Trader_Behavior_Insights_Report.pdf

├── outputs

├── README.md
