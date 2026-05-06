# Customer Churn Prediction Platform

## Project Overview
This project predicts whether a telecom customer is likely to churn using Machine Learning and Explainable AI techniques.

The project includes:
- Exploratory Data Analysis (EDA)
- Data preprocessing pipelines
- Logistic Regression
- Random Forest
- XGBoost
- Hyperparameter tuning
- SHAP explainability
- Streamlit deployment

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- SHAP
- Streamlit
- Matplotlib
- Seaborn

---

## Dataset
Telco Customer Churn Dataset

Features include:
- Contract type
- Monthly charges
- Internet service
- Tech support
- Tenure
- Payment methods

Target:
- Churn (Yes/No)

---

## Model Performance

### Tuned XGBoost Results

| Metric | Score |
|---|---|
| Accuracy | 77.7% |
| Precision | 56.1% |
| Recall | 73.3% |
| F1-Score | 63.6% |
| ROC-AUC | 0.839 |

---

## Explainable AI

SHAP analysis was used to:
- identify key churn drivers
- explain individual customer predictions
- improve model transparency

Key churn drivers included:
- Month-to-month contracts
- High monthly charges
- Lack of tech support
- Lack of online security
- Short customer tenure

---

## Streamlit App

The Streamlit application allows users to:
- input customer information
- predict churn probability
- view risk levels
- receive business interpretation

---

## How To Run

Install requirements:

```bash
pip install -r requirements.txt
```

Run Streamlit app:

```bash
streamlit run app.py
```

---

## Author

Chiedoziem Ugwuja
MSc Artificial Intelligence and Data Science
niversity of Hull