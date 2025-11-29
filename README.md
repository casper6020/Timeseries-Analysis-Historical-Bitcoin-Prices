# <img src="https://cdn-icons-png.flaticon.com/128/11315/11315900.png" width="20" /> Motivation
The highly volatile nature of cryptocurrency market makes it an interesting environment to test popular time series models. Unlike traditional assets, cryptocurrencies lack intrinsic value, and operate without a central governing authority. Moreover, their prices are heavily influenced by human sentiment, market speculation, and evolving regulatory pressures.

## <img src="https://cdn-icons-png.flaticon.com/128/3176/3176324.png" width="20" /> Objectives
- A detailed Exploratory Data Analysis
- Test Stationarity
- Apply Differencing Method
- Apply Forecasting Model

## <img src="https://cdn-icons-png.flaticon.com/128/18289/18289400.png" width=20 /> Dataset
- __Title__:Historical Bitcoin Prices
- __Source__: Kaggle
- __Data Size__: (2042,13)
## <img src="https://cdn-icons-png.flaticon.com/128/6259/6259277.png" width=20 /> Libraries
- Pandas
- Numpy
- Statsmodel

## <img src="https://cdn-icons-png.flaticon.com/128/1844/1844921.png" width=20 /> Evaluation Metrices
- ADF (Augmented Dickey-Fuller) Test to check stationarity. 

  
## <img src="https://cdn-icons-png.flaticon.com/128/9623/9623606.png" width=20 /> Insights
- We learned that the historical bitcoin prices are non-stationary.
- From 2017, the bitcoin prices started to rise, and the price rose significantly until January 2018, with seasonal decrease.
- This increase in bitcoin prices at the end of 2017 can be attributed to excessive media coverage, limited supply, fear of missing out and overall growth in crypto industry.
- Since January 2018, the price started to fall, with seasonal increase.

<p align="center">
    <img src="Exponential Moving Average.png" width="45%" alt="Image 1 Description" style="float: left; margin-right: 2%;">
    <img src="time_series_forecast.png" width="45%" alt="Image 2 Description" style="float: right; margin-left: 2%;">
</p>
<br clear="all" />
