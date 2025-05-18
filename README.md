<p alight="center">
<img src="https://github.com/donmarcolaureano/tesla_ticker/assets/140132043/bc8d6726-f81e-4489-93fc-8d6a5bb9d4cc"/>
</p>

## <p style="text-align: center;">Tesla Ticker | Historical Stock Price Dataset </p>
This repository contains a Jupyter Notebook that performs exploratory data analysis (EDA) and forecasting on Tesla's historical stock price data. The analysis includes statistical summaries, visualizations, and insights into the stock's performance over time.

## Table of Contents
Overview
Features
Getting Started
Dependencies
Usage
License

## Overview

The notebook tesla_notebook.ipynb provides an in-depth analysis of Tesla's stock data. It covers:

- Loading and inspecting the dataset
- Statistical analysis of stock prices
- Visualization of stock trends
- Calculation of moving averages
- Forecasting future stock prices using time series models

## Features

- Data Loading: Reads historical stock data from a CSV file.
- Statistical Analysis: Computes mean, median, standard deviation, and other statistical measures.
- Data Visualization: Plots stock prices, moving averages, and volume over time.
- Forecasting: Implements time series models to predict future stock prices.

## Getting Started

### To run the analysis:

1. Clone the repository: git clone https://github.com/donmarcolaureano/tesla_ticker.git
2. Navigate to the project directory: cd tesla_ticker
3. Open the Jupyter Notebook: jupyter notebook tesla_notebook.ipynb

## Dependencies

Ensure you have the following Python packages installed:

- pandas
- matplotlib
- seaborn
- numpy
- jupyter

### You can install them using pip: pip install pandas matplotlib seaborn numpy jupyter

## Usage

The notebook is designed for educational and analytical purposes. You can modify the code to analyze different stock datasets or extend the analysis with additional metrics.


### Data
The original data for this project is provided by Kaggle and can be found <a href="https://www.kaggle.com/datasets/muhammadibrahimqasmi/tesla-stock-insights-and-predictions">here</a>

### Data Dictionary
| Field Name | Description |
| ---------- | ----------- |
| Open | Opening price of the stock for the trading day | 
| High | Highest price of the stock during the trading day | 
| Low | Lowest price of the stock during the trading day | 
| Close | Closing price of the stock for the trading day | 
| Volume | Number of shares traded during the trading day | 
| Adj Close | Adjusted closing price of the stock for the trading day | 

Feel free to contribute to this project by submitting issues or pull requests.
