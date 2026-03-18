# Dogecoin Price Prediction

A beginner-friendly data science project that analyzes and predicts Dogecoin (DOGE-USD) prices using Time Series Analysis with the ARIMA model.

---

## Project Description

This project explores historical Dogecoin price data to:
- Analyze price trends over time
- Find correlations between price features (Open, High, Low, Close, Volume)
- Build a Time Series prediction model using **SARIMAX**
- Split data into training and testing sets to evaluate model performance

The dataset used is `DOGE-USD.csv` which contains daily Dogecoin price data including Open, High, Low, Close, and Volume columns.

---

## Libraries Used

| Library | Purpose |
|---|---|
| `Pandas` | Loading and manipulating data (DataFrames) |
| `NumPy` | Fast numerical computations |
| `Matplotlib` | Plotting and visualizing data |
| `Seaborn` | Beautiful statistical visualizations |
| `Scikit-learn` | Machine learning tools (RandomForestRegressor) |
| `Statsmodels` | ARIMA and SARIMAX time series models |

---

## Project Structure

```
dogecoin-price-prediction/
│
├── DOGE-USD.csv          # Dataset
├── Dogecoin_prediction.ipynb  # Main notebook
└── README.md             # You are here!
```

---

## Key Concepts Used

- **DataFrame** → table structure to store and analyze data
- **Correlation** → finding relationships between price columns
- **Data Preprocessing** → converting dates, handling missing values
- **Train/Test Split** → splitting data to train and evaluate the model
- **SARIMAX(p, d, q)** → time series forecasting model

---

