# TimeSeries-HWK

In the initial Time-Series Plotting, the overall long term uptrend of the Yen futures illustrates the Yen's strenghtening against the dollar over years/decades. On lower timeframes(daily/weekly), we would see much more chop in the short run (daily) while the intermediate timeframe (weekly) gives us some larger trends to the up or downside.

The ARMA model isn't a good fit due to the fact that none of the p-values in the summary table are below 0.05. Most likely, the model needs to adjust the lag order or add input variables to make it more statistically signficant. Despite the low signficance, the 5 day forcast shows returns in the black for the Yen futures.

Based on the p-values, the ARIMA model is not a good fit as none are p < 0.05, thus not statistically significant. The graph illustrates a rising Yen over the next 5 days which is a similar forecast by the ARMA model.

The Garch model had a much better performance than either the ARMA/ARIMA models, with all but one having p-values < 0.05. This alludes to the common saying in financial markets that "volatility is easier to forecast than prices or returns."

## Conclusions

Based on the time series analysis, I would buy the Yen now with the expectation that it would rise over the next 5 days. Even so, risk is forecasted to also rise; thus, there may be some higher volatility in the price swings. I better keep a close eye on the charts.

The Garch model looks pretty good with only one run not holding a statistical significance. I'd say that's a much more reliable model of volatility than the ARMA/ARIMA predictions for returns/prices. I wouldn't bet the bank on the latter two.
