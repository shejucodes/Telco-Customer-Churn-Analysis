# 📉 Telco Customer Churn Prediction

## 📌 Project Overview
Customer churn is a major problem for telecom companies. In this project, I analyzed a dataset of 7,000+ customers to identify why they leave and built a Machine Learning model to predict churn.

**Goal:** Predict which customers are at high risk of leaving and identify the key drivers of churn.

## 🛠️ Tech Stack
*   **Language:** Python
*   **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn
*   **Model:** Logistic Regression

## 📊 Key Insights & Results
After analyzing the data and training the model, I found the following:

1.  **Model Accuracy:** **79%**
2.  **Top Churn Driver:** **Fiber Optic Internet**. Customers with this service are significantly more likely to leave, suggesting potential service quality or pricing issues.
3.  **Top Retention Factor:** **Two-Year Contracts**. Customers on long-term contracts rarely churn compared to Month-to-Month users.
4.  **Tenure Matters:** New customers (0-10 months) are the most fragile. Loyalty increases significantly after 1 year.

## 📷 Visualization Highlights
*Check the notebook for full interactive visualizations.*

| Feature | Insight |
|:---:|:---|
| **Contract Type** | Month-to-month contracts have the highest churn rate. |
| **Feature Importance** | Fiber Optic service pushes churn up; Long contracts push churn down. |

## 🚀 How to Run
1. Clone the repository.
2. Install dependencies: `pip install pandas numpy scikit-learn matplotlib seaborn`
3. Run the Jupyter Notebook `Churn_Analysis.ipynb`.

---
*Author: [Your Name]*
