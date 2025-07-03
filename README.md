
# 🌞 Solar Panel Efficiency Predictor

This repository contains a machine learning pipeline to **predict the efficiency of solar panels** based on various environmental, operational, and physical features.This project aims to predict the operational efficiency of solar panels using environmental and maintenance-related data. By leveraging advanced regression techniques and ensemble learning models, the solution helps optimize energy output and panel longevity — simulating a real-world data-driven infrastructure problem.

## 📌 Problem Statement

The objective is to build a predictive model that estimates **solar panel efficiency** using features such as:

- Temperature  
- Irradiance (solar radiation)  
- Humidity  
- Panel Age  
- Maintenance History  
- Sensor Readings (e.g., voltage, current)
- .... Many other Features

This model aids in:

- Optimizing solar energy production  
- Proactive maintenance scheduling  
- Enhancing decision-making in solar installations  

## 🧰 Features of the Project

- Data preprocessing and cleaning
- Handling negative values and missing data
- Feature engineering (including polynomial features)
- Feature selection using SHAP values
- Hyperparameter optimization with Optuna
- Model training using:
  - XGBoost
  - LightGBM
  - CatBoost
- Stacked ensemble model for final prediction

## 📈 Model Performance

| Step                             | Accuracy (%) |
|----------------------------------|--------------|
| Individual ML Models             | 85.82        |
| Stacked Ensemble                 | 89.82        |
| SHAP + Optuna Optimization       | 89.89        |
| **Target Accuracy**              | **91+**      |

## 📁 Repository Contents
-Efficiency predicator model file
- Requirements.txt

## 🔄 Workflow Overview
### Preprocessing:
- Drop invalid records (e.g., negative values)
- Encode and normalize features

### Feature Engineering:
- Polynomial and interaction features
- SHAP-based feature selection

### Modeling:
- Train and validate ML models
- Perform hyperparameter tuning
- Stack final ensemble

### Prediction:
- Predict solar panel efficiency for new/unseen data

## 📌 Future Enhancements
- Time-series modeling using LSTM/GRU for temporal trends
- Integration with live sensor data via APIs
- Model deployment as a web service

## 👨‍💻 Author
 - Ayush
 - B.Tech CSE, 3rd Year
- Interested in ML, analytics, and renewable energy systems
