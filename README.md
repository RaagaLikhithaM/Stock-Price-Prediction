# Stock-Price-Prediction

This repository contains historical stock price data for Amazon (AMZN) from May 15, 1997, to April 21, 2023. The dataset provides daily trading information, offering a comprehensive look at Amazon's stock performance over more than two decades.


**Dataset Details**

_File Format_- CSV (Comma-Separated Values)
_Time Range_
Start Date: May 15, 1997
End Date: April 21, 2023
_Columns_
-Date: Trading date in YYYY-MM-DD format
-Open: Opening price for the day
-High: Highest price reached during the day
-Low: Lowest price reached during the day
-Close: Closing price for the day
-Adj Close: Adjusted closing price (accounts for stock splits and dividends)
-Volume: Number of shares traded

**Data Statistics**

-Total Records: 6,125
-Frequency: Daily (excluding weekends and holidays)

**Summary Statistics**

Open	High	Low	Close	Adj Close	Volume
Count	6,524	6,524	6,524	6,524	6,524	6,524
Mean	64.41	65.13	63.68	64.41	51.51	20,327,490
Std	36.41	36.68	36.14	36.40	38.36	18,872,520
Min	1.96	1.98	1.38	1.40	1.40	591,600
25%	38.66	39.25	38.16	38.72	24.38	9,768,100
50%	47.88	48.45	47.32	47.82	31.58	13,818,600
75%	89.83	90.79	88.30	89.47	76.37	23,613,600
Max	172.71	172.96	170.54	171.78	164.02	217,294,200

**Usage**

This dataset can be utilized for various purposes, including:
Historical analysis of Amazon's stock performance
Technical analysis and pattern recognition
Building and testing trading algorithms
Financial modeling and forecasting
Academic research in finance and economics
Machine learning projects focused on stock price prediction

**Data Preprocessing**

The dataset has already undergone some preprocessing:
Adjusted closing prices are provided to account for stock splits and dividends
Missing values have been handled (if any)
Date format is consistent throughout the dataset

**Data Processing**

The project involves the following data processing steps:
_Loading the dataset:_ The Amazon stock price data is loaded from a CSV file using pandas.
_Data exploration:_ Basic statistics and information about the dataset are calculated, including:
_Date range:_ May 15, 1997 to April 21, 2023
Summary statistics for Open, High, Low, Close, Adjusted Close, and Volume
_Data cleaning: _The dataset has been preprocessed to handle any missing values and ensure consistency in date formats.

**Analysis**

The project includes the following analyses:
_Summary statistics:_ Calculated for all numerical columns (Open, High, Low, Close, Adjusted Close, and Volume).
_Time series visualization:_ The closing prices are plotted over time to visualize Amazon's stock price trends.
_Data transformation:_ The dataset is converted to a time series format with the Date column set as the index.

**Tools and Libraries Used**

Python: The primary programming language for the project
Pandas: Used for data manipulation and analysis
Matplotlib (implied): Likely used for creating visualizations

**Future Work**

This project lays the groundwork for more advanced analyses, such as:
Technical indicator calculations
Price prediction models
Correlation analysis with market indices or other tech stocks
Volatility analysis



