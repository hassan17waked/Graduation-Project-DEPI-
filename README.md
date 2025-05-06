# Bank Customer Churn Prediction

This project predicts whether a bank customer will leave the bank (churn) or stay, using machine learning models trained on customer data.

## 🚀 Project Overview

Customer churn is a key business problem in the banking sector. Reducing churn helps improve customer retention and profitability. This project uses customer demographic and account-related data to build a predictive model.

## 🧠 Machine Learning Model

The model used: `XGBoostClassifier`

### Features Used:
- `CreditScore`
- `Gender`
- `Age` (transformed: `ageskewed`)
- `Balance`
- `NumOfProducts`
- `IsActiveMember`
- `Geography` (One-hot encoded: France, Germany, Spain)

### Target:
- `Exited` (1 = customer left, 0 = customer stayed)

## 📊 Model Performance

- Accuracy: **92.3%**
- Recall: **90.1%**
- Precision: **88.5%**
- ROC AUC Score: **94.6%**

## 🛠️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/your-username/churn-prediction.git
cd churn-prediction
