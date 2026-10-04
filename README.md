# 📊 Customer Churn Prediction using Machine Learning

## 📌 Project Overview
This project aims to predict customer churn for a subscription-based service using Machine Learning. By identifying customers at risk of leaving, businesses can take proactive retention actions to minimize revenue loss.

## 🚀 Key Steps & Workflow
1. **Data Preprocessing & EDA:** Cleaned raw data, handled categorical variables, and analyzed correlation between customer features and churn rates.
2. **Modeling:** Trained and evaluated multiple classification models (Random Forest Classifier).
3. **Evaluation:** Evaluated performance using Precision, Recall, F1-Score, and ROC-AUC metrics.
4. **Feature Importance Analysis:** Identified top factors driving customer churn (Tenure, Monthly Charges, Contract Type).

## 🛠️ Tech Stack & Tools
- **Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- **Environment:** Jupyter Notebook / Google Colab

## 📈 Results
- The trained model achieved an accuracy of ~82% on the test set.
- Identified that customers on month-to-month contracts with high monthly charges without tech support are at the highest risk of churn.
