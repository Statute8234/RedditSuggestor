# RedditSuggestor

[![Static Badge](https://img.shields.io/badge/tkinter-purple)](https://pypi.org/project/tkinter/)
[![Static Badge](https://img.shields.io/badge/threading-gray)](https://pypi.org/project/threading/)
[![Static Badge](https://img.shields.io/badge/pandas-blue)](https://pypi.org/project/pandas/)
[![Static Badge](https://img.shields.io/badge/random-pink)](https://pypi.org/project/random/)
[![Static Badge](https://img.shields.io/badge/difflib-purple)](https://pypi.org/project/difflib/)
[![Static Badge](https://img.shields.io/badge/praw-black)](https://pypi.org/project/praw/)
[![Static Badge](https://img.shields.io/badge/openpyxl-pink)](https://pypi.org/project/openpyxl/)
[![Static Badge](https://img.shields.io/badge/sklearn-yellow)](https://pypi.org/project/sklearn/)
[![Static Badge](https://img.shields.io/badge/openpyxl-yellow)](https://pypi.org/project/openpyxl/)
[![Static Badge](https://img.shields.io/badge/pandas-pink)](https://pypi.org/project/pandas/)
[![Static Badge](https://img.shields.io/badge/praw-purple)](https://pypi.org/project/praw/)
[![Static Badge](https://img.shields.io/badge/nltk-blue)](https://pypi.org/project/nltk/)



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
