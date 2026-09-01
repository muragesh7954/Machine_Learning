# Next-Day Stock Return Prediction

Machine learning project for predicting **next-day stock returns** using historical OHLCV data and technical indicators.

## Approach

- Cleaned and validated historical OHLCV data.
- Created return, moving-average, volatility, price-behavior, volume, lag, and technical-indicator features.
- Used chronological **Train / Validation / Test** splits to avoid time-series leakage.
- Compared **Baseline, Linear Regression, and XGBoost** models.
- Evaluated models using **RMSE, MAE, R², and Directional Accuracy**.
- Compared model error distributions using **KS Test** and **Mann–Whitney U Test**.
- Estimated **bootstrap confidence intervals** for model performance.
- Used XGBoost feature importance and evaluated a simple return-based trading strategy using **Sharpe Ratio and Maximum Drawdown**.

## Tech Stack

**Python · Pandas · NumPy · Scikit-learn · XGBoost · SciPy · TA · Matplotlib · Plotly**

## Key Features

- Historical returns and lagged returns
- Moving averages
- Rolling volatility
- OHLC price behavior
- Volume indicators
- Technical indicators
- ATR and OBV
- Date/time features

## Repository

```text
next-day-stock-return-prediction/
│
├── notebook.ipynb
├── README.md
└── data/
```

> **Note:** This project is for educational/research purposes and does not constitute financial advice.