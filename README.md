# MSCS 634 – Advanced Big Data and Data Mining  
## Final Project – Deliverable 4  
**Group Members:**   
Pabitra Bhandari  
Haeri Kyoung  
Vamsi Krishna Gajulapalli  
Prakash Tamang 

### [This is the Powerpoint link for Project Presentation](https://cumber-my.sharepoint.com/:p:/g/personal/pbhandari28619_ucumberlands_edu/IQD-cR7YkP32S4K1i8qXCdlWAT1QsHsuPwWGTX3dilUbgdg?e=Ij3Jia)
---

## 1. Dataset Summary

This project uses the **Online_Retail_II** dataset, which contains transactional records from a UK-based online retail company. The dataset includes more than 500 records and multiple attributes such as:

- Invoice number  
- Stock code  
- Product description  
- Quantity  
- Invoice date  
- Unit price  
- Customer ID  
- Country  

The dataset was selected because it meets the project requirements (8+ attributes and 500+ records) and supports multiple data mining techniques. It allows meaningful analysis of customer purchasing behavior, transaction patterns, and product relationships.

---

## 2. Project Steps

The project followed a structured data mining workflow:

### Data Preprocessing
- Removed duplicates and canceled transactions.
- Handled missing values.
- Converted date fields to proper format.
- Removed invalid or unrealistic values.
- Created derived feature: **Total Transaction Value (Quantity × UnitPrice)**.

### Exploratory Data Analysis (EDA)
- Examined feature distributions.
- Identified outliers.
- Analyzed country-level sales trends.
- Evaluated correlations between numerical variables.

### Regression Modeling
- Built Linear Regression and Regularized Regression models.
- Evaluated using R², MSE, RMSE.
- Applied cross-validation to assess generalization.

### Classification
- Developed classification models to predict categorical outcomes.
- Evaluated using Accuracy, Precision, Recall, F1-score, and Confusion Matrix.

### Clustering
- Applied K-Means to segment customers.
- Identified distinct purchasing behavior groups.

### Association Rule Mining
- Used Apriori or FP-Growth algorithm.
- Identified frequently co-purchased products.
- Evaluated rules using support, confidence, and lift.

---

## 3. Major Findings

- Most transactions involve small quantities, but bulk purchases significantly influence revenue.
- Feature engineering improved model performance across tasks.
- Regularized regression provided better generalization than basic linear regression.
- Classification models captured meaningful customer behavior patterns.
- Clustering revealed distinct customer segments based on purchasing activity.
- Association rule mining identified strong product bundling opportunities.

Overall, combining supervised and unsupervised learning techniques provided comprehensive insights into transactional patterns and customer behavior.

---

