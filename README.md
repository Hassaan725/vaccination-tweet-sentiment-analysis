## COVID-19 Vaccination Tweet Sentiment Analysis

This project analyzes public sentiment on COVID-19 vaccination by processing real-world tweets using Natural Language Processing (NLP) techniques. It uses Python-based tools for data cleaning, sentiment scoring, visualization, and classification using machine learning (Logistic Regression).

## Project Objectives

- Preprocess tweets using NLP techniques (tokenization, stopword removal, etc.)
- Calculate sentiment polarity using TextBlob
- Visualize tweet sentiment distributions and frequent words
- Build and evaluate a Logistic Regression model to classify sentiment

## Dataset

Name: COVID-19 Vaccination Tweets  
Source: https://www.kaggle.com/datasets/gpreda/covid19-tweets  
Format: CSV file inside a ZIP archive

Note: The full dataset is not included in this repository due to size. You can download it from the link above and upload it to Google Colab or your local environment.

## Technologies and Libraries Used

- Python 3.x
- Pandas, NumPy, re
- NLTK, TextBlob
- Matplotlib, Seaborn, WordCloud
- Scikit-learn (Logistic Regression, CountVectorizer)

## Workflow Overview

1. Data Loading  
   Load and inspect tweet data

2. Text Preprocessing  
   Lowercasing, removing URLs, mentions, hashtags, punctuation  
   Tokenization and stopword removal

3. Sentiment Analysis  
   Calculate polarity using TextBlob  
   Label tweets as Positive, Neutral, or Negative

4. Visualization  
   Count plot of sentiment distribution  
   WordCloud of frequent terms

5. Model Building  
   Convert text to numeric vectors using CountVectorizer  
   Train Logistic Regression model  
   Evaluate performance using classification metrics

## Sample Output

Tweet: "I’m so happy to get vaccinated today!"  
Polarity Score: 0.8 → Sentiment: Positive

## How to Run the Project

Option 1: Google Colab  
- Open the notebook in Google Colab  
- Upload the dataset  
- Run all cells

Option 2: Local Machine  
1. Clone the repository  
2. Install the required packages:
