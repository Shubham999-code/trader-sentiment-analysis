# trader-sentiment-analysis
Data analysis project exploring the relationship between trader behavior and Bitcoin market sentiment (Fear &amp; Greed Index) using Python and EDA.





# 📁 Datasets Used #
Historical Trader Data

Contains detailed trade execution records.

Key columns: Account, Execution Price, Size USD, Side, Closed PnL, Timestamp IST

Fear & Greed Index

Provides daily market sentiment (Fear, Greed, etc.).

Columns: date, classification







# 🎯 Objective #
Understand how different market sentiments (Fear, Greed, etc.) impact:

Trader profit/loss

Trading volume

Trade direction (BUY vs SELL)






# 🧹 Data Preprocessing #
Converted timestamps to date format

Merged both datasets on date to align trades with sentiment






# 📊 Key Insights #
Most Active Sentiment: Extreme Greed

Highest Avg PnL: (Sentiment with best performance)

Volume Trends: Notable increase in USD traded during high Greed periods

Trade Side Split: More BUYs during Greed, more SELLs during Fear






# 🛠️ Tools Used #
Python, Pandas, Matplotlib, Seaborn

Google Colab






# 📂 Output #
Final merged dataset: trader_sentiment_merged.csv
