💳 Credit Card Fraud Detection

Oasis Infobyte Data Analytics Internship — Task 3, Level 2

---

📌 Project Overview

This project focuses on detecting fraudulent credit card transactions using machine learning.

Credit card fraud detection is a challenging classification problem because fraudulent transactions represent only a very small portion of all transactions.

The project explores the transaction data, addresses the class imbalance problem, builds classification models, and evaluates their ability to identify fraudulent transactions.

---

🎯 Objectives

- Explore the credit card transaction dataset
- Understand the distribution of fraudulent and legitimate transactions
- Analyse transaction amount and time patterns
- Identify the challenges caused by class imbalance
- Prepare the data for machine learning
- Split the dataset using a stratified approach
- Train fraud detection models
- Evaluate models using appropriate classification metrics
- Analyse the trade-off between fraud detection and false positives
- Examine the practical scalability of fraud detection systems

---

🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

📊 Dataset

The project uses a credit card transaction dataset containing anonymised transaction features and a target variable indicating whether a transaction was fraudulent.

The dataset contains:

- 284,807 transactions
- 492 fraudulent transactions
- Highly imbalanced classes

This imbalance makes fraud detection different from ordinary classification problems because a model can achieve high accuracy while still failing to detect fraudulent transactions.

---

🔍 Exploratory Data Analysis

The dataset was explored to understand:

- Transaction class distribution
- Fraudulent vs legitimate transactions
- Transaction amount patterns
- Transaction time patterns
- Relationships between transaction features

Visualisations were used to highlight the significant imbalance between fraudulent and legitimate transactions.

---

⚠️ Class Imbalance

Fraudulent transactions represent only a very small percentage of the dataset.

Because of this, accuracy alone is not a reliable measure of model performance.

For example, a model could predict almost every transaction as legitimate and still achieve very high accuracy while detecting very few fraudulent transactions.

Therefore, this project focuses on:

- Precision
- Recall
- F1-score
- ROC-AUC

---

🤖 Machine Learning

A classification approach was used to distinguish fraudulent transactions from legitimate ones.

The data was divided into training and testing sets using a stratified split to preserve the distribution of fraudulent transactions.

Class imbalance was considered during model development because correctly identifying fraudulent transactions is more important than simply maximising overall accuracy.

---

📈 Model Evaluation

The model was evaluated using several metrics.

Logistic Regression Results

Metric| Score
Precision| 0.13
Recall| 0.90
F1-Score| 0.23
ROC-AUC| 0.976

The model achieved a high recall of 0.90, meaning it was able to identify a large proportion of fraudulent transactions.

However, its lower precision indicates that some legitimate transactions were also classified as fraudulent.

---

⚖️ Precision vs Recall

Fraud detection requires a balance between precision and recall.

High Recall

High recall is important because missing a fraudulent transaction can result in financial loss.

High Precision

High precision is also important because incorrectly flagging legitimate transactions can inconvenience customers and require additional verification.

Therefore, the ideal fraud detection system should balance both objectives according to the business requirements.

---

📊 Evaluation Metrics

Precision

Measures how many transactions predicted as fraudulent were actually fraudulent.

Recall

Measures how many of the actual fraudulent transactions were successfully detected.

F1-Score

Combines precision and recall into a single metric.

ROC-AUC

Measures how effectively the model distinguishes fraudulent transactions from legitimate ones across different classification thresholds.

---

💡 Key Insights

- Credit card fraud detection is highly affected by class imbalance.
- Accuracy alone can give a misleading impression of model performance.
- Recall is particularly important when the goal is to detect as many fraudulent transactions as possible.
- The model achieved a high ROC-AUC score of 0.976.
- The high recall came with lower precision, showing the trade-off between catching fraud and generating false alerts.
- Fraud detection systems need to balance model performance with real-world customer and financial considerations.

---

🚀 Real-World Scalability

A real-world fraud detection system may need to process a very large number of transactions in a short period of time.

For production use, such a system would need:

- Fast prediction times
- Automated transaction monitoring
- Real-time or near-real-time scoring
- Regular model retraining
- Monitoring for changes in fraud patterns
- Appropriate alert thresholds
- Secure handling of transaction data

---

📁 Project Files

DataAnalytics-L2-FraudDetection/
│
├── README.md
├── Fraud_Detection.ipynb
├── creditcard.csv
└── screenshots/

---

🎯 Conclusion

This project demonstrates how machine learning can be applied to credit card fraud detection.

The analysis highlighted the importance of handling class imbalance and using appropriate evaluation metrics instead of relying solely on accuracy.

The Logistic Regression model achieved a 0.90 recall and 0.976 ROC-AUC, showing strong ability to distinguish fraudulent transactions, although its precision indicates that further optimisation would be useful to reduce false alerts.

Overall, the project provided practical experience in imbalanced classification, fraud analytics, model evaluation, and real-world machine learning considerations.
