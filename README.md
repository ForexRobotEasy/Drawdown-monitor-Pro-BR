# Drawdown Monitor Pro BR

The Drawdown Monitor Pro BR is an automated forex software developed by the Forex Robot Easy Team. It is designed to monitor drawdowns on multiple timeframes and generate alerts when the drawdown exceeds a specified threshold.

## Features
- Monitors drawdowns on up to 5 different timeframes simultaneously
- Executes trades based on time frame control
- Calculates drawdown percentage and generates alerts when it exceeds the threshold
- Provides trade execution functions and trade information storage

## Installation
To use this software, you need to have the MetaTrader platform installed on your computer. Follow these steps to install the Drawdown Monitor Pro BR:

1. Download the Drawdown Monitor Pro BR file from the [official developer's website](https://forexroboteasy.com/forex-robot-review/drawdown-monitor-pro-br-review-automated-forex-software-for-account-time-frame-control/).
2. Open the MetaTrader platform and navigate to the 'File' menu.
3. Select 'Open Data Folder' from the drop-down menu.
4. In the data folder, locate the 'MQL4' folder and open it.
5. Copy the Drawdown Monitor Pro BR file into the 'Experts' folder.
6. Restart the MetaTrader platform.

## Usage
To use the Drawdown Monitor Pro BR, follow these steps:

1. Open the MetaTrader platform and select the desired currency pair and timeframe.
2. Attach the Drawdown Monitor Pro BR to the chart by dragging it from the Navigator panel onto the chart.
3. Configure the settings in the Expert Advisor properties window, including the maximum number of timeframes, maximum lots, and drawdown threshold.
4. Click the 'OK' button to apply the settings.
5. The Drawdown Monitor Pro BR will automatically execute trades based on the time frame control and monitor drawdowns on each timeframe.
6. When a drawdown exceeds the specified threshold, an alert will be generated, displaying the relevant trade information.

## Code Explanation
The provided code is a simplified version of the Drawdown Monitor Pro BR software. Here is a breakdown of its functionality:

1. The necessary libraries are included, and constants are defined.
2. An instance of the Trade class is created.
3. A structure called STradeInfo is defined to store trade information.
4. An array of ArrayLongList is created to store trade information for different timeframes.
5. The ExecuteTrade function is defined to execute trades and store trade information.
6. The AnalyzeDrawdowns function is defined to analyze drawdowns and generate alerts.
7. The OnTick function is the main program entry point, where drawdowns are monitored and trades are executed.
8. The OnInit function is the program initialization function, where trade execution settings are configured.
9. The OnDeinit function is the program termination function, where all open trades are closed before termination.

## Disclaimer
Forex Robot Easy is not the official developer of the Drawdown Monitor Pro BR software. The provided code is only a sample that demonstrates how the software works. To find the official developer of this product and obtain the complete and official version, use the MQL5 platform.

For detailed reviews and trading results of the Drawdown Monitor Pro BR software, visit the [official developer's website](https://forexroboteasy.com/forex-robot-review/drawdown-monitor-pro-br-review-automated-forex-software-for-account-time-frame-control/).
