## 📈 Cointegration-Based Pairs Trading Strategy: GOOG & MSFT

This repository features a fully implemented and optimized **market-neutral pairs trading strategy** between GOOG and MSFT. The model uses **Johansen cointegration**, **dynamic volatility targeting**, **ATR-based stop-loss**, and **parameter optimization** to generate trades based on relative mispricing.

### 🚀 Highlights
- ✅ **Cointegration Detected** (Johansen Test): GOOG & MSFT
- ✅ **Fully parameterized backtest framework** with Grid, Random & Bayesian optimization
- ✅ **Robust risk control**: Max drawdown capped at –8.7% with volatility filters & stop-loss
- ✅ **Out-of-sample generalization** confirms real-world applicability (2023–2024)

---

### 📊 Performance Summary

#### 🔁 In-Sample (2018–2022)
| Metric                | Value         |
|-----------------------|---------------|
| Total Return          | 44.80%        |
| Annualized Return     | 6.27%         |
| Annualized Volatility | 9.21%         |
| Sharpe Ratio          | 0.68          |
| Sortino Ratio         | 0.78          |
| Max Drawdown          | –8.67%        |

#### 🧪 Out-of-Sample (2023–2024)
| Metric                | Value         |
|-----------------------|---------------|
| Total Return          | 9.33%         |
| Annualized Return     | 8.64%         |
| Annualized Volatility | 10.75%        |
| Sharpe Ratio          | 0.80          |
| Sortino Ratio         | 0.67          |
| Max Drawdown          | –8.87%        |

#### 📉 Baseline: Buy-and-Hold (GOOG & MSFT Equal-Weighted)
| Metric                | Value         |
|-----------------------|---------------|
| Total Return          | 275.68%       |
| Annualized Return     | 24.32%        |
| Annualized Volatility | 28.74%        |
| Sharpe Ratio          | 0.85          |
| Sortino Ratio         | 1.15          |
| Max Drawdown          | –40.54%       |

---

### 📄 PDF Report
A complete write-up including methodology, charts, code explanation, and interpretations:

👉 [📄 View Full Report (Google Drive)](https://drive.google.com/file/d/1ZEI7BnvRLfd9WSh-Igyba2ojisQhTBeQ/view?usp=sharing)

---

### 🔍 Repository Structure
- `pairs_trading_model.ipynb` – Core strategy logic & backtest
- `baseline_buy_and_hold.ipynb` – Benchmark for performance comparison
- `optimization_module.py` – Grid, random, and Bayesian optimization
- `/charts/` – Strategy performance visualizations

---

### 💡 Takeaway
This is a **realistic, risk-managed, self-built strategy** suitable for use in asset management or hedge fund environments. It showcases:

- Practical Python implementation without external trading APIs
- Full-cycle model development (data → strategy → backtest → evaluation)
- A strong emphasis on **overfitting prevention**, **capital preservation**, and **real-world deployability**
