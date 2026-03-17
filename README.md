# weather-prediction-lstm
# 🌦️ Weather Prediction using LSTM (Delhi Climate Dataset)

## 📌 Overview

This project predicts **next-day temperature** using a deep learning model (LSTM) based on historical weather data.

---

## 📊 Dataset

* Daily Delhi Climate Dataset
* Features:

  * Mean Temperature
  * Humidity
  * Wind Speed
  * Mean Pressure

---

## 🤖 Model

* LSTM (Long Short-Term Memory)
* Multivariate input (4 features)
* Output: Temperature

---

## ⚙️ Methodology

1. Data preprocessing (handling missing values)
2. Feature scaling using MinMaxScaler
3. Time-series sequence creation (10 days window)
4. LSTM model training
5. Testing on unseen dataset

---

## 📈 Results

* RMSE: **1.99°C**
* MAE: **1.64°C**
* R² Score: **0.90**

👉 The model successfully captures temperature trends with high accuracy.

---

## 📊 Output Visualization

![Prediction](outputs/prediction_plot.png)

---

## 🚀 How to Run

```bash
pip install -r requirements.txt
python train.py
```

---

## 🧠 Key Learnings

* Time-series forecasting using LSTM
* Multivariate sequence modeling
* Model evaluation using RMSE, MAE, R²

---

## 🔥 Future Improvements

* Multi-step forecasting (7-day prediction)
* Hyperparameter tuning
* Deployment using Streamlit

---
