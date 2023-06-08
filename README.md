# Time-Series-Forecasting-Basics

## Time Series Forecasting

Time series forecasting is a branch of statistical analysis and machine learning that deals with predicting future values based on historical data points that are ordered chronologically. It is widely used in various domains such as finance, economics, weather forecasting, stock market analysis, and demand forecasting.

### Key Concepts in Time Series Forecasting

1. **Time Series Data**: Time series data is a sequence of observations collected at regular time intervals. It typically consists of a timestamp and a corresponding value. The data can be univariate, containing a single variable, or multivariate, containing multiple variables.

2. **Trends**: Trends refer to the long-term patterns or tendencies in a time series. A trend can be upward (indicating growth or increasing values), downward (indicating decline or decreasing values), or stationary (indicating no significant trend).

3. **Seasonality**: Seasonality refers to recurring patterns in a time series that repeat over fixed time intervals, such as daily, weekly, monthly, or yearly. Seasonality can be additive or multiplicative, and it can affect the amplitude or the shape of the data.

4. **Stationarity**: Stationarity is a crucial assumption in time series analysis. A time series is said to be stationary if its statistical properties, such as mean, variance, and autocovariance, remain constant over time. Stationarity simplifies the modeling process and allows for more accurate forecasting.

5. **Autocorrelation**: Autocorrelation measures the relationship between observations at different time points in a time series. It quantifies the correlation between a variable and its lagged values. Positive autocorrelation indicates that high (low) values tend to be followed by high (low) values, while negative autocorrelation indicates an inverse relationship.

### Time Series Forecasting Techniques

1. **Moving Average**: The moving average method calculates the average of the previous values over a specified window size. It is used to smooth out random fluctuations and highlight underlying trends or patterns.

2. **Exponential Smoothing**: Exponential smoothing assigns exponentially decreasing weights to past observations, giving more importance to recent data points. It is suitable for time series data with a decreasing trend or no clear seasonality.

3. **Autoregressive Integrated Moving Average (ARIMA)**: ARIMA models combine autoregression (AR), moving average (MA), and differencing (I) components. ARIMA models are widely used for forecasting time series with stationary properties and can handle trends and seasonality.

4. **Seasonal Decomposition of Time Series (STL)**: STL decomposes a time series into three components: trend, seasonality, and remainder. It separates the different components to analyze and forecast each individually.

5. **Machine Learning Models**: Machine learning models, such as linear regression, support vector machines (SVM), random forests, and recurrent neural networks (RNN), can also be used for time series forecasting. These models can capture complex patterns and dependencies in the data and provide accurate predictions.

### Evaluation of Time Series Forecasting

To evaluate the performance of time series forecasting models, several metrics are commonly used:

1. **Mean Absolute Error (MAE)**: MAE measures the average absolute difference between the predicted and actual values. It provides an indication of the average forecasting error.

2. **Mean Squared Error (MSE)**: MSE calculates the average of the squared differences between the predicted and actual values. It gives more weight to large errors and is widely used in time series analysis.

3. **Root Mean Squared Error (RMSE)**: RMSE is the square root of MSE and is used to measure the average magnitude of the forecasting errors in the same units as the original data.

4

. **Mean Absolute Percentage Error (MAPE)**: MAPE calculates the average percentage difference between the predicted and actual values. It is particularly useful for evaluating forecasts of different scales or magnitudes.

5. **Forecast Error Variance Decomposition (FEVD)**: FEVD decomposes the forecast error variance into contributions from different components, such as trends, seasonality, and residual errors. It helps to understand the relative importance of each component in the forecast error.

In summary, time series forecasting is a valuable technique for predicting future values based on historical data. Understanding key concepts such as trends, seasonality, and stationarity is crucial for accurate modeling. Various techniques and models are available for time series forecasting, and evaluation metrics help assess the performance of the forecasts.
