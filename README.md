Trading Bot Concept and Blueprint: 

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

    5- Testing and resutls. 

We need to define what STRATEGY means before proceeding any further. 
Strategy: consits of multiple pieces that need to allign in order for a signal to be issued. 

Understanding the term strategy is crucial in working on this project. Using multiple factors and blending in a group of indicators under a single unmbrella is called a strategy. Our strategy consits mainly on moving avergaes such as simple and exponent moving avrages and traking the pivot points when they cross each others will be the main key to determining the market direction. We can strenghten the validity of these signals by implementing RSI, or Macd restrictions to reduce weak calls. 

 1- Tracking price movment: There are many methods that can be used to tack price movement, but the main goal of this step is to determine if there trend is going up or down. One way to tell is by looking at the moving averages and target the instance when they cross. One famous method is using the 100 SMA or EMA as a hard guide of trend reversals. When the price is above the 100 EMA or SMA, it indicates an uptrend and when the price is under, it indicates a downtrend. We can also track the behavoir of the 20 and 50 moving averages to catch trend reversals. Additionally, these moving averages values can be costumized such as using the famous option's trading 4,9,18 moving averages for a fast paced day trading opportunities. 

 2- Setting trading restrictions: since this bot is meant to trade automatically, we have to cooperate a restriction condition or a few of them to ditch weak signals such as issuing a buy signal when the RSI is in the overbought zone, and issing a sell order when the RSI is in the oversold zone as massive losses can occure. This can be acheived by using other indicators such as MACD crossover. 

 3- Printing buy/sell/exit signals: This step requires printing buy/sell and exit signals on the chart. This can also notify the system to issue these calls for automated trading bot to talk to the api to execute these orders in exchange when deployed. 

 4- Implenting a stop loss to cut down losses: Stop loss should act as a mechanism to reduce losses if the trade goes the other direction before it is too late. This can be implemented in a percentage increaments such as 5, 10 or 20 percent loss. It can also be costumized depending on the user's loss tolerance. in addition, this can acheived by using Average True Range as a reference. This strategy will experiment with ranges where the loss is not significantly high and to handle fake outs at the same time where the price might move to the opposite direction for liquidity grab. One way of acheiving this is to use a stop loss that is 2 times the Average True Range value.

 5- Testing and resutls: in order for a strategy to be succesfull and before it is deployed,it has to acheive a good winning rate. The testing will consit of using $100 worth of paper trading to back test and tweak for any changes required to acheive a good resutls. 

Will be updated later ... 


