# 📈 Pair Trading Strategy using Python

This project implements a **Pair Trading Strategy** to identify and exploit market inefficiencies between two co-moving stocks. Pair trading is a market-neutral strategy that uses statistical methods to find mispricings between two historically correlated assets.

---

## 🔍 What is Pair Trading?

Pair trading involves:
- Identifying two stocks (a "pair") with a high historical correlation
- Monitoring the spread (price difference or ratio) between them
- Taking **long** and **short** positions when the spread deviates from its mean
- Closing the positions when the spread reverts back

- ## 🧠 Key Features

- 📊 Automatic selection of stock pairs based on correlation or cointegration
- ⚖️ Z-score-based entry and exit signals
- 🧪 Backtesting over historical stock price data
- 📈 Cumulative returns plotted vs market benchmark
