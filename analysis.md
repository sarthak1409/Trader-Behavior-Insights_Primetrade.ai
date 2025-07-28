# 📈 Sentiment vs Trader Performance – EDA Summary

We aimed to explore the link between market sentiment (numerical values) and trader outcomes (Closed PnL). Here's the process followed and insights gained:

## 🔍 EDA Process

- Cleaned and filtered out zero-PnL rows for more accurate analysis.
- Classified sentiment into three categories:
  - **Low Sentiment**: value ≤ 44
  - **Medium Sentiment**: 44 < value ≤ 50
  - **High Sentiment**: value > 50
- Grouped average Closed PnL per sentiment category.
- Visualized the relationship using a bar plot.

## 📊 Key Insights

- Traders in **high sentiment** conditions earn the highest average profits.
- **Medium sentiment** periods showed minimal or no gains.
- Even **low sentiment** conditions showed slight positive returns, possibly from shorting or volatility-based strategies.

The bar plot below summarizes this trend visually.

![Sentiment vs PnL](assets/sentiment_vs_pnl.png)