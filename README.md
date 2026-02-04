## Note on Data Alignment
The market sentiment dataset and trader dataset span different time ranges.
Trades without matching sentiment labels were retained and treated as neutral to avoid data loss

# Trader Performance vs Market Sentiment

## Objective
Analyze how market sentiment (Fear vs Greed) relates to trader behavior and performance on Hyperliquid.

## Datasets
- Bitcoin Fear & Greed Index
- Hyperliquid Historical Trader Data

## Methodology
- Loaded and inspected both datasets
- Cleaned data and handled timestamps
- Aligned data at daily level
- Engineered trader performance metrics
- Analyzed behavior and performance across sentiment regimes
- Derived actionable strategy insights

## Key Insights
- Traders perform better during Greed periods with higher PnL and win rates.
- Fear periods show defensive behavior but worse overall outcomes.
- Frequent traders benefit more during Greed than Fear.

## Strategy Recommendations
- Reduce trade activity and exposure during Fear periods.
- Increase activity selectively for frequent traders during Greed periods.

## How to Run
Open the notebook and run all cells from top to bottom.
