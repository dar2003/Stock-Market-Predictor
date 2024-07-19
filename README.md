# Stock-Market-Predictor

In this project, I developed a stock market prediction model using Python. The project flow included several key steps:

1. **Data Scraping:** I began by scraping historical stock market data from online sources to gather the necessary dataset.
2. **Data Visualization:** Using Plotly, I visualized the data to identify initial trends and patterns.
3. **Stationarity Check:** I conducted a stationarity check to ensure the time series data was suitable for ARIMA modeling.
4. **Data Decomposition:** I decomposed the time series into trend, seasonality, and noise components to better understand the underlying patterns.
5. **ARIMA Modeling:** I determined the optimal `p`, `d`, and `q` parameters for the ARIMA model through a systematic approach.
6. **Forecasting:** With the ARIMA model, I predicted the stock prices for the next 30 days.
7. **SARIMA Modeling:** To account for seasonality, I implemented the SARIMA model and compared its performance against the ARIMA model.
8. **Hyperparameter Tuning:** Finally, I fine-tuned the model parameters to enhance prediction accuracy.

Overall, this project not only involved technical skills in data scraping and time series analysis but also required a deep understanding of statistical modeling and forecasting techniques.
