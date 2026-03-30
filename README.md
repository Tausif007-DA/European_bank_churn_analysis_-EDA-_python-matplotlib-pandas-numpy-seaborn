# European_bank_churn_analysis_-EDA-_python-matplotlib-pandas-numpy-seaborn


# 🏦 Bank Customer Churn Analysis (EDA Project)

## 📌 Project Overview

Customer churn is a major challenge for banks, as losing customers directly impacts revenue and growth.
This project analyzes a European bank customer dataset to identify key factors driving churn and uncover high-risk customer segments.

The goal is to move beyond basic analysis and generate **actionable business insights** that can help improve customer retention.

---

## 🎯 Business Objectives

* What is the overall churn rate?
* Which geography has the highest churn?
* Does gender influence churn behavior?
* Which age group is more likely to churn?
* Does credit score impact churn?
* Are high-value customers leaving?
* Does customer engagement (activity & products) affect churn?
* What combination of factors leads to churn?

---

## 📊 Dataset Description

The dataset contains customer-level information including:

* **Demographics**: Age, Gender, Geography
* **Financial Data**: Balance, Credit Score, Estimated Salary
* **Behavioral Data**: Number of Products, Active Status, Credit Card Usage
* **Target Variable**: `Exited` (1 = Churned, 0 = Retained)

---

## 🛠️ Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

## 🔍 Analysis Approach

The project follows a structured EDA approach:

1. **Data Understanding**

   * Checked structure, data types, and summary statistics
   * Verified data quality and missing values

2. **Univariate & Bivariate Analysis**

   * Distribution of churn
   * Geography vs churn
   * Gender vs churn
   * Age vs churn

3. **Feature Impact Analysis**

   * Credit Score vs churn
   * Balance vs churn
   * Number of products vs churn
   * Active membership vs churn
   * Salary & credit card impact

4. **Segment Analysis**

   * Identified high-value customers
   * Compared churn across segments
   * Built high-risk customer profiles

---

## 📈 Key Insights

### 1. Geography Impact

* Certain regions (e.g., Germany) show higher churn rates
* Indicates possible regional dissatisfaction or competition

---

### 2. Age Factor

* Middle-aged and older customers show higher churn
* Suggests changing financial needs or expectations

---

### 3. High-Value Customers at Risk 🚨

* Customers with **higher account balances** have higher churn
* This is critical as these customers contribute significantly to revenue

---

### 4. Customer Engagement is Key 🔑

* **Inactive members churn significantly more**
* Customers with fewer products are more likely to leave
* Engagement is a stronger driver than income or credit card ownership

---

### 5. Weak Factors

* Estimated salary has little impact on churn
* Having a credit card does not significantly reduce churn

---

## 🎯 High-Risk Customer Segment

The most vulnerable customers are:

* Age > 40
* High account balance
* Inactive members
* Low product usage

👉 These customers show a significantly higher churn rate and represent **high-value loss for the bank**

---

## 💡 Business Recommendations

* 🎯 Target high-value inactive customers with personalized offers
* 📞 Improve engagement through proactive communication
* 🧩 Increase product adoption (cross-sell strategies)
* 🌍 Investigate high-churn regions for service gaps
* 🤝 Provide premium support for valuable customers

---

## 🚀 Conclusion

Churn is not driven by a single factor but by a **combination of behavior and engagement**.
The analysis shows that even high-value customers leave when they are not actively engaged.

Focusing on **customer engagement and personalized retention strategies** can significantly reduce churn and improve long-term profitability.

---

## 📎 Future Scope

* Build a churn prediction model (Machine Learning)
* Deploy dashboard using Power BI / Tableau
* Perform cohort analysis for deeper behavioral insights

---

## 👤 Author

**Tausif Raza**
Aspiring Data Analyst | SQL | Python | Power BI

---
