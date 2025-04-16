# Cointegration‑Based Pairs Trading Model

**Report:** Cointegration‑Based Pairs Trading Model Development and Risk Management  
📂 **Complete Source Code and Model Output** — available on GitHub:  
🔗 [View the Code and Results on GitHub](https://github.com/siiiiiiiiiii/Cointegration-Based-Pairs-Trading-Model-)

---

## Table of Contents

1. [Introduction](#introduction)  
2. [Features](#features)  
3. [Getting Started](#getting-started)  
   - [Prerequisites](#prerequisites)  
   - [Installation](#installation)  
4. [Usage](#usage)  
5. [Model Architecture & Workflow](#model-architecture--workflow)  
   1. [Data Acquisition & Preprocessing](#data-acquisition--preprocessing)  
   2. [Cointegration Testing & Hedge Ratio](#cointegration-testing--hedge-ratio)  
   3. [Risk Management & Leverage Adjustment](#risk-management--leverage-adjustment)  
   4. [Multi‑Stage Parameter Optimization](#multi-stage-parameter-optimization)  
6. [Results](#results)  
   - [Backtest Performance (6 years)](#backtest-performance-6-years)  
   - [Out‑of‑Sample Performance (2023–2024)](#out-of-sample-performance-2023–2024)  
   - [Comparison with Buy‑and‑Hold Baseline](#comparison-with-buy-and-hold-baseline)  
7. [Notes on Objective Function Penalty](#notes-on-objective-function-penalty)  
8. [Contributing](#contributing)  
9. [License](#license)

---

## Introduction

In today’s financial markets, trading strategies must balance profitability and risk control. This project implements a market‑neutral pairs trading model on GOOG and MSFT, integrating:

- **Statistical testing**: Johansen cointegration  
- **Regression analysis**: OLS hedge ratio  
- **Risk control**: ATR‑based stop‑loss  
- **Dynamic leverage**: target volatility scaling  
- **Parameter tuning**: Grid Search, Random Search, Bayesian Optimization  

After six years of backtesting, the strategy delivered stable risk‑adjusted returns and improved further in out‑of‑sample testing, demonstrating strong generalization and robustness.

---

## Features

- Fetches historical price data via `yfinance`  
- Log‑transforms prices for statistical robustness  
- Johansen test to confirm cointegration  
- OLS regression for hedge‑ratio calculation  
- ATR‑based dynamic stop‑loss thresholds  
- Volatility‑target leverage adjustment  
- Multi‑stage hyperparameter optimization  
- Comprehensive backtest and out‑of‑sample evaluation  
- Clear visualization of performance metrics

---

## Getting Started

### Prerequisites

- Python 3.8+  
- `yfinance`, `pandas`, `numpy`, `statsmodels`, `ta`, `scikit‑learn`, `bayesian‑optimization` (or your chosen BO lib)  
- `matplotlib` for plotting

```bash
pip install yfinance pandas numpy statsmodels ta scikit-learn bayesian-optimization matplotlib
