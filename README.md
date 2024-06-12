# Sales_Forecasting_using_Excel
Forecasting
•	Forecasting is a must skill for any data science enthusiast. Learn step-by-step how to forecast in Excel using 3 methods 
1.	function 
2.	graph trend line 
3.	forecast sheet
•	FORECAST - predicts future values by using linear regression; a legacy function for backwards compatibility with Excel 2013 and earlier.
•	LINEAR - identical to the FORECAST function; part of the new suite of forecasting functions in Excel 2016 and Excel 2019.
The four ETS functions are purposed for exponential smoothing forecasts. These functions are only available in Excel for Office 365, Excel 2019, and Excel 2016.
•	ETS - predicts future values based on the exponential smoothing algorithm.
•	ETS.CONFINT - calculates the confidence interval.
•	ETS.SEASONALITY - calculates the length of a seasonal or other recurring pattern.
•	ETS.STAT - returns statistical values for time series forecasting.
Excel FORECAST function
The FORECAST function in Excel is used to predict a future value by using linear regression. In other words, FORECAST projects a future value along a line of best fit based on historical data.
=FORECAST(x, known_y’s, known_x’s)
The FORECAST function uses the following arguments:
1.	X (required argument) – This is a numeric x-value for which we want to forecast a new y-value.
2.	Known_y’s (required argument) – The dependent array or range of data.
3.	Known_x’s (required argument) – This is the independent array or range of data that is known to us

