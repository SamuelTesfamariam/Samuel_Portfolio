# [**Project 1: Forecasting the Global Price of Metal Index using ARIMA Model**](https://github.com/SamuelTesfamariam/Metal-Price-Index-Forecast)
1. Streamed data from FRED for the global index of metal prices (ticker: PMETAINDEXM)
2. Run an Augmented Dicky Fuller test (ADF) to test for Unit root
    - Here I used the Ender's approach to test for unit root.
    - I also transformed the data as needed to achieve stationarity in the series
3. Estimated an ARIMA(1, 1, 1) model after comparing different models
4. Run a test prediction on a hold-out sample (test data) for a forecast vs. actuals comparison
5. Finally made a six month forecast for the series.

![](https://github.com/SamuelTesfamariam/Samuel_Portfolio/commit/6ef0fc4c1a3552f0842025213a2617f41824da0d#diff-2561ec15da11043278a5e4f8a186347b698fd9e6d70d57ad3367054afc706fd4)

![](/Images/Series%20transformation.png)

![](/Images/ADF%20Test%20results.PNG)

![](/Images/ACF_PACF%20plot.png)

![](/Images/Models%20comparison.PNG)

![](/Images/estimated%20model%20fit%20and%20residuals.png)

![](/Images/forecast%20vs%20actuals.png)

![](/Images/6%20month%20forecast.png)
