✍️ Autocomplete and Autocorrect Data Analytics

Oasis Infobyte Data Analytics Internship — Task 9, Level 2

---

📌 Project Overview

This project focuses on building an Autocomplete and Autocorrect system using Python and Natural Language Processing (NLP) techniques.

The project uses the text of Alice’s Adventures in Wonderland from Project Gutenberg as a language corpus. The text was processed to identify word patterns and develop systems that can suggest likely next words and correct common spelling errors.

---

🎯 Objectives

- Clean and preprocess a text corpus for NLP analysis
- Tokenize text into individual words
- Analyse word frequencies
- Generate bigrams to identify common word sequences
- Build an autocomplete system for next-word prediction
- Build an autocorrect system for spelling correction
- Evaluate the performance of the systems
- Visualize key findings

---

🗂️ Dataset

Text Corpus: Alice’s Adventures in Wonderland by Lewis Carroll

Source: Project Gutenberg

"Project Gutenberg — Alice’s Adventures in Wonderland" (https://reference-url-citation.invalid/0)

The text is used as the language corpus for training and testing the autocomplete and autocorrect approaches.

---

🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- NLTK
- PySpellChecker
- Matplotlib
- Jupyter Notebook

---

🔍 Project Workflow

1. Text Preprocessing

- Loaded the text corpus
- Cleaned unnecessary whitespace
- Converted text to lowercase
- Extracted alphabetic words

2. Word Frequency Analysis

Counted word occurrences to identify the most frequently used words in the corpus.

3. Bigram Generation

Generated pairs of consecutive words to identify common word sequences and support next-word prediction.

4. Autocomplete

Built an autocomplete system that uses previously observed word patterns to suggest likely next words.

5. Autocorrect

Implemented an autocorrect system using PySpellChecker to identify and correct misspelled words.

6. Evaluation

Tested the systems using sample inputs and measured autocorrect performance.

---

📊 Results

The autocorrect system was tested using 10 intentionally misspelled words.

Autocorrect Accuracy: 90%

The autocomplete system was also tested using sample word pairs and evaluated using Top-3 prediction accuracy, measuring whether the expected next word appeared among the three suggested words.

---

📈 Visualizations

The project includes visualizations showing:

- Top 20 most frequent words
- Common words predicted after "Alice"

These visualizations provide a better understanding of word usage and prediction patterns within the corpus.

---

💡 Key Insights

- Frequently occurring words provide useful information for language modelling.
- Bigram patterns can be used to generate simple next-word predictions.
- Edit-distance-based spelling correction can effectively correct common typing errors.
- A text corpus can be transformed into a basic predictive language system using relatively simple NLP techniques.

---

📁 Repository Structure

DataAnalytics-L2-AutocompleteAutocorrect/
│
├── README.md
├── Autocomplete_Autocorrect.ipynb
│
└── screenshots/
    ├── word_frequency.png
    └── autocomplete_prediction.png

---

👩‍💻 Author

Blessing Amula

Data Analytics Intern | Economics Graduate

Oasis Infobyte Data Analytics Internship

Level 2 — Task 5: Autocomplete and Autocorrect Data Analytics
