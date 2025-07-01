
# Customer Churn Prediction

This project uses machine learning to predict whether a customer is likely to churn based on their account details and service usage. The goal is to help businesses retain customers by identifying churn risk early.

---

## Dataset
- Source: [IBM Telco Customer Churn Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- Size: 7,032 rows × 21 columns
- Target: `Churn` (Yes/No)

---

##  Objective
To build and compare classification models that can predict customer churn with good accuracy, recall, and AUC score.

---

## Tools & Libraries
- Python
- pandas, numpy
- matplotlib, seaborn
- scikit-learn
- xgboost

---

## Models Tested

| Model                | Accuracy | Recall (Churn) | F1 (Churn) | ROC-AUC |
|---------------------|----------|----------------|------------|---------|
| Logistic Regression | 80%      | **57%**        | **61%**    | **0.836** ✅ |
| Random Forest        | 79%      | 52%            | 57%        | 0.816   |
| XGBoost              | 77%      | 52%            | 54%        | 0.814   |

 **Logistic Regression** performed best overall.

---

## Results Summary
- Churn rate: ~26%
- Most important features: `Contract`, `Tenure`, `MonthlyCharges`, `PaymentMethod`
- Final model achieves **balanced recall and precision**, with strong ROC-AUC

---

## Key Skills Demonstrated
- Data cleaning and feature engineering
- Classification modeling
- Handling imbalanced datasets
- Evaluation metrics (Confusion Matrix, ROC-AUC, F1)
- Business application of data science

---

## How to Run

```bash
pip install -r requirements.txt
## Author

Vanessa Chinhengo
