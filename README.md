# Trader Behavior Analysis Using Market Sentiment

## Problem Statement
This project analyzes how market sentiment (Fear vs Greed) influences trader behavior and performance using historical Hyperliquid trading data combined with the Bitcoin Fear & Greed Index.

## Datasets
- **Historical Trader Data (Hyperliquid):**
  Contains trade-level information such as execution price, size, PnL, and timestamps.
- **Bitcoin Fear & Greed Index:**
  Daily sentiment classification representing overall market psychology.

Dataset links are provided in the assignment description.

## Methodology
- Normalized trade timestamps (IST, day-first format)
- Aligned trades with daily sentiment using date-based merging
- Defined performance using realized PnL, ROI, and win rate
- Analyzed profitability, risk, and trader-level behavior across sentiment regimes
- ## How to Run
The analysis was developed in Google Colab and can be run locally by installing the dependencies listed in `requirements.txt` and executing the notebook top-to-bottom.


## Key Insights
- Trading during Greed periods shows higher average returns but significantly higher downside risk
- Fear periods exhibit lower trade frequency but improved consistency
- Certain traders remain profitable across sentiment regimes, indicating strategy robustness

## Limitations
- Sentiment data is market-wide and not asset-specific
- Transaction costs and slippage are not included
- Analysis limited to available historical window

## Next Steps
- Strategy backtesting under sentiment regimes
- Asset-specific sentiment analysis
- Incorporating volatility and position duration
