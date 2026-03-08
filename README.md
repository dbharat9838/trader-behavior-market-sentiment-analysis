# trader-behavior-market-sentiment-analysis
Analyze how Bitcoin market sentiment (Fear/Greed) relates to trader behavior and trading performance. The goal is to identify patterns that can inform better trading strategies.
## Methodology
1. Loaded Bitcoin Fear & Greed sentiment dataset and historical trader data.
2. Cleaned the datasets by checking missing values and aligning timestamps by date.
3. Merged both datasets using date to analyze trader behavior based on market sentiment.
4. Calculated key metrics including:
   - Daily PnL
   - Win rate
   - Trade frequency
   - Average position size
   - Long vs Short ratio

## Key Insights
1. Traders achieved higher win rates during Extreme Greed sentiment compared to Fear conditions.
2. Trading activity increased significantly during Fear periods, indicating higher market volatility.
3. Large drawdowns were observed during Greed conditions, suggesting traders may take excessive risk in bullish markets.

## Strategy Recommendations
1. Increase trading activity cautiously during Extreme Greed but manage risk with smaller position sizes.
2. During Fear conditions, traders should reduce leverage and use stop-loss orders to manage volatility.

## Conclusion
Market sentiment plays an important role in trader behavior and performance. Combining sentiment indicators with disciplined risk management can improve trading strategies and reduce potential losses.
