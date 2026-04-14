# Stock Data Analysis

This project analyzes the historical stock price and historical revenue data for two companies: Tesla (TSLA) and GameStop (GME). 

## Overview
The Jupyter Notebook `Stock_Data.ipynb` performs the following tasks:
- **Stock Data Extraction**: Uses the `yfinance` library to download the maximum available historical stock price data for Tesla and GameStop.
- **Revenue Data Extraction**: Uses `pandas` and web scraping techniques to extract historical quarterly revenue data for both companies from provided web pages.
- **Data Visualization**: Uses `matplotlib` to graph the historical stock prices alongside the historical revenue for each company to visualize their financial performance over time.

## Libraries Used
- `yfinance`: To retrieve historical market data.
- `pandas`: To scrape and clean the revenue data from HTML tables.
- `matplotlib`: To plot the final stock and revenue graphs.