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


The project utilizes machine learning techniques and the Reddit API to predict post title success and suggest improvements through Reddit Title Wizard and Title Genius.

## Table of Contents

- [About](#about)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## About

The project consists of two main components: Reddit Title Wizard and Title Genius, which use machine learning techniques to predict post title success and suggest improvements, integrating with the Reddit API.

## Features

- Reddit Title Wizard: A GUI-based application that allows users to input Reddit post titles, predict their potential performance, and receive suggestions for improvement.
- Title Genius: A command-line tool that collects Reddit post data, predicts the success of titles, and suggests improved titles based on similarity and other factors.

Prerequisites
- Python 3.x
- Required Python libraries:
- openpyxl
- pandas
- praw
- scikit-learn
- nltk
- tkinter
- threading

## Installation

Clone the repository:
- git clone [<repository_url>](https://github.com/Statute8234/RedditSuggestor.git)

Install dependencies:
- pip install openpyxl pandas praw scikit-learn nltk tkinter

Set up NLTK:
- python -m nltk.downloader stopwords punkt

Set up Reddit API credentials:
- Create a Reddit app to get client_id, client_secret, and user_agent.
- Replace the placeholders in the code with your credentials.

## Usage

# Reddit Title Wizard
- Run the application:
  - python RedditTitleWizard.py
  - Using the application:
    - Enter a post title in the "Enter post title" field.
    - Click the "Submit" button to get predictions for points, comments, and awards.
    - View the suggested title in the "would you like to try:" field.
    - Optionally, upload a photo using the "Upload Photo" button.

# Title Genius
- Run the script:
  - python TitleGenius.py
  - Follow the prompts:
    - The script will prompt you to enter a title for prediction.
    - It will fetch the latest data from the specified subreddit and update the Excel file.
    - The script will then predict and display the potential success of the input title and suggest an improved title.

## Contributing

Contributions are welcome! To contribute to Monster Maze, follow these steps:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/YourFeature
   ```
3. Make your changes and commit them:
   ```bash
   git commit -m "Add new feature"
   ```
4. Push to the branch:
   ```bash
   git push origin feature/YourFeature
   ```
5. Create a new Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
