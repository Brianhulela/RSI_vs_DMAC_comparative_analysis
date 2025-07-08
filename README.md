# Bayesian Optimization of DMAC and RSI

This Jupyter notebook explores and compares two of the most well-known trading strategies in technical analysis:

- **Dual Moving Average Crossover (DMAC)** — a trend-following strategy
- **Relative Strength Index (RSI) Mean Reversion** — a momentum-based strategy

To find the most effective parameter combinations for each strategy, the notebook uses **Bayesian Optimization**, a more efficient alternative to grid or random search.

### Dataset

The strategies are tested on **Microsoft (MSFT)** historical data from **2020 to mid-2025**, with a clear separation between training and testing periods to simulate realistic forward-looking performance evaluation.

### What This Notebook Covers

- Visual exploration of the MSFT stock price and return distributions
- Implementation of DMAC and RSI-based strategies with parameterized backtests
- Use of Bayesian Optimization to tune strategy parameters for best performance
- Clear performance comparisons:
  - Strategy return vs. Buy & Hold
  - Trade frequency
  - Final portfolio value
- Multiple performance visualizations including equity curves and percentage returns

### Key Takeaways

This project helps answer a practical question:  
**Can a simple, well-tuned strategy outperform Buy & Hold in a modern market?**

It also highlights the trade-offs between different strategy types — trend-following vs. mean-reverting — and when each might shine or struggle depending on market conditions.

---
