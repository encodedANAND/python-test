# python-test

We have analysed the financial stocks from National Stock Exchange (NSE) for companies like TCS, INFOSYS. We have used **'NSEpy'** library to get data from NSE. **NIFTY IT** data has also been analysed. 

Various operations performed on the dataset includes:<br/>
1. Handling of unequal time series data due to stock market holidays. **Linear Interpolation Technique** is used to get data for non-working days so as to maintain uniform time-series.
2. Calculating Moving Average on weekly basis for window size of 4 weeks, 16 weeks, 28 weeks,40 weeks and 52 weeks.
3. Calculating Volume Shocks ,i.e., Volume traded is 10% higher or lower than the previous day.
4. Calculating Price Shocks ,i.e., Price difference between that day and next day is more than 2%.
5. Calculating rolling window average for different window sizes on daily basis. Average is taken for window sizes of 10 days, 30 days,50 days and 75 days.

For Data Visualization, **Bokeh** library is used. This library provides immpressive visualizations.Basically, line plot is used to plot the daily stocks.
