# Cointegration Pairs Trading Model

A market‑neutral, statistical arbitrage strategy that exploits long‑term equilibrium relationships between equity pairs. Built in Python, it combines econometric testing, risk controls, and multi‑stage parameter tuning to deliver stable, risk‐adjusted returns.

---

## 📖 Table of Contents

- [Key Features](#key-features)  
- [Performance](#performance)  
- [Getting Started](#getting-started)  
  - [Prerequisites](#prerequisites)  
  - [Installation](#installation)  
- [Usage](#usage)  
- [Configuration](#configuration)  
- [Results](#results)  
  - [Backtest (6 years)](#backtest-6-years)  
  - [Out‑of‑Sample (2023–2024)](#out‑of‑sample-2023–2024)  
- [Comparison to Buy‑and‑Hold](#comparison-to-buy‑and‑hold)  
- [Contributing](#contributing)  
- [License](#license)  

---

## 🔑 Key Features

- **Johansen Cointegration Test**: Identifies statistically significant pairs.  
- **OLS Hedge Ratio**: Estimates optimal long/short weights.  
- **ATR‑Based Stop Loss**: Dynamic exit to control drawdowns.  
- **Target‑Volatility Leverage**: Scales positions to a fixed volatility target.  
- **Multi‑Stage Parameter Optimization**: Grid Search, Random Search, and Bayesian Optimization.

---

## 📈 Performance

### Backtest (6 years)
- **Annualized Return:** 6.27%  
- **Annualized Volatility:** 9.21%  
- **Sharpe Ratio:** 0.68  
- **Sortino Ratio:** 0.78  
- **Max Drawdown:** –8.67%  

### Out‑of‑Sample (2023–2024)
- **Annualized Return:** 8.64%  
- **Sharpe Ratio:** 0.80  
- **Max Drawdown:** –8.67% (stable)

---

## 🚀 Getting Started

### Prerequisites

- Python 3.8+  
- `pandas`, `numpy`, `statsmodels`, `scikit-learn`  
- `yfinance` (or another data provider)  
- `ta` (technical indicators)  
- `optuna` (for Bayesian Optimization)

### Installation

1. Clone this repository  
   ```bash
   git clone https://github.com/siiiiiiiiiii/Cointegration-Based-Pairs-Trading-Model-.git
   cd Cointegration-Based-Pairs-Trading-Model-
