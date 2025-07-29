# 📈 Netflix Stock Price Prediction using LSTM

This project uses **Long Short-Term Memory (LSTM)**, a type of recurrent neural network (RNN), to forecast the closing stock prices of **Netflix (NFLX)** using historical time series data.

## 📂 Project Structure

- `Netflix LSTM.ipynb`: Jupyter notebook with full implementation
- `Netflix_stock_data.csv`: Dataset used for training and testing (daily Netflix stock prices)
- `README.md`: Project overview and instructions

---

## 🧠 Project Objective

To build a deep learning model that can **predict future stock prices** based on historical price trends, helping in financial analysis and decision-making.

---

## 🔍 Dataset Overview

- **Source**: Netflix_stock_data Kaggle
- **Columns**: Date, Open, High, Low, Close, Volume
- **Used Feature**: `Close` (closing price)

---

## ⚙️ Technologies Used

- Python 3
- Pandas & NumPy
- Scikit-learn
- Matplotlib & Seaborn
- TensorFlow / Keras

---

## 🚀 Model Architecture

- Scaled closing price using `MinMaxScaler`
- Created sequences of 60 time steps as input features
- Built LSTM model:
  - 2 LSTM layers
  - 1 Dropout layer to prevent overfitting
  - 1 Dense output layer
- Trained using `'adam'` optimizer and `'mean_squared_error'` loss

---

## 📈 Results

- Visualized predictions vs actual stock prices
- Suitable for short-term forecasting and trend analysis

---

## 🛠️ How to Run

1. Clone this repo  
   ```bash
   git clone https://github.com/yourusername/netflix-stock-prediction.git
   cd netflix-stock-prediction
