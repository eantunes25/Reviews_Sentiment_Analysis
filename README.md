# Reviews_Sentiment_Analysis

Sentiment Analysis of Amazon Fine Food Reviews

# Overview
This project analyzes customer sentiments in Amazon Fine Food product reviews using:

VADER (rule-based sentiment analysis from NLTK)

RoBERTa (deep learning transformer via Hugging Face)

# Files
Sentiment_Analysis.ipynb: Core notebook for EDA and sentiment analysis

reviews_dataset.csv: (linked externally due to size)

# Methods Used
Data Preprocessing: Cleaning, tokenization, lemmatization

VADER: Adds a compound score and sentiment label

RoBERTa: Uses cardiffnlp/twitter-roberta-base-sentiment for contextual sentiment labeling

Visualization: Word clouds and sentiment distribution plots

# Libraries
pandas, matplotlib, seaborn

nltk

transformers (Hugging Face)

wordcloud



# Dataset Access

The original dataset is too large for direct upload to GitHub. You can download it from the following link:

➡️ [Download reviews_dataset.csv ](https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews).

Once downloaded, place it in the root folder of the project to run the notebook as intended.
