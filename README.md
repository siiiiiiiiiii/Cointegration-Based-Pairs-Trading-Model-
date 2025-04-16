# 🧠 Cointegration-Based Pairs Trading Model

**Author:** Siu King Sum

📂 **Complete Source Code and Model Output** — available in this repository.

This repository contains the full implementation, optimization logic, performance evaluation, and research documentation of a **market-neutral pairs trading strategy** using historical stock data from Google (GOOG) and Microsoft (MSFT). The strategy is built in Python, with risk control mechanisms and parameter optimization designed for realistic financial applications.

---

## 📁 Files Included

- `Pairs_Trading_Report.pdf` — A complete report detailing the trading logic, statistical tests, risk controls, parameter selection process, backtest results, and out-of-sample validation.  
- `Pairs_Trading_Model.ipynb` — A Jupyter Notebook containing the full Python source code, including Johansen testing, regression spread construction, position sizing, and all performance plots.

---

## 📌 Project Overview

This project develops a **cointegration-based statistical arbitrage model**, a classic market-neutral approach widely used in hedge funds and quantitative trading desks. The model identifies and trades on temporary deviations in the price relationship between two historically correlated assets.

The core structure of the model includes:

- ✅ **Johansen Cointegration Test** to detect long-term equilibrium between the log-transformed prices of GOOG and MSFT  
- ✅ **OLS Regression** to compute the hedge ratio and construct the mean-reverting spread  
- ✅ **Trading Signals** generated based on Z-score thresholds of the spread  
- ✅ **ATR-Based Stop-Loss** to dynamically adjust to market volatility  
- ✅ **Volatility-Targeted Position Sizing** that scales exposure based on rolling return volatility  
- ✅ **Multi-Stage Parameter Optimization** using Grid Search, Random Search, and Bayesian Optimization to avoid overfitting

The system also evaluates risk-adjusted returns using common financial metrics such as Sharpe Ratio, Sortino Ratio, and Maximum Drawdown.

---

## 📈 Performance Summary

The strategy is evaluated over a 6-year backtest (2017–2023) and a 1-year out-of-sample test (2023–2024). Results show strong stability and generalization:

| Period             | Annualized Return | Annualized Volatility | Sharpe Ratio | Max Drawdown |
|-------------------|-------------------|------------------------|--------------|--------------|
| Backtest (2017–23)| 6.27%             | 9.21%                  | 0.68         | -8.67%       |
| Out-of-Sample     | 8.64%             | ~9%                    | 0.80         | -8.87%       |

💡 While the absolute return is lower than a Buy-and-Hold approach (e.g., GOOG+MSFT = ~24.32%), the strategy offers:

- 📉 Lower volatility (less than one-third of Buy-and-Hold)  
- 🛡️ Controlled drawdown (maximum drawdown remains under -9%)  
- 🔁 Market-neutral returns, suitable for volatile or sideways markets  
- 🧠 Strong generalization: out-of-sample results outperform backtest

---

## 🔍 Why This Project Matters

This project demonstrates not only technical fluency with financial time series modeling but also strong **risk awareness** and **robustness considerations**. Unlike many toy models, this strategy includes:

- Realistic transaction cost assumptions  
- Adaptive stop-loss tied to volatility  
- Defensive leverage adjustment for capital preservation  
- Objective function penalization to avoid over-optimizing for total return

It serves as a **template for scalable and robust quant strategies** under real-world conditions and may be extended to other asset pairs or integrated into a broader portfolio allocation system.

---

## 📬 Contact

If you're interested in this work or wish to collaborate, feel free to reach out via GitHub or email.

