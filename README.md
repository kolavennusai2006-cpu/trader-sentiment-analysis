# Trader Performance vs Market Sentiment Analysis

## Objective
To analyze how Bitcoin market sentiment (Fear/Greed Index) relates to trader behavior and performance on Hyperliquid. 
The goal is to uncover behavioral patterns and propose data-driven trading strategy recommendations.

---

## Methodology

1. Data Preparation
   - Loaded sentiment and trade datasets
   - Checked missing values and duplicates
   - Converted timestamps to daily granularity
   - Merged datasets on aligned date column

2. Feature Engineering
   - Daily PnL per trader
   - Win rate per trader
   - Average trade size
   - Trades per day
   - Long/Short distribution

3. Sentiment-Based Analysis
   - Compared profitability across sentiment regimes
   - Examined win rate variation
   - Analyzed trade size behavior
   - Conducted behavioral segmentation (Frequent vs Infrequent Traders)

---

## Key Insights

- Extreme Greed periods show the highest average profitability and win rates.
- Extreme Fear environments exhibit the weakest trader performance.
- Traders deploy larger capital during Fear regimes despite lower win rates.
- Infrequent traders significantly outperform frequent traders, indicating overtrading reduces profitability.

---

## Strategy Recommendations

1. Sentiment-Based Participation Rule  
   Increase participation during Extreme Greed regimes while maintaining moderate position sizing.

2. Avoid Overtrading  
   Limit trade frequency using stricter entry filters to improve risk-adjusted returns.

3. Risk Control in Fear Markets  
   Implement position size caps and tighter stop-loss controls during Fear periods.

---

## How to Run

Install dependencies:

pip install -r requirements.txt

Open and run the notebook from top to bottom.
