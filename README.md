# Aurabit Capital Assignment

##### high frequency market making trading strategy and data processing

## Questions :

### 1. Given the historical data, could you make any observations for market statistics? 
You can think along these lines but feel free to be more creative and go beyond these examples and directions:
- a) Are there any patterns in volume/volatility/number of trades/number of book orders?
- b) Are there any seasonality effect on the market? For example, any effect grouped by weekday, by month, or day of the month, etc.?
- c) How about some intra-day seasonality patterns? For example, it is well known that traded volumes in most intraday market follow an U shaped pattern, with market open being the most liquid time of the day, and gradually decaying afterwards
- d) How about some periods with relatively high return or low return on the stock, or periods with relatively low or high volatility, can you make any interesting observations about these periods?

### 2. Could you try to find features or models to forecast the direction of the stock?
- a) You can work to choose any kind of prediction horizon, for example, 1Min/5min/10min/1hour return
- b) You can also only select and work on a specific period of the day. For example, you can try to make a model only to predict the expected return after auction period, or the expected return after lunch break, etc.
- c) You can choose to work on any features that you think might be of interest. For example, is past return useful to predict future return? If so or if not, you can write your analysis process and result.
- d) How do you evaluate the fitness of your features or models? Please explain your methodology and analysis carefully. You can choose your own method of designing the in sample and testing data during the 4-month historical data.
- e) If you manage to find something that can be of predictive power, either a single feature or a more complex model, how would you construct a trade around it? Would your trade be sensitive to transaction cost or market bid offer spread? 