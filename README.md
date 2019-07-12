# API Scraping and NLP Processing
Project 3: Web APIs &amp; Classification
For project 3, our goal is two-fold:

Using Reddit's API, we'll collect posts from two subreddits of your choosing.
You'll then use NLP to train a classifier on which subreddit a given post came from. This is a binary classification problem.

## The Data Science Process

### Problem Statement

> - Are we able to create a classifier which can correctly predicxt which subreddit a given post came from

### Data Collection

> - https://www.reddit.com/r/crossfit.json

> - https://www.reddit.com/r/running/.json

### Data Cleaning and EDA

> - Located the text from each post

> - Created a data frame with all posts

> - Created a new column to identify each post as NOT a CrossFit post

> - Cleaned up each post by removing line breaks and extra spaces

> - Removed any post that was “ ‘   ’  “

### Preprocessing and Modeling

> - Remove HTML

> - Remove Non-Letters

> - Convert to lower case, split into individual words

> - Convert the stop words to a set

> - Remove stop words

> - Join the words back into one string separated by space

> - Instantiate a CountVectorizer

> - Instantiate a Pipeline

> - Instantiate a GridSearch

> - Run data through the model

### Evaluation and Conceptual Understanding

> - Train Accuracy Score: 99.83

> - Test Accuracy Score: 95.26

> - Best Max Features: 10,000

> - Best Model – Logistic Regression

### Conclusion and Recommendations

> - It seemed to work!
