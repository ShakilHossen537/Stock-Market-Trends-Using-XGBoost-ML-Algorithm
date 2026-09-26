# Stock-Market-Trends-Using-XGBoost-ML-Algorithm

# Project Overview

This project focuses on analyzing and forecasting Zomato stock prices using the XGBoost machine learning algorithm. The project follows an end-to-end machine learning workflow, starting from historical stock data collection and preprocessing to feature engineering, model training, prediction, evaluation, and visualization.

Historical Zomato stock market data was obtained from Yahoo Finance, including Open, High, Low, Close, Adjusted Close, and trading volume. The XGBoost model was trained to identify patterns and forecast future stock prices.

# Research Objective

Analyze historical Zomato stock price trends
Develop a machine learning model for stock price forecasting
Apply the XGBoost algorithm to financial time-series data
Perform feature engineering using financial indicators
Evaluate model performance using MSE, MAE, and R²
Compare actual and predicted stock prices
Explore future improvements for financial forecasting

# Project Workflow

1. Data Collection

Historical Zomato stock price data was collected using Yahoo Finance.

The dataset contains:

Open Price
High Price
Low Price
Close Price
Adjusted Close Price
Trading Volume

The data covers the period from Zomato's IPO to the latest recorded trading data used in the study.

2. Data Preprocessing

The collected data was prepared for machine learning through:

Handling missing values
Data cleaning
Feature transformation
Feature scaling
Train-test splitting

The dataset was divided into 80% training data and 20% testing data.

3. Feature Engineering

Additional financial features were developed to improve the forecasting process.

These include:

Moving averages
Volatility
Monthly trends
Historical price-related features

Min-Max Scaling was also applied to normalize the input features between 0 and 1.

4. Machine Learning Model

XGBoost (Extreme Gradient Boosting) was selected as the primary machine learning algorithm.

XGBoost was selected because of its:

Efficient training performance
Scalability
Regularization capabilities
Ability to handle structured datasets
Capability to model nonlinear relationships

The model uses L1 and L2 regularization to help control overfitting.

5. Model Evaluation

The trained model was evaluated using the following metrics:

Mean Squared Error (MSE)
Measures the average squared difference between actual and predicted stock prices.

Mean Absolute Error (MAE)
Measures the average absolute difference between actual and predicted values.

R² Score
Measures how much of the variation in stock prices is explained by the model.

# Results & Analysis

The XGBoost model was used to predict Zomato stock prices on unseen data.

The analysis compared:

Actual vs predicted stock prices
Stock opening and closing prices
High and low prices
Training and testing data
Historical price trends
Short-term future price predictions

The paper reports an 85.2% prediction accuracy for the XGBoost-based approach.

The prediction plots showed that the model was able to follow the overall movement of Zomato's stock price, although deviations became more noticeable during periods of higher market volatility.

# Visualizations

The project includes visual analysis of:

XGBoost model performance
MAE, MSE, and R²
Actual vs predicted closing price
Monthly Open vs Close price
Monthly High vs Low price
Training vs testing data
Closing price vs timestamp
Last 15 days vs next 10 days prediction
Original vs predicted closing price

# Research Insights

The study demonstrates the application of XGBoost for stock price forecasting using historical financial data.

# Key observations include:

XGBoost can model nonlinear patterns in stock-price data.
The model closely follows the overall movement of the actual stock price.
Prediction deviations become more visible during volatile periods.
Regularization helps control overfitting.
XGBoost provides efficient processing for structured financial datasets.

# Future Scope

The research identifies several possible directions for improving the forecasting system:

Sentiment Analysis: Incorporate financial news and social media sentiment using NLP.
Advanced Feature Engineering: Add technical indicators, economic variables, and lag features.
Real-Time Prediction: Develop a system for real-time market forecasting.
Cross-Asset Forecasting: Extend the model to multiple stocks and portfolios.
Explainable AI: Use SHAP and similar techniques to improve model interpretability.
Market Shock Handling: Explore reinforcement learning and transfer learning.
Alternative Data: Incorporate additional sources such as transaction-level or other external data.

# Tools & Technologies

Programming Language: Python
Machine Learning: XGBoost
Data Processing: Pandas, NumPy
Data Source: Yahoo Finance
Data Scaling: MinMaxScaler
Data Visualization: Matplotlib / visualization tools
Evaluation Metrics: MSE, MAE, R²
Development Environment: Jupyter Notebook / Google Colab
Version Control: GitHub

# Key Deliverables

Historical Zomato stock price dataset
Data preprocessing and feature engineering scripts
XGBoost machine learning model
Stock price prediction results
Model evaluation using MSE, MAE, and R²
Actual vs predicted stock price visualizations
Short-term future price forecasting
Research paper and documentation
GitHub repository containing project source code

# Project Structure

Zomato-Stock-Price-Prediction/│
├── dataset/
│   └── zomato.csv

│
├── notebooks/
│   └── Zomato_Stock_Prediction.ipynb
│
├── src/
│   ├── data_preprocessing.py
│   ├── feature_engineering.py
│   ├── model_training.py
│   └── prediction.py
│
├── results/
│   ├── actual_vs_predicted.png
│   ├── stock_trends.png
│   └── model_performance.png
│
├── research-paper/
│   └── research_paper.pdf
│
├── requirements.txt
└── README.md

# Research Paper

Title: A Comprehensive Study of Stock Market Trends Using XGBoost Machine Learning Algorithm

The research examines machine learning approaches for stock market forecasting and applies XGBoost to the prediction of Zomato stock prices.

# Author

Md Shakil Hossen,
Department of Computer Science and Engineering,
Chandigarh University, Mohali, India

Research focus: Machine Learning, Artificial Intelligence, Financial Data Analysis, and Predictive Analytics.
