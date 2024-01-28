The purpose of this project is to elliminate Manual stocks/Crypto traidng  by crafting a strategy that signals a buy/sell order when market conditions allow for a succefull trade. 
This strategy should be also able to notify the trader or the automatic trading system of when to exit a trade. 
This project depends on charts provided by Tradingview platform which provides charts for both stocks and Crypto. These charts have different time frames that track and print price movments in the form of japanese trading candlesticks. 
Tradingview supports different time frames, but the main ones used by most traders are the 1, 5 and 15 min charts for day trading and the 1, 4 hours and the daily candle for swing trading. Tradingview also developed its own unique scripting 
language -PineScript- that allows for the creation of indicators and strategies which is what will be used to complete this project. It also allows for back testing of strategies by allowing backtrackingof upto 10000 bar. 

This strategy consists of the following main componets : 
    1- Tracking price movment. 
    2- Setting trading restrictions. 
    3- Printing buy/sell/exit signals. 
    4- Implenting a stop loss to cut down losses.  

We need to define what STRATEGY means before proceeding any further. 
Strategy: consits of multiple pieces that need to allign in order for a signal to be issued. 

Understanding the term strategy is crucial in working on this project. Using multiple factors and blending in a group of indicators under a single unmbrella is called a strategy. Our strategy consits mainly on moving avergaes such as simple and exponent 
moving avrages and traking the pivot points when they cross each others will be the main key to determining the market direction. We can strenghten the validity of these signals with implementing RSI, or Macd restrictions to reduce weak calls. 
