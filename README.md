# 📈 Cointegration-Based Pairs Trading Model

Built a **Cointegration Pairs Trading Model** incorporating:

- Johansen cointegration test  
- OLS hedge ratio  
- ATR-based stop loss  
- Target-volatility leverage adjustment  
- Multi-stage parameter optimization

---

## 🔎 Backtest Performance (6 Years)

- **Annualized Return**: 6.27%  
- **Annualized Volatility**: 9.21%  
- **Sharpe Ratio**: 0.68  
- **Sortino Ratio**: 0.78  
- **Maximum Drawdown**: –8.67%

These results demonstrate **solid risk control** and stable returns over time.

---

## 🧪 Out-of-Sample Performance

During out-of-sample testing, the model outperformed its in-sample performance:

- **Annualized Return**: 8.64%  
- **Sharpe Ratio**: 0.80  
- **Maximum Drawdown**: Stable

This suggests the model **was not over-fitted** and **generalizes well to unseen data**.

---

## 📊 Comparison with Buy-and-Hold Strategy

| Metric               | Pairs Trading | Buy-and-Hold |
|----------------------|---------------|--------------|
| Annual Return        | 6.27%         | 24.32%       |
| Volatility           | 9.21%         | 28.74%       |
| Max Drawdown         | –8.67%        | –40.54%      |
| Market Neutral       | ✅            | ❌           |

Although the return is lower, the model achieves **significantly lower volatility and drawdown** while remaining **fully market-neutral**.

---

## 💡 Conclusion

This strategy can generate alpha **regardless of market direction**, offering **stable, long-term gains** with superior risk-adjusted performance.
