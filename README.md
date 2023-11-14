# Order Blocks Zone Scalper MT4

This is the source code for the Order Blocks Zone Scalper MT4 robot. This robot is designed to automate and optimize your order blocks trading strategy. 

## Input Parameters

- **EMAperiod**: Period for EMA cross
- **MAperiod**: Period for MA filter
- **RSIPeriod**: Period for RSI filter
- **MAthreshold**: Threshold for MA filter
- **RSIThreshold**: Threshold for RSI filter

## Global Variables

- **emaValue**: EMA value
- **maValue**: MA value
- **rsiValue**: RSI value

## Initialization

The robot initializes necessary indicators and sets up error handling and logging.

## Starting the Robot

The robot starts by checking for order blocks and retesting them. If order blocks are found, it switches to a smaller timeframe and checks for EMA cross. If an EMA cross is detected, it applies the MA and RSI filters. If both filters are satisfied, the robot enters a trade.

## Functions

- **CheckOrderBlocks()**: This function checks for order blocks and retests them.
- **SwitchToSmallerTimeframe()**: This function switches to a smaller timeframe.
- **CheckEMACross()**: This function checks for EMA cross.
- **ApplyMAFilter()**: This function applies the MA filter.
- **ApplyRSIFilter()**: This function applies the RSI filter.
- **EnterTrade()**: This function enters a trade.

## Backlink

This code was developed for the Order Blocks Zone Scalper MT4 robot, which can be found at [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/review-order-blocks-zone-scalper-mt4-automate-and-optimize-your-order-blocks-trading-strategy/).
