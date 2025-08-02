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
![Traditional Model Evaluation](images/evaluation%20metrics%20Traditional%20Model.png)

### 🧪 Traditional Model Cross-Validated Metrics
![Traditional CV Metrics](images/cross-validated%20metrics%20Traditional%20Model.png)

### ⚡ CatBoost Evaluation Metrics
![CatBoost Evaluation](images/catboost%20Evaluation%20Metrics.png)

### 🔁 CatBoost Cross-Validated Metrics
![CatBoost CV Metrics](images/Catboost%20cross-validated%20metrics.png)

### 📉 ROC Curve Comparison
![ROC Curve](images/ROC%20Curve%20Comparison.png)

### 🔀 Confusion Matrix - Tuned Models
![Confusion Matrix](images/Confusion%20Matrix%20Random%20VS%20Grid.png)

### 🧠 Feature Importances
- Logistic Regression  
  ![Logistic Regression Features](images/Logisitic%20Regression%20Feature%20Importance.png)

- Random Forest  
  ![Random Forest Features](images/Random%20Forest%20Feature%20Importance.png)

- CatBoost  
  ![CatBoost Features](images/CatBoost%20Feature%20Importance.png)

### 📊 Cross-Model Comparison
- Preliminary Comparison  
  ![Preliminary](images/Preliminary%20comparison%20chart.png)

- Classification Metrics Comparison  
  ![Model Metrics](images/Cross-validated%20classification%20metrics%20by%20model.png)

- Train vs Test - Tuned Models  
  ![Train vs Test](images/Train%20VS%20Test%20Tuned%20Models%20Random%20VS%20Grid.png)

- Random vs Grid - Tuned Models  
  ![Eval Random vs Grid](images/Evaluation%20for%20Tuned%20Models%20Random%20VS%20Grid.png)

---

## 📁 Repository Structure
```
├── Heart-Disease-Prediction.ipynb       # Main notebook
├── images/                              # Visualizations used in README
│   ├── *.png
├── README.md                            # Project description and setup
```

## 🧪 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/Heart-Disease-Prediction.git
   cd Heart-Disease-Prediction
   ```
2. (Optional) Create a virtual environment and activate it:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

## 📜 License
This project is intended for educational and research purposes only.
This project is for educational and research purposes.
