# 📊 Quantitative Risk Models by Sai Ram

Welcome! This repository contains practical risk models used in portfolio risk management, implemented using Python.

---

## 🧠 Project 1: Value at Risk (VaR) – Monte Carlo Simulation

This notebook estimates **1-day VaR** using a Monte Carlo approach:

- Simulates 100,000 possible daily returns
- Uses normal distribution based on daily mean and volatility
- Calculates **95% and 99% Value at Risk**
- Visualizes the simulated loss distribution with VaR markers

📁 File: `VaR_MonteCarlo_Sai.ipynb`

📈 Sample Output:
VaR 95% ≈ ₹34,010
VaR 99% ≈ ₹47,452

---

## 📚 Tools Used
- Python
- NumPy
- Seaborn
- Matplotlib
- Jupyter / Google Colab

---

## 📊 Option Greeks – Delta, Gamma, Vega

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

> 🔧 Inspired using ChatGPT, customized with my logic and assumptions.


---

## 👤 Author

**Sai Ram**  
CPQFRM Aspirant | Python for Quant Risk | Fund Risk Analytics  
📫 [GitHub Profile](https://github.com/SaiRam-quant)
