# S&P500-Equity-Forecasting

**Overview**

This project investigates how machine learning techniques can forecast stock prices using historical market data and macroeconomic factors. The objective was to evaluate how effectively a predictive model could capture future price movements. Forecasting was compared across a range of some of the largest companies in the S&P 500.
The analysis includes data collection, inflation adjustment using CPI data and price forecasting using an MLP neural network.

**Project Components**

-	Collected historical data using Yahoo Finance
-	Performed explanatory analysis of price trends + volatility 
-	Adjusted stock prices for inflation using CPI data
-	Created time series for forecasting
-	Developed MLP forecasting model
-	Tested the impact of different training window lengths

  <img width="2444" height="910" alt="image" src="https://github.com/user-attachments/assets/a860a835-d19e-4c16-b26f-e3cb9a9dc267" />
  Comparison of stock performance across selected S&P 500 companies over a sample period
  
<img width="2050" height="1000" alt="image" src="https://github.com/user-attachments/assets/dc1d3000-3f3b-42b6-9d2f-d649e7629d0e" />
MLP model achieved RMSE of 12.2 when forecasting inflation-adjusted prices for Microsoft
<img width="798" height="394" alt="image" src="https://github.com/user-attachments/assets/b1d67011-5d08-44d7-8e74-13ca6992be50" />
Comparison of forecasting accuracy across companies using MAE and RMSE

  
**Results**

-	Goldman Sachs had the strongest performance over the 252 trading days, with its increase by around 76%, whilst Microsoft decreased by approximately 20%.
-	Shorter training windows generally produced more accurate forecasts, with a 6-month window outperforming longer windows.
-	Forecasting performance varied dramatically across companies, with Bank of America having the lowest prediction error (RMSE = 1.28) whilst Tesla and Goldman Sachs were far harder to model accurately, with each having an RMSE of 18.50 and 17.52, respectively.
-	Stocks that were less volatile and had smoother price trends tended to generate the most reliable forecasts.
Overall, the results suggest the machine learning models can capture broad price trends for less volatile stocks, but forecasting accuracy drops and market volatility decreases.

**Technology used**

Python, pandas, NumPy, matplotlib, seaborn, scikit-learn, yfinance and Jupyter Notebook.





