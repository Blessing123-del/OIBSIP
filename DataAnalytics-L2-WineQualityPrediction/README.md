
🍷 Wine Quality Prediction Using Machine Learning

Oasis Infobyte Data Analytics Internship — Task 2, Level 2

«Predicting wine quality through machine learning.»

📌 Project Overview

This project focuses on predicting wine quality based on its physicochemical properties, including acidity, density, sulphates, and alcohol content.

Multiple machine learning classification models were trained and compared to determine which model was most suitable for predicting wine quality.

🎯 Objectives

- Predict wine quality using machine learning classification techniques.
- Understand how physicochemical properties influence wine quality.
- Address class imbalance and prepare the data for reliable modelling.
- Train and compare multiple classification algorithms.
- Evaluate model performance using appropriate classification metrics.
- Identify the most important features influencing wine quality predictions.
- Determine the most suitable model for potential real-world deployment.

🔎 Key Steps

1. 📂 Data Exploration

Loaded and explored the Wine Quality dataset to understand its structure and quality score distribution.

2. 📊 Exploratory Data Analysis

Performed exploratory data analysis using:

- Distribution plots
- Correlation heatmap
- Quality score analysis

3. ⚖️ Class Imbalance Analysis

Examined class imbalance and identified quality scores that were underrepresented in the dataset.

4. 🔄 Target Variable Engineering

Engineered the target variable by grouping quality scores into meaningful quality classes for classification.

5. ✂️ Data Splitting

Performed a stratified train/test split to preserve the distribution of quality classes across the training and testing datasets.

6. 🤖 Model Training

Trained and compared three classification models:

- Random Forest
- SGD Classifier
- Support Vector Classifier (SVC)

7. 📈 Model Evaluation

Evaluated each model using:

- Accuracy
- Classification reports
- Confusion matrices

8. 🌲 Feature Importance

Created a feature importance chart to identify the chemical properties that contributed most to the Random Forest predictions.

9. 🏆 Model Comparison

Compared the performance of all three classification models side-by-side and identified the most suitable model based on predictive performance and practical deployment considerations.

📊 Model Performance

The three classification models were evaluated and compared using standard classification metrics.

Model| Accuracy
Random Forest| 67.20%
SGD Classifier| 57.20%
SVC| 64.60%

Based on the evaluation results, Random Forest achieved the highest accuracy among the three models tested.

🛠️ Tools & Technologies

🐍 Python | 🐼 Pandas | 🔢 NumPy | 🤖 Scikit-learn | 📊 Matplotlib | 📈 Seaborn | 🌲 Random Forest | 📓 Jupyter Notebook

📸 Screenshots

Project Screenshots

"Project Screenshots" (./screenshots/project-screenshots.png)

📁 Repository Structure

DataAnalytics-L2-WineQualityPrediction/
│
├── 📓 Wine Quality Prediction.ipynb
├── 📄 README.md
├── 📊 Dataset
│
└── 📸 screenshots/
    └── project-screenshots.png

💡 Conclusion

This project provided practical experience in applying machine learning classification techniques to predict wine quality from physicochemical properties.

Through exploratory data analysis, target variable engineering, class imbalance analysis, model training, evaluation, and feature importance analysis, the project demonstrated how machine learning can be used to transform chemical characteristics into meaningful quality predictions.

Among the models tested, Random Forest achieved the strongest predictive performance, making it the most suitable model within this project for potential real-world application.

👩🏽‍💻 Author

Amula Blessing Peresuwode

Data Analytics Intern — Oasis Infobyte

---

#OasisInfobyte #DataAnalysis #Internship #DataAnalytics #MachineLearning #WineQualityPrediction #Python #Classification