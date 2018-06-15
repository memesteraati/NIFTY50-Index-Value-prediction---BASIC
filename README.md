# NIFTY50-Index value-prediction using python---BASIC
Test pet project(from scratch) to map and test the correlations between NIFTY50 Index &amp; NASDAQ Index, USD/INR Exchange rate, WTI Crude oil price using the most suitable machine learning model/s.

Problem Clarification:

Predict future (next 6 months-TEST) value of NIFTY50 index when the data from the following Macroeconomic data(past 18 months data-TRAINING):

* NIFTY50 index value (CNX Nifty)
* NASDAQ composite index value (IXIC)
* USD/INR exchange rate
* WTI Crude oil price value

Any and all requisite financial data for the mentioned 2 years can be found at Quandl.
https://www.quandl.com/tools/python
Examples:
https://www.quandl.com/data/NSE/NIFTY_50-National-Stock-Exchange-of-India-NSE-Stock-Index-Nifty-50
https://www.quandl.com/data/NASDAQOMX/COMP-NASDAQ-Composite-COMP
https://www.eia.gov/dnav/pet/hist/RWTCD.htm
https://www.quandl.com/data/CUR/INR-Currency-Exchange-Rates-USD-INR

Framework: 
- Apache MxNet with Gluon deep learning interface and Module APIs (Python)
- https://mxnet.incubator.apache.org/install/index.html?device=MacOS&language=Python&processor=CPU
- https://github.com/gluon-api/gluon-api
- Do visit https://gluon.mxnet.io/ for further clarification.
- https://github.com/quandl/quandl-python

Run the Gluon Test python program - running a 2 layer NN for training and testing an MNSIT data set, in the repository to validate prerequisites.

OBJECTIVES:
1. Find out the most suitable ML/Deep learning model for the given time series analysis.
2. Calculate and optimize the Mean Absolute Error (MAE) for actual and predicted prices.
3. Hypothesis testing to test hypothesis analysis correlation between stock markets/indices.
4. Map the correlation percentage of each of the given macroenomonic factors with the CNX Nifty to facilitate work into fundamental market analysis of CNX Nifty and further work into efficiency of fundamental analysis for CNX Nifty.



