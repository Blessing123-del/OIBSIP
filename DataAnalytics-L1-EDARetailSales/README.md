# Retail Sales Exploratory Data Analysis (EDA)

**Oasis Infobyte Data Analytics Internship — Task 1, Level 1**

---

## 📌 Project Overview

This project performs an Exploratory Data Analysis (EDA) on an e-commerce retail sales dataset. The analysis explores customer demographics, product categories, order quantities, sales revenue, shipping status, and purchasing patterns.

The goal of this project is to clean the raw transactional dataset, examine underlying data distributions, identify meaningful purchasing patterns, and produce actionable insights to support marketing, inventory management, and logistics decisions.

---

## 🎯 Project Objectives

* Explore overall customer purchasing patterns.
* Analyze sales and revenue generation across product categories.
* Examine demographic buying behavior across age groups and gender.
* Analyze order quantities, unit prices, and total basket value.
* Investigate shipping status distribution and operational order fulfillment.
* Uncover operational bottlenecks and commercial trends in retail performance.

---

## 🛠️ Tools & Technologies

* **Language:** Python
* **Environment:** Jupyter Notebook
* **Data Manipulation & Analysis:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn

---

## 📊 Dataset & Features

The dataset contains **1,000 retail transactions** detailing customer profiles, product metrics, and order fulfillment status.

| Column            | Description                                                     |
| :---------------- | :-------------------------------------------------------------- |
| `Customer ID`     | Unique customer identifier                                      |
| `Gender`          | Gender of the customer                                          |
| `Region`          | Geographic region of the customer                               |
| `Age`             | Customer age                                                    |
| `Product Name`    | Name of the purchased item                                      |
| `Category`        | Department classification (Electronics, Wearables, Accessories) |
| `Unit Price`      | Price per single unit                                           |
| `Quantity`        | Number of units purchased                                       |
| `Total Price`     | Total transaction value (`Unit Price` × `Quantity`)             |
| `Shipping Fee`    | Cost of shipping for the order                                  |
| `Shipping Status` | Fulfillment state (In Transit, Returned, Delivered, Unknown)    |
| `Order Date`      | Date of the transaction                                         |

---

## 🧹 Data Cleaning & Preparation

The raw dataset was audited and preprocessed to ensure data quality before exploratory analysis:

1. **Inspection:** Reviewed the data structure using `.shape`, `.info()`, and `.describe()`.
2. **Missing Values:** Identified missing records in `Region`, `Age`, and `Shipping Status` and handled them appropriately.
3. **Data Type Casting:** Converted `Order Date` into a standard datetime format for time-series analysis.
4. **Data Integrity:** Checked for duplicate transactions, inconsistent entries, and potential outliers in price and quantity distributions.
5. **Final Validation:** Confirmed that no remaining null values were present across the analyzed fields.

---

## 📈 Exploratory Data Analysis & Key Findings

### 1. Revenue by Product Category

* **Electronics** dominated total revenue, generating **1,200,500** and significantly outperforming the other categories.
* **Wearables** generated **74,200**.
* **Accessories** generated **71,900**.
* **Takeaway:** Electronics was the primary revenue driver, accounting for approximately **89% of total revenue**.

### 2. Customer Demographics

* **Age Distribution:** Customers aged **56–65** recorded the highest representation and transaction volume, while the **under-18** bracket had the lowest activity.
* **Gender Analysis:** Male customers recorded higher total purchasing activity and order volume compared with female customers.

### 3. Summary Statistics

* **Average Customer Age:** 46.93 years
* **Average Unit Price:** 457.70
* **Average Basket Quantity:** 3.01 units
* **Average Order Value (Total Price):** 1,346.60
* **Average Shipping Fee:** 12.42

### 4. Shipping & Fulfillment Breakdown

Total transaction value aggregated across order fulfillment stages:

* **In Transit:** 443,560

* **Returned:** 415,640

* **Delivered:** 407,380

* **Unknown:** 80,020

* **Critical Finding:** The total value of **Returned** items (415,640) was slightly higher than the total value of **Delivered** goods (407,380), highlighting a potential operational risk that warrants further investigation.

---

## 💡 Business Recommendations

* **Prioritize High-Revenue Inventory:** Allocate procurement capital and safety stock primarily to the **Electronics** category given its overwhelming revenue contribution.
* **Refine Demographic Targeting:** Develop targeted marketing campaigns based on the purchasing patterns of the **56–65 age group** and male customers, while testing suitable promotional strategies for younger demographics.
* **Investigate Returns:** Conduct an operational review to understand why returned transaction value was comparable to delivered transaction value. Potential areas to investigate include product quality, delivery delays, and product-description mismatches.
* **Standardize Order Tracking:** Investigate orders categorized under `Unknown` status and improve tracking integration with logistics providers.

---
DataAnalytics-L1-EDARetailSales/

│

├── screenshots/

│   └── [project screenshots]

├── EDA RETAIL SALES.ipynb

├── README.md

└── retail_sales_dataset.csv

---

## 👤 Author

**Amula Blessing Peresuwode**

**Data Analyst Intern — Oasis Infobyte**

**Skills demonstrated:** Python • Pandas • NumPy • Matplotlib • Seaborn • Exploratory Data Analysis
## 📁 Repository Structure

