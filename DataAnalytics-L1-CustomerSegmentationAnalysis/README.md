👥 Customer Segmentation Analysis

Oasis Infobyte Data Analytics Internship — Task 2, Level 1

---

📌 Project Overview

This project focuses on customer segmentation analysis using e-commerce transaction data. The goal is to identify distinct groups of customers based on their purchasing behaviour and provide insights that can support more targeted marketing strategies.

The analysis uses RFM (Recency, Frequency, Monetary) analysis and K-Means clustering to group customers with similar purchasing patterns.

---

🎯 Objectives

- Analyse customer purchasing behaviour
- Clean and prepare the transaction dataset
- Calculate Recency, Frequency, and Monetary (RFM) features
- Standardise the customer features before clustering
- Determine the optimal number of clusters using the Elbow Method
- Apply K-Means clustering
- Profile and interpret each customer segment
- Develop marketing recommendations for each segment

---

🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

---

📊 Dataset

The project uses an Online Retail e-commerce transaction dataset containing information about customer purchases.

Key information includes:

- Customer ID
- Invoice Date
- Quantity
- Unit Price
- Product information
- Transaction details

---

🔍 Analysis Performed

1. Data Cleaning

The dataset was inspected and cleaned by:

- Handling missing values
- Removing invalid transactions
- Removing duplicate records
- Creating a purchase value feature

2. RFM Analysis

Customer behaviour was measured using three key features:

- Recency — how recently a customer made a purchase
- Frequency — how often a customer made purchases
- Monetary — how much a customer spent

3. Feature Standardisation

The RFM features were standardised using StandardScaler so that differences in feature scales would not disproportionately affect the clustering algorithm.

4. K-Means Clustering

The Elbow Method was used to determine a suitable number of customer segments.

K-Means clustering was then applied to group customers based on similarities in their RFM behaviour.

5. Cluster Analysis

Each cluster was profiled using its average Recency, Frequency, and Monetary values to understand the characteristics of the different customer groups.

---

📈 Visualisations

The analysis includes:

- Elbow Method plot
- Customer cluster scatter plots
- RFM feature comparisons
- Customer count by cluster
- Cluster profile visualisations

---

💡 Key Insights

The clustering analysis revealed distinct customer groups with different purchasing behaviours. Some customers demonstrated high purchase frequency and significantly higher spending, while other groups showed lower purchasing activity.

These differences provide an opportunity to develop customer-specific marketing strategies instead of applying the same approach to every customer.

---

🎯 Marketing Recommendations

Based on the customer segments:

- High-value customers: Reward with loyalty benefits, exclusive offers, and personalised promotions.
- Regular customers: Encourage repeat purchases through targeted discounts and product recommendations.
- Less-active customers: Use re-engagement campaigns, personalised offers, and incentives to encourage them to return.

---

✅ Conclusion

Customer segmentation provides a data-driven way to understand different types of customers and their purchasing behaviour. By combining RFM analysis with K-Means clustering, businesses can identify valuable customer segments and develop more targeted marketing strategies.

This project demonstrates the use of data cleaning, feature engineering, standardisation, clustering, visualisation, and business insight generation in customer analytics.

---

📁 Project Files

DataAnalytics-L1-CustomerSegmentationAnalysis/
│
├── README.md
├── Customer_Segmentation.ipynb
├── Online_Retail.csv
└── screenshots/

---

🔗 Technologies

Python | Pandas | NumPy | Scikit-learn | Matplotlib | Seaborn | Jupyter Notebook
