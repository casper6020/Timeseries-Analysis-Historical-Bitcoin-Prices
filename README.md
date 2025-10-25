# <img src="https://cdn-icons-png.flaticon.com/128/18492/18492156.png" width=20/> Timeseries-Analysis-Historical-Bitcoin-Prices
In this repository, we conducted time series analysis on historical bitcoin prices and applied ARIMA model to predict future prices.

<p align="center">
    <img src="Exponential Moving Average.png" width="45%" alt="Image 1 Description" style="float: left; margin-right: 2%;">
    <img src="time_series_forecast.png" width="45%" alt="Image 2 Description" style="float: right; margin-left: 2%;">
</p>
<br clear="all" />

## <img src="https://cdn-icons-png.flaticon.com/128/3176/3176324.png" width="20" /> Objectives
- Calculate Simple, Cumulative and Exponential Moving Averages.
- Check for Stationarity in the data.
- Apply ARIMA model for forecasting.

## <img src="https://cdn-icons-png.flaticon.com/128/18289/18289400.png" width=20 /> Dataset
- __Title__:Historical Bitcoin Prices
- __Source__: Kaggle
- __Data Size__: (2042,13)
## <img src="https://cdn-icons-png.flaticon.com/128/6259/6259277.png" width=20 /> Libraries
- Pandas
- Numpy
- Statsmodel

## <img src="https://cdn-icons-png.flaticon.com/128/1844/1844921.png" width=20 /> Evaluation Metrices
- ADF (Augmented Dickey-Fuller) Test to check statinarity. 

## <img src="https://cdn-icons-png.flaticon.com/128/9623/9623606.png" width=20 /> Insights
- We learned that the historical bitcoin prices are non-stationary.
- From 2017, the bitcoin prices started to rise, and the price rose significantly until January 2018, with seasonal decrease.
- Since January 2018, the price started to fall, with seasonal increase.
