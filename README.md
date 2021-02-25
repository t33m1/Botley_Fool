# **Botley Fool**
## An Anlysis of Technical Indicators Used for Trading

## Analysis Strategy:
1. Buy five shares in three companies across three markets - Healthcare, Oil & Gas, and Technology.
1. Utilize Alpaca to buy the different positions and create the portfolio.
1. Choose the most commonly used indicators then run analysis on them over time on each postion in our portfolio.
1. Use the AlphaVantage API to retrieve technical indicator performance for each position in our portfolio at an hourly interval.

## Technical Indicators We Will Use:
* MACD: Calculated by subtracting the 26-period EXPONENTIAL MOVING AVERAGE (EMA) from the 12-period EMA; the result of that calculation is the MACD.
	* When MACD is positive, the short-term average is located above the long-term average; this is an indication of upward MOMENTUM.
	* When MACD is negative, the short-term average is located below the long-term average; this is an indication of downward MOMENTUM.
* RSI: Compares the size of recent gains to recent losses to determine an asset's price MOMENTUM, either up or down.
	* Designed to indicate whether a security is overbought or oversold in relation to recent price levels.
	* Calculated using average price gains and losses over a given period of time.
	* The default range observed between 30 and 70.
* BOLLINGER BANDS: A technical indicator that has bands generally placed two STANDARD DEVIATIONS away from a SIMPLE MOVING AVERAGE.
	* A move toward the upper band suggests the asset is being overbought and a move closer to the lower band suggests the asset is being oversold. 
* SIMPLE MOVING AVERAGE (SMA):
    * Calculates the mean of a given set of prices over the specific number of days in the past; i.e. over the previous 15/30/100/200 days.
* EXPONENTIAL MOVING AVERAGE (EMA):
    * Weighted average that gives greater importance to more recent stock price (example - 12 days) making it more responsive to new trends.

# Summary of Major Findings:
* The original intent was to choose a few indicators and place trades based on those indicators and/or a combination of indicators and __analyze__ which indicator or indicator combination produced the best gains (results).

## Is MACD a Better Trading Strategy Indicator Than Using SMA & EMA in Combination?
* Absolutely, in our opinion.
    * MACD actually takes the 26 period EMA and subtracts it from the 12 period EMA.
    * MACD is a Leading indicator since it can provide insight on on upward or downward trend
## Is Bollinger Bands a Better Indicator than MACD?
* We found that MACD is better for quick trades ad Bollinger Bands is better for longer trades.
## Is Bollinger Bands by Itself a Better Indicator than When Combined With RSI?
* If we were to __actually__ trade, the Bollinger Bands strategy would have been slightly more efficient than RSI since it signals a buy or sell sooner than RSI does.
    * Combining RSI and Bollinger Bands in a single trading algorithm could help filter out some of the false buy or sell signals. 
## How Could we Follow Trends to Trade With Accuracy using Historical Data With the Lowest Risk?

## Has MACD or RSI Historically Helped Forecast the Best Returns?
* MACD, without a doubt, and this is based on all historical data we found on the internet by creating our own plots on various tickers
    * While they are both __leading__ indicators, MACD tends to have quicker foresight
## Which Indicators or Group of Indicators has the Best Results?
* MACD and Bollinger Bands
 
