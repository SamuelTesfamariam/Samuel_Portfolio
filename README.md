# Samuel's Portfolio of Projects

## Project 1: Forecasting the Global Price of Metal Index using ARIMA Model
1. Streamed data from FRED for the global index of metal prices (ticker: PMETAINDEXM)
2. Run an Augmented Dicky Fuller test (ADF) to test for Unit root
  - Here I used the Ender's approach to test for unit root.
  - I also transformed the data as needed to achieve stationarity in the series
3. Estimated an ARIMA model (ARIMA (1, 1, 1)
4. Run a test prediction on a hold-out sample (test data)
5. Finally made a six month forecast for the series.

![](https://github.com/SamuelTesfamariam/Samuel_Portfolio/blob/main/Images/Plot%20of%20the%20series.png)
![](https://github.com/SamuelTesfamariam/Samuel_Portfolio/blob/main/Images/Series%20transformation.png)
![](https://github.com/SamuelTesfamariam/Samuel_Portfolio/blob/main/Images/ADF%20Test%20results.PNG)
![](https://github.com/SamuelTesfamariam/Samuel_Portfolio/blob/main/Images/ACF_PACF%20plot.png)
![](https://github.com/SamuelTesfamariam/Samuel_Portfolio/blob/main/Images/Models%20comparison.PNG)
![](https://github.com/SamuelTesfamariam/Samuel_Portfolio/blob/main/Images/estimated%20model%20fit%20and%20residuals.png)
![](https://github.com/SamuelTesfamariam/Samuel_Portfolio/blob/main/Images/forecast%20vs%20actuals.png)
![](https://github.com/SamuelTesfamariam/Samuel_Portfolio/blob/main/Images/6%20month%20forecast.png)
