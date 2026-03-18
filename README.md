# 🐶 Dogecoin Price Prediction

A beginner-friendly data science project that analyzes and predicts Dogecoin (DOGE-USD) prices using Time Series Analysis with the ARIMA model.

---

## 📌 Project Description

This project explores historical Dogecoin price data to:
- Analyze price trends over time
- Find correlations between price features (Open, High, Low, Close, Volume)
- Build a Time Series prediction model using **ARIMA**
- Split data into training and testing sets to evaluate model performance

The dataset used is `DOGE-USD.csv` which contains daily Dogecoin price data including Open, High, Low, Close, and Volume columns.

---

## 🛠️ Libraries Used

| Library | Purpose |
|---|---|
| `Pandas` | Loading and manipulating data (DataFrames) |
| `NumPy` | Fast numerical computations |
| `Matplotlib` | Plotting and visualizing data |
| `Seaborn` | Beautiful statistical visualizations |
| `Scikit-learn` | Machine learning tools (RandomForestRegressor) |
| `Statsmodels` | ARIMA and SARIMAX time series models |

### Install all libraries at once:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn statsmodels
```

> **Note:** If you're using Google Colab, most of these libraries are pre-installed! 🎉

---

## 📂 Project Structure

```
dogecoin-price-prediction/
│
├── DOGE-USD.csv          # Dataset
├── dogecoin_prediction.ipynb  # Main notebook
└── README.md             # You are here!
```

---

## 🔑 Key Concepts Used

- **DataFrame** → table structure to store and analyze data
- **Correlation** → finding relationships between price columns
- **Data Preprocessing** → converting dates, handling missing values
- **Train/Test Split** → splitting data to train and evaluate the model
- **ARIMA(p, d, q)** → time series forecasting model

---

## 👶 Who is this for?

This project is built for **complete beginners** who are just starting out with:
- Python for Data Science
- Time Series Analysis
- Cryptocurrency Data Analysis

---

## 🚀 How to Open in Google Colab

1. Go to [colab.research.google.com](https://colab.research.google.com)
2. Click **File → Open Notebook → GitHub**
3. Paste this repository link
4. Open the `.ipynb` file
5. Run all cells and explore! ✅

---

## 📈 Model Used

### ARIMA (AutoRegressive Integrated Moving Average)
| Parameter | Name | Meaning |
|---|---|---|
| `p` | AutoRegression | how many past values to use |
| `d` | Integration | how many times to stabilize data |
| `q` | Moving Average | how many past errors to consider |

---

*Made with ❤️ as a beginner data science project*
