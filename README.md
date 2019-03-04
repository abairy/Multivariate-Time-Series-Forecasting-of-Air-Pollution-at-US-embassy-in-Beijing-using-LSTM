# Multivariate-Time-Series-Forecasting-of-Air-Pollution-at-US-embassy-in-Beijing-using-LSTM

 Conducted Exploratory Analysis and Visualization using Pandas and Seaborn on the Beijing PM2.5 Dataset   
 Scaled, encoded and converted the Time Series data into a Supervised Learning data to feed the LSTM network  
 Evaluated by combining the forecast with the test dataset, inverting the scaling and achieving a test RMSE of 23.4
 
 This is a dataset that reports on the weather and the level of pollution each hour for five years at the US embassy in Beijing, China.

The data includes the date-time, the pollution called PM2.5 concentration, and the weather information including dew point, temperature, pressure, wind direction, wind speed and the cumulative number of hours of snow and rain. The complete feature list in the raw data is as follows:

No: row number
year: year of data in this row
month: month of data in this row
day: day of data in this row
hour: hour of data in this row
pm2.5: PM2.5 concentration
DEWP: Dew Point
TEMP: Temperature
PRES: Pressure
cbwd: Combined wind direction
Iws: Cumulated wind speed
Is: Cumulated hours of snow
Ir: Cumulated hours of rain

Download Dataset and run the LSTM.py file
