# Customer-Churn-Prediction
# Customer Churn Prediction Using Machine Learning

## 📌 Project Overview

This project aims to predict customer churn in the telecommunications industry using Machine Learning techniques. It analyzes customer demographics, service subscriptions, contract details and billing information to identify customers who are likely to discontinue their services. The project also incorporates model explainability and customer risk segmentation to generate actionable insights that support customer retention strategies.

## 🎯 Objectives

- Analyze customer behavior and identify churn patterns.
- Perform data cleaning, preprocessing and exploratory data analysis.
- Develop and compare multiple Machine Learning classification models.
- Optimize model performance using hyperparameter tuning and cross-validation.
- Interpret model predictions using SHAP.
- Identify high-risk customer segments and propose retention strategies.

## 📂 Dataset

**Dataset:** Telco Customer Churn

- Total Records: 7,043
- Original Features: 21 (excluding the target variable)
- Target Variable: `Churn`
- Prediction Classes: Stayed (0) and Churned (1)

The dataset contains customer demographics, tenure, contract type, internet services, payment methods and billing information.

## 🛠️ Technologies & Tools

- **Programming Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
- **Machine Learning:** Scikit-learn, XGBoost
- **Explainable AI:** SHAP
- **Environment:** Jupyter Notebook

## ⚙️ Project Workflow

1. **Data Understanding:** Examined dataset structure, feature types and customer churn distribution.
2. **Data Preprocessing:** Handled missing values, removed unnecessary columns, standardized categorical values and encoded the target variable.
3. **Exploratory Data Analysis:** Investigated customer demographics, contract types, billing patterns and service-related factors affecting churn.
4. **Feature Engineering:** Created a new feature, `ServiceCount`, to represent the number of services used by each customer.
5. **Model Development:** Built Logistic Regression, Random Forest and XGBoost classification models.
6. **Hyperparameter Tuning:** Applied stratified 5-fold cross-validation and hyperparameter optimization to improve model performance.
7. **Model Evaluation:** Compared models using Accuracy, Precision, Recall, F1-Score, ROC-AUC and Confusion Matrices.
8. **Model Explainability:** Applied SHAP and feature importance analysis to understand the factors influencing predictions.
9. **Customer Risk Assessment:** Segmented customers into Low, Medium and High churn-risk categories using out-of-fold prediction probabilities.
10. **Business Recommendations:** Identified high-risk customer characteristics and proposed targeted retention strategies.

## 📊 Model Performance

Final test-set evaluation:

| Model               |   F1-Score |    ROC-AUC |
| ------------------- | ---------: | ---------: |
| Logistic Regression |     0.6176 |     0.8408 |
| Random Forest       |     0.6279 |     0.8424 |
| XGBoost             | **0.6363** | **0.8450** |

**Best Performing Model: XGBoost**

- Accuracy: 77%
- Precision: 55%
- Recall: 75%
- F1-Score: 63.63%
- ROC-AUC: 84.50%

## 🔍 Explainable AI & Risk Segmentation

SHAP analysis was used to understand the contribution of individual features to customer churn predictions.

Customers were categorized into three risk groups:

- Low Risk
- Medium Risk
- High Risk

The high-risk group contained 1,878 customers, of whom 1,075 were actual churners, representing an observed churn rate of 57.24%.

## 💡 Business Insights & Recommendations

Based on high-risk customer characteristics, the project proposes:

- Reviewing incentives for month-to-month contract customers.
- Offering technical support and online security assistance.
- Reviewing service experience among fiber-optic internet customers.
- Encouraging convenient automatic payment methods.
- Providing early engagement support for newly acquired customers.
- Reviewing suitable pricing plans for customers with higher monthly charges.

These recommendations are exploratory and have not been experimentally validated.

## 🚀 Key Outcomes

- Developed an end-to-end customer churn prediction pipeline.
- Compared three Machine Learning classification algorithms.
- Achieved an F1-score of 63.63% and ROC-AUC of 84.50% with XGBoost.
- Applied SHAP for model interpretability.
- Developed a customer risk assessment framework.
- Generated data-driven customer retention recommendations.

## 📁 Project Structure

```text
Customer-Churn-Prediction/
│
├── Customer Churn Prediction.ipynb
├── telco dataset.csv
└── README.md
```

##

## 👩‍💻 Author

**Atchaya A D R**

Aspiring Data Scientist | Machine Learning | Deep Learning | Data Analytics

[GitHub](https://github.com/Atchaya-2004)

---

⭐ If you find this project useful, feel free to explore the repository!
