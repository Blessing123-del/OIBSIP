
🏠 House Price Prediction Using Linear Regression

Oasis Infobyte Data Analytics Internship — Task 1, Level 2

«Turning housing data into meaningful predictions.»

This project focuses on predicting house prices using Linear Regression, a supervised machine learning technique. The project involved exploring the dataset, identifying important factors that influence house prices, preparing the data for modeling, training a prediction model, and evaluating its performance.

---

📌 Project Overview

The goal of this project was to build a machine learning model capable of predicting house prices based on relevant property characteristics.

The project covers the complete workflow from data exploration and preprocessing to model development, evaluation, and interpretation.

---

🎯 Objectives

- Build a machine learning model for predicting house prices.
- Identify key factors that influence property prices.
- Prepare and transform raw data for machine learning.
- Evaluate the accuracy and performance of the regression model.
- Interpret model coefficients to understand feature impact.
- Develop practical skills in applying machine learning to real-world datasets.

---

🔎 Project Workflow

1. 📂 Data Exploration

- Loaded and explored the house price dataset.
- Examined the dataset structure and key characteristics.
- Checked for missing values and potential data quality issues.

2. 🧹 Data Cleaning & Preparation

- Checked and handled missing values.
- Prepared categorical features for machine learning.
- Selected relevant features that could influence house prices.

3. 🔄 Feature Engineering

Relevant property features included factors such as:

- Area
- Location
- Number of rooms
- Property age

Categorical variables were transformed into numerical features using One-Hot Encoding.

4. 📊 Exploratory Data Analysis

- Created a correlation heatmap to identify relationships between variables.
- Examined relationships between property characteristics and house prices.

5. 🤖 Model Development

- Split the dataset into 80% training data and 20% testing data.
- Trained a Linear Regression model using Scikit-learn.

6. 📈 Model Evaluation

The model was evaluated using:

- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

7. 📉 Model Visualization

Created visualizations to assess model performance, including:

- Actual vs. Predicted Price Plot
- Residual Plot
- Correlation Heatmap

8. 💡 Model Interpretation

Analyzed model coefficients to understand the positive and negative impact of different features on house prices.

---

📊 Key Model Results

Metric| Result
R² Score| 0.872
RMSE| 31,327.80

The Linear Regression model achieved an R² score of 0.872, indicating that the model explained a substantial proportion of the variation in house prices within the dataset.

---

🛠️ Tools & Technologies

🐍 Python
🐼 Pandas
🔢 NumPy
🤖 Scikit-learn
📊 Matplotlib
📈 Seaborn
📓 Jupyter Notebook

---

📁 Repository Structure

DataAnalytics-L2-HousePricePrediction/
│
├── 📓 House Price Prediction.ipynb
├── 📄 README.md
├── 📊 Dataset
│
└── 📸 screenshots/
    ├── project screenshots 
    
---

💡 Conclusion

This project provided practical experience in applying supervised machine learning to a real-world housing dataset.

Through data cleaning, feature engineering, visualization, Linear Regression modeling, and performance evaluation, the project demonstrated how raw housing data can be transformed into meaningful predictions and insights.

It also strengthened my understanding of how data preparation, feature selection, model evaluation, and coefficient interpretation contribute to building an effective machine learning solution.

---

👩🏽‍💻 Author

Amula Blessing Peresuwode

Data Analytics Intern — Oasis Infobyte

---

🔗 Project

Explore the complete project, including the Jupyter Notebook, dataset, and visualizations, in this repository.