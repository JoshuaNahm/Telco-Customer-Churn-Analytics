# BA305 Project: Customer Churn Prediction in the Telecom Industry

## 📋 Project Overview

This project was conducted as part of the BA305 course to develop a predictive model for **customer churn** in the telecom industry. 

By analyzing customer behavior, we aimed to identify at-risk customers and provide actionable insights to improve customer retention strategies.

The project was divided into key phases:

1. **Data Exploration & Cleaning**

2. **Feature Engineering & Data Preprocessing**

3. **Model Building & Evaluation**

4. **Insights & Recommendations**

---

## 📊 Data Sources

- **Telco Customer Churn Dataset:** Contains customer demographics, service details, account information, and churn status.

- **Records:** 7,043 entries with 21 variables.

- **Key Features:** Tenure, Monthly Charges, Contract Type, Payment Method, and more.

---

## ⚙️ Technologies Used

- **Programming Language:** Python

- **Libraries:** pandas, numpy, seaborn, matplotlib, scikit-learn, XGBoost, CatBoost, LightGBM

- **Techniques:** SMOTE for class imbalance, Grid Search & Random Search for hyperparameter tuning

---

## 🚀 Methodology

### 1. **Data Preprocessing**

- Removed irrelevant columns like `customerID`.

- Encoded categorical variables using **Label Encoding** and **One-Hot Encoding**.

- Handled missing values in `TotalCharges` and normalized numerical features.

### 2. **Exploratory Data Analysis (EDA)**

- Identified trends such as higher churn rates for month-to-month contracts and electronic check payments.

- Visualized churn patterns based on tenure, contract type, and payment method.

### 3. **Model Building & Evaluation**

- Implemented various models:

  - **Logistic Regression:** Baseline model with 81% accuracy.

  - **Random Forest:** Best performance with 85% accuracy and strong feature interpretability.

  - **XGBoost & CatBoost:** Strong models with competitive F1-scores (~84%).

  - **LightGBM:** Efficient model with excellent scalability for larger datasets.

- Applied **SMOTE** to address class imbalance, improving recall for churn prediction.

---

## 📈 Results & Key Findings

- **Top Predictors of Churn:**

  - **Monthly Charges:** Higher charges correlated with increased churn likelihood.

  - **Tenure:** Shorter tenures (0-6 months) significantly increased churn risk.

  - **Contract Type:** Month-to-month contracts had the highest churn rates (~89%).

  - **Payment Method:** Electronic check users were more likely to churn (~57%).

- **Model Performance:**

  - **Random Forest:** 85% accuracy, strong interpretability.

  - **LightGBM:** High efficiency and scalability, ideal for real-time applications.

---

## ✅ Insights & Recommendations

- **Engagement Strategies:** Target customers on month-to-month contracts with loyalty programs.

- **Payment Optimization:** Offer alternative payment methods to electronic check users.

- **Retention Focus:** Prioritize new customers with proactive onboarding and support.

- **Pricing Adjustments:** Address high monthly charges through discounts or bundled services.

---

## 📚 Resources

- **Bain & Company Study:** Retaining customers boosts profitability by over 25%.

- **SMOTE Technique:** Improved model performance by balancing class distribution.

---

## 🎯 Conclusion

Our models successfully predict customer churn with high accuracy, providing telecom companies with actionable insights to reduce churn rates.

By leveraging **Random Forest** and **LightGBM**, businesses can enhance customer retention, optimize resource allocation, and improve long-term profitability.
"""
