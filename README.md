# 🧠 Cointegration-Based Pairs Trading Model

**Author:** Siu King Sum

📂 **Complete Source Code and Model Output** — available in this repository  
📄 [👉 Read the Full PDF Report](./Pairs_Trading_Report.pdf)  
📊 [👉 Open the Jupyter Notebook](./Pairs_Trading_Model.ipynb)

---

## 📌 Overview

This project implements a cointegration-based pairs trading strategy on GOOG and MSFT. It combines:

- ✅ Johansen Cointegration Test  
- ✅ OLS hedge ratio for spread  
- ✅ ATR-based stop-loss  
- ✅ Target volatility leverage  
- ✅ Grid/Random/Bayesian optimization  

---

## 📈 Performance Summary

| Period            | Annualized Return | Sharpe Ratio | Max Drawdown |
|------------------|-------------------|--------------|--------------|
| Backtest (2017–23) | 6.27%            | 0.68         | -8.67%       |
| Out-of-Sample     | 8.64%            | 0.80         | Stable       |

📌 Stable, market-neutral, and resilient under out-of-sample testing.

---

## 📁 Files Included

- `Pairs_Trading_Report.pdf` — Full project report  
- `Pairs_Trading_Model.ipynb` — Source code and backtest  
- `README.md` — This page
