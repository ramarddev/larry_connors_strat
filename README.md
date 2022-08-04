# Larry Connors Tradingzone Strategy

This a bot to trade with the strategy from Trading Zone YouTube channel, using theese indicators and configurations:
- MA 10
    - To determine if we can get the trade or not
- MA 200 / EMA 200
    - To see trend. If price above MA/EMA only buys and price under only sells
- RSI 2
    - RSI of 2 periods
    - Oversell under 10 and 
    - Overbuy above 90
- ATR
    - This is used to set the Stop Loss 

The rules for this strategy are:
- Buy
    1. Price above MA/EMA 200
    2. Price under MA10
    3. Price oversell

- Sell
    1. Price under MA/EMA 200
    2. Price above MA10
    3. Price overbuy

Then, for the Stop Loss we use the ATR 1.5

For the Take Profit:
- Buys
    - Price cloeses above MA10
- Sells
    - Price closes under MA10
