# trader-sentiment-analysis
# 📊 Trader Performance & Market Sentiment Analysis

This project explores how **Bitcoin market sentiment (Fear/Greed)** affects **trader performance** using real trading data from Hyperliquid.

## 🚀 Objectives

- Merge daily sentiment data with trader execution logs
- Analyze average PnL, win rate, and trade sizes by sentiment
- Visualize and interpret trader behavior across market conditions

## 📁 Data

- `fear_greed_index.csv`: Market sentiment classification per day
- `historical_data.csv`: Trader transactions (account, price, size, PnL, leverage, etc.)

## 📈 Key Insights

- **Extreme Greed** correlates with the **highest average profits** and **win rate**
- **Fear periods** also present **high-profit potential** but with increased volatility
- **Extreme Fear** tends to yield poor performance and higher risk

## 📊 Visualizations

Plots are stored in the `plots/` folder, including:
- Average PnL by sentiment
- Win rate by sentiment

## 📚 Libraries Used
- pandas
- matplotlib
- seaborn
- numpy
