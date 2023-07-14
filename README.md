# Quant_Trading_Stratigies

The project involves using Logistic regression models in order to predict the closing price of next trading session for the Nifty 50 index using a set of input variables derived from the OHLC data of the Index.

Using a set of input variables such as (C-L) > (H-C), (H>Ht-1) & (L>Lt-1) we fit the model on the preceding calendar year and use the present year to run the model and back test the trading strategy.

Based on the performance of the strategies created by the Logistic regression model, we evaluate the performance by comparing the two amongst themselves and against the benchmark
