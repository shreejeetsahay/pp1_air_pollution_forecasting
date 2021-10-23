# Air Pollution Forecasting
## Problem Statement-
Given the dataset that reports on the weather and the level of pollution each hour for five years at the US embassy in Beijing, China.

The data includes the date-time, the pollution called PM2.5 concentration, and the weather information including dew point, temperature, pressure, wind direction, wind speed and the cumulative number of hours of snow and rain. The complete feature list in the raw data is as follows:
<ul>
    <li>No: row number</li>
    <li>year: year of data in this row</li>
    <li>month: month of data in this row </li>
    <li>day: day of data in this row</li>
    <li>hour: hour of data in this row </li>
    <li>pm2.5: PM2.5 concentration </li>
    <li>DEWP: Dew Point</li>
    <li>TEMP: Temperature</li>
    <li>PRES: Pressure</li>
    <li>cbwd: Combined wind direction</li>
    <li>Iws: Cumulated wind speed</li>
    <li>Is: Cumulated hours of snow</li>
    <li>Ir: Cumulated hours of rain</li>
</ul>
<b>PROBLEM-</b> Use this data such that given the weather conditions and pollution for prior time step forecast the pollution at the next hour.

<hr>
Please check the notebook file for the solution, where LSTM RNN is used to build the model.

