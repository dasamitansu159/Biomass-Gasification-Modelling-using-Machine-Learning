# Biomass Gasification Modeling using Machine Learning

This repository contains machine learning models for predicting gas composition from biomass gasification.  
The focus is on four major syngas components: **CO, CO₂, H₂, and CH₄**.

---

## Dataset
The dataset is based on biomass properties and gasification conditions.  
Inputs include:
- **Proximate Analysis**: Moisture Content (MC), Volatile Matter (VM), Fixed Carbon (FC), Ash  
- **Ultimate Analysis**: C, H, O, N, S  
- **Operating Conditions**: Temperature (°C), Equivalence Ratio (ER), Steam/Biomass Ratio (S/B)  

Outputs:
- **Gas Composition (vol%)**: CO, CO₂, H₂, CH₄  


---

## Models Implemented
The following models were developed and compared:
- Linear Regression  
- Support Vector Regression (SVR)  
- Random Forest Regressor  
- XGBoost Regressor  
- CatBoost Regressor  
- Artificial Neural Network (ANN)  

---

## Results
- Models were evaluated using **R² score**, **MSE**, and **MAE**.  
- Random Forest, XGBoost, and CatBoost showed strong performance for CO, CO₂, H₂, and CH₄ predictions.  
- ANN achieved low error for CO prediction after ~200 epochs of training.  

---

## Tools & Libraries
- **Python 3.x**  
- Scikit-learn  
- XGBoost  
- CatBoost  
- TensorFlow / Keras (for ANN)  
- Matplotlib & Seaborn (for visualization)  
