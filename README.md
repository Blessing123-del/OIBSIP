📊 Oasis Infobyte Data Analytics Internship

OIBSIP — Data Analytics Projects

This repository contains my completed projects from the Oasis Infobyte Data Analytics Internship (OIBSIP).

The projects cover exploratory data analysis, data cleaning, customer segmentation, sentiment analysis, regression, classification, fraud detection, Google Play Store analysis, and Natural Language Processing.

Throughout the internship, I worked with real-world datasets and applied data analytics, machine learning, and NLP techniques to transform raw data into meaningful insights and practical solutions.

---

📂 Repository Structure

OIBSIP/
│
├── DataAnalytics-L1-EDARetailSales/
├── DataAnalytics-L1-CustomerSegmentationAnalysis/
├── DataAnalytics-L1-CleaningData/
├── DataAnalytics-L1-SentimentAnalysis/
│
├── DataAnalytics-L2-PredictingHousePriceswithLinearRegression/
├── DataAnalytics-L2-WineQualityPrediction/
├── DataAnalytics-L2-FraudDetection/
├── DataAnalytics-L2-GooglePlayStoreAnalysis/
└── DataAnalytics-L2-AutocompleteAutocorrect/

Each project folder contains its own README.md, notebook/source files, and relevant project outputs.

---

🟢 Level 1 Projects

1. 🛍️ Retail Sales Exploratory Data Analysis

Project: EDA on Retail Sales Data

Performed exploratory data analysis on e-commerce retail sales data to uncover sales trends, customer behaviour, product performance, demographic patterns, and shipping insights.

Key Areas

- Data inspection and cleaning
- Statistical analysis
- Customer demographic analysis
- Product category performance
- Sales and purchasing behaviour
- Shipping status analysis
- Data visualization

Tools

Python • Pandas • NumPy • Matplotlib • Seaborn • Jupyter Notebook

---

2. 👥 Customer Segmentation Analysis

Project: Customer Segmentation using RFM and K-Means

Performed customer segmentation using Recency, Frequency, and Monetary (RFM) analysis and K-Means clustering.

The project involved preparing transaction data, calculating customer-level behavioural metrics, standardising features, determining suitable clusters, and profiling customer segments.

Key Areas

- Data cleaning and preparation
- RFM analysis
- Feature standardisation
- Elbow Method
- K-Means clustering
- Customer segment profiling
- Marketing recommendations

Tools

Python • Pandas • NumPy • Scikit-learn • Matplotlib • Seaborn • Jupyter Notebook

---

3. 🧹 Data Cleaning

Project: Data Cleaning and Preprocessing

Cleaned and transformed a raw dataset into an analysis-ready dataset.

The project focused on identifying and handling missing values, duplicate records, inconsistent entries, incorrect data types, and numerical outliers.

Key Areas

- Missing-value handling
- Duplicate detection
- Data-type correction
- Inconsistent data handling
- Outlier detection
- Before-and-after data quality comparison

Tools

Python • Pandas • NumPy • Jupyter Notebook

---

4. 💬 Sentiment Analysis

Project: Twitter Sentiment Analysis

Developed a sentiment analysis system to classify text into Positive, Negative, and Neutral categories using Natural Language Processing and machine learning techniques.

Key Areas

- Text preprocessing
- TF-IDF feature extraction
- Train-test splitting
- Naive Bayes classification
- Logistic Regression
- Confusion matrices
- Precision, Recall and F1-score
- WordCloud visualization
- Misclassified text analysis

Results

Model| Accuracy
Naive Bayes| 70.79%
Logistic Regression| 75.12%

Logistic Regression achieved the better overall accuracy.

Tools

Python • Pandas • NLTK • Scikit-learn • Matplotlib • Seaborn • Jupyter Notebook

---

🔵 Level 2 Projects

5. 🏠 Predicting House Prices with Linear Regression

Project: House Price Prediction

Built machine learning models to predict house prices using Linear Regression and Ridge Regression.

The project involved data preparation, exploratory analysis, feature selection, encoding, model training, and performance evaluation.

Results

Model| R² Score| RMSE
Linear Regression| 0.872| 31,327.8
Ridge Regression| 0.844| —

Tools

Python • Pandas • NumPy • Scikit-learn • Matplotlib • Seaborn • Jupyter Notebook

---

6. 🍷 Wine Quality Prediction

Project: Wine Quality Classification

Developed a machine learning classification system to predict wine quality categories.

Wine quality scores were grouped into Low, Medium, and High categories before training and evaluating multiple classification models.

Models & Results

Model| Accuracy
Random Forest| 67.2%
SVC| 64.6%
SGD Classifier| 57.2%

Random Forest achieved the highest accuracy among the tested models.

Tools

Python • Pandas • NumPy • Scikit-learn • Matplotlib • Seaborn • Jupyter Notebook

---

7. 💳 Fraud Detection

Project: Credit Card Fraud Detection

Built a machine learning solution for detecting potentially fraudulent credit card transactions in a highly imbalanced dataset.

The project focused on exploratory analysis, data preparation, class imbalance, model training, and evaluation using metrics appropriate for fraud detection.

Model Evaluation

The Logistic Regression model achieved:

- Precision: 0.13
- Recall: 0.90
- F1-score: 0.23
- ROC-AUC: 0.976

These metrics highlight the importance of balancing fraud detection with the number of false positive predictions.

Dataset

The dataset was obtained from Kaggle:

"Credit Card Fraud Detection Dataset — Kaggle" (https://reference-url-citation.invalid/0)

Tools

Python • Pandas • NumPy • Scikit-learn • Matplotlib • Seaborn • Jupyter Notebook

---

8. 📱 Unveiling the Android App Market

Project: Google Play Store Analysis

Analysed Google Play Store data to understand app categories, ratings, installations, pricing, and user sentiment.

The project combined exploratory data analysis with sentiment analysis of user reviews to identify patterns in the Android app market.

Key Areas

- App category analysis
- Ratings analysis
- Installation trends
- Free vs paid applications
- App size and installation analysis
- User review sentiment
- Market pattern analysis
- Data visualization

Key Findings

- FAMILY was the largest app category.
- The average app rating was approximately 4.19.
- Free applications greatly outnumbered paid applications.
- The correlation between app size and installs was approximately 0.17.
- User reviews contained more positive than negative sentiment.

Tools

Python • Pandas • NumPy • Matplotlib • Seaborn • Natural Language Processing • Jupyter Notebook

---

9. ✍️ Autocomplete and Autocorrect Data Analytics

Project: NLP-Based Autocomplete and Autocorrect System

Developed an autocomplete and autocorrect system using Natural Language Processing techniques.

The text of Alice’s Adventures in Wonderland by Lewis Carroll from Project Gutenberg was used as the language corpus.

Key Areas

- Text preprocessing
- Tokenization
- Word-frequency analysis
- Bigram generation
- Next-word prediction
- Autocomplete
- Spelling correction
- Performance evaluation
- Data visualization

Autocomplete

A bigram-based approach was used to identify common word sequences and generate likely next-word suggestions.

The autocomplete system was tested using sample word pairs and evaluated using Top-3 prediction accuracy.

Autocorrect

An autocorrect system was developed using PySpellChecker to identify and correct spelling errors.

The system achieved:

90% accuracy on the selected test examples.

Dataset

Alice’s Adventures in Wonderland — Project Gutenberg

"Project Gutenberg — Alice’s Adventures in Wonderland" (https://reference-url-citation.invalid/1)

Tools

Python • Pandas • NumPy • NLTK • PySpellChecker • Matplotlib • Jupyter Notebook

---

🛠️ Skills & Technologies

Through these projects, I gained practical experience with:

Programming & Data Analysis

- Python
- Pandas
- NumPy

Data Visualization

- Matplotlib
- Seaborn

Machine Learning

- Linear Regression
- Ridge Regression
- K-Means Clustering
- Random Forest
- Naive Bayes
- Logistic Regression
- Support Vector Classification
- SGD Classification

Natural Language Processing

- Text preprocessing
- TF-IDF
- N-grams
- Sentiment analysis
- Word-frequency analysis
- Autocomplete
- Autocorrect
- PySpellChecker

Development & Documentation

- Jupyter Notebook
- GitHub
- Data analysis documentation
- Project presentation

---

📚 Key Learning Outcomes

These projects strengthened my ability to:

- Clean and prepare real-world datasets
- Perform exploratory data analysis
- Create meaningful data visualizations
- Identify patterns and trends in data
- Segment customers based on behaviour
- Build and evaluate machine learning models
- Work with imbalanced datasets
- Apply Natural Language Processing techniques
- Compare model performance using appropriate metrics
- Communicate analytical findings clearly
- Document and present data analytics projects professionally

---

🎯 Internship Goal

The OIBSIP internship provided practical experience in applying data analytics, machine learning, and Natural Language Processing to different real-world problems.

Across these projects, I developed the ability to move from:

Raw Data → Data Cleaning → Analysis → Modelling → Evaluation → Insights

---

👩‍💻 Author

Amula Blessing Peresuwode

Data Analyst | Economics Graduate

---

📌 Internship

Oasis Infobyte Data Analytics Internship — OIBSIP

Completed Projects: 9
Level 1: 4 Tasks
Level 2: 5 Tasks
