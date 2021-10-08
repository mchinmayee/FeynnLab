# Steps: ARIMA Model

## 1.	Read  dataset and check for seasonality
 Read csv_file
Analyse trend, seasonal, residual properties
Use Exponential smoothing to forecast features as : trend, seasonal, residual
## 2.	Find train and test sets
Split data in to train and test datases.	
## 3.	 Check for Stationary
``a)	Augmented Dickey Fuller test
	If p_value >0.05 then dataset is non-stationary and has a unit root
b)	Go for differentiation (d value)
	Check the order of derivative where the p-value < 0.05
``
## 4.	Set p and q values
Use ACF plot and PACF plot to find p and q values
p denotes the value for AR model
q denotes the values for MA model
## 5.	Build the model
``Fit the model
    Find prediction values
    Forecast future values.
``