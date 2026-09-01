# ITC Next-Day Return Prediction

Machine learning project to predict **ITC's next-day stock return** using historical OHLCV data, technical indicators, and machine learning models.

## 🎯 Objective

Predict the next-day log return of ITC and compare different prediction approaches.

## 🔄 Workflow

```text
ITC OHLCV Data
      ↓
Data Cleaning & Quality Checks
      ↓
Log Returns & Target Creation
      ↓
Feature Engineering
      ↓
EDA & Correlation Analysis
      ↓
Time-Based Train / Validation / Test Split
      ↓
Baseline / Linear Regression / XGBoost
      ↓
Model Evaluation
      ↓
Statistical Error Analysis
      ↓
Trading Strategy & Risk Metrics
```

## ⚙️ Features

- Historical returns and lagged returns
- Simple moving averages
- Volatility measures
- OHLC price behaviour
- Volume features
- RSI, MACD, Bollinger Bands
- ATR and OBV
- Date/time features

## 🤖 Models

- Baseline
- Linear Regression
- XGBoost Regressor

## 📊 Evaluation

Models are evaluated using:

- RMSE
- MAE
- R²
- Directional Accuracy
- KS Test
- Mann-Whitney U Test
- Bootstrap Confidence Intervals

## 📈 Trading & Risk Analysis

The best-performing model is used to generate trading signals and evaluate:

- Strategy Return
- Sharpe Ratio
- Maximum Drawdown

## 🛠️ Tech Stack

Python • Pandas • NumPy • Scikit-learn • XGBoost • SciPy • TA • Matplotlib • Plotly • Seaborn

## 📁 Repository Structure

```text
ITC-next-day-return-prediction/
│
├── README.md
├── dataset/
│   └── ITC.csv
├── notebooks/
│   └── itc_return_prediction.ipynb
├── src/
├── requirements.txt
└── results/
```