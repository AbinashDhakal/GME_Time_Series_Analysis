# GME_Time_Series_Analysis
Time Series Analysis 
Welcome to the Time Series Analysis in Python workspace! This repository contains code and data to help you explore time series analysis using Python. Follow along with the provided code and instructions to gain insights into analyzing time-dependent data.

Contents:
## 1. File Overview
notebook-solution.ipynb: This file contains the solution code. If you need to refer to the solution at any point, navigate to this notebook.
## 2. Setting up the Environment
The initial code cell sets up the environment by importing necessary libraries and configuring visualization settings. This ensures that you have the required tools to proceed with the analysis.

## 3. Loading and Inspecting the Data
In this section, we utilize the yfinance package to download market data from the Yahoo! Finance API. We define the date range and select a specific ticker (in this case, "GME" for GameStop) for analysis.

## 4. Data Summary
The .describe() method is used to provide a numeric summary of the data, giving you an overview of key statistics for the selected time period.

## 5. Visualizing the Data
We use Plotly, a powerful visualization library, to create a line plot depicting the closing prices of GameStop over time. This visualization allows for a clear understanding of the stock's price trends.

## 6. Key Events Annotations
Annotations are added to the plot to highlight three significant events in the GameStop timeline:

Announcement of the new board and the start of hype on r/wallstreetbets.
Date when the RobinHood trading app restricted trading for GameStop.
Late February surge driven by increased activity on r/wallstreetbets.
Note: A workaround is implemented due to a bug with Plotly, where date conversion to milliseconds is required for annotations.
