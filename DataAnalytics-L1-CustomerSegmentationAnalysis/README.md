# 🛒 Customer Segmentation Analysis

**Oasis Infobyte Data Analytics Internship — Task 2, Level 1**

---

## 📌 Project Overview

This project focuses on segmenting e-commerce customers based on their purchasing behaviour using **RFM (Recency, Frequency, Monetary) analysis** and **K-Means Clustering**.

The objective was to transform raw transaction data into meaningful customer segments that can help a business understand customer value, identify high-value customers, and develop more targeted marketing and retention strategies.

---

## 🎯 Project Objectives

- Clean and preprocess the raw online retail dataset.
- Analyse customer purchasing behaviour.
- Calculate **Recency, Frequency, and Monetary (RFM)** metrics.
- Prepare RFM data for machine learning.
- Apply **K-Means Clustering** to identify distinct customer groups.
- Profile the resulting customer segments.
- Develop business recommendations based on the customer segments.

---

## 📊 Dataset Overview

The project uses an online retail transaction dataset containing information about customer purchases, products, quantities, transaction dates, prices, and customer identifiers.

| Column | Description |
|---|---|
| `InvoiceNo` | Unique invoice or transaction number |
| `StockCode` | Unique product code |
| `Description` | Product description |
| `Quantity` | Number of items purchased |
| `InvoiceDate` | Date and time of the transaction |
| `UnitPrice` | Price per unit |
| `CustomerID` | Unique customer identifier |
| `Country` | Customer's country |

---

## 🛠️ Tools & Technologies

- **Language:** Python
- **Environment:** Jupyter Notebook
- **Data Manipulation:** Pandas, NumPy
- **Machine Learning:** Scikit-learn
- **Clustering:** K-Means
- **Feature Scaling:** StandardScaler
- **Visualization:** Matplotlib, Seaborn

---

## 🧹 Data Cleaning & Preparation

The raw transaction data was cleaned and prepared before performing customer segmentation.

The following steps were carried out:

1. Inspected the dataset structure, data types, and summary statistics.
2. Checked for missing values and handled records with missing customer identifiers.
3. Removed invalid transaction records where necessary.
4. Created a **PurchaseValue** variable to represent the value of each transaction.
5. Grouped transaction-level data by customer to prepare the RFM metrics.
6. Verified the resulting customer-level dataset before applying clustering.

After cleaning, the dataset contained **9,049 transaction records** available for the analysis.

---

## 🔄 RFM Analysis

RFM analysis was used to measure customer behaviour using three key metrics:

### Recency

Measures how recently a customer made a purchase.

A lower Recency value indicates a customer who purchased more recently.

### Frequency

Measures how frequently a customer makes purchases.

A higher Frequency value indicates more frequent purchasing behaviour.

### Monetary

Measures the total amount spent by a customer.

A higher Monetary value indicates greater customer spending.

The RFM analysis produced **360 unique customer profiles** for segmentation.

---

## 🤖 K-Means Customer Segmentation

K-Means Clustering was applied to the RFM features to identify groups of customers with similar purchasing behaviour.

The customer data was standardized using **StandardScaler** before clustering so that differences in the scale of Recency, Frequency, and Monetary values would not unfairly influence the clustering process.

After evaluating the clustering results, **3 customer clusters** were selected for the final segmentation.

---

## 👥 Customer Segment Profiles

The resulting clusters revealed three distinct customer groups:

| Cluster | Recency | Frequency | Monetary | Customer Profile |
|---|---:|---:|---:|---|
| **0** | 4.92 | 1.12 | 383.98 | Low-frequency, lower-value customers |
| **1** | 1.56 | 1.22 | 378.66 | Recent but relatively low-frequency customers |
| **2** | 2.43 | 4.43 | 5,043.28 | High-frequency, high-value customers |

### 🟢 Cluster 0 — Low-Value / At-Risk Customers

These customers have relatively high Recency values, low purchase frequency, and low monetary value.

They represent customers who purchase infrequently and may require re-engagement strategies.

### 🟡 Cluster 1 — Recent / Occasional Customers

These customers have the lowest Recency value, meaning they have purchased relatively recently. However, their purchase frequency and monetary value remain relatively low.

This group represents an opportunity to increase customer engagement and purchase frequency.

### 🔵 Cluster 2 — High-Value Customers

This cluster stands out because of its significantly higher purchase frequency and monetary value.

These customers are the strongest contributors to customer revenue and represent the most valuable customer segment.

---

## 💡 Key Insights

The segmentation analysis revealed that:

- Customer behaviour differs significantly across the three clusters.
- **Cluster 2** contains the highest-value customers based on both purchasing frequency and monetary value.
- Cluster 2 customers have an average Monetary value of approximately **5,043.28**, considerably higher than the other clusters.
- Clusters 0 and 1 have much lower monetary values, indicating opportunities for customer development and retention.
- RFM analysis provides a useful way to move from raw transaction data to actionable customer profiles.

---

## 💼 Business Recommendations

### 🌟 High-Value Customers — Cluster 2

- Introduce loyalty and VIP rewards.
- Provide personalized product recommendations.
- Offer early access to new products or special promotions.
- Focus on retention because these customers contribute significantly to revenue.

### 📈 Recent / Occasional Customers — Cluster 1

- Encourage repeat purchases through personalized recommendations.
- Use targeted promotions to increase purchasing frequency.
- Introduce loyalty incentives to encourage customers to become regular buyers.

### ⚠️ Low-Value / At-Risk Customers — Cluster 0

- Run targeted re-engagement campaigns.
- Provide relevant offers based on previous purchases.
- Analyse potential reasons for reduced engagement.
- Encourage customers to return through personalized promotions.

---

## 📈 Project Outcome

This project demonstrates how **RFM analysis and K-Means Clustering** can be combined to transform transactional retail data into meaningful customer segments.

The resulting customer profiles provide a foundation for more targeted marketing, customer retention, loyalty programmes, and revenue-growth strategies.

---

## 📁 Repository Structure

```text
DataAnalytics-L1-CustomerSegmentationAnalysis/
│
├── Online_Retail.csv
├── customer_segmentation.ipynb
├── screenshots/
│   └── project_visualizations.png
│
└── README.md
```

---

## 👤 Author

**Amula Blessing Peresuwode**

**Data Analyst Intern — Oasis Infobyte**

**Skills demonstrated:** Python • Pandas • NumPy • Scikit-learn • K-Means Clustering • RFM Analysis • Data Visualization
