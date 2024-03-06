# SDP Robot

![SDP Robot](https://forexroboteasy.com/wp-content/uploads/2021/10/sdp-robot.jpg)

This is the code for the SDP Robot developed by the Forex Robot Easy Team. The SDP Robot is a forex trading robot that uses support and resistance levels to execute buy and sell trades. It is designed to help traders identify potential entry and exit points in the market.

## Features
- Support and resistance level identification and analysis functions
- Trade execution based on support and resistance levels
- Risk and position size calculation for each trade
- Trade management features including stop loss and take profit levels
- Trade monitoring and automatic trade closure

## How It Works

The SDP Robot algorithm is implemented in the `OnTick()` function. Here's a breakdown of how it works:

1. Check if it is news time. If it is, disable the robot. This is done to avoid trading during volatile market conditions.
2. Get a list of symbols to trade.
3. Loop through each symbol and perform the following steps:
   - Calculate support and resistance levels for different time frames (weekly and daily).
   - Execute trades based on the identified support and resistance levels. If the bid price is above the weekly resistance level, a buy trade is executed with a stop loss at the weekly support level and a take profit at a distance equal to the weekly resistance level minus the weekly support level. If the ask price is below the weekly support level, a sell trade is executed with a stop loss at the weekly resistance level and a take profit at a distance equal to the weekly support level minus the weekly resistance level. The same logic applies to the daily support and resistance levels.
4. Calculate risk and position size for each trade. The risk is calculated based on the entry price and stop loss level, and the position size is calculated based on the risk and the account balance.
5. Set the stop loss and take profit levels for each trade.
6. Monitor open trades and close them based on pre-defined conditions.

## Product Description

The SDP Robot is a powerful forex trading robot developed by the Forex Robot Easy Team. It is designed to help traders identify profitable trading opportunities based on support and resistance levels. With its advanced algorithms, the SDP Robot can analyze market trends and execute trades with precision.

Key Features:
- Support and Resistance Level Identification: The SDP Robot uses sophisticated algorithms to calculate support and resistance levels for different time frames. This helps traders identify potential entry and exit points in the market.
- Trade Execution: Once support and resistance levels are identified, the SDP Robot automatically executes buy and sell trades at optimal prices. Traders can customize the stop loss and take profit levels to manage risk and maximize profits.
- Risk and Position Size Calculation: The SDP Robot calculates the risk for each trade based on the entry price and stop loss level. It also calculates the position size based on the risk and the trader's account balance.
- Trade Management: The SDP Robot allows traders to set stop loss and take profit levels for each trade. This helps to minimize losses and lock in profits as the market moves.
- Trade Monitoring and Automatic Closure: The SDP Robot continuously monitors open trades and closes them based on pre-defined conditions. This ensures that trades are managed effectively and helps to protect profits.

Please note that ForexRobotEasy is not the official developer of this product. We only provide a sample code that demonstrates how the SDP Robot algorithm can work. To find the official developer of this product and access detailed reviews and trading results, please visit [Forex Robot Easy - SDP Robot Review](https://forexroboteasy.com/forex-robot-review/sdp-robot-review-trade-safely-with-support-and-resistance/). For further information and to purchase the SDP Robot, please refer to the official developer's website or search for it on MQL5.
