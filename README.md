# 🚴 CitiBike Ride Demand Prediction & Monitoring Dashboard

This project predicts hourly CitiBike demand using historical data, and provides a live monitoring dashboard to visualize model performance using error metrics such as MAE, MSE, and RMSE.

---

## 📌 Project Overview

- ⏱ **Predicts** number of bike rides for the next 6 hours
- 📈 **Monitors** model performance over time
- 🌐 **Deployed on Streamlit (via Render)** for real-time access
- 🔁 Integrated with **Hopsworks Feature Store** and **MLflow**
- 🧠 Built with Python, Pandas, Plotly, and Streamlit

---

## 🚀 Features

| Feature                      | Description                                              |
|-----------------------------|----------------------------------------------------------|
| ✅ Time-series feature view | Pulls hourly CitiBike data via Hopsworks Feature Store   |
| 📊 Model training pipeline  | Uses scikit-learn regressors with MLflow tracking        |
| 🧪 Monitoring Dashboard      | MAE, MSE, RMSE metrics updated dynamically               |
| 📥 Export option             | Download error data for offline analysis                |
| 🌍 Optional location filter | Analyze performance per station or pickup zone          |
| 🧾 Error metric selector     | Switch between MAE / MSE / RMSE in dashboard            |

---

## 🧪 Technologies Used

- `streamlit`
- `plotly`
- `scikit-learn`
- `pandas`
- `hopsworks`
- `python-dotenv`
- `folium` (optional for mapping)

---
