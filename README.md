
# Customer Churn Prediction using Machine Learning

Predicting telecom customer churn using machine learning models including **Naive Bayes**, **K-Nearest Neighbors (KNN)**, and **XGBoost**. The project includes data preprocessing, exploratory data analysis (EDA), feature engineering, model evaluation, and business insights through data visualization.

---

## Project Overview

Customer churn prediction helps businesses identify customers who are likely to leave their services. By detecting churn early, organizations can implement retention strategies, improve customer satisfaction, and reduce revenue loss.

This project develops and compares multiple classification models to predict customer churn using the Telco Customer Churn dataset.

---

## Project Highlights

- Built three machine learning classification models.
- Performed data preprocessing and feature engineering.
- Compared model performance using multiple evaluation metrics.
- Created business-oriented visualizations and dashboard.
- Designed a system architecture illustrating the end-to-end ML pipeline.

---

## Dataset

The dataset contains telecom customer information including:

- Gender
- Senior Citizen
- Partner
- Dependents
- Tenure
- Internet Service
- Contract Type
- Monthly Charges
- Total Charges
- Churn

Dataset location:

```
data/Churn_Modelling.csv
```

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Jupyter Notebook

---

## Machine Learning Workflow

1. Data Collection
2. Data Cleaning
3. Data Preprocessing
4. Feature Engineering
5. Exploratory Data Analysis
6. Model Training
7. Model Evaluation
8. Dashboard Visualization

---

## Models Implemented

- Naive Bayes
- K-Nearest Neighbors (KNN)
- XGBoost

---

## Key Insights

- XGBoost achieved the best customer churn prediction performance.
- KNN demonstrated strong overall accuracy.
- Customer tenure significantly influenced churn probability.
- Dashboard visualizations provide actionable business insights for customer retention.

---

## Repository Structure

```text
customer-churn-prediction/
│
├── data/
│   └── Churn_Modelling.csv
│
├── notebooks/
│   └── Customer_Churn_Prediction.ipynb
│
├── reports/
│   └── Customer_Churn_Prediction_Report.pdf
│
├── images/
│   ├── dashboard.png
│
├── README.md
├── LICENSE
└── .gitignore
```

---

## Future Improvements

- Hyperparameter tuning
- Cross-validation
- Model deployment using Streamlit or Flask
- Real-time churn prediction API
- SHAP and LIME model explainability

---

## Author

**Samaa Shafqat**

MS Business Analytics

SZABIST Islamabad

---

## License

This project is licensed under the MIT License.
