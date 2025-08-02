# 🫀 Heart Disease Prediction with Traditional ML vs. CatBoost

## Overview
This project investigates the performance of different machine learning models in predicting heart disease using structured clinical data. We compare traditional algorithms—**Logistic Regression**, **K-Nearest Neighbors (KNN)**, and **Random Forest**—against **CatBoost**, a modern gradient boosting method designed for high accuracy on tabular data and native handling of categorical features.

## Objectives
- Build a robust heart disease prediction pipeline.
- Evaluate model performance using cross-validation.
- Compare traditional ML models vs. CatBoost on metrics like **Accuracy**, **F1 Score**, **Precision**, **Recall**, and **AUC**.
- Assess the trade-offs between model **simplicity**, **interpretability**, and **predictive power**.

## Dataset
We use the [UCI Cleveland Heart Disease dataset](https://archive.ics.uci.edu/ml/datasets/heart+Disease), a widely studied dataset in medical ML research.

## Tools & Libraries
- Python, Jupyter Notebook
- Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn
- CatBoost

## 🔍 Key Visualizations

### 📊 Traditional Model Evaluation Metrics
evaluation metrics Traditional Model.png

### ⚡ CatBoost Evaluation Metrics
![CatBoost Evaluation](images/catboost%20Evaluation%20Metrics.png)

### 🔁 CatBoost Cross-Validated Metrics
![CatBoost CV Metrics](images/Catboost%20cross-validated%20metrics.png)

### 🔥 CatBoost Feature Importance
![Feature Importance](images/CatBoost%20Feature%20Importance.png)

### 📉 Confusion Matrix (Random vs Grid)
![Confusion Matrix](images/Confusion%20Matrix%20%20Random%20VS%20Grid.png)

### 📈 Cross-Validated Metrics for All Models
![Cross-Validated](images/Cross-validated%20classifiaction%20metrics%20by%20model.png)

### 🧪 Traditional Model Cross-Validated Metrics
![Traditional CV](images/cross-validated%20metrics%20Traditional%20Model.png)

### 🧮 Tuned Models: Random vs Grid Evaluation
![Tuned Evaluation](images/Evaluation%20for%20Tuned%20Models%20Random%20VS%20Grid.png)

## 🗂️ Repository Structure
├── Heart-Disease-Prediction.ipynb # Main notebook
├── images/ # Evaluation visualizations
│ ├── Catboost cross-validated metrics.png
│ ├── catboost Evaluation Metrics.png
│ ├── CatBoost Feature Importance.png
│ ├── Confusion Matrix Random VS Grid.png
│ ├── Cross-validated classifiaction metrics by model.png
│ ├── cross-validated metrics Traditional Model.png
│ ├── Evaluation for Tuned Models Random VS Grid.png
│ └── evaluation metrics Traditional Model.png
├── README.md # Project description and setup
