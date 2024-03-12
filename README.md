# Project1

The project uses Python libraries and APIs to analyze Reddit data, predict user input, and suggest new titles based on cosine similarity. It retrieves new posts from a subreddit, checks for duplicates, and adds unique posts. The script then predicts scores, comments, and awards using a Naive Bayes classifier, and outputs the best suggestion with its combined score.

## Table of Contents

- [About](#about)
- [Features](#features)
- [Imports](#Imports)
- [Rating: 7/10](#Rating)

# About

The project uses Python libraries and APIs to analyze data from the Reddit platform, predict user input, and suggest new titles based on cosine similarity. The script loads an Excel file with existing data and accesses the Reddit API to retrieve new posts from a specific subreddit. It checks for duplicate titles and adds unique posts to the file. The script then predicts the score, comments, and awards using a Naive Bayes classifier trained on the existing data. The script then suggests a new title based on the combined score of each suggestion.

# Features

The project uses Python libraries and APIs to analyze Reddit data and suggest titles. It retrieves data from a specific subreddit and loads existing data from an Excel file. The script checks for duplicate titles and adds unique posts to avoid redundancy. A Naive Bayes classifier is trained on the existing data to predict attributes like score, comments, and awards for new posts. The script suggests new titles based on cosine similarity, which compares new post titles with existing ones. The suggested title is based on the combined score of each suggestion, which may include factors like upvotes, comments, and awards. This project demonstrates how Python can be used to analyze Reddit data and provide intelligent title suggestions based on existing patterns.

# Imports

openpyxl, pandas, praw, sklearn.model_selection, sklearn.feature_extraction.text, sklearn.naive_bayes, nltk, sklearn.feature_extraction.text, nltk.tokenize, nltk.corpus, sklearn.metrics.pairwise

# Rating

The project effectively uses APIs, data processing, and machine learning techniques for predictive analysis on Reddit. It gathers data, performs predictions, and suggests titles based on similarity metrics. However, improvements in code organization, documentation, and user interface are needed. Refinement of prediction models and suggestion algorithms could enhance accuracy and relevance. Overall, a solid project with potential for expansion and enhancement.
