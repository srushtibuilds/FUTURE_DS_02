# FUTURE_DS_02
Interactive Power BI dashboard analyzing customer churn, retention trends, customer lifetime patterns, and key retention drivers using the Telco Customer Churn dataset.
# Customer Retention & Churn Analysis Dashboard

## Project Overview

This project focuses on analyzing customer churn and retention patterns using the Telco Customer Churn dataset. The objective is to identify why customers leave, understand customer lifetime behavior, and uncover key retention drivers that can help businesses improve customer loyalty and reduce churn.

The dashboard was developed in Power BI and presents actionable business insights through interactive visualizations and KPI metrics.

---

## Business Problem

Customer churn directly impacts revenue and long-term business growth. Subscription-based businesses and SaaS companies need to understand:

* Why customers leave the platform
* Which customer segments are most likely to churn
* How long customers remain active
* What factors contribute to customer retention
* What actions can reduce churn and improve customer satisfaction

---

## Dataset

**Dataset:** Telco Customer Churn Dataset

The dataset contains customer demographics, subscription information, contract details, payment methods, internet services, tenure, monthly charges, total charges, and churn status.

---

## Data Cleaning & Preparation

The following preprocessing steps were performed:

* Removed null and missing values
* Converted Total Charges to numeric format
* Verified data types for all columns
* Created tenure groups for customer lifetime analysis
* Validated churn labels and categorical fields
* Created custom DAX measures for KPI calculations

---

## KPIs Created

### Total Customers

Measures the total customer base.

### Churned Customers

Measures the number of customers who left the service.

### Churn Rate (%)

Percentage of customers who churned.

### Retention Rate (%)

Percentage of customers retained.

---

## Dashboard Visualizations

### 1. Contract Type vs Churn Risk

Analyzes churn rate across different contract types.

**Key Finding:**
Month-to-month customers exhibit the highest churn risk compared to long-term contract customers.

---

### 2. Customer Lifetime Analysis

Analyzes churn behavior across tenure groups.

**Key Finding:**
Most churn occurs during the first year of the customer lifecycle.

---

### 3. Payment Method Analysis

Compares churn levels across payment methods.

**Key Finding:**
Customers using Electronic Check show higher churn levels than customers using automated payment methods.

---

### 4. Internet Service Analysis

Examines churn distribution across service types.

**Key Finding:**
Fiber Optic customers account for the largest share of churn.

---

### 5. Decomposition Tree

Identifies the major drivers contributing to customer churn.

**Key Finding:**
Internet service type is a significant factor influencing churn behavior.

---

### 6. Pricing Analysis

Explores the relationship between Monthly Charges, Total Charges, and Churn.

**Key Finding:**
Customers with higher monthly charges tend to show higher churn behavior.

---

## Key Insights

* Churn Rate: 26.54%
* Retention Rate: 73.46%
* Month-to-month contracts have the highest churn risk.
* Most customer churn occurs during the first year.
* Fiber Optic customers contribute the largest portion of churn.
* Electronic Check users exhibit higher churn levels.
* Higher monthly charges are associated with increased customer churn.

---

## Business Recommendations

1. Encourage customers to move from month-to-month contracts to longer-term plans.
2. Strengthen onboarding and engagement during the first year.
3. Improve customer experience for Fiber Optic subscribers.
4. Promote automated payment methods such as AutoPay and Credit Cards.
5. Introduce loyalty programs and retention campaigns for high-risk customer segments.

---

## Tools Used

* Power BI
* Power Query
* DAX
* Data Visualization
* Business Analytics

---



