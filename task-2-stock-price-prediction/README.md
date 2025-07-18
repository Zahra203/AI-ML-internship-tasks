# Task 2 - Stock Price Prediction
## Objective
Use historical stock market data to predict the next day's closing price.

##  Dataset
- Stock: AAPL (Apple Inc.)
- Source: Yahoo Finance via `yfinance` Python API
- Date Range: 2022–2024
- Features: Open, High, Low, Volume
- Target: Next day’s Close price

## Models Used
- Linear Regression
- Random Forest Regressor

## Libraries Used (with Short Explanation)

| Library           | Purpose                                      |
|-------------------|----------------------------------------------|
| **yfinance**      | To fetch stock price data from Yahoo Finance |
| **pandas**        | To handle and process tabular data           |
| **numpy**         | For numerical calculations and arrays        |
| **matplotlib**    | To create basic plots (like line charts)     |
| **seaborn**       | To create stylish, advanced plots            |
| **sklearn.linear_model** | To apply Linear Regression model     |
| **sklearn.ensemble**     | To use Random Forest model            |
| **sklearn.metrics**      | To evaluate model accuracy (MAE, RMSE)|
| **sklearn.model_selection** | To split data into train and test |

## Final Insights – Task 2: Stock Price Prediction

1. **Data Source & Objective**  
   We used Apple Inc. (AAPL) stock data from **Yahoo Finance** via the `yfinance` API to build a machine learning model that predicts the **next day’s closing price** based on current day values like Open, High, Low, and Volume.

2. **Clean and Consistent Data**  
   The dataset had no missing values and contained all required features for a short-term prediction task.

3. **Feature Impact**  
   - Features like **Open, High, Low**, and **Volume** helped predict the next day's Close price.  
   - These features are strongly correlated with stock movement and proved useful for the models.

4. **Model Comparison**  
   - **Linear Regression** captured basic trends but underperformed due to the complexity of real-world stock data.
   - **Random Forest Regressor** performed better by capturing nonlinear patterns, resulting in **lower MAE and RMSE**.

5. **Visual Analysis**  
   The actual vs predicted plot showed that the **Random Forest model** closely followed the trend of real closing prices, especially during stable market periods.

6. **Conclusion**  
   - While predicting exact stock prices is inherently difficult, especially with limited features, the model was able to give **reasonably accurate next-day predictions**.
   - More advanced models or additional features (like technical indicators, market news sentiment, etc.) could further improve performance.


## Files
- `stock_prediction.ipynb`: Code and plots
- `README.md`: Task description and summary
