# 📊 Cointegration-Based Pairs Trading Model

This repository implements a **market-neutral pairs trading strategy** using advanced statistical and risk management techniques.

---

## 🧠 Strategy Overview

This model integrates:

- **Johansen Cointegration Test** – To identify cointegrated pairs.
- **OLS Hedge Ratio** – For computing the optimal long-short ratio.
- **ATR-Based Stop Loss** – Dynamic stop loss based on market volatility.
- **Target Volatility Adjustment** – Leverage is adjusted to maintain consistent portfolio risk.
- **Multi-Stage Parameter Optimization** – Using Grid Search, Random Search, and Bayesian Optimization.

---

## 📈 Backtest Performance (2017–2022)

- **Annualized Return**: 6.27%  
- **Annualized Volatility**: 9.21%  
- **Sharpe Ratio**: 0.68  
- **Sortino Ratio**: 0.78  
- **Max Drawdown**: –8.67%

The strategy shows **solid risk-adjusted performance** and **robust drawdown control**.

---

## 🧪 Out-of-Sample Performance (2023–2024)

- **Annualized Return**: 8.64%  
- **Sharpe Ratio**: 0.80  
- **Stable Drawdown** maintained

This suggests the model **generalizes well to unseen data** and is **not overfitted**.

---

## 📉 Comparison with Buy-and-Hold

| Strategy             | Annual Return | Volatility | Max Drawdown |
|----------------------|----------------|------------|----------------|
| **Pairs Trading**    | 6.27%          | 9.21%      | –8.67%         |
| **Buy-and-Hold**     | 24.32%         | 28.74%     | –40.54%        |

While Buy-and-Hold yields higher returns, the **Pairs Trading strategy maintains significantly lower risk** and is **fully market-neutral**, capable of generating alpha in any market condition.

---

## 📂 Full Code & Results

🔗 [View Full Code on GitHub](https://github.com/siiiiiiiiiii/Cointegration-Based-Pairs-Trading-Model-)

The repository includes:

- Python source code
- Statistical tests & signal logic
- Backtesting & performance evaluation
- Output charts and logs

---

## ✅ Conclusion

This project demonstrates how to build a statistically sound and risk-aware pairs trading system. The results show that with proper testing and risk control, a **market-neutral strategy** can yield **stable and robust long-term gains**, even in volatile markets.
