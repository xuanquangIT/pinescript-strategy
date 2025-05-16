# pinescript-strategy

## ADX-Filtered Mean Reversion

A sophisticated mean reversion strategy that uses ADX as a trend filter combined with Bollinger Bands and RSI to identify optimal reversal points. The strategy enters long when price reaches the lower Bollinger Band during an uptrend with oversold RSI conditions, and enters short when price touches the upper Bollinger Band during a downtrend with overbought RSI readings. Position management includes ATR-based stop losses and profit targets for precise risk management.

[View on TradingView](https://www.tradingview.com/script/2umVBjzd-ADX-Filtered-Mean-Reversion/)

![image](https://github.com/user-attachments/assets/21861570-4c35-4343-bc11-b2a180011e1f)


![image](https://github.com/user-attachments/assets/09bcd04e-54e4-4f33-923d-3ead90d95b95)


## 5 EMA Trend Strategy

An advanced trend-following strategy utilizing five exponential moving averages (EMA6, EMA10, EMA20, EMA50, EMA100) to identify strong trends and potential entry points. The strategy generates buy signals when price closes above EMA6 after opening below it with all EMAs properly aligned in ascending order (6>10>20>50>100), and sell signals when price closes below EMA6 after opening above it with EMAs in descending order. The strategy features dynamic stop losses based on recent price action, adjustable risk-reward ratios, and automatic position management with breakeven features.

[View on TradingView](https://www.tradingview.com/script/gcXvYyYw-5-EMA-Trend-Strategy/)

![image](https://github.com/user-attachments/assets/ad0f2930-e6a1-4b6c-bb87-5582092f1bfa)


![image](https://github.com/user-attachments/assets/ecc7f9bb-c239-4a9c-9a91-6174a81ea352)


## Backtest MA+MACD For BTC

A Bitcoin-specific trading strategy combining Moving Average crossovers with MACD momentum confirmation. The system uses customizable MA types (EMA/SMA) with an optional third MA for additional trend filtering. Entry signals are generated on MA crossovers with confirmatory MACD alignment (MACD line above signal for longs, below for shorts). Risk management is handled through dynamic stop losses based on recent price swings and a configurable risk-reward ratio (default 2.9:1) for consistent position sizing and profit targets.

[View on TradingView](https://www.tradingview.com/script/r0q8zl4k-Backtest-MA-MACD-For-BTC/)

![image](https://github.com/user-attachments/assets/931358fb-f280-4109-a4d6-d8f71b5fdce2)

![image](https://github.com/user-attachments/assets/fc1b5465-2817-43c3-8237-46fac911203a)

