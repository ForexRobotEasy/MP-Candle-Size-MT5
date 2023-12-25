# MP Candle Size MT5

This code is a sample implementation of the MP Candle Size MT5 indicator, developed by the Forex Robot Easy Team. It is a price action tool designed for intraday traders to analyze the size of each candle in a given time period. The indicator calculates the difference between the highest and lowest prices of each candle, providing valuable insights into market volatility and potential trading opportunities.

## Customization Function

The `CustomizeCandleColors` function allows users to customize the colors of bullish and bearish candles on the chart. By default, the bullish color is set to Green and the bearish color is set to Red. Traders can modify these colors based on their preferences by changing the values of the `bullishColor` and `bearishColor` variables.

## Candle Size Oscillator Function

The `CalculateCandleSize` function calculates the size of each candle by subtracting the lowest price from the highest price. This information can be used to gauge market volatility and identify potential trend reversals or continuation patterns.

## Expert initialization function

The `OnInit` function is called during the initialization of the expert advisor. It sets the default colors for bullish and bearish candles and calls the `CustomizeCandleColors` function to apply the customization options. Traders can modify the default colors by changing the values of the `bullishColor` and `bearishColor` variables.

## Expert deinitialization function

The `OnDeinit` function is called when the expert advisor is being deinitialized. It can be used to handle any necessary cleanup or closing operations, if required.

## Expert tick function

The `OnTick` function is called on each tick of the chart. Traders can add their own code here to execute specific actions or strategies based on market conditions.

## Expert start function

The `OnStart` function is called when the expert advisor is started. Traders can add their own code here to execute specific actions or strategies at the start of the expert advisor.

Please note that Forex Robot Easy is not the official developer of this product. We are only providing a sample code that can work as described in this product. To find the official developer of this product, please use MQL5.

For detailed reviews and trading results of this product, please visit [Forex Robot Easy - MP Candle Size MT5 Review](https://forexroboteasy.com/forex-robot-review/mp-candle-size-mt5-review-price-action-tool-for-intraday-traders/).
