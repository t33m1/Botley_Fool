# **Botley Fool**
## An Anlysis of Technical Indicators Used for Trading - Analyzed Across Different Markets to Determine Which May or May Not Provide the Best Indication

## Trading Strategies:
* Buy five shares in three companies across three markets - Healthcare, Oil & Gas, and Technology.
* Utilize Alpaca to buy the different positions and create the portfolio.
* Choose the most commonly used indicators then run an alysis.
* Use the AlphaVantage API to retrieve technical indicator performance for each position in our portfolio at an hourly interval.

## Most Commonnly Used Technical Indicators:
### OSCILLATORS: Construct high and low bands between two extreme values, and then builds a trend indicator that fluctuates within these bounds.
1. Traders use the trend indicator to discover short-term overbought or oversold conditions.
	1. When the value of the oscillator approaches the upper extreme value, analysts consider the asset to be overbought.
	1. When the value of the oscillator approaches the lower extreme value, analysts consider the asset to be oversold.
	
* MACD: Calculated by subtracting the 26-period EXPONENTIAL MOVING AVERAGE (EMA) from the 12-period EMA; the result of that calculation is the MACD.
	* When MACD is positive, the short-term average is located above the long-term average; this is an indication of upward MOMENTUM.
	* When MACD is negative, the short-term average is located below the long-term average; this is an indication of downward MOMENTUM.
	    	* Many traders will also watch for a move above or below the zero line. A move above zero signals a buy, while a cross below zero signals to sell.
	    	* Based on the assumption that the tendency of the price of a traded asset is to revert to a trend line.
		* To discover the trend line, look at the MOVING AVERAGE of asset prices over different time periods, i.e. 50/100/200 days.
* RSI: Compares the size of recent gains to recent losses to determine an asset's price MOMENTUM, either up or down.
	* The RSI was designed to indicate whether a security is overbought or oversold in relation to recent price levels.
	* The RSI is calculated using average price gains and losses over a given period of time.
	* The default time period is 14 periods with values bounded from 0 to 100.
* BOLLINGER BAND: A technical indicator that has bands generally placed two STANDARD DEVIATIONS away from a SIMPLE MOVING AVERAGE.
	* A move toward the upper band suggests the asset is being overbought and a move closer to the lower band suggests the asset is being oversold. 
	* Since STANDARD DEVIATION is used as a statistical measure of VOLATILITY, this indicator adjusts itself to market conditions.
* SIMPLE MOVING AVERAGE (SMA): Calculates the mean of a given set of prices over the specific number of days in the past; i.e. over the previous 15/30/100/200 days.
* EXPONENTIAL MOVING AVERAGE (EMA): Weighted average that gives greater importance to more recent stock price making it more responsive to new trends.
* (OBV): ......
* MONEY FLOW (MFI): Unlike conventional oscillators such as the Relative Strength Index (RSI), MFI incorporates both price and volume, as opposed to just price.
	* For this reason, some analysts refer to MFI as the volume-weighted RSI.
* STOCHASTIC: A MOMENTUM indicator comparing a particular closing price of a security to a range of its prices over a certain period of time.
	* The sensitivity of the oscillator to market movements is reducible by adjusting that time period or by taking a MOVING AVERAGE of the result.
	* It is used to generate overbought and oversold trading signals, utilizing a 0–100 bounded range of values.

## Top 5 Most Commonly Used Oscillating Indicators:
* MACD
* RSI
* BBANDS
* SMA/EMA
* OBV

## Factors used in Oscillators			
* MOMENTUM: Indicates if prices are increasing at an increasing rate or decreasing at a decreasing rate; look for uptrend, then use RSI to determine entry or exit.
* MOVING AVERAGES: When price crosses above MOVING AVERAGE trade long; when price crosses below MOVING AVERAGE trade short.
	* For example, if a stock rises above its 200-day MOVING AVERAGE, that might be taken as a bullish signal.
* VOLUME: how much of a certain financial asset has been traded in a period of time.
* VOLATILITY: .....
	* BETA: Approximates the overall volatility of a security's returns against the returns of a relevant benchmark (usually the S&P 500 is used).
		* For example, a stock with a beta value of 1.1 has historically moved 110% for every 100% move in the benchmark, based on price level.
		* Conversely, a stock with a beta of .9 has historically moved 90% for every 100% move in the underlying index.
	* STANDARD DEVIATION: The difference in a stocks price change between a set interval
		* For example: from market open to close; or with swing trading, using a longer inerval such as a week or month)
