# Customer Churn Prediction

## Project Overview

This project focuses on predicting customer churn using machine learning techniques. The objective is to identify customers who are likely to leave a company based on demographic and service-related information. Early churn prediction helps businesses improve customer retention and reduce revenue loss.

The project covers the complete machine learning workflow, including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and model interpretation.

---

## Dataset
From Kaggle https://www.kaggle.com/datasets/blastchar/telco-customer-churn?utm_source
The dataset contains customer information such as:

- Demographics
- Account information
- Services subscribed
- Contract type
- Payment method
- Monthly charges
- Total charges
- Customer churn status (target variable)

**Target variable:**

- `Churn`
  - Yes – customer left
  - No – customer stayed

---

## Project Workflow

- Data loading and inspection
- Data cleaning
- Exploratory Data Analysis (EDA)
- Feature engineering
- Data preprocessing using Scikit-learn Pipeline
- Model training
- Model comparison
- Hyperparameter tuning
- Model evaluation
- Feature importance analysis
- SHAP explainability
- Conclusions

---

## Models

The following machine learning models were evaluated:

- Logistic Regression (L1 Regularization)
- Logistic Regression (L2 Regularization)
- XGBoost Classifier

The best-performing model was selected based on classification metrics.

---

## Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC
- Confusion Matrix

---

## Explainability

Model interpretability was performed using:

- Permutation Feature Importance
- SHAP (SHapley Additive exPlanations)

These techniques help identify the features that have the greatest impact on customer churn predictions.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- SHAP

---

## Repository Structure

```
customer-churn/
│
├── customer_churn.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

---

## Results

The project demonstrates an end-to-end binary classification workflow using modern machine learning practices. Different models were compared, and explainable AI techniques were applied to better understand model predictions and feature importance.

---

## Future Improvements

- Cross-validation
- Threshold optimization
- Probability calibration
- Automated hyperparameter tuning with Optuna
- Model deployment using Streamlit or FastAPI

---

## Author

**Aryna Kachaharava**

Machine Learning & Data Science Portfolio
