# Trading Bot

Steps to making a trading bot
- Choose an exchange
- Connect to the exchange's API
- Determine your `trading strategy`
- Implement `bot`
- Test and debug your bot
- Deploy your bot

**What is trading strategy?**

`Algorithmic trading:` A strategy that involves using computer programs to automate the process of buying and selling assets based on a set of predetermined rules.

`Trend following:` A strategy that involves buying an asset when its price is trending upwards and selling it when the trend is downward.

`Momentum trading:` A strategy that involves buying an asset that is showing strong price momentum and selling it when the momentum starts to decline.

`Mean reversion:` A strategy that involves buying an asset when it is undervalued and selling it when it is overvalued, based on the assumption that its price will eventually revert back to its average value.

`Arbitrage:` A strategy that involves taking advantage of price discrepancies between different markets or exchanges to buy an asset at a low price and sell it at a higher price.

`Fundamental analysis:` A strategy that involves analyzing a company's financial health, industry trends, and other fundamental factors to determine the intrinsic value of its stock.

`Technical analysis:` A strategy that involves using past price and volume data to identify trends and make trading decisions.

`Index fund rebalancing:` A strategy that involves buying and selling stocks in an index fund to keep the portfolio balanced and aligned with the underlying index.

`Volatility trading:` A strategy that involves buying and selling assets based on changes in their volatility, with the aim of profiting from price swings.

`Market making:` A strategy that involves continuously buying and selling an asset to facilitate trade and earn the bid-ask spread.

`Trend-Following Strategies`
The most common algorithmic trading strategies follow trends in moving averages, channel breakouts, price level movements, and related technical indicators. These are the easiest and simplest strategies to implement through algorithmic trading because these strategies do not involve making any predictions or price forecasts. Trades are initiated based on the occurrence of desirable trends, which are easy and straightforward to implement through algorithms without getting into the complexity of predictive analysis. Using 50- and 200-day moving averages is a popular trend-following strategy.

`Arbitrage Opportunities`
Buying a dual-listed stock at a lower price in one market and simultaneously selling it at a higher price in another market offers the price differential as risk-free profit or arbitrage. The same operation can be replicated for stocks vs. futures instruments as price differentials do exist from time to time. Implementing an algorithm to identify such price differentials and placing the orders efficiently allows profitable opportunities.

`Index Fund Rebalancing`
Index funds have defined periods of rebalancing to bring their holdings to par with their respective benchmark indices. This creates profitable opportunities for algorithmic traders, who capitalize on expected trades that offer 20 to 80 basis points profits depending on the number of stocks in the index fund just before index fund rebalancing. Such trades are initiated via algorithmic trading systems for timely execution and the best prices.

`Mathematical Model-Based Strategies`
Proven mathematical models, like the delta-neutral trading strategy, allow trading on a combination of options and the underlying security. (Delta neutral is a portfolio strategy consisting of multiple positions with offsetting positive and negative deltas—a ratio comparing the change in the price of an asset, usually a marketable security, to the corresponding change in the price of its derivative—so that the overall delta of the assets in question totals zero.) 

`Trading Range (Mean Reversion)`
Mean reversion strategy is based on the concept that the high and low prices of an asset are a temporary phenomenon that revert to their mean value (average value) periodically. Identifying and defining a price range and implementing an algorithm based on it allows trades to be placed automatically when the price of an asset breaks in and out of its defined range.

`Volume-Weighted Average Price (VWAP)`
Volume-weighted average price strategy breaks up a large order and releases dynamically determined smaller chunks of the order to the market using stock-specific historical volume profiles. The aim is to execute the order close to the volume-weighted average price (VWAP).

`Time Weighted Average Price (TWAP)`
Time-weighted average price strategy breaks up a large order and releases dynamically determined smaller chunks of the order to the market using evenly divided time slots between a start and end time. The aim is to execute the order close to the average price between the start and end times thereby minimizing market impact.

`Percentage of Volume (POV)`
Until the trade order is fully filled, this algorithm continues sending partial orders according to the defined participation ratio and according to the volume traded in the markets. The related “steps strategy” sends orders at a user-defined percentage of market volumes and increases or decreases this participation rate when the stock price reaches user-defined levels.

`Implementation Shortfall`
The implementation shortfall strategy aims at minimizing the execution cost of an order by trading off the real-time market, thereby saving on the cost of the order and benefiting from the opportunity cost of delayed execution. The strategy will increase the targeted participation rate when the stock price moves favorably and decrease it when the stock price moves adversely.


## Links

- ML Models
    - https://github.com/huseinzol05/Stock-Prediction-Models

- Advances Crypto Trading Bot
    - https://hummingbot.org
    - https://github.com/jesse-ai/jesse ✅
    - https://github.com/hummingbot/hummingbot ✅
    - https://github.com/freqtrade/freqtrade
    - https://github.com/CryptoSignal/Crypto-Signal
    - https://market.astrabit.io/strategies
    - https://www.kucoin.com/trading-bot
        - KuCoin has 6 trading bots
            - Spot Grid
            - Futures Grid
            - Martingale ✅
                - My personal favouite
                - Works best for sideways
            - Smart Rebalance
            - Infinity Grid
            - DCA

- Quant Trading
    - https://github.com/je-suis-tm/quant-trading
    - https://github.com/hummingbot/hummingbot 
    - https://www.reddit.com/r/quant/comments/kmdnty/open_source_hft_market_maker_bot_for_crypto/

- Interface
    - https://app.trality.com/bot/edit/63ba86b5c4b536559091cde1/strategy
    - https://geekflare.com/crypto-trading-bots
    - https://ocw.mit.edu/courses/15-450-analytics-of-finance-fall-2010/pages/lecture-notes