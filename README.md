# Development
pip install -e .

# mag-7-backtesting

# Background
The task involves the creaton of a backtestng sofware to evaluate the performance of a specifed set
of stocks known as the "Magnifcent 7" (Microsof [MSFT], Apple [AAPL], Nvidia [NVDA], Amazon
[AMZN], Google [GOOG], Meta [META], Tesla [TSLA]) in the US stock market. The program should
employ the Double Bollinger Bands strategy as the basis for trading signals or any other strategy that
you deem more applicable. For further details on this strategy, refer to the comprehensive guide
available at (htps://www.3candlereversal.com/post/kathy-lien-s-double-bollinger-band-strategy).

# Tasks
1. Extract historical price data for the stocks MSFT, AAPL, NVDA, AMZN, GOOG, META, and TSLA
using the Yahoo Finance API (yfnance). The data should span from 2013-01-01 to 2023-12-31
2. Implement the Double Bollinger Band indicator to generate buy and sell signals based on the
specifed strategy
3. Design a backtestng loop to simulate trading with these signals. Assume an inital capital of
$10,000. The minimum transacton size is set at 1 share per trade
4. Compute the following performance metrics to assess the strategy's efectveness:

# Performance Metrics
• Total Return
• Annual Return
• Annual Volatlity
• Sharpe Rato
• Sortno Rato
• Maximum Drawdown

# Submission
Upload the project to GitHub and share the link to hr@banksidecap.com

# Instructons
• Please use Python for the entre project, you can either code in Python fle or Jupyter
Notebook
• Please refrain from using any backtestng framework (i.e., Backtestng.py, Backtrader and etc)
• Please adhere to clean code and best sofware practce

# Room for Improvement

Naive Strategy was used for Trading: Use all money when possible, and sell all when sell signal
Trading Strategy currently only looks at One stock at a time

