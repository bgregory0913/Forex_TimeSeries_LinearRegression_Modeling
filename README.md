<h3 align="center">Time Series & Linear Regression Modeling</h3>
<p align="center">
  <a href="ttps://https://github.com/bgregory0913/Forex_TimeSeries_LinearRegression_Modeling">
    <img src="forex_img.png" alt="yen_futures" align="center">
  </a>
</p>

# __Linear Regression and Time Series Modeling of ForEx Futures__

## Comparing Time-Series and Linear Regression models to predict Yen futures returns.

### Project Purpose:
1. Time Series_Analysis:
    1. Create time-series models of Yen historical exchange rate futures to predict behavior.
1. Linear Regression Analysis:
    1. Use Scikit-Learn linear regression modeling to predict Yen futures returns with lagged Yen futures returns and categorical calendar seasonal effects.


### Project Overview:
The financial departments of large companies often deal with foreign currency transactions while doing international business. As a result, they are always looking for anything that can help them better understand the future direction and risk of various currencies. Hedge funds, too, are keenly interested in anything that will give them a consistent edge in predicting currency movements.

In this code, we can test time-series tools in order to predict future movements in the value of the Japanese Yen versus the U.S. dollar.


### Findings:
#### Time-Series Analysis
1. Based on the time-series analysis models, the Yen is performing well and indicates decent chance for future returns but with increasing risk.
1. The risk/volatility of the Yen is expected to increase.
1. The models created do not provide enough confidence to use for trading.

#### Linear Regression Analysis
1. The predicted returns and the actual returns are too far off to consider this a confident model.
1. The in-sample RMSE is higher than the out-of-sample RMSE by about 0.15 and the out-of-sample should be higher than the in-sample RMSE.
1. The model may either need more data or needs to be tuned to be used as a more confident predictor.


### Built With:
This project is written in Python using Jupyter Notebook in combination with tha following modules:
* [JupyterNotebook](https://jupyter.org/)
* [Python](https://www.python.org/)
* [Pandas](https://pandas.pydata.org/)
* [NumPy](https://numpy.org/)
* [scikitLearn](https://scikit-learn.org/stable/)
* [StatsModels](https://www.statsmodels.org/stable/index.html)
* [ARCH](https://pypi.org/project/arch/)
   
   
## Using the Tool:
To setup an instance of this project on your own, install Jupyter Notebook [JupyterNotebook](https://jupyter.org/), as well as the following Python modules:

pip install Pandas
pip install -U scikit-learn   
pip install --user -U numpy
pip install statsmodels
pip install arch

This is supported on Windows, MacOS, and Linux operating systems.
