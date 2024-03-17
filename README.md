# RedditSuggestor

The project uses Python libraries and APIs to analyze Reddit data, predict user input, and suggest new titles based on cosine similarity. It retrieves new posts from a subreddit, checks for duplicates, and adds unique posts. The script then predicts scores, comments, and awards using a Naive Bayes classifier, and outputs the best suggestion with its combined score.

## Table of Contents

- [About](#about)
- [Features](#features)
- [Imports](#Imports)
- [Rating: 6/10](#Rating)

# About

The project uses Python libraries and APIs to analyze data from the Reddit platform, predict user input, and suggest new titles based on cosine similarity. The script loads an Excel file with existing data and accesses the Reddit API to retrieve new posts from a specific subreddit. It checks for duplicate titles and adds unique posts to the file. The script then predicts the score, comments, and awards using a Naive Bayes classifier trained on the existing data. The script then suggests a new title based on the combined score of each suggestion.

# Features

The project uses Python libraries and APIs to analyze Reddit data and suggest titles. It retrieves data from a specific subreddit and loads existing data from an Excel file. The script checks for duplicate titles and adds unique posts to avoid redundancy. A Naive Bayes classifier is trained on the existing data to predict attributes like score, comments, and awards for new posts. The script suggests new titles based on cosine similarity, which compares new post titles with existing ones. The suggested title is based on the combined score of each suggestion, which may include factors like upvotes, comments, and awards. This project demonstrates how Python can be used to analyze Reddit data and provide intelligent title suggestions based on existing patterns.

# Imports

openpyxl, pandas, praw, sklearn.model_selection, sklearn.feature_extraction.text, sklearn.naive_bayes, nltk, sklearn.feature_extraction.text, nltk.tokenize, nltk.corpus, sklearn.metrics.pairwise

# Rating

The code is functional and incorporates features such as fetching data from Reddit, performing predictions, and suggesting titles. It has a 6/10 overall rating. The code achieves its intended purpose of fetching data, performing predictions, and suggesting titles. The tkinter interface provides a user-friendly way to interact with the program. The code effectively uses threading to prevent the GUI from freezing during long-running tasks. The code handles exceptions gracefully.
However, there are some cons, such as code duplication, complexity, variable naming, GUI layout, magic numbers, and hardcoded values. To reduce these issues, the code could be refactored into a single function, simplified title suggestion logic, improved variable naming, and improved GUI layout. Additionally, the code should use named constants instead of magic numbers to improve code readability and maintainability.
To improve the code, the code should be externalized configurations, store paths, API credentials, and other configurations outside the code, and add more comments explaining the purpose and logic of complex operations. This will make it easier for others to understand the code and improve its overall functionality.
