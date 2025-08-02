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

## Key Visualizations

### 📊 Traditional Model Evaluation Metrics
![Traditional Evaluation](images/evaluation%20metrics%20Traditional%20Model.png)

### ⚡ CatBoost Evaluation Metrics
![CatBoost Evaluation](images/catboost%20Evaluation%20Metrics.png)

### 🔁 Cross-Validated Metrics Comparison
![Traditional CV](images/cross-validated%20metrics%20Traditional%20Model.png)
![CatBoost CV](images/Catboost%20cross-validated%20metrics.png)

### 🧪 Evaluation of Tuned Models
![Tuned Model Comparison](images/Evaluation%20for%20Tuned%20Models%20Random%20VS%20Grid.png)
![Confusion Matrix](images/Confusion%20Matrix%20Random%20VS%20Grid.png)

### 📉 ROC Curve
![ROC](images/ROC%20Curve%20Comparison.png)

### 🔬 Feature Importance
![CatBoost Feature](images/CatBoost%20Feature%20Importance.png)
![LogReg Feature](images/Logisitic%20Regression%20Feature%20Importance.png)
![RF Feature](images/Random%20Forest%20Feature%20Importance.png)

## Repository Structure
```
├── Heart-Disease-Prediction.ipynb   # Main notebook
├── images/                          # Evaluation visualizations
│   ├── [All evaluation .png files]
├── README.md                        # Project description and setup
```

## How to Run
1. Clone the repository
2. Set up a virtual environment and install dependencies
3. Run `Heart-Disease-Prediction.ipynb` using Jupyter Notebook

## License
This project is for educational and research purposes.
