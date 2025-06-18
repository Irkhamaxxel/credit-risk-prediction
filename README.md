# Credit Risk Prediction using Machine Learning

This project focuses on building predictive models to assess whether a loan applicant is likely to default.

## 📊 Dataset
The dataset contains borrower information with the following features:

| Feature | Description |
|--------|-------------|
| `person_age` | Age |
| `person_income` | Annual income |
| `person_home_ownership` | Home ownership status |
| `person_emp_length` | Employment length (in years) |
| `loan_intent` | Purpose of the loan (e.g., education, medical) |
| `loan_grade` | Loan grade assigned |
| `loan_amnt` | Total loan amount |
| `loan_int_rate` | Interest rate of the loan |
| `loan_status` | Target variable (0 = non-default, 1 = default) |
| `loan_percent_income` | Percentage of income used to repay the loan |
| `cb_person_default_on_file` | Whether borrower has previously defaulted |
| `cb_preson_cred_hist_length` | Credit history length in years |

## 🧠 Models Used
- Logistic Regression
- XGBoost
- Random Forest

## 🧪 Evaluation Metrics
- Accuracy
- Predicted Probability of Default

## 🔍 How to Use
1. Preprocess the dataset
2. Train models
3. Predict and evaluate with new data

## 📁 Files
- `credit_risk_dataset.csv`: The dataset
- `Credit Risk Prediction using Machine Learning.ipynb`: Main notebook

