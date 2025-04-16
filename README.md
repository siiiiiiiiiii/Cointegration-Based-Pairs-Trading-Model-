# 🧠 Cointegration-Based Pairs Trading Model

**Author:** Siu King Sum

📂 **Complete Source Code and Model Output** — available in this repository  
📄 [👉 Click here to read the full PDF report](./Cointegration-based%20pairs%20trading%20model%20%2Epdf)  
📊 [👉 Click here to open the Jupyter Notebook](./Cointegration-Based%20Pairs%20Trading%20Model.ipynb)

---

## 📌 Overview

This project builds a **cointegration-based pairs trading strategy** using GOOG and MSFT. The model integrates:

- Johansen Cointegration Test for long-term equilibrium detection  
- OLS hedge ratio for spread construction  
- ATR-based dynamic stop-loss  
- Target volatility-based leverage adjustment  
- Grid Search, Random Search, and Bayesian Optimization for parameter tuning

---

## 📈 Performance Summary

| Metric               | Backtest (2017–2023) | Out-of-Sample (2023–2024) |
|---------------------|----------------------|----------------------------|
| Annualized Return   | 6.27%                | 8.64%                      |
| Sharpe Ratio        | 0.68                 | 0.80                       |
| Max Drawdown        | -8.67%               | Stable                     |
| Volatility          | 9.21%                | Lower than Buy-and-Hold    |

✅ Outperforms Buy-and-Hold in downside protection  
✅ Market neutral with stable returns and robust generalization

---

## 📁 File Structure

- `📄 Cointegration-based pairs trading model .pdf` — Detailed report and results  
- `📓 Cointegration-Based Pairs Trading Model.ipynb` — Python notebook with full code  
- `📘 README.md` — Project overview

---

🔗 **Explore the logic, risk controls, and code inside the notebook.**  
The strategy is designed to operate in volatile markets with stability and resilience.
