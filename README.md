# FX Candle Analysis

## Background
FX trading has been easier for people who had enough time to analyze charts in realtime. But, they, especially winners in the fiedls wouldn't hold positions all the time of their trading, since holding positions for longer increased the risks of loss. They spent much time to find the best timing to invest on by carefully and technically analyzing charts and other related infomation.

Basically, I wanted to achieve 2 things, to win the games, but to spend less time for trading. In order to achieve these at one time, I needed to find the secrets of FX charts and build smart bot to analyze charts to some extents with notifying me in realtime. This FX Candle Analysis repository was for the 1st goal and it would be the historical data analysis.

### How can you win in the FX games?
There were many trading strategies around the world. Traders have demonstrated that their strategies were right by the outcome of their tradings. Since there may be no perfect strategies in the FX games, it's not easy to tell which strategies were(and would be) the best for all. Also, some strategies must heve been created to increase losers by poeple gaining profits from them like exchange companies, which meant traders needed to know what were the useless strategies. Since FX games were minus-sum games and exchanges won all the time, understanding how they won the games would lead to the good strategies for winners.

If you were a trader working in a FX exchange, how you would do to gain the profits from users(losers)?

This question included one assumption that they could manipulate FX prices to some extents. This seemed to be ridiculous at first, but it would be somehow possible if many exchanges around the world thought the same way and did the similar strategies to gain their profits. To make it simple, you could suppose it was true(at least I believed that it had been unknown trueth), which meant you could manipulate the prices your own way. (If you could really do that, it's too easy to win the games anyway)

You would find some simple strategies below as a FX exhcnage trader. 

1. Gain more trading fees from traders
2. Make them Stop Loss to lose their money

You would manipulate the prices to achieve these simple goals.

If these kind of assumptions were true for all the exchanges in the world, you would know how the prices move in the futures.


### Trading Traps

Based on the assumptions above, I could tell the two trading traps. You might see these were very common for traders, even though these were not recognized as intentional traps. 

1. **Temptation to Winning**: Traders must see many times that they would win if they invested on. Then, they repeated the cycles of investing and losing later (Exchanges would gain much trading fees). If you didn't feel you could win, you wouldn't have invested on in the first place.
2. **Collecting Orders and Reversing**: Their buy/sell orders were executed, but after that, the prices gone the other way.


### Strategies to win the FX Games?

1. Find the price points to collect so many orders at a time
2. Suppose the price would across those points in the near futures
3. After confirming that the price acrossed them, invest on the other way (this requires confidence)
4. Order Stop Loss at the near points


## Analyiss for historical chart data

### Data

dataset: [FX-1-Minute-Data](https://github.com/philipperemy/FX-1-Minute-Data)  
trading pair: gbpusd
datetime: EST

### Analysis

When volatility was high in general?

- in the evening? which timezone?
- Thrusday or Friday?
- just after HH:00 or before 5 mins of them?