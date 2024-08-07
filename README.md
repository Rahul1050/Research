# Research
# Stock Data Analysis and Machine Learning Project

## Overview

This project focuses on the analysis of stock data using machine learning techniques to generate trading signals and evaluate the performance of various trading strategies. The goal is to identify the most effective combinations of indicators for stock trading.

## Table of Contents

- [Introduction](#introduction)
- [Objectives](#objectives)
- [Methodology](#methodology)
- [Data](#data)
- [Feature Engineering](#feature-engineering)
- [Modeling](#modeling)
- [Results](#results)
- [Conclusion](#conclusion)
- [Running the Code](#running-the-code)
- [Future Work](#future-work)

## Introduction

This repository contains the code and documentation for a research project on automating the analysis of stock data, generating trading signals, and evaluating the performance of trading strategies. The project employs machine learning models, particularly focusing on Gradient Boosting Regressor, to assess the importance of key features in trading strategies.

## Objectives

1. To automate the process of analyzing stock data.
2. To generate trading signals based on the analyzed data.
3. To evaluate the performance of different trading strategies.
4. To identify the most effective combinations of indicators for stock trading.

## Methodology

The methodology involves several key steps:
1. **Data Collection:** Gathering historical stock data.
2. **Feature Engineering:** Creating relevant features from raw data to use in modeling.
3. **Model Training:** Using machine learning models to predict stock price changes.
4. **Signal Generation:** Developing trading signals based on model predictions.
5. **Strategy Evaluation:** Testing and evaluating the performance of different trading strategies.

## Data

The data used in this project includes historical stock prices, volumes, and other relevant financial indicators. The dataset is sourced from reliable financial data providers.

## Feature Engineering

Feature engineering is a crucial part of this project. It involves creating new features from the raw data, such as:

- Volume/Float ratio
- Volume per minute
- Market Cap per minute
- Market Force Indicator

These features are used to train the machine learning models.

## Modeling

The primary model used in this project is the Gradient Boosting Regressor. The target variable for the model is "Change," which represents the change in stock price. The model is trained on historical data and used to predict future price changes.

## Results

The results section includes the performance metrics of the models, the effectiveness of the generated trading signals, and the evaluation of different trading strategies. Detailed analysis and visualizations are provided to illustrate the findings.

## Conclusion

This project demonstrates the potential of using machine learning for stock data analysis and trading strategy development. The findings highlight the importance of feature engineering and model selection in predicting stock price changes and generating effective trading signals.

## Running the Code

To run the code, follow these instructions:

1. Add the CSV file that you want to check to the project directory and update the CSV file path in the `FeatureImportance.py` code.
2. Add all the required CSV files to the project directory before running the remaining scripts.
3. Run the scripts in the following order:
    1. `FeatureImportance.py`
    2. `Images2csv.py`
    3. `analyze_feature_combinations.py`
    4. `stock_trading_strategy_analysis.py`

Codes won't work if one doesn't follow this order.

## Future Work

Future work will focus on:

- Enhancing feature engineering techniques.
- Exploring additional machine learning models.
- Implementing real-time trading strategies.
- Conducting further backtesting and validation.

