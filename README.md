# 📊 Quantitative Risk Models by Sai Ram

Welcome! This repository contains practical risk models used in portfolio risk management, implemented using Python.

## 🧠 Project 1: Value at Risk (VaR) – Monte Carlo Simulation

This model estimates potential loss using a 1-day Monte Carlo simulation.  
We model daily returns as normally distributed and simulate 10,000 paths.

### Assumptions:
- Initial Portfolio: ₹10,00,000
- Annual Return: 12%
- Annual Volatility: 20%
- Time Horizon: 1 day
- Simulations: 10,000
- Model: Geometric Brownian Motion

### Insights:
- Simulated 1-day loss using lognormal paths
- VaR 95% = ₹34,010 → 5% chance of losing more than this in a day
- VaR 99% = ₹47,452 → 1% chance of worse loss

## 🧠 Project 2: Option Greeks – Delta, Gamma, Vega

This notebook shows how option sensitivities (Greeks) change with stock price.

### Assumptions:
- Underlying: ₹100 stock
- Strike: ₹100 (ATM)
- Volatility: 25%
- Time to expiry: 30 days
- Risk-free rate: 5%

### Insights:
- **Delta** rises with price and tells us how option reacts to price moves.
- **Gamma** peaks at ATM → high delta risk when near expiry.
- **Vega** is highest at ATM → tells how sensitive the option is to volatility changes.

🧠 I used this model to understand option hedging and how risk changes near expiry.

## 🧠 Project 3:Stress Testing – Portfolio Under Volatility Shock

This simulation models a ₹10 lakh portfolio over 1 year using Monte Carlo.  
It compares normal vs stressed volatility scenarios.

### Assumptions:
- Initial Portfolio: ₹10,00,000
- Annual Return: 12%
- Normal Volatility: 20%
- Stressed Volatility: 40%
- Days: 252
- Simulations: 10,000

### Insights:
- Under stress, losses become more severe and unpredictable.
- VaR shifts significantly — from ~₹70K to ₹1.8 lakh.
- Fund managers use this to build **capital buffers** and avoid leverage traps.
---
## 👤 Author

**Sai Ram**  
CPQFRM Aspirant | Python for Quant Risk | Fund Risk Analytics  
📫 [GitHub Profile](https://github.com/SaiRam-quant)
