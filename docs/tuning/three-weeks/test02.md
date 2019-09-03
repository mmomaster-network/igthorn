Test 2

Changes:
- smaller buy_down_interval to get rid of assumption that price is constantly dropping
- smaller rebuy_interval to kick of more traders faster

Settings:
```
    budget             | 1000
    chunks             | 10
    profit_interval    | 0.005
    buy_down_interval  | 0.005
    retarget_interval  | 0.015
    rebuy_interval     | 0.02
    stop_loss_interval | 0.05
```

Symbol: XRPUSDT
Date range: 2019-06-03 - 2019-06-22 (inclusive)
Number of events: 2849135
Market start price: 0.44396000
Market last price: 0.47729000
Market performance: 6.9831758469693455%
Naive strategy performance: xxxx%
Number of orders: 2471
Number of trades: 798
    - gaining trades: 732
    - stop losses: 66
Estimated number of retargeted orders = 2471 - 732 * 2 - 66 = 941