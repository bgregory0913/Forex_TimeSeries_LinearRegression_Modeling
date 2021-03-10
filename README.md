# Forex_TimeSeries_LinearRegression_Modeling

### Code Purpose:
1. TimeSeries_Analysis:
    1. A jupyter notebook file that reads Yen historical exchange rate futures and creates time-series models to predict behavior.
1. LinearRegression_Analysis:
    1. A jupyter notebook file that reads Yen historical exchange rate futures and uses Scikit-Learn linear regression modeling to predict Yen futures returns with lagged Yen futures returns and categorical calendar seasonal effects.

### Findings:
#### Time-Series Analysis
1. Based on the time-series analysis models, the Yen is performing well and indicates decent chance for future returns but with increasing risk.
1. The risk/volatility of the Yen is expected to increase.
1. The models created do not provide enough confidence to use for trading.

#### Linear Regression Analysis
1. The predicted returns and the actual returns are too far off to consider this a confident model.
1. The in-sample RMSE is higher than the out-of-sample RMSE by about 0.15 and the out-of-sample should be higher than the in-sample RMSE.
1. The model may either need more data or needs to be tuned to be used as a more confident predictor.