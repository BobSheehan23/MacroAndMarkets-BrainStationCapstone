# Capstone Project: Tactical Asset Allocation

## Project Overview
The goal of this project is to create a machine learning model that helps non-expert investors optimize their investment choices. By leveraging machine learning techniques, the model aims to uncover complex connections between economic indicators and market regimes, thereby aiding in Tactical Asset Allocation.

# Project Organization
- Data Loading/Cleaning
- Exploratory Data Analysis
- Preprocessing
- Modelling
- Findings

## Problem Area
The intersection of Economics and Finance, particularly Tactical Asset Allocation, presents significant challenges. The economy and financial markets do not always move in tandem, and different market segments may perform variably depending on the economic business cycle. Currently, only the financial industry and their clients have the resources to understand and act on these patterns effectively.

## Proposed Data Science Solution
The solution involves using machine learning algorithms, including supervised learning (regression and classification) and unsupervised learning (clustering), to identify intricate relationships between economic indicators and market regimes. Advanced techniques like Recurrent Neural Networks (RNNs) and Long Short-Term Memory (LSTM) networks may eventually be employed to capture temporal patterns in economic and market data.

## Impact of the Solution
This project has the potential to significantly benefit non-expert investors by optimizing their investment choices, saving them both time and money. Unlike existing options such as robo-advisors and human financial advisors, this service aims to provide professional-grade insights at a low cost or even for free.

## Description of the Dataset
The datasets used in this project include:

1. **Economic Indicators Dataset**: Contains macroeconomic indicators such as GDP growth rates, unemployment rates, inflation rates, interest rates, consumer confidence indices, and manufacturing indices from various countries and regions. Sources include the World Bank, IMF, OECD, and national statistical agencies.

2. **Financial Market Data**: Comprises historical stock market data, including stock prices, trading volumes, market indices (e.g., S&P 500, Dow Jones Industrial Average, NASDAQ Composite), sector-specific indices, and other financial indicators like bond yields and commodity prices. This data can be sourced from providers like Yahoo Finance, Google Finance, or Alpha Vantage.

3. **Alternative Data Sources**: Provides unique insights into market trends and consumer behavior through web traffic data, satellite imagery, credit card transactions, and mobile app usage statistics. These datasets are more challenging to obtain and process but offer a competitive edge in investment decision-making.

## Data Dictionary
A comprehensive data dictionary will be created to document the various variables and their sources. This will include detailed descriptions of each variable, its source, and its relevance to the project.

## Combining the Data Dictionaries
```python
combined_data_dict = {**asset_classes_data_dict, **economic_indicators_data_dict}
```

## Printing the Combined Data Dictionary
```python
print(combined_data_dict)
```
