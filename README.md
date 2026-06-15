# Crypto-Signal-Direction
### CryptoSignal AI - Cryptocurrency Price Direction Prediction
## Project Overview

CryptoSignal AI is a machine learning-powered web application that predicts the next-day price direction of cryptocurrencies. The application analyzes market data, technical indicators, and sentiment metrics to determine whether a cryptocurrency is likely to move up (Bullish) or down (Bearish).

The project is built using Streamlit, Scikit-Learn, Pandas, and Plotly, providing an interactive and professional dashboard for crypto market analysis.

## Objectives
Predict next-day cryptocurrency price movement.
Compare multiple machine learning algorithms.
Visualize prediction confidence and market sentiment.
Provide an easy-to-use interface for traders and analysts.
## Supported Cryptocurrencies
Bitcoin (BTC)
Ethereum (ETH)
Binance Coin (BNB)
Solana (SOL)
XRP
## Features
Market Data Analysis
Open, High, Low, Close Price Analysis
Trading Volume Analysis
Market Capitalization Tracking
Technical Indicators
RSI (Relative Strength Index)
MACD (Moving Average Convergence Divergence)
SMA 20
SMA 50
Bollinger Bands
ATR (Average True Range)
30-Day Volatility
Sentiment Analysis
Fear & Greed Index
Market Sentiment Classification
Machine Learning Models

The application trains and compares:

Logistic Regression
Decision Tree Classifier
Random Forest Classifier
Gradient Boosting Classifier
Extra Trees Classifier

The model with the highest ROC-AUC score is automatically selected for predictions.

## Technologies Used
Technology	Purpose
Python	Programming Language
Streamlit	Web Application Framework
Pandas	Data Manipulation
NumPy	Numerical Computing
Scikit-Learn	Machine Learning
Plotly	Interactive Visualizations
## Project Structure
CryptoSignal-AI/
│
├── crypto_daily.csv
├── crypto.py
├── README.md
│
└── assets/
## Machine Learning Workflow
Data Preparation
Missing value handling
Feature scaling
One-hot encoding for categorical features
Model Training
Train-Test Split (80:20)
Model comparison using:
Accuracy
ROC-AUC Score
Classification Report
Confusion Matrix
Prediction

The best-performing model predicts:

📈 Bullish (Price Up)
📉 Bearish (Price Down)

with confidence scores.

## Input Parameters

Users can customize:

Price Data
Close Price
Trading Volume
Market Cap
Technical Indicators
RSI
MACD
SMA 20
SMA 50
Bollinger Bands
ATR
Volatility
Market Sentiment
Fear & Greed Index
Sentiment Category
## Output

The dashboard displays:

Predicted Market Direction
Confidence Percentage
Upward Probability
Downward Probability
Selected Best Model
## Installation
cd CryptoSignal-AI
Install Dependencies
pip install -r requirements.txt
Run Application
streamlit run crypto.py
## Requirements
streamlit
pandas
numpy
plotly
scikit-learn
## Future Enhancements
Real-time cryptocurrency API integration
Historical price forecasting
Deep Learning (LSTM/GRU) implementation
Portfolio recommendation system
Live market sentiment tracking
Advanced trading signal generation
## Dashboard Highlights
Modern Dark-Themed UI
Interactive Controls
Real-Time Prediction Engine
Professional Analytics Layout
Machine Learning Model Comparison
## Author
Shameel m 

Machine Learning | Data Science 

## Project Summary

CryptoSignal AI combines machine learning, technical analysis, and market sentiment indicators to provide intelligent cryptocurrency price direction predictions through a professional Streamlit dashboard. It serves as an educational and analytical tool for understanding crypto market behavior and ML-based forecasting.
