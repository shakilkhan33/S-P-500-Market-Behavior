# Applying Machine Learning Methods to Forecast S&P 500 Market Behavior

## Abstract:
Machine learning is now used in many areas, including financial markets. However, Stock data is hard to work with because it changes quickly and there is a huge amount of information to look at. A previous study by Alzaman used data from the Toronto Stock Exchange to test if machine-learning models could predict whether a stock would rise or fall. Their results showed that the method worked for that market.

In this project, I used the same idea but with a different dataset. I collected S&P 500 stock data using the yfinance library and built a similar machine-learning model to predict stock movement. I explored the data, created the features, and trained the model following a workflow. The main goal of this study is to see how well these methods work on S&P 500 data and whether they can be used to understand general market behavior.

### Tools: Python, YFinance, NumPy, Matplotlib, Pandas, Seaborn, Sklearn

- Built and evaluated machine-learning models (Linear Regression vs. Random Forest) on historical S&P 500 stock data, improving next-day Apple price prediction accuracy as measured by lower MAE and higher R2 on held-out test data.
- Engineered time-series features (1-5 day returns and lagged prices) from YFinance data using Python, enabling models to capture non-linear market patterns and outperform baseline linear approaches.
- Analyzed market behavior across five major S&P 500 companies by visualizing price trends, sector distribution, and correlations, demonstrating the dominance of tech stocks and inter-stock relationships relevant to portfolio diversification.
