# Trend Based Fibo MT4

This code is a custom indicator for MetaTrader 4 (MT4) that calculates Fibonacci levels based on the trend of the market. It is designed to be used in forex trading to identify potential support and resistance levels.

## Input Parameters

- **levels**: This parameter determines the number of Fibonacci levels to calculate. The default value is 7.
- **frame**: This parameter determines the frame for Fibonacci level calculations. The default value is 100.

## How it Works

The code uses the `CalculateTrendBasedFibo` function to calculate the Fibonacci levels based on the current trend of the market. 

The main trend is determined by taking the highest and lowest prices within the specified frame. The retracement trend is based on the current price.

The range of the main trend is calculated by subtracting the highest and lowest prices. 

The Fibonacci levels are then calculated by dividing the range into equal parts based on the number of levels specified.

The code creates horizontal lines on the chart to represent each Fibonacci level.

## Product Description

Trend Based Fibo MT4 is a reliable forex indicator developed by the Forex Robot Easy Team. It is designed to assist traders in identifying potential support and resistance levels using Fibonacci retracement levels.

This indicator calculates Fibonacci levels based on the current trend of the market. It allows traders to specify the number of levels to calculate and the frame for the calculations.

By using Trend Based Fibo MT4, traders can have a better understanding of the market trend and identify key levels where price may reverse or consolidate.

Please note that Forex Robot Easy is not the official developer of this product. We only provide sample code that demonstrates how this indicator works. To find the official developer of this product, please visit the MQL5 website.

For detailed reviews and trading results of this product, please visit [https://forexroboteasy.com/forex-robot-review/trend-based-fibo-mt4-review-reliable-forex-indicator/](https://forexroboteasy.com/forex-robot-review/trend-based-fibo-mt4-review-reliable-forex-indicator/).
