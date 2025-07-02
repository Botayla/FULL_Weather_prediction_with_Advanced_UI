#### Project about predict  the full weather report of India/delhi 
*about the data*
get the data from kaggle , data have 1463 record about the weather starting from day 1/1/2013 to 1/1/2017

<div style="border-radius: 50px; background: #A55B4B; color: white; padding: 10px; text-align: center; font-size: 25px;">
    Data preprocessing

</div>
plot each column to know if the graph is stationary or not with plot function and seasonal decompose to get the trend,seasonality,residual in the graph
plot the acf(autocorrelation function ) and pacf(partial autocorrelation function)
test for stationary with augmented dicky fualler test (adfuller function ) and get the number of diffrences to make the graph station

<div style="border-radius: 50px; background: #A55B4B; color: white; padding: 10px; text-align: center; font-size: 25px;">
    Model

</div>
****Facebook Prophet Model Details:** (Prophet) Model Details:**
    
    - Univariate time series forecasting model developed by Meta (Facebook)
    - Captures trends, seasonality, and holiday effects
    - Automatically detects change points in weather pattern    
    - Trained separately for each weather variable (Temperature, Humidity, Wind Speed, Pressure)
    - Ideal for daily weather data with seasonality and trend
