# Sales-forecasting-using-SARIMA

In this project I have used the Seasonal Auto-Regressive Integrated Moving Average model (a type of ARIMA) to forecast the sales.

It can be applied to any sales data, after doing some changes according to the dataset.

It works for both seasonal or non-sesonal data.

How to use this:
1. The dataset file(.csv) should be kept in the dataset folder.
2. And the directory path should be changed in the main.ipynb file.
3. The product_wise.ipynb can be used: If the data is combined, eg: of a retail store, so sales of all the products   will be in a single csv file. So this code can be used to seperate the data product wise.
4. A few things in the main.ipynb should be modified according to the dataset to get the perfect result.
#Details:
ARIMA: Autoregressive Integrated Moving Averages
## Process:
1. Visualize the data
2. Make the data stationary if its not
3. Plot correlation and autocorrelation charts
4. Construct the arima/sarima model
5. make predictions

Dickey–Fuller(Null hypothesis) test was done to check if the data is stationary or not.
