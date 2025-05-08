# 🌦️ ML Weather Dashboard

A machine learning-powered weather forecasting application that predicts temperature using features like humidity, wind speed, and pressure. Built with Python and scikit-learn, and designed for easy extension into a dashboard or API.

---

## 📌 Features

- Predicts daily temperature based on historical weather data.
- Uses Random Forest Regressor for accurate predictions.
- Model evaluation with MAE and RMSE.
- Visual comparison of actual vs predicted temperatures.
- Easily expandable into a web dashboard (e.g., with Streamlit).

---

## 📁 Project Structure

ml-weather-dashboard/
├── data/
│ └── weather_data.csv # Weather dataset
├── models/
│ └── weather_forecast_model.pkl # Saved ML model
├── main.py # ML training & evaluation script
├── requirements.txt # Python dependencies
└── README.md # Project description

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/ml-weather-dashboard.git
cd ml-weather-dashboard
