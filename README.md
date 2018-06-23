# StockMarketPrediction
Lessons from building a Machine learning approach to stock market prediction

# Approaches
## * Intra-day Volatility
### Aim : 
Screen and identify the stocks (that have high volatility ) to trade with.
### Assumption : 
The stocks that fluctuate the most are the stocks to trade with 

### Method : 
Observe the stocks that fluctuate in the first 4 hours of trading 
Run the script at t= 4 hrs and based on the metric, screen for the stocks to consider
### Metrics used 
1. Standard deviation of log returns
2. Standard deviation of price
3. Number of times 

## * ML Model based on features
Aim : Predict if a stock ends up x% above the previous days price.
### Assumption : 
The stocks have factored in the extrinsic factors such as news and company fundamentals in its current market price. Given enough price movement data and the right features, it should be possible to predict the movement of stocks, at least for a short term.
### Factors used


