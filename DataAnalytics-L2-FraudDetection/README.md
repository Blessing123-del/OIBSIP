
💳 Fraud Detection Using Machine Learning

Oasis Infobyte Data Analytics Internship — Task 3, Level 2

«Detecting fraudulent transactions with machine learning.»

📌 Project Overview

This project focuses on building a machine learning pipeline to identify fraudulent financial transactions from a highly imbalanced dataset.

The project addressed the challenges of class imbalance, explored transaction patterns, trained multiple classification models, and evaluated their ability to detect fraudulent transactions accurately.

🎯 Objectives

- Build a machine learning system for detecting fraudulent transactions.
- Address severe class imbalance in financial transaction data.
- Identify patterns that distinguish fraudulent transactions from legitimate ones.
- Compare multiple classification models for fraud detection.
- Evaluate models using metrics appropriate for imbalanced datasets.
- Understand the Precision-Recall trade-off in fraud detection.
- Explore how a fraud detection system could be scaled for real-world financial applications.

🔎 Key Steps

1. 📂 Data Exploration

Loaded and explored the transaction dataset to understand its structure and identify the level of class imbalance.

2. 💰 Transaction Analysis

Analysed the distribution of transaction amounts for fraudulent and non-fraudulent transactions.

3. ⏰ Pattern Analysis

Examined transaction patterns based on time of day to identify potential differences between fraudulent and legitimate transactions.

4. ⚖️ Class Imbalance Analysis

Investigated why standard accuracy can be misleading when working with highly imbalanced fraud datasets.

5. 🔄 SMOTE

Applied SMOTE (Synthetic Minority Oversampling Technique) to address class imbalance and improve the representation of fraudulent transactions during model training.

6. ✂️ Data Splitting

Performed a stratified train/test split to ensure fraud cases were appropriately represented in both datasets.

7. 🤖 Model Training

Trained and compared two classification models:

- Logistic Regression
- Random Forest

8. 📊 Model Evaluation

Evaluated model performance using metrics suited to imbalanced classification problems:

- Precision
- Recall
- F1-Score
- AUC-ROC

9. 🎯 Precision-Recall Analysis

Analysed the trade-off between Precision and Recall to understand which metric is particularly important when detecting fraudulent transactions.

10. 🔍 Feature Importance

Examined feature importance to identify variables that contributed to fraud predictions.

11. 🚀 Real-World Application

Considered how the fraud detection model could be scaled to handle large volumes of financial transactions in real-world financial applications.

📊 Model Performance

The models were evaluated using Precision, Recall, F1-Score, and AUC-ROC rather than relying solely on accuracy, since fraud detection datasets are typically highly imbalanced.

The evaluation focused particularly on the model's ability to correctly identify fraudulent transactions while minimizing false alarms.

🛠️ Tools & Technologies

🐍 Python | 🐼 Pandas | 🔢 NumPy | 🤖 Scikit-learn | ⚖️ Imbalanced-learn (SMOTE) | 📊 Matplotlib | 📈 Seaborn | 📓 Jupyter Notebook

📸 Screenshots

Project Screenshots

"Project Screenshots" (./screenshots/project-screenshots.png)

📁 Repository Structure

DataAnalytics-L2-FraudDetection/
│
├── 📓 Fraud Detection.ipynb
├── 📄 README.md
├── 📊 Dataset
│
└── 📸 screenshots/
    └── project-screenshots.png

💡 Conclusion

This project provided practical experience in applying machine learning to financial fraud detection.

Through exploratory data analysis, class imbalance handling with SMOTE, model training, performance evaluation, Precision-Recall analysis, and feature importance analysis, the project demonstrated how machine learning can be used to identify potentially fraudulent transactions.

The project also highlighted the importance of selecting appropriate evaluation metrics when working with highly imbalanced datasets and provided insight into how fraud detection systems can be developed for large-scale financial applications.

👩🏽‍💻 Author

Amula Blessing Peresuwode

Data Analytics Intern — Oasis Infobyte

---

#OasisInfobyte #DataAnalysis #Internship #DataAnalytics #MachineLearning #FraudDetection