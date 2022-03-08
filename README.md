# Backesting_with_python

Hello, world! I'm JP, an absolute newbie at data analysis. I'm finishing my Google Data Analytics Professional Certificate, so yes I need to create a presence around these platforms to acquire and demonstrate some new skills.
	This is my first project on this platform and also my first project related to data, it is not a coincidence the subject of this is related to trading strategies, as trading strategies and backtesting brought my attention into data analysis.
  Basically, I will fetch data from different sources and make visualizations to spot some characteristics, measure some specific values like volatility, then we will run a backtest using VectorBT, a python library for quantitative analysis based on Pandas and NumPy objects.
  
<b>The markets:</b> We will run the backtest of this strategy across a group of cryptocurrency pairs.

<b>The strategy:</b> This strategy has been documented by Larry Connors and Cesar Alvarez in their book Short Term Trading Strategies That Work, it consists in: 
  *While price action is above its 200 moving average, and 2-period RSI closes below 10 buy long. Close when price closes above 5day moving average.
  *While price action is below its 200 moving average, and 2-period RSI closes above 10 buy long. Close when price closes above 5day moving average.

<b>Data periods:</b>
	We will use a daily close price of 2 years (1/2019 to 1/2021).
  
<b>Objective:</b>
	Get insights about the use of mean reversion strategies across various markets and the relation volatility(Average True Range) / profitability(trades PnL in %) and explore and learn as much as I can about pandas, NumPy and matplotlib
  
This is of course not a “go and try this strategy”. It is just me learning how to use some python packages and pandas tools.
So <b>thanks a lot for reading this!</b>
