# TAR_Model_to_capture_long_trend
This is a simple R coding program to do with the economic indexs with TAR model. Threshold autoregressive model(TAR) is a time series model to analyze the change of rigeme of the time series. The detailed and instructive desciption is shown on www.ssc.wisc.edu/~bhansen/papers/saii_11.pdf. And the output is a csv and a graph of the time series with highlighted regimes.


## econometrics basics
TAR model can be seen as a basic ar process with a dummy variable on y to test the change of regimes. As any other mathematical models, we can know whether its effecive from the aspect of p value, AIC and other statistics.

## why it can capture the long trend?
We use the data of about 15 years (data in cleandata..csv). And the polts (plots in TAR_plot.zip) shows that we perfectly capure the characteristics of regimes when data is fluctuating on the high level, mid level and low level.
And as many literature said, this TAR model is accurate to capture the asymmetric pattern of the real economy data.
