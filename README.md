# Stock Trading Analysis

Welcome to the Stock Trading Analysis project. This repository contains a detailed analysis of historical stock price data, focusing on Apple Inc. (AAPL) for the period from May 2014 to May 2020. The analysis includes the calculation of moving averages, buy and sell signal logic, and a visualization of key trading events.

## Analysis Overview

In this project, we explore the historical performance of Apple stock, aiming to provide insights for traders and investors. The analysis is structured as follows:

1. **Calculating Moving Averages**: We begin by calculating the 30-day Simple Moving Average (SMA30) and the 100-day Simple Moving Average (SMA100). These moving averages help smooth out the price data and identify trends.

2. **Visualizing Stock Prices and SMAs**: We create visually appealing plots that display the historical adjusted close prices of Apple stock, along with the SMA30 and SMA100. This visualization helps stakeholders understand how the stock's price relates to these moving averages.

3. **Buy and Sell Signal Logic**: We define a function to determine buy and sell signals based on the relationship between SMA30 and SMA100. The function tracks buy and sell prices, holding status, and actions, indicating past trading decisions based on the moving averages.

4. **Applying Buy and Sell Signals to the Data**: We apply the buy and sell signal logic to our stock data and create new columns, including "Buy Price," "Sell Price," "Hold," and "Actions." These columns provide information on when the stocks were bought, sold, or held based on the calculated moving averages.

## Key Observations

- The adjusted close price of Apple stock generally follows the trends of SMA30 and SMA100.
- Buy points are strategically placed to optimize entry into the market, taking advantage of potential gains.
- Profit and loss transactions demonstrate the effectiveness of our trading strategy.

## Conclusion

This analysis provides valuable insights into the historical performance of Apple stock. By following the highlighted buy and sell points, investors and traders could have potentially achieved a positive overall performance during the selected timeframe.

## Getting Started

To get started with this analysis, follow these steps:

1. Clone this repository to your local machine.
2. Review the Jupyter Notebook containing the code and analysis: [Stock_Trading_Analysis.ipynb](Stock_Trading_Analysis.ipynb).
3. Ensure you have the necessary libraries installed to run the code. You can install them using `pip` or `conda`.
4. Run the Jupyter Notebook and explore the analysis in detail.

## Contributing

If you'd like to contribute to this project or provide feedback, feel free to open an issue or submit a pull request. We welcome collaboration and improvements to this analysis.

---

*Disclaimer: The information provided in this analysis is for educational purposes only and should not be considered as financial advice. Always conduct your own research and seek professional guidance before making investment decisions.*
