# Investment Visualization

This Jupyter Notebook is designed for the visualization of personal investments. It imports trading data from CSV files, which contain securities transactions in the format of downloads from the Fidelity trading platform. For privacy purposes, the trading data in this Notebook is generated randomly. In addition, it extracts price data for all the securities listed in the CSV files using the AlphaVantage API.

With this data, the script constructs a Pandas DataFrame. The DataFrame contains the value and profitability of each security in the portfolio over time. Moreover, it calculates the total value and profit of the entire investment portfolio, as well as the allocation of the investments by region over time.

The region allocation data for all securities is imported as an Excel file that was created manually. The collection of the region allocation data might be automated in the future but is currently not supported by the AlphaVantage API.
