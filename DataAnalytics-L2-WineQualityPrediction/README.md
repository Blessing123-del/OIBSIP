🍷 Wine Quality Prediction

Oasis Infobyte Data Analytics Internship — Task 2, Level 2

---

📌 Project Overview

This project focuses on predicting wine quality categories using machine learning classification techniques.

The original wine quality scores were transformed into three categories — Low, Medium, and High — to create a classification problem.

Different machine learning models were trained and compared to determine which model performed best at predicting wine quality.

---

🎯 Objectives

- Explore and understand the wine quality dataset
- Inspect data types and identify missing values
- Analyse the distribution of wine quality
- Transform quality scores into classification categories
- Examine class balance
- Prepare features for machine learning
- Split the dataset into training and testing sets
- Train multiple classification models
- Evaluate model performance
- Compare the models and identify the best-performing approach
- Analyse important features influencing wine quality

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

The dataset contains measurements describing the chemical properties of wine.

Features include variables such as:

- Fixed acidity
- Volatile acidity
- Citric acid
- Residual sugar
- Chlorides
- Free sulfur dioxide
- Total sulfur dioxide
- Density
- pH
- Sulphates
- Alcohol

The quality score was used as the basis for creating the target classification variable.

---

🔄 Data Preparation

The wine quality scores were grouped into three categories:

- Low
- Medium
- High

The dataset was then prepared for machine learning by separating the features from the target variable and splitting the data into training and testing sets.

---

🔍 Exploratory Data Analysis

Exploratory analysis was performed to understand the dataset and identify patterns between the chemical properties and wine quality.

Visualisations included:

- Quality distribution
- Feature distributions
- Correlation analysis
- Correlation heatmap

Class distribution was also examined to identify potential imbalance between the quality categories.

---

🤖 Machine Learning Models

Three classification algorithms were trained and evaluated:

1. Random Forest

Random Forest was used to capture potentially complex relationships between the chemical properties and wine quality.

Accuracy: 67.2%

2. SGD Classifier

The Stochastic Gradient Descent classifier was tested as another classification approach.

Accuracy: 57.2%

3. Support Vector Classifier (SVC)

SVC was used to identify decision boundaries between the different wine quality categories.

Accuracy: 64.6%

---

📈 Model Comparison

Model| Accuracy
Random Forest| 67.2%
SVC| 64.6%
SGD Classifier| 57.2%

🏆 Best Model

Random Forest achieved the highest accuracy at 67.2%, making it the best-performing model among the three tested approaches.

---

📊 Model Evaluation

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion matrices

These metrics provide a more detailed understanding of how well each model classified the different wine quality categories.

---

💡 Key Insights

- Wine quality can be approached as a classification problem by grouping quality scores into meaningful categories.
- The chemical properties of wine provide useful information for predicting quality.
- Random Forest achieved the highest accuracy among the tested models.
- Model performance varied depending on the algorithm used.
- Classification performance can be affected by the distribution of observations across the quality categories.

---

📁 Project Files

DataAnalytics-L2-WineQualityPrediction/
│
├── README.md
├── Wine_Quality_Prediction.ipynb
├── winequality.csv
└── screenshots/

---

🎯 Conclusion

This project demonstrates the application of machine learning classification techniques to wine quality prediction.

After transforming wine quality scores into Low, Medium, and High categories, three classification algorithms were tested.

Among the models evaluated, Random Forest performed best with an accuracy of 67.2%.

The project provided practical experience in data preprocessing, exploratory analysis, classification modelling, model evaluation, and comparing machine learning algorithms.
