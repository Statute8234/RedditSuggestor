# RedditSuggestor

[![Static Badge](https://img.shields.io/badge/tkinter-brightgreen)](https://docs.python.org/3/library/tkinter.html)
[![Static Badge](https://img.shields.io/badge/filedialog-yellow)](https://docs.python.org/3/library/tkinter.filedialog.html)
[![Static Badge](https://img.shields.io/badge/ttk-blue)](https://docs.python.org/3/library/tkinter.ttk.html)
[![Static Badge](https://img.shields.io/badge/threading-orange)](https://docs.python.org/3/library/threading.html)
[![Static Badge](https://img.shields.io/badge/pandas-red)](https://pandas.pydata.org/pandas-docs/stable/)
[![Static Badge](https://img.shields.io/badge/random-purple)](https://docs.python.org/3/library/random.html)
[![Static Badge](https://img.shields.io/badge/difflib-pink)](https://docs.python.org/3/library/difflib.html)
[![Static Badge](https://img.shields.io/badge/praw-teal)](https://praw.readthedocs.io/en/stable/)
[![Static Badge](https://img.shields.io/badge/openpyxl-ivory)](https://openpyxl.readthedocs.io/en/stable/)
[![Static Badge](https://img.shields.io/badge/scikit--learn-9cf)](https://scikit-learn.org/stable/)
[![Static Badge](https://img.shields.io/badge/CountVectorizer-magenta)](https://scikit-learn.org/stable/modules/generated/sklearn.feature_extraction.text.CountVectorizer.html)
[![Static Badge](https://img.shields.io/badge/MultinomialNB-lightgrey)](https://scikit-learn.org/stable/modules/generated/sklearn.naive_bayes.MultinomialNB.html)


The project uses Python libraries and APIs to analyze Reddit data, predict user input, and suggest new titles based on cosine similarity. It retrieves new posts from a subreddit, checks for duplicates, and adds unique posts. The script then predicts scores, comments, and awards using a Naive Bayes classifier, and outputs the best suggestion with its combined score.

## Table of Contents

- [About](#about)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Rating: 7/10](#Rating)

# About

The project uses Python libraries and APIs to analyze data from the Reddit platform, predict user input, and suggest new titles based on cosine similarity. The script loads an Excel file with existing data and accesses the Reddit API to retrieve new posts from a specific subreddit. It checks for duplicate titles and adds unique posts to the file. The script then predicts the score, comments, and awards using a Naive Bayes classifier trained on the existing data. The script then suggests a new title based on the combined score of each suggestion.

# Features

The project uses Python libraries and APIs to analyze Reddit data and suggest titles. It retrieves data from a specific subreddit and loads existing data from an Excel file. The script checks for duplicate titles and adds unique posts to avoid redundancy. A Naive Bayes classifier is trained on the existing data to predict attributes like score, comments, and awards for new posts. The script suggests new titles based on cosine similarity, which compares new post titles with existing ones. The suggested title is based on the combined score of each suggestion, which may include factors like upvotes, comments, and awards. This project demonstrates how Python can be used to analyze Reddit data and provide intelligent title suggestions based on existing patterns.

# Installation

1) HTTPS - https://github.com/[User]/RedditSuggestor.git
2) CLONE - git@github.com:{User]/RedditSuggestor.git

# Usage

This script is suitable for various GitHub scenarios, particularly for data collection, machine learning, and user interaction projects. It automates the process of collecting and updating data from Reddit, stores and manages data in an Excel file, and demonstrates the use of Naive Bayes classification for predicting outcomes based on textual data. It also provides an example of creating a GUI with Tkinter for interacting with a machine learning model and demonstrates how to integrate various functionalities into a single user interface.

The Reddit Post Predictor project collects data from Reddit, trains a machine learning model to predict post performance, and provides a GUI for user interaction. It features a user-friendly GUI for input and prediction. To install, clone the repository, install the required dependencies, update the PATH variable in main.py to point to your Excel file, add your Reddit API credentials in main.py, and run the application.

This project is licensed under the MIT License, providing a clear structure and usage guide for users who want to clone, modify, and use the project for their purposes.

# Rating

The code is functional and incorporates features such as fetching data from Reddit, performing predictions, and suggesting titles. The code achieves its intended purpose of fetching data, performing predictions, and suggesting titles. The tkinter interface provides a user-friendly way to interact with the program. The code effectively uses threading to prevent the GUI from freezing during long-running tasks. The code handles exceptions gracefully.
However, there are some cons, such as code duplication, complexity, variable naming, GUI layout, magic numbers, and hardcoded values. To reduce these issues, the code could be refactored into a single function, simplified title suggestion logic, improved variable naming, and improved GUI layout. Additionally, the code should use named constants instead of magic numbers to improve code readability and maintainability.
To improve the code, the code should be externalized configurations, store paths, API credentials, and other configurations outside the code, and add more comments explaining the purpose and logic of complex operations. This will make it easier for others to understand the code and improve its overall functionality.
