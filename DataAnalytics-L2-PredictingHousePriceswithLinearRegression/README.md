# 🏠 House Price Prediction with Linear Regression

### Oasis Infobyte Data Analytics Internship — Task 1, Level 2

---

## 📌 Project Overview

This project focuses on predicting house prices using **machine learning and regression analysis**.

The dataset was explored and prepared for modelling by handling missing values, selecting relevant features, encoding categorical variables, and analysing relationships between features and house prices.

**Linear Regression** was used as the primary prediction model, with **Ridge Regression** included as an additional model for comparison.

---

## 🎯 Objectives

- Explore the house price dataset
- Identify important factors affecting house prices
- Handle missing values and prepare the data
- Select relevant features for prediction
- Encode categorical variables
- Split the dataset into training and testing sets
- Build a Linear Regression model
- Evaluate model performance using RMSE and R²
- Compare Linear Regression with Ridge Regression
- Visualise actual vs predicted prices and model residuals

---

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📊 Project Workflow

### 1. Data Loading and Inspection

The dataset was loaded into Python and inspected to understand:

- Number of rows and columns
- Data types
- Missing values
- Numerical and categorical features
- Target variable

### 2. Data Cleaning

The dataset was prepared for analysis by:

- Checking for missing values
- Handling incomplete records
- Removing unnecessary features where applicable
- Preparing variables for modelling

### 3. Exploratory Data Analysis

Exploratory analysis was performed to understand relationships between house prices and other variables.

Visualisations included:

- Distribution plots
- Correlation analysis
- Correlation heatmap
- Feature relationships

### 4. Feature Engineering

Relevant features were selected for prediction.

Categorical variables were transformed using **One-Hot Encoding** so they could be used by the machine learning models.

### 5. Train-Test Split

The prepared dataset was divided into:

- Training data
- Testing data

This allowed the models to be trained on one portion of the dataset and evaluated on unseen data.

### 6. Linear Regression

A **Linear Regression** model was trained to predict house prices based on the selected features.

### 7. Model Evaluation

The model was evaluated using:

- Root Mean Squared Error (RMSE)
- R² Score

The Linear Regression model achieved:

- **R² Score:** 0.872
- **RMSE:** 31,327.8

This indicates that the model explained approximately **87.2% of the variation in house prices** in the test data.

### 8. Ridge Regression

Ridge Regression was also tested as an alternative regularised regression model.

The Ridge model achieved an **R² Score of 0.844**.

Based on the results, Linear Regression performed better on this dataset.

### 9. Visualisations

The project includes visualisations such as:

- Correlation heatmap
- Actual vs predicted house prices
- Residual analysis
- Feature/coefficient analysis

---

## 📈 Model Comparison

| Model | R² Score | RMSE |
|---|---:|---:|
| Linear Regression | **0.872** | **31,327.8** |
| Ridge Regression | 0.844 | — |

### 🏆 Best Model

**Linear Regression** achieved the best performance among the tested models based on the R² score.

---

## 💡 Key Insights

- Several property features have measurable relationships with house prices.
- Feature selection and preprocessing are important for improving prediction quality.
- Linear Regression provided strong predictive performance on the dataset.
- Ridge Regression provided a useful comparison but performed slightly lower than Linear Regression.
- Model evaluation metrics help determine how well predictions generalise to unseen data.

---

## 📁 Project Files

```text
DataAnalytics-L2-PredictingHousePriceswithLinearRegression/
│
├── README.md
├── House_Price_Prediction.ipynb
├── house_prices.csv
└── screenshots/
```

---

## 🎯 Conclusion

This project demonstrates how **exploratory data analysis, data preprocessing, feature engineering, and regression modelling** can be combined to predict house prices.

The Linear Regression model achieved an **R² score of 0.872**, showing strong predictive performance on the test dataset.

The project provided practical experience in preparing real-world data and applying machine learning techniques to a regression problem.
