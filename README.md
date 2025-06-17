# Portfolio Optimization using Modern Portfolio Theory (MPT)

This project implements **Markowitz’s Modern Portfolio Theory** to optimize the allocation of assets among five major tech stocks: **AAPL, MSFT, AMZN, GOOGL, and TSLA**. It includes simulation of portfolios, visualization of the **Efficient Frontier**, and optimization of the **tangency portfolio** (maximum Sharpe ratio).

> *Note: This project is based on an open-source implementation, which I extended and modified for personal learning, demonstration, and deeper understanding.*

---

## Problem Statement

> Given historical stock data, how can we create an optimal portfolio with the best risk-return tradeoff?

Using daily adjusted closing prices from 2018 to 2025, we:
- Calculate daily returns and their covariance matrix
- Simulate 10,000 random portfolios
- Visualize the efficient frontier
- Use **scipy.optimize** to find the maximum Sharpe ratio portfolio
- Plot the **Capital Allocation Line (CAL)** using a 2% risk-free rate

---

## Tools & Libraries Used

- [`yfinance`](https://pypi.org/project/yfinance/) – for downloading stock price data
- `numpy`, `pandas` – for numerical operations and data manipulation
- `matplotlib` – for plotting
- `scipy.optimize` – for Sharpe ratio optimization

---
