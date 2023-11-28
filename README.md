# Good Monday MT5 ReadMe File

This is the ReadMe file for the code of Good Monday MT5, a forex trading robot developed by Forex Robot Easy Team. Please note that ForexRobotEasy is not the official developer of this product. We are only showcasing a sample code that can work as described in the official product.

To find the official developer of this product, please refer to the MQL5 website.

## Product Description

Good Monday MT5 is a forex trading robot designed to trade multiple currency pairs based on price gaps at the opening of the forex market. The robot identifies valid price gaps and enters buy or sell orders accordingly.

The key features of Good Monday MT5 are as follows:

- **Currency Pairs**: The robot is designed to trade the following currency pairs: GBPUSD, AUDUSD, NZDUSD, USDCAD, EURGBP, EURCHF, GBPCAD, GBPAUD, AUDCHF, AUDJPY, AUDNZD, CHFJPY, CADJPY, NZDJPY, NZDCHF, EURUSD, GBPCHF, and GBPJPY. These currency pairs can be modified in the input parameters.

- **Gap Threshold**: The robot uses a user-defined gap threshold to determine the validity of a price gap. The default gap threshold is set to 0.1.

- **Stop Loss and Take Profit**: The robot allows users to set their desired stop loss and take profit levels for each trade. The default stop loss is set to 50 pips, and the default take profit is set to 100 pips.

The code provided in this repository showcases the main trading logic of Good Monday MT5. It includes the following functions:

- **OnInit**: This function is called during the initialization of the expert advisor.

- **OnDeinit**: This function is called during the deinitialization of the expert advisor.

- **OnTick**: This function is called on every tick of the price data. It loops through the specified currency pairs, calculates the price gap, and executes buy or sell orders based on the validity and direction of the gap.

- **CalculatePriceGap**: This function calculates the price gap for a given currency pair. It returns the calculated gap value.

- **IsGapValid**: This function checks if the price gap is valid based on the user-defined gap threshold. It returns true if the gap is greater than the threshold, and false otherwise.

- **IsGapUp**: This function checks if the price gap is up. It returns true if the gap is positive, and false otherwise.

- **Buy**: This function places a buy order for the given currency pair at the opening of the forex market.

- **Sell**: This function places a sell order for the given currency pair at the opening of the forex market.

- **OnTradeError**: This function handles trade errors.

- **OnTradeTransaction**: This function handles order close events.

- **OnTimer**: This function handles timer events.

- **OnChartEvent**: These functions handle chart events.

Please note that the code provided in this repository is a simplified version for demonstration purposes. The actual code used in the official product may include additional features, optimizations, and error handling mechanisms.

For detailed reviews and trading results of the official Good Monday MT5 product, please visit the following link: [Good Monday MT5 Review - Optimized Forex Trading with Gap Focus](https://forexroboteasy.com/forex-robot-review/good-monday-mt5-review-optimized-forex-trading-with-gap-focus/).

## Disclaimer

ForexRobotEasy is not the official developer of Good Monday MT5. We are only providing a sample code that can work as described in the official product. To find the official developer and obtain the complete and optimized version of the Good Monday MT5 forex trading robot, please refer to the MQL5 website.
