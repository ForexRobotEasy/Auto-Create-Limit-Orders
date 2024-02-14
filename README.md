# Auto Create Limit Orders

This code is a sample implementation of a trading robot that automatically creates limit orders in the foreign exchange market. It is developed by the Forex Robot Easy Team and can be found on their website [forexroboteasy.com](https://forexroboteasy.com). Please note that ForexRobotEasy is not the official developer of this product, and this code serves as a demonstration of how the product works.

## Installation

To use this code, you will need to have the MetaTrader platform installed on your computer. Once you have MetaTrader installed, follow these steps:

1. Copy the `Trade.mqh` library file to the `Trade` directory in your MetaTrader installation folder.

2. Open MetaEditor and create a new Expert Advisor (EA) file.

3. Copy and paste the entire code from this file into the new EA file.

4. Save the EA file and compile it in MetaEditor.

5. Open MetaTrader, go to the 'Navigator' panel, and find the EA under the 'Expert Advisors' section.

6. Drag and drop the EA onto the desired chart to activate it.

## Usage

This trading robot is designed to create limit orders with specified parameters. It has the following main features:

- `AutoCreateLimitOrders` class: This class contains the necessary functions and variables to create limit orders.

  - `lotSize`: The lot size for the limit order.
  - `stopLoss`: The stop loss level for the limit order.
  - `takeProfit`: The take profit level for the limit order.

- `createLimitOrder` function: This function is used to create a limit order with the specified symbol and price. It calculates the stop loss and take profit levels based on the given price and opens the limit order using the `CTrade` library.

- `OnStart` function: This is the entry point of the program. It creates an instance of the `AutoCreateLimitOrders` class with the specified parameters and calls the `createLimitOrder` function to create a limit order with the given symbol and price. It also displays a message indicating the successful creation of the limit order.

To use this code with your own parameters, you can modify the values in the `AutoCreateLimitOrders` constructor and the `symbol` and `price` variables in the `OnStart` function.

## Product Description

Auto Create Limit Orders is an automated trading robot developed by the Forex Robot Easy Team. It allows traders to automatically create limit orders in the foreign exchange market based on specified parameters. With this robot, traders can set the lot size, stop loss level, and take profit level for their limit orders.

This product is designed to streamline the trading process and eliminate the need for manual order placement. By automatically creating limit orders, traders can take advantage of market opportunities without constantly monitoring the market.

Please note that this code serves as a demonstration of how the product works and is not the official developer's version. To find the official developer of this product and access detailed reviews and trading results, please visit [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/auto-create-limit-orders-unbiased-forex-software-review/).
