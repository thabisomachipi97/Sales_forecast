# Sales_forecast
Sales forecasting using multiple models - Seasonal Naïve, Holt-Winters, ARIMA, SARIMA and Linear Regression Model

## Project Objective
### Goal of the Project

This project aimed to leverage various quantitative methods, including Time Series Models and Causal Models, to forecast product sales within the dataset.

Key steps undertaken:

    1. Conducted time series analysis to explore the data and identify trends.
    2. Applied multiple forecasting models to the training dataset.
    3. Selected the most accurate model to generate forecasts on the test dataset.

Models covered in the notebook include:
1. Seasonal Naive Model
2. Holt-Winters Model (Triple Exponential Smoothing)
3. ARIMA Model and Seasonal ARIMA Models
4. Linear Regression Model

## Conclusion
We explored various time-series models along with a regression model for forecasting. Our results showed that the linear regression model performed better than the other time-series models. Consequently, this dataset is better suited for forecasting sales using a regression model rather than traditional time-series approaches. A key assumption of regression models is that historical patterns will persist into the future. Given that our data exhibited strong seasonality and a linear trend, it is understandable why the linear regression model outperformed the others.
