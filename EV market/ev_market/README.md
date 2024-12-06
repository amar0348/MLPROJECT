
# EV Market Forecast Analysis

## Overview
This project analyzes the Electric Vehicle (EV) market dataset to predict future sales trends and market growth. Using time series analysis and forecasting techniques like ARIMA and SARIMAX, the analysis predicts the future trajectory of EV sales and provides insights into market behavior. The focus is on understanding how sales are expected to increase and how various features of the EV market may evolve over time.

## Dataset
The dataset contains monthly data related to vehicle sales in the Electric Vehicle (EV) market, with columns such as:
- **YEAR**: The year of data entry
- **2 W, 3 W, 4 W, BUS**: Different product categories in the market
- **TOTAL**: Total sales for that period

## Objectives
- To explore trends in the EV market using time series analysis.
- To forecast future sales for the next 12 months based on historical data.
- To identify key patterns and seasonality that could affect the growth of the EV market.

## Tools and Libraries
- **Python**: Programming language used for analysis.
- **Pandas**: For data manipulation and analysis.
- **Matplotlib**: For plotting graphs.
- **Statsmodels**: For time series analysis and forecasting (SARIMAX model).
- **NumPy**: For numerical operations.

## Steps
1. **Data Preparation**: Clean the dataset, ensuring that it is in a time series format.
2. **Stationarity Check**: Conduct Augmented Dickey-Fuller (ADF) tests to check if the series is stationary.
3. **Modeling**: Fit ARIMA and SARIMAX models to the dataset to identify the most suitable forecasting model.
4. **Forecasting**: Use the fitted models to forecast future sales for the next 12 months.
5. **Analysis**: Interpret the forecast results, including trends, seasonality, and confidence intervals.

## Results
- The forecast shows an increasing trend in EV market sales, indicating the market's expected growth over the next 12 months.
- The results provide valuable insights for businesses and policymakers looking to understand the future dynamics of the EV market.