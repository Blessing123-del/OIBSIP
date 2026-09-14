🧹 Data Cleaning and Preprocessing

Oasis Infobyte Data Analytics Internship — Task 3, Level 1

---

📌 Project Overview

This project demonstrates the process of transforming a messy dataset into a clean, consistent, and analysis-ready dataset.

The analysis focuses on identifying and resolving common data quality issues such as missing values, duplicate records, inconsistent formatting, incorrect data types, and numerical outliers.

The goal is to produce a reliable dataset that can be confidently used for further analysis and modelling.

---

🎯 Objectives

- Inspect the dataset and identify data quality issues
- Generate a data quality report
- Handle missing values using appropriate strategies
- Identify and remove duplicate records
- Standardise inconsistent values and formatting
- Detect numerical outliers using the IQR method
- Correct inappropriate data types
- Compare the dataset before and after cleaning
- Export the cleaned dataset as a new CSV file

---

🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Jupyter Notebook

---

📊 Dataset

The project uses a deliberately messy dataset to demonstrate practical data cleaning techniques.

The dataset contains common real-world data quality issues, including:

- Missing values
- Duplicate records
- Inconsistent categorical values
- Incorrect data types
- Numerical outliers
- Inconsistent formatting

---

🔍 Data Cleaning Process

1. Initial Data Inspection

The dataset was inspected to understand its structure and identify potential quality issues.

The inspection included:

- Number of rows and columns
- Column names
- Data types
- Missing values
- Duplicate records
- Unique values
- Numerical value ranges

---

2. Missing Value Treatment

Missing values were identified for each column and handled using appropriate methods based on the nature of the data.

Depending on the column, strategies included:

- Median imputation for numerical values
- Mode imputation for categorical values
- Appropriate row removal where necessary

The chosen methods were documented to ensure that the cleaning decisions were transparent and reproducible.

---

3. Duplicate Removal

Duplicate records were identified and removed to prevent repeated observations from affecting the analysis.

The number of duplicate rows identified and removed was documented during the cleaning process.

---

4. Data Standardisation

Inconsistent values and formatting were standardised to ensure consistency throughout the dataset.

Examples include:

- Standardising categorical values
- Correcting inconsistent text formatting
- Converting dates into a consistent format
- Removing unnecessary spaces and inconsistencies

---

5. Outlier Detection

The Interquartile Range (IQR) method was used to identify potential outliers in numerical columns.

Outliers were reviewed before deciding whether they should be:

- Retained
- Capped
- Removed

This approach helped ensure that legitimate observations were not unnecessarily discarded.

---

6. Data Type Correction

Incorrect data types were identified and corrected.

Examples include:

- Converting dates to datetime format
- Converting numerical values to appropriate numeric types
- Treating identification fields as strings where necessary

---

📋 Before vs. After Cleaning

A comparison was created to show the improvement in data quality after preprocessing.

The comparison includes:

- Row count
- Missing value count
- Duplicate count
- Data type accuracy

This provides a clear view of the changes made during the cleaning process.

---

📁 Output

After completing the cleaning process, the final analysis-ready dataset was exported as a new CSV file.

This ensures that the original raw dataset remains unchanged while the cleaned version can be used for future analysis.

---

💡 Key Outcomes

The data cleaning process improved the quality and consistency of the dataset by:

- Resolving missing data
- Removing duplicate records
- Standardising inconsistent values
- Correcting data types
- Identifying and handling outliers
- Producing a clean dataset ready for analysis

---

✅ Conclusion

Data cleaning is an essential stage of the data analytics process because the quality of insights depends heavily on the quality of the underlying data.

This project demonstrates a structured approach to identifying, documenting, and resolving common data quality problems using Pandas and NumPy, resulting in a cleaner and more reliable dataset for further analysis.

---

📁 Project Files

DataAnalytics-L1-CleaningData/
│
├── README.md
├── Data_Cleaning.ipynb
├── messy_dataset.csv
├── cleaned_dataset.csv
└── screenshots/

---

🔗 Technologies

Python | Pandas | NumPy | Jupyter Notebook
