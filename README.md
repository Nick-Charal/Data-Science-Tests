# Data Science Tests

This repository contains notebooks for analyzing financial data and querying city demographics and crime data.

## 1. House Sales (`House_Sales.ipynb`)
This project predicts housing prices based on various property features using data analysis and machine learning models.

### Overview
- **Data Wrangling**: Cleans the housing dataset by removing unnecessary identifiers and imputing missing values for bedrooms and bathrooms.
- **Exploratory Data Analysis**: Uses visualization tools to identify correlations between housing prices and features like waterfront views and square footage.
- **Model Development**: Fits and evaluates multiple regression models to predict prices, including Simple and Multiple Linear Regression, Polynomial Regression Pipelines, and Ridge Regression.

### Libraries Used
- `pandas` & `numpy`: For data manipulation and analysis.
- `matplotlib` & `seaborn`: For data visualization and correlation mapping.
- `scikit-learn`: For building regression models, preprocessing, and model evaluation.

## 2. Chicago Data SQL Queries (`SQL_Queries.ipynb`)
This project demonstrates how to load real-world datasets into a local SQLite database and perform various SQL queries to extract insights.

### Overview
- **Data Ingestion**: Downloads Chicago Census, Public Schools, and Crime Data as CSVs and loads them into a `FinalDB.db` SQLite database using `pandas` and the `sqlite3` library.
- **SQL Analysis**: Uses the `ipython-sql` magic extension (`%sql`) to run queries directly within the notebook.
- **Data Exploration**: Includes queries to find community areas with specific poverty metrics, detailed school safety scores, and specific types of recorded crimes (e.g., incidents involving minors, schools, etc.).

### Libraries Used
- `pandas`: To read CSVs and write them to a SQLite database.
- `sqlite3`: To interact with the local SQLite database.
- `ipython-sql`: To execute SQL queries directly in notebook cells.
- `prettytable`: For formatting the SQL output in a tabular format.

## 3. Stock Data Analysis (`Stock_Data_Visualization.ipynb`)
This project analyzes the historical stock price and historical revenue data for two companies: Tesla (TSLA) and GameStop (GME). 

### Overview
- **Stock Data Extraction**: Uses the `yfinance` library to download the maximum available historical stock price data for Tesla and GameStop.
- **Revenue Data Extraction**: Uses `pandas` and web scraping techniques to extract historical quarterly revenue data for both companies from provided web pages.
- **Data Visualization**: Uses `matplotlib` to graph the historical stock prices alongside the historical revenue for each company to visualize their financial performance over time.

### Libraries Used
- `yfinance`: To retrieve historical market data.
- `pandas` & `bs4`: To scrape and clean the revenue data from HTML tables.
- `matplotlib`: To plot the final stock and revenue graphs.