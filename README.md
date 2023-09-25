## ARIMA <br>

<br> Basic ARIMA model on a single product at one location using exhaustive search and best pick manual model comparison. High MAE for prototype model for around 30 products.
As ARIMA can't be optimized for MAE but only for RMSE, the model building is stopped here and a decent trend was predicted in the final run. <br>

Conclusion: The model was successfully trained for trend prediction (based on quantity here). Including more parameter or features would result in an accurate trend and quantity too based on sales, profit and other factors.
![image](https://github.com/kirtiitt/ARIMA/assets/137528591/68724100-307a-42f9-ad54-952042fd0ba7)
<br>
Observations: Instead of follwoing the linear growth here, exponential growth can also be used to manage the demands more accurately and practical situations.

References: https://github.com/gmonaci/ARIMA/blob/master/time-series-analysis-ARIMA.ipynb
