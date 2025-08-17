# 🌬️ Turbine Energy Yield Prediction

## 📌 Project Overview
This repository hosts a complete machine learning workflow for predicting **Turbine Energy Yield (TEY)** from gas turbine operational and environmental parameters.  
The workflow applies robust preprocessing, feature engineering, model benchmarking, and diagnostic evaluation — ensuring **accuracy, reproducibility, and interpretability**.

---
## 🎯 Objective
Develop a regression model that:
- Accurately predicts the **turbine energy yield** (target variable)
- Handles data variability and outliers effectively
- Provides transparent, well‑documented preprocessing and modeling steps
- Supports scalability and reproducibility for future datasets

---
## 📊 Data Description
The dataset comprises the following features:

Target Variable: Turbine Energy Yield (TEY) in MWH
Features:  
- Ambient Temperature (AT) in C  
- Ambient Pressure (AP) in mbar  
- Ambient Humidity (AH) in %  
- Air Filter Difference Pressure (AFDP) in mbar  
- Gas Turbine Exhaust Pressure (GTEP) in mbar  
- Turbine Inlet Temperature (TIT) in C  
- Turbine After Temperature (TAT) in C  
- Compressor Discharge Pressure (CDP) in mbar  
- Carbon Monoxide (CO) in mg/m3  
- Nitrogen Oxides (NOx) in mg/m3  

## 💡 Modeling Approach    
1. Data Exploration: Exploratory data analysis and visualization to understand feature distributions and relationships  
2. Feature Engineering: (As detailed in the complete README)  
3. Model Selection: Training and evaluation of multiple regression models  
-  Linear Regression
-  Random Forest Regression
-  Support Vector Regression (SVR)
- Decision Tree Regression
- Gradient Boosting Regression
- KNN Regressor
4. Evaluation Metrics:
-  Mean Absolute Error (MAE) 
-  Mean Squared Error (MSE)
-  Root Mean Squared Error (RMSE)
-  R² Score
5. Model Tuning: Hyperparameter optimization using grid search or similar techniques 
6. Analysing the models for over fitting/Under fitting
7. Save the model for future use  

