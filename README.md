Stock Trend Prediction Using Machine Learning
Predict Up / Down / Neutral market trend using technical indicators (SMA, ATR, Stochastic Oscillator) and ML models (XGBoost & Logistic Regression)

This project focuses on predicting next-day stock trend (Up, Down, or Neutral) using historical stock market data and technical indicators.
The goal is to build a classification system that learns from past OHLCV (Open, High, Low, Close, Volume) data and predicts the market movement for the next trading day.

This project includes:

**Data preprocessing

Technical indicator generation,
Feature engineering,
Categorical trend labeling,
Model training (XGBoost, Logistic Regression),
Evaluation metrics,
Feature importance analysis**

Dataset

The dataset contains historical stock data (Google Stock).
Columns include:

**Open,
High,
Low,
Close,
Volume**

Technical Indicators Used

**Simple Moving Average,
Average True Range,
Stochastic Oscillator**

Additional Features

**Volume_Change,
SMA_10,
ATR_5,
Stochastic_K,
Volatility metrics (e.g., STD of price),
Price Change (%)**

Trend Labeling (Target Variable)

The target variable Trend is categorized as:
Label	Meaning

**0	Down,
1	Neutral,
2	Up**

 Machine Learning Model:

**XGBoost Classifier,
Handles nonlinear patterns,
Robust to noise,
Shows highest accuracy,
Feature importance ranking used to select best indicators**

 Model Evaluation
 Metrics used:
 
**Accuracy,
Precision,
Recall**,
**F1-Score,
Classification Report,
Confusion Matrix**

 Final Output
 The system predicts:
**Trend: Up,
Trend: Down,
Trend: Neutral**
