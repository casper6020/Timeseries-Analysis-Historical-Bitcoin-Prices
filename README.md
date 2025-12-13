# <img src="https://cdn-icons-png.flaticon.com/128/11315/11315900.png" width="20" /> Motivation
The highly volatile nature of cryptocurrency market makes it an interesting environment to test popular time series models. Unlike traditional assets, cryptocurrencies lack intrinsic value, and operate without a central governing authority. Moreover, their prices are heavily influenced by human sentiment, market speculation, and evolving regulatory pressures.

## <img src="https://cdn-icons-png.flaticon.com/128/5431/5431282.png" width="20" /> Features
- __Moving Average__ Calculation
  - __SMA__ -> What's the average of the recent window?
  - __CMA__ -> What's the average of everything so far?
  - __EMA__ -> What's the recent trend, but with more importance on the newest data?

<p align="center">
    <img src="simple_moving_average.png" width="33%" alt="Image 1 Description" style="float: left; margin-right: 2%;">
    <img src="CMA.png" width="33%" alt="Image 1 Description" style="float: center; margin-right: 2%;">
    <img src="Exponential Moving Average.png" width="33%" alt="Image 2 Description" style="float: right; margin-left: 2%;">
</p>
<br clear="all" />

- __Stationarity__ Check
  - We check for stationarity because non-stationary data is unreliable for prediction.  
- __Differencing__ Method
  - When time-series data is non-stationary, we need to apply differencing to create stability for prediction.

<p align="center">
    <img src="differencing.png" width="50%" alt="Image 1 Description" style="float: center; margin-right: 2%;">
</p>
<br clear="all" />

- __Forecasting__ using __ARIMA__ Model
    - ARIMA (Autoregressive Integrated Moving Average)

<p align="center">
    <img src="time_series_forecast.png" width="50%" alt="Image 1 Description" style="float: center; margin-right: 2%;">
</p>
<br clear="all" />

## <img src="https://cdn-icons-png.flaticon.com/128/18289/18289400.png" width=20 /> Dataset
- __Title__:Historical Bitcoin Prices
- __Source__: Kaggle
- __Data Size__: (2042,13)
## <img src="https://cdn-icons-png.flaticon.com/128/8074/8074804.png" width=20 /> Libraries
- Pandas
- Numpy
- Statsmodel
- Datetime

## <img src="https://cdn-icons-png.flaticon.com/128/9623/9623606.png" width=20 /> Insights
- We learned that the historical bitcoin prices are non-stationary.
- From 2017, the bitcoin prices started to rise, and the price rose significantly until January 2018, with seasonal decrease.
- This increase in bitcoin prices at the end of 2017 can be attributed to excessive media coverage, limited supply, fear of missing out and overall growth in crypto industry.
- Since January 2018, the price started to fall, with seasonal increase.
