# PortfolioManagementOptimization

## Overview

This repository contains the analysis of time series forecasting techniques applied to portfolio management at Guide Me in Finance (GMF) Investments. The focus is on predicting market trends and optimizing asset allocation using historical financial data.


## Business Objective

Guide Me in Finance (GMF) Investments aims to leverage advanced time series forecasting models to predict market trends, optimize asset allocation, and enhance portfolio performance.

## Data Collection

Data was sourced from YFinance for three key assets: Tesla (TSLA), Vanguard Total Bond Market ETF (BND), and S&P 500 ETF (SPY), covering the period from January 1, 2015, to October 31, 2024.

## Data Preprocessing

Data was cleaned and normalized, with missing values handled appropriately. EDA was conducted to understand trends and volatility.

## Exploratory Data Analysis (EDA)

EDA involved visualizations of closing prices, daily percentage changes, and seasonal decomposition to identify trends.

## Model Development

Time series forecasting models (ARIMA, SARIMA, LSTM) were implemented and evaluated using performance metrics like MAE, RMSE, and MAPE.

## Forecasting Future Trends

Forecasts for Tesla’s stock prices were generated, including confidence intervals to indicate uncertainty.

## Portfolio Optimization

A sample portfolio was created, and optimization strategies were applied to maximize returns while minimizing risks.

## Installation

To get started with the project, clone the repository:

```
git clone https://github.com/yourusername/PortfolioManagementOptimization.git
cd PortfolioManagementOptimization
```
Install the required packages:

```
pip install -r requirements.txt
```
## Usage
Run the analysis scripts to generate insights and visualizations. Ensure that the YFinance library is installed for data extraction.

## License
This project is licensed under the MIT License. See the LICENSE file for details.
