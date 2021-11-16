# Unit 10 Homework: A Yen for the Future - Rachel Pierce
#### November 2021

## Instructions:
### Two Main Tasks:
1. Time-Series Forecasting
2. Linear Regression Forecasting

#
### Please refer to the following documents in GitHub:
- The **time_series_analysis.ipynb** and **regression_analysis.ipynb** files (open in Jupyter Lab) for code details.

#

## Part 1 
### Time-Series Forecasting - Completed
1. Decomposition using a Hodrick-Prescott Filter (Decompose the Settle price into trend and noise) 
2. Forecasting Returns using an ARMA Model
3. Forecasting the Settle Price using an ARIMA Model
4. Forecasting Volatility with GARCH

#### **Part 1 Questions:**
1. Based on your time series analysis, would you buy the yen now?
2. Is the risk of the yen expected to increase or decrease?
3. Based on the model evaluation, would you feel confident in using these models for trading?  
*Answer:* No, I would not buy the yen now.  The forecast above is showing that volatility is going to increase over the next 5 days.  The risk will increase since volatility is forecasted to go up at each horizon.  I would feel confident in the model as it can predict volatility, which can support a decision to buy or sell depending on the data output.  In this case, the model is predicting higher volatility which supports my decision not to buy yen at this time.
#

## Part 2
### Linear Regression Forecasting - Completed
1. Data Preparation
2. Fitting a Linear Regression Model
3. Making predictions using the testing data
4. Out-of-sample performance
5. In-sample performance

#### **Part 2 Question:**
Does this model perform better or worse on out-of-sample data compared to in-sample data?  
- Out-of-sample RMSE: 0.415  
- In-sample RMSE: 0.596  
*Answer:* Typically, in-sample error will be lower than out-of-sample error; however, in this case, the in-sample error was 0.596, which is HIGHER than the out-of-sample error of 0.415.  This means that the model performed better on out-of-sample data compared to in-sample data.


