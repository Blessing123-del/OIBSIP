💬 Sentiment Analysis

Oasis Infobyte Data Analytics Internship — Task 4, Level 1

---

📌 Project Overview

This project focuses on sentiment analysis of text data to classify user opinions into positive, negative, and neutral sentiments.

The project applies Natural Language Processing (NLP) techniques to clean and transform text data, extract meaningful features using TF-IDF, and train machine learning models to predict the sentiment of unseen text.

---

🎯 Objectives

- Inspect and analyse the sentiment distribution
- Preprocess text data using NLP techniques
- Convert text into numerical features using TF-IDF
- Split the dataset into training and testing sets
- Train and compare two classification models
- Evaluate model performance using multiple metrics
- Analyse model errors
- Identify the best-performing model
- Discuss real-world applications of sentiment analysis

---

🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- NLTK
- Matplotlib
- Seaborn
- Jupyter Notebook

---

📊 Dataset

The project uses a Twitter Sentiment dataset containing text entries labelled according to their sentiment.

The sentiment classes analysed are:

- Positive
- Negative
- Neutral

Irrelevant entries were excluded from the classification analysis.

---

🔍 Analysis Performed

1. Data Inspection

The dataset was inspected to understand its structure, class distribution, missing values, and text data.

2. Text Preprocessing

The text was prepared for machine learning through steps including:

- Lowercasing
- Punctuation removal
- Stopword removal
- Text tokenisation
- Cleaning unnecessary characters

3. TF-IDF Feature Extraction

TF-IDF (Term Frequency-Inverse Document Frequency) was used to transform text into numerical features that machine learning models can process.

4. Model Training

Two classification algorithms were trained and compared:

- Naive Bayes
- Logistic Regression

5. Model Evaluation

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion matrix

6. Error Analysis

Misclassified examples were reviewed to understand why certain texts were difficult for the models to classify correctly.

---

📈 Visualisations

The project includes:

- Sentiment distribution chart
- Confusion matrices
- Model performance comparison
- WordClouds for sentiment classes

---

💡 Key Insights

The analysis showed differences in how well the two machine learning models handled the sentiment classification task.

Model performance was compared using multiple evaluation metrics rather than relying only on accuracy.

---

🏆 Best Performing Model

Logistic Regression achieved better overall performance than Naive Bayes on the test dataset, making it the stronger model for this sentiment classification task.

---

🌍 Real-World Applications

Sentiment analysis can be used by organisations to:

- Monitor customer opinions
- Analyse product reviews
- Track public reactions
- Measure brand perception
- Identify customer satisfaction trends
- Support social media monitoring

---

✅ Conclusion

This project demonstrates how Natural Language Processing and machine learning can be combined to automatically analyse and classify text sentiment.

The project provided practical experience in text preprocessing, TF-IDF feature extraction, machine learning classification, model evaluation, visualisation, and error analysis.

---

📁 Project Files

DataAnalytics-L1-SentimentAnalysis/
│
├── README.md
├── Sentiment_Analysis.ipynb
├── Twitter_Sentiment.csv
└── screenshots/

---

🔗 Technologies

Python | Pandas | NumPy | Scikit-learn | NLTK | Matplotlib | Seaborn | Jupyter Notebook
