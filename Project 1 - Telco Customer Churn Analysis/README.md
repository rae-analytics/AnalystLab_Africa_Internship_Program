# Project 1 – Telco Customer Churn Analysis

## 📌 Project Overview

This project was completed as part of the **AnalystLab Africa Internship Program**.

The objective was to analyze customer churn at **ABC Communications Ltd** and identify customer segments and business factors associated with higher churn rates. The analysis was used to develop data-driven recommendations that can support customer retention strategies.

---

## 🎯 Business Problem

Customer churn is a major challenge in the telecommunications industry. When customers leave, businesses can lose recurring revenue and customer lifetime value while also incurring additional costs to acquire new customers.

ABC Communications Ltd engaged AnalystLab Africa Consulting to investigate customer churn and identify patterns that could help management understand which customers are more likely to leave and where retention efforts should be focused.

---

## 🎯 Project Objectives

The analysis aimed to:

- Understand the composition of the customer base.
- Identify customer segments with high churn rates.
- Examine the relationship between contract type and retention.
- Investigate the relationship between tenure and customer loyalty.
- Identify services associated with customer churn.
- Determine which payment methods have higher churn.
- Develop actionable recommendations for improving customer retention.

---

## ❓ Business Questions

The analysis addressed the following questions:

1. What does the customer base look like?
2. Which segments have the highest churn?
3. Does contract type influence retention?
4. Does tenure affect loyalty?
5. Which services influence churn?
6. Which payment methods have higher churn?
7. What actions should management take?

---

## 📊 Dataset

**Dataset:** Telco Customer Churn Dataset

The dataset contains customer information including:

- Customer demographics
- Tenure
- Phone and internet services
- Online security and technical support
- Contract type
- Paperless billing
- Payment method
- Monthly charges
- Total charges
- Churn status

The dataset contains **7,043 customer records and 21 variables** before cleaning.

---

## 🛠️ Tools & Technologies

- **Python**
- **Pandas** – data loading, cleaning and analysis
- **NumPy** – numerical operations
- **Matplotlib** – data visualization
- **Seaborn** – statistical visualizations
- **Google Colab** – development environment
- **GitHub** – project documentation and portfolio

---

## 🧹 Data Preparation

The dataset was inspected for structure, data types, missing values and duplicates.

The main data-quality issue identified was the `TotalCharges` column, which was initially stored as a string/object data type.

It was converted to numeric using Pandas. This resulted in **11 missing values**, which were removed because they represented a very small portion of the dataset.

A numerical version of the `Churn` variable was also created for correlation analysis:

- `No = 0`
- `Yes = 1`

---

## 📈 Analysis & Visualization

The analysis included:

- Customer demographic analysis
- Churn rate analysis by customer segment
- Contract type analysis
- Tenure analysis
- Service analysis
- Payment method analysis
- Numerical correlation analysis

Visualizations included:

- Bar charts
- Pie charts
- Histograms
- Box plot
- Correlation heatmap

---

## 🔍 Key Findings

### 1. Contract Type

Month-to-month customers had the highest churn rate at **42.7%**, compared with **11.3%** for one-year contracts and **2.8%** for two-year contracts.

### 2. Customer Tenure

Churned customers had a median tenure of approximately **10 months**, compared with approximately **38 months** among customers who stayed.

### 3. Internet Service

Fiber optic customers had a churn rate of **41.9%**, compared with **19.0%** for DSL customers and **7.4%** for customers without internet service.

### 4. Additional Services

Customers without Online Security had a churn rate of **41.8%**, compared with **14.6%** among customers with the service.

Customers without Tech Support also had a substantially higher churn rate (**41.6%**) than customers with the service (**15.2%**).

### 5. Payment Method

Electronic check users had the highest churn rate at **45.3%**, substantially higher than the other payment methods.

---

## ⚠️ Business Risks

The analysis identified three major business risks:

1. **High exposure to month-to-month customers**  
   The high churn rate among month-to-month customers may negatively affect recurring revenue.

2. **Early customer attrition**  
   Higher churn among newer customers may reduce customer lifetime value and the return on customer acquisition efforts.

3. **High-risk service and payment segments**  
   Persistent churn among fiber optic and electronic-check customers could create concentrated revenue and retention challenges.

---

## 💡 Business Opportunities

The analysis identified several opportunities:

1. **Encourage longer-term contracts** through targeted incentives and loyalty benefits.
2. **Strengthen early-stage customer retention** through improved onboarding and proactive engagement.
3. **Improve value and support for high-risk service segments**, particularly fiber optic customers and customers without Online Security or Tech Support.

---

## 📌 Recommendations

Based on the analysis, the following actions are recommended:

1. Offer targeted incentives to suitable month-to-month customers to encourage migration to longer-term contracts.
2. Introduce an early-tenure retention program with onboarding support, check-ins and targeted offers.
3. Investigate the factors contributing to high churn among fiber optic customers.
4. Promote Online Security and Tech Support through bundled packages or introductory offers.
5. Review the electronic-check payment experience and encourage alternative payment methods where appropriate.
6. Develop a churn-risk monitoring system to identify high-risk customers and enable proactive retention interventions.

---

## 📁 Project Files

| File | Description |
|---|---|
| `Telco_Customer_Churn_Analysis.ipynb` | Complete Python analysis and visualizations |
| `Business_Understanding_Report.pdf` | Business research and project context |
| `Dataset_Inspection_Report.pdf` | Dataset inspection and data preparation findings |

---

## 📋 Conclusion

The analysis identified several customer characteristics associated with higher churn, particularly month-to-month contracts, shorter tenure, fiber optic internet service, lack of additional support/security services, and electronic-check payments.

These findings provide ABC Communications Ltd with areas to prioritize when developing customer retention strategies. Targeted interventions focused on high-risk customer segments could help reduce avoidable churn and improve long-term customer retention.

---

## 👤 Project Context

**Program:** AnalystLab Africa Internship Program  
**Role:** Junior Data Analyst  
**Organization:** AnalystLab Africa

#DataAnalytics #Python #CustomerChurn #DataAnalysis #AnalystLabAfrica
