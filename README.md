# Prediction-in-Time-Series-Dataset
- Project 1 for UCS757: Building Innovative Systems, Thapar Institute. 

## Context
- A time series dataset based on road pavement is given. Different values from sensors are recorded by some IoT based firm.

## Task
- The task is to predict Parameters 9-13 for year 10 and compare the obtained results with the given data. The evaluation paramter is taken as RMSE.

## Approach
-  The approach I followed is to clean and reshape the data first that makes it easier to handle and work on. After verifying the shape of training and test data sets I applied the models available for Time Series Dataset, a few to mention:
    - Moving Average (MA)
    - Autoregressive Moving Average (ARMA)
    - Autoregressive Integrated Moving Average (ARIMA)
    - Seasonal Autoregressive Integrated Moving-Average (SARIMA)
    
- After training our 9 year sensor values on these models available, we predicted values for the 10th year and compared with already available data to find out the Root Mean Square Error.

## Conclusion
- I found the best working model to be Autoregressive Moving Average (ARMA). Though it depends on how someone has cleaned or transformed the data. The RMSE for this model is found to be 47.53224774629032.
