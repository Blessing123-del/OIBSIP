📱 Google Play Store Analysis

Oasis Infobyte Data Analytics Internship — Task 4, Level 2

---

📌 Project Overview

This project analyses Google Play Store app data to uncover patterns and trends related to app categories, ratings, installs, pricing, and user reviews.

The analysis combines Google Play Store app information with user review sentiment to understand what contributes to app popularity and how users respond to different applications.

---

🎯 Objectives

- Explore the Google Play Store dataset
- Clean and prepare app data for analysis
- Analyse app categories and popularity
- Examine app ratings and reviews
- Analyse free and paid applications
- Investigate installs and app size
- Explore pricing and potential revenue patterns
- Analyse user review sentiment
- Compare sentiment across app categories
- Generate meaningful business insights

---

🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- TextBlob
- Jupyter Notebook

---

📊 Datasets

The project uses two datasets:

Google Play Store Dataset

Contains information about Android applications, including:

- App name
- Category
- Rating
- Reviews
- Size
- Installs
- Type
- Price
- Content Rating
- Genres

User Reviews Dataset

Contains user reviews and their associated sentiment information.

The sentiment categories include:

- Positive
- Negative
- Neutral

---

🧹 Data Cleaning

The datasets were inspected and prepared before analysis.

The cleaning process included:

- Checking for missing values
- Removing or handling duplicate records
- Cleaning numerical fields
- Converting install values into usable numerical values
- Cleaning price values
- Preparing rating and review data
- Preparing review text for sentiment analysis

---

🔍 Exploratory Data Analysis

The analysis examined the distribution and performance of apps across different categories.

The most represented categories included:

Category| Number of Apps
FAMILY| 1,943
GAME| 1,121
TOOLS| 843
BUSINESS| 427
MEDICAL| 408

FAMILY was the most represented category in the dataset.

---

⭐ App Ratings

The overall average app rating was approximately:

4.19

This indicates that the apps in the dataset generally received positive ratings from users.

Rating distributions were also explored to understand how app quality varies across the Play Store.

---

💰 Free vs Paid Apps

The dataset contained significantly more free applications than paid applications.

App Type| Count
Free| 9,591
Paid| 765
Other/Invalid| 1

This demonstrates the dominance of the free-app model within the dataset.

---

📥 Installs and App Size

The relationship between app size and number of installs was also investigated.

The correlation between app size and installs was approximately:

0.169

This represents a relatively weak positive relationship, suggesting that larger app size alone does not strongly determine how many installs an application receives.

---

💬 Sentiment Analysis

User reviews were analysed to understand how users feel about applications.

The sentiment distribution was:

Sentiment| Reviews
Positive| 23,998
Negative| 8,271
Neutral| 5,163

Positive reviews represented the largest sentiment group.

---

📊 Sentiment by Category

Sentiment was further analysed across app categories to identify differences in user experiences.

This helps reveal:

- Categories receiving more positive feedback
- Categories with higher negative sentiment
- Areas where users may experience problems
- Potential opportunities for app developers to improve their products

---

💡 Key Insights

- FAMILY was the most represented app category.
- GAME and TOOLS were also among the largest categories.
- The average app rating was approximately 4.19.
- Free applications significantly outnumbered paid applications.
- The relationship between app size and installs was relatively weak.
- Positive reviews were substantially more common than negative reviews.
- User sentiment can provide additional information beyond numerical ratings when evaluating app performance.

---

📈 Business Applications

The insights from this analysis can help app developers and businesses:

- Identify popular app categories
- Understand user preferences
- Improve app features based on feedback
- Monitor customer satisfaction
- Develop better pricing strategies
- Identify opportunities in competitive categories
- Use sentiment trends to guide product improvements

---

📁 Project Files

DataAnalytics-L2-GooglePlayStoreAnalysis/
│
├── README.md
├── Google_Play_Store_Analysis.ipynb
├── googleplaystore.csv
├── googleplaystore_user_reviews.csv
└── screenshots/

---

🎯 Conclusion

This project demonstrates how data analysis and sentiment analysis can be combined to understand the Android app market.

The analysis revealed important patterns in app categories, ratings, installs, pricing, and user sentiment.

By combining quantitative Play Store data with user review sentiment, the project provides a broader view of app performance and user experience.

The insights can support better decisions around app development, marketing, pricing, and customer satisfaction.
