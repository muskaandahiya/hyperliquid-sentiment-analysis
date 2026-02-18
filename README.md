# hyperliquid-sentiment-analysis
# Trader Performance vs Market Sentiment

## Objective
Analyze how Bitcoin market sentiment (Fear/Greed Index) relates to trader behavior and performance on Hyperliquid.

## Dataset
- Bitcoin Fear/Greed Index (daily sentiment)
- Historical Hyperliquid trader transaction data

## Methodology
- Converted timestamps to daily granularity
- Aligned trader data with sentiment data by date
- Created metrics such as daily PnL, trade count, win rate, trade size, and long/short ratio
- Compared trader behavior and performance across sentiment regimes
- Segmented traders by activity level

## Key Insights
1. Trader profitability and win rate were higher during Greed periods compared to Fear periods.
2. Trade frequency and average trade size increased during Greed days.
3. High-frequency traders experienced larger drawdowns during Fear days.

## Strategy Recommendations
- Reduce trade frequency and leverage during Fear-dominated markets.
- Allow higher participation during Greed periods with strict risk controls.

## How to Run
1. Clone the repository
2. Install dependencies
3. Run the notebook
