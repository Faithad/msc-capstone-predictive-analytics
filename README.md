# Customer Churn Prediction

## 📌 Project Overview

This project builds a machine learning model to predict customer churn using telecom data.
The goal is to identify customers likely to leave and help businesses take proactive retention actions.

---

## 🚀 Open Notebook in Colab

👉 https://colab.research.google.com/github/Faithad/msc-capstone-predictive-analytics/blob/main/notebooks/capstone_model.ipynb

---

## 📊 Dataset

* Source: IBM Telco Customer Churn dataset
* Contains customer demographics, services, and billing information
* Target variable: **Churn (Yes/No)**

---

## 🧹 Data Preprocessing

* Removed unnecessary columns (e.g., customerID)
* Handled missing values
* Converted categorical variables to numeric
* Applied one-hot encoding
* Scaled features using StandardScaler

---

## 🤖 Model

* Algorithm: Logistic Regression
* Train/Test split: 80/20
* Feature scaling applied for better convergence

---

## 📈 Results

* Accuracy: ~0.78
* Model shows good performance in predicting non-churn customers
* Some imbalance observed in churn prediction (class imbalance)

---

## 📉 Evaluation Metrics

* Classification Report (Precision, Recall, F1-score)
* Confusion Matrix

---

## 🛠️ Tools & Technologies

* Python
* Pandas
* NumPy
* Scikit-learn
* Google Colab

---

## 💡 Key Insights

* Customers with higher monthly charges are more likely to churn
* Contract type and tenure strongly influence churn behavior
* Class imbalance affects prediction performance

---

## 📁 Project Structure

```
notebooks/
  capstone_model.ipynb
README.md
project_report.pdf
```

---

## 👤 Author

Faith Adeyemi

---

## 📌 Future Improvements

* Try advanced models (Random Forest, XGBoost)
* Handle class imbalance (SMOTE / resampling)
* Hyperparameter tuning
* Deploy model as a web app

---
