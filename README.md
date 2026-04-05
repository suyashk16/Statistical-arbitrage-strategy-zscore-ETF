
# 📈 Statistical Arbitrage using Z-Score

This project implements a mean-reversion statistical arbitrage strategy using rolling Z-score on asset spread. The strategy identifies deviations from the mean and trades expecting reversion.

Strategy Logic:
Z-score > +2 → Sell spread
Z-score < -2 → Buy spread
Exit when Z-score returns to 0

Backtested on ~10 years of daily data.

Performance:
Total Trades: 130
Win Rate: ~37%
Profit Factor: ~2.87
Sharpe Ratio: ~2.4

Insights:
Low win rate but strong reward-to-risk ratio. Strategy benefits from disciplined exits and mean-reversion behavior, resulting in a stable equity curve over time.

Tech Stack:
Python, Pandas, NumPy, Matplotlib

File:
stat_arb_zscore_ETF.ipynb

Limitations:
No advanced position sizing, simplified cost model, no slippage or latency modeling.

Author:
Suyash Khairnar
