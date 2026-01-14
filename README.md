# 🫀 Heart Disease Prediction — Security-Hardened Machine Learning (OWASP AI Top 10)

## Overview

This project explores heart disease prediction using structured clinical data while demonstrating how **machine learning systems can be designed with security, governance, and trust in mind**.

In addition to comparing traditional machine learning models (**Logistic Regression**, **K-Nearest Neighbors**, **Random Forest**) against **CatBoost**, a modern gradient boosting algorithm optimized for tabular data, the project explicitly integrates **OWASP AI Top 10 security controls** into the ML workflow.

The result is not just a performant model, but a **production-aware, security-hardened AI system** suitable for high-impact domains like healthcare.

---

## Objectives

* Build a robust heart disease prediction pipeline using structured clinical data
* Compare traditional ML models vs. CatBoost using cross-validated metrics
* Evaluate trade-offs between **accuracy**, **interpretability**, and **model complexity**
* Integrate **AI security controls** aligned with the OWASP AI Top 10
* Demonstrate responsible, decision-support-focused AI design in a healthcare context

---

## Dataset

The project uses the **UCI Cleveland Heart Disease dataset**, a widely studied benchmark in medical ML research:

🔗 [https://archive.ics.uci.edu/ml/datasets/heart+Disease](https://archive.ics.uci.edu/ml/datasets/heart+Disease)

The dataset is static, well-documented, and contains **no personally identifiable information (PII)**.

---

## 🔐 AI Security (OWASP AI Top 10)

This project incorporates **security-aware design principles aligned with the OWASP AI Top 10**, demonstrating how AI risks can be mitigated directly within the ML pipeline rather than treated as an afterthought.

### Implemented Controls

* **A01 – Model Manipulation / Data Poisoning**

  * Training data integrity validation
  * Explicit schema enforcement
  * Isolation of the authoritative training dataset from derived artifacts

* **A03 – Input Validation**

  * Enforcement of physiological bounds for key clinical features
  * Rejection of malformed or out-of-range inputs prior to inference

* **A04 – Automation Bias**

  * Clear decision-support framing
  * Explicit disclaimers to prevent misuse as a clinical diagnostic tool
  * Emphasis on human judgment and medical oversight

* **A05 – Transparency**

  * Feature importance analysis to improve interpretability
  * Visibility into which features most influence predictions
  * Audit-friendly model behavior inspection

> Security checks are intentionally applied to the **authoritative training dataset** to prevent integrity controls from being bypassed by derived evaluation or reporting artifacts.

---

## 🧠 Threat Model (High-Level)

### Assets

* Training dataset
* Trained ML models
* Prediction outputs
* Evaluation metrics and visualizations

### Threats & Mitigations

| Threat                       | OWASP AI Category | Mitigation                                   |
| ---------------------------- | ----------------- | -------------------------------------------- |
| Training data poisoning      | A01               | Dataset integrity checks, static data source |
| Out-of-range inputs          | A03               | Input validation and range enforcement       |
| Over-reliance on predictions | A04               | Decision-support framing and disclaimers     |
| Opaque model behavior        | A05               | Feature importance analysis                  |

This threat model highlights how **AI-specific risks are addressed at the system design level**, not just at the model level.

---

## Tools & Libraries

* **Python**, Jupyter Notebook
* **Pandas**, **NumPy**, **Matplotlib**, **Seaborn**
* **Scikit-learn**
* **CatBoost**

---

## Key Visualizations

### 📊 CatBoost CV Metrics

![Catboost cv metrics](./images/catboost_cv_metrics.png)

### 📊 CatBoost Evaluation

![Catboost evaluation](./images/catboost_evaluation.png)

### 📊 CatBoost Feature Importance

![Catboost feature importance](./images/catboost_feature_importance.png)

### 📊 Confusion Matrix (Random vs Grid)

![Confusion matrix random vs grid](./images/confusion_matrix_random_vs_grid.png)

### 📊 Cross-Validated Metrics by Model

![Cross validated metrics by model](./images/cross_validated_metrics_by_model.png)

### 📊 Traditional Model CV Metrics

![Traditional cv metrics](./images/traditional_cv_metrics.png)

### 📊 Evaluation of Tuned Models

![Evaluation tuned models](./images/evaluation_tuned_models.png)

### 📊 Traditional Model Evaluation

![Traditional evaluation](./images/traditional_evaluation.png)

---

## Repository Structure

```
├── Heart-Disease-Prediction.ipynb   # Main notebook (ML + AI security controls)
├── images/                          # Evaluation and transparency visualizations
│   ├── catboost_cv_metrics.png
│   ├── catboost_evaluation.png
│   ├── catboost_feature_importance.png
│   ├── confusion_matrix_random_vs_grid.png
│   ├── cross_validated_metrics_by_model.png
│   ├── traditional_cv_metrics.png
│   ├── evaluation_tuned_models.png
│   ├── traditional_evaluation.png
├── README.md                        # Project overview, AI security, and threat model
```

---

## How to Run

1. Clone the repository
2. Create and activate a virtual environment
3. Install required dependencies
4. Run `Heart-Disease-Prediction.ipynb` using Jupyter Notebook

---

## Why This Project Matters

Machine learning accuracy alone is not sufficient in healthcare contexts.
This project demonstrates how AI systems can be designed to:

* Reduce misuse and over-reliance
* Improve transparency and trust
* Embed security and governance from the start

---

## License

This project is intended for **educational and research purposes only** and is **not a medical device**.

---

