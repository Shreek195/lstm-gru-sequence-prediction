# 📈 Bitcoin Price Prediction using LSTM & GRU (Deep Learning)

This project builds and compares two deep learning models — LSTM and GRU — to predict Bitcoin closing prices using historical data. The pipeline includes data preprocessing, windowing, model training, evaluation, and visualization.

---

## 🧠 Objective

Predict the future closing price of Bitcoin using sequence modeling with LSTM and GRU architectures. Evaluate both models using RMSE and visualize their predictions against actual values.

---

## 📁 Dataset

The dataset consists of historical Bitcoin prices with columns:
- `Date`
- `Open`
- `High`
- `Low`
- `Close`
- `Volume`

Only the **`Close`** price is used for prediction, as it reflects the final market sentiment for a given day and is commonly used in financial forecasting.

---

## 🔧 Features

- Data cleaning and formatting
- Min-Max Scaling
- Time-series windowing
- LSTM & GRU model construction
- Callbacks (EarlyStopping & ModelCheckpoint)
- RMSE evaluation on training and test sets
- Inverse scaling of predictions
- Graphical comparison of actual vs predicted prices
- RMSE bar chart comparison

---
