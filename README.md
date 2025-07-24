# Time-series-stock-market-analysis
Time series forecasting project comparing ARIMA, SARIMA, and LSTM models for stock price prediction using Python.

# 📈 Stock Price Forecasting: LSTM vs ARIMA/SARIMA

This project compares traditional time series forecasting techniques (**ARIMA**, **SARIMA**) with a deep learning model (**LSTM**) to predict stock prices. The notebook is developed using Python and Jupyter and is part of my internship project at Zidio.

---

## 📌 Project Objectives

- Collect and analyze historical stock data
- Understand and visualize trend, seasonality, and noise
- Apply and compare:
  - ARIMA (Auto-Regressive Integrated Moving Average)
  - SARIMA (Seasonal ARIMA)
  - LSTM (Long Short-Term Memory neural network)
- Evaluate model performance using RMSE
- Visualize predictions for each method

---

## 🛠 Tools & Libraries

- Python
- Pandas, NumPy
- Matplotlib, Seaborn, Plotly
- Statsmodels (ARIMA, SARIMA)
- TensorFlow / Keras (LSTM)
- Scikit-learn (for preprocessing & evaluation)

---

## 📁 Files

| File | Description |
|------|-------------|
| `compare both lstm and arima sarima forecasting.ipynb` | Main Jupyter notebook with all models |
| `stock_data.csv` *(optional)* | Historical stock dataset used for modeling |
| `README.md` | Project overview |
| `dashboard.png` or `report.pdf` *(optional)* | Output visuals or final report |

---

## 📊 Forecasting Models Used

### 1. **ARIMA**
- Captures autoregressive and moving average patterns
- Best for linear, stationary time series

### 2. **SARIMA**
- Extension of ARIMA for handling **seasonal** data
- Includes seasonal trend and cyclical effects

### 3. **LSTM**
- Recurrent Neural Network capable of learning long-term dependencies
- Effective for nonlinear and complex patterns

---

## 📈 Evaluation Metric

- **RMSE (Root Mean Squared Error)** is used to compare prediction accuracy between models.

---

## 🧠 Key Insights

- ARIMA/SARIMA perform well for simple and seasonal data
- LSTM may outperform traditional models when trends are nonlinear or noisy
- Model choice depends on data complexity, computational resources, and interpretability needs

---

## 🧪 How to Run

1. Clone the repo:
```bash
git clone https://github.com/yourusername/stock-price-forecasting-lstm-vs-arima.git

2. Install required libraries:
```bash
pip install -r requirements.txt

3. Open the notebook:
```bash
jupyter notebook compare\ both\ lstm\ and\ arima\ sarima\ forecasting.ipynb
