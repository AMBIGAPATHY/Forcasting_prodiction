
# 📊 Demand Forecasting System using XGBoost & LightGBM

Production-Grade Time Series Demand Prediction System

---

## 📌 Overview

This project implements an end-to-end machine learning pipeline to forecast weekly product demand using historical sales and pricing data.

The system includes:

- Advanced time-series feature engineering  
- Price elasticity modeling  
- Gradient boosting models (XGBoost & LightGBM)  
- Model interpretability using SHAP  
- 8-week forward demand forecasting  
- Business-oriented insights for decision making  

The solution is designed to support inventory optimization, pricing strategy, and supply chain planning.

---

## 🚀 Key Features

- Weekly demand prediction  
- Lag feature engineering  
- Rolling averages & seasonality modeling  
- Discount percentage & price trend analysis  
- Price elasticity impact evaluation  
- Gradient boosting regression models  
- SHAP-based model interpretability  
- Automated forecast export (CSV output)  

---

## 🛠 Technology Stack

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- XGBoost  
- LightGBM  
- SHAP  
- Matplotlib  
- Holidays Library  

---

# 📂 Project Structure

```
├── data/
│   ├── historical_dataset.csv
│   ├── forecast_next_8_weeks.csv
├── notebooks/
│   ├── Demand_Forecasting_Colab.ipynb
│   ├── Best_Model_Finding_For_Forecasting.ipynb
├── resultmodel_results_summary.csv
├── requirements.txt
└── README.md
```

---

# 🔍 Problem Statement

Develop a predictive model to estimate weekly product demand based on:

- Historical sales data  
- Pricing information  
- Discount periods  
- Time-based seasonality  

The objective is to generate accurate forecasts for the next 8 weeks.

---

# 🔧 Feature Engineering

The following features were engineered:

- Lag features (previous week demand)  
- Rolling averages  
- Discount percentage  
- Price change trends  
- Seasonal indicators  
- Holiday impact features  

Price elasticity was analyzed to understand how pricing changes affect demand.

---

# 🤖 Model Development

Two primary models were implemented:

- XGBoost Regressor  
- LightGBM Regressor  

Evaluation metrics used:

- MAE (Mean Absolute Error)  
- RMSE (Root Mean Squared Error)  
- MAPE (Mean Absolute Percentage Error)  

Model performance was compared to identify the best forecasting model.

---

# 📈 Model Interpretability

SHAP (SHapley Additive exPlanations) was used to:

- Identify top features influencing demand  
- Understand pricing sensitivity  
- Improve business transparency  

---

# 📊 Output

The final model generates:

- Weekly demand forecasts  
- 8-week forward prediction CSV export  
- Performance summary metrics  
- Actual vs Predicted comparison visualizations  

---

# 💼 Business Applications

This system can be used for:

- Inventory planning  
- Supply chain optimization  
- Dynamic pricing strategy  
- Promotion impact analysis  
- Demand anomaly detection  

---

# 🔄 Scalability & Deployment Strategy

- Batch inference pipeline  
- Periodic retraining to handle model drift  
- Feature recalculation automation  
- Cloud deployment ready (AWS / GCP compatible)  
- REST API integration possible for real-time systems  

---

# 🚀 Future Improvements

- Integrate real-time weather APIs  
- Add economic indicators  
- Implement automated alert system for demand spikes  
- Deploy as a production REST API  
- Containerize using Docker  

---

# 📄 License

This project is licensed under the MIT License.
