
# 💸 UPI Transactions Analysis Dashboard | Power BI

<p align="center">
  <img src="https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" />
  <img src="https://img.shields.io/badge/Excel-Dataset-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white" />
  <img src="https://img.shields.io/badge/Data%20Analytics-Project-1769AA?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Status-Completed-2E8B57?style=for-the-badge" />
</p>

<p align="center">
  <b>Turning UPI Transaction Data into Meaningful Business Insights 📊</b>
</p>

---

## 📌 Project Overview

The **UPI Transactions Analysis Dashboard** is a data analytics project developed using **Microsoft Power BI Desktop** as part of the **Udemy Complete Data Analyst Bootcamp – Basic to Advanced**.

The project focuses on analyzing digital payment transactions to explore transaction amounts, payment methods, transaction status, banks, merchants, locations, customer demographics, and device usage.

The goal is to transform raw transaction data into meaningful visual insights that help users understand payment patterns and support data-driven decision-making.

## 🎯 Project Objectives

- 📊 Analyze transaction amounts and transaction activity.
- 💳 Compare payment methods, transaction types, and payment modes.
- 🏦 Explore sending and receiving bank distributions.
- 🛍️ Analyze merchant categories and transaction purposes.
- 🌍 Compare transaction patterns across cities.
- 📱 Explore device usage and customer demographics.
- ✅ Examine successful and failed transactions.
- 💡 Develop actionable recommendations based on the analysis.

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| Microsoft Power BI Desktop | Dashboard development and data visualization |
| Power Query | Data cleaning and transformation |
| Excel | Dataset storage and source data inspection |
| Data Modeling | Organizing data for analysis |
| DAX | Creating calculated measures, where required |
| Data Visualization | Presenting patterns and comparisons |

## 📂 Dataset Description

The project dataset contains **20,000 transaction records** and **20 columns**.

| Feature | Description |
|---|---|
| TransactionID | Unique transaction reference |
| TransactionDate | Date of the transaction |
| Amount | Transaction amount |
| BankNameSent | Sending bank |
| BankNameReceived | Receiving bank |
| RemainingBalance | Recorded remaining balance |
| City | Transaction-associated city |
| Gender | Customer gender category |
| TransactionType | Payment or transfer |
| Status | Successful or failed transaction |
| TransactionTime | Transaction time |
| DeviceType | Mobile, laptop, or tablet |
| PaymentMethod | Phone number, QR code, or UPI ID |
| MerchantName | Merchant associated with the transaction |
| Purpose | Food, shopping, travel, bills, or other purposes |
| CustomerAge | Customer age |
| PaymentMode | Instant or scheduled |
| Currency | Currency recorded for the transaction |

**Dataset period:** January 1, 2024 – December 30, 2024.

> **Data note:** The dataset contains multiple currencies (INR, USD, EUR and GBP). Transaction values should be analyzed separately by currency or converted using a documented exchange rate before calculating combined totals.

## 📈 Key Analysis Areas

### 1. Transaction Performance
- Transaction amount analysis
- Transaction count and average transaction value
- Successful versus failed transactions
- Monthly transaction trends

### 2. Payment Analysis
- Payment method comparison
- Transaction type analysis
- Instant versus scheduled payments
- Transaction purpose analysis

### 3. Banking Analysis
- Sending bank comparison
- Receiving bank comparison
- Bank-wise transaction activity

### 4. Merchant & Location Analysis
- Merchant-wise transaction activity
- City-level comparisons
- Transaction purpose by location

### 5. Customer & Device Analysis
- Customer age-group analysis
- Gender-based transaction distribution
- Device usage patterns

## 💡 Business Recommendations

- **Monitor failed transactions:** Investigate failure patterns by date, payment method, bank, and device.
- **Improve payment reliability:** Identify categories with higher failure rates and investigate possible causes.
- **Optimize the user experience:** Review device and payment-method usage to identify opportunities for smoother transactions.
- **Understand customer behaviour:** Compare transaction purposes and age groups without assuming that correlations imply causation.
- **Monitor bank performance:** Compare transaction volumes and failure rates using consistent definitions.
- **Improve data quality:** Check missing values, duplicate transaction IDs, invalid dates, and inconsistent categories.
- **Ensure accurate reporting:** Keep different currencies separate unless a valid conversion method is applied.

*These recommendations should be validated against the dashboard's actual results before being used for business decisions.*

## 🔄 Project Workflow

```text
Raw Transaction Dataset (Excel)
              ↓
     Data Inspection
              ↓
   Data Cleaning & Preparation
         (Power Query)
              ↓
     Data Modeling / DAX
              ↓
   Interactive Power BI Report
              ↓
      Pattern Identification
              ↓
 Business Insights & Recommendations
```

## 📁 Repository Structure

```text
UPI-Transactions-Analysis-PowerBI/
│
├── README.md
├── UPI Transactions.pbix
└── UPI+Transactions.xlsx
```

- **README.md:** Project documentation.
- **UPI Transactions.pbix:** Power BI report file.
- **UPI+Transactions.xlsx:** Source dataset.

## 🚀 How to Explore the Project

1. Clone or download this repository.
2. Open `UPI Transactions.pbix` using Microsoft Power BI Desktop.
3. Interact with the available charts, filters, and slicers.
4. Explore transaction patterns across different categories.
5. Review the findings and recommendations.

> Note: Visuals and interactive features depend on the report configuration. A compatible Power BI Desktop installation is required to open the PBIX file.

## 🎓 Learning Outcomes

Through this project, I practiced:

- Working with structured transaction data.
- Preparing data for reporting.
- Exploring data using Power BI visuals.
- Understanding transaction KPIs and category comparisons.
- Translating analytical observations into business recommendations.
- Documenting a data analytics project for a professional portfolio.

## 👨‍💻 Project Information

**Project:** UPI Transactions Analysis Dashboard  
**Domain:** Digital Payments & Financial Data Analytics  
**Primary Tool:** Microsoft Power BI Desktop  
**Learning Program:** Udemy Complete Data Analyst Bootcamp – Basic to Advanced

## 🙌 Acknowledgement

This project was completed as part of my learning journey through the Udemy Complete Data Analyst Bootcamp. It helped me practice Power BI and strengthen my understanding of data analysis and visualization.

## ⭐ Support

If you find this project useful, consider giving this repository a ⭐ on GitHub.

<p align="center">
  <b>THANK YOU FOR VISITING! 🙏</b>
  <br/>
  <i>Learning • Analyzing • Improving • Growing 🚀</i>
</p>
