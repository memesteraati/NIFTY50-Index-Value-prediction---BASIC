# NIFTY50-price-prediction using python---BASIC
Test pet project(from scartch) to map and test the correlations between NIFTY50 Index &amp; NASDAQ Index, USD/INR Exchange rate, International Oil price using machine learning models.

Problem Clarification:

Predict future (next 6 months-TEST) value of NIFTY50 index when the data from the following Macroeconomic data(past 18 months data-TRAINING):

* NIFTY50 index value (CNX Nifty)
* NASDAQ composite index value (IXIC)
* USD/INR exchange rate
* WTI Crude oil price value

Any and all requisite financial data for the mentioned 2 years can be found at Quandl.
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

OBJECTIVES:
1. Find out the most suitable ML/Deep learning model for the given time series analysis.
2. Calculate and optimize the Mean Absolute Error (MAE) for actual and predicted prices. 



