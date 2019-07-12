# API Scraping and NLP Processing
Project 3: Web APIs &amp; Classification
For project 3, our goal is two-fold:

Using Reddit's API, you'll collect posts from two subreddits of your choosing.
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

> - Is text data successfully converted to a matrix representation?
> - Are methods such as stop words, stemming, and lemmatization explored?
> - Does the student properly split and/or sample the data for validation/training purposes?
> - Does the student test and evaluate a variety of models to identify a production algorithm (AT MINIMUM: Bayes and one other > - model)?
> - Does the student defend their choice of production model relevant to the data at hand and the problem?
> - Does the student explain how the model works and evaluate its performance successes/downfalls?

### Evaluation and Conceptual Understanding

> - Does the student accurately identify and explain the baseline score?
> - Does the student select and use metrics relevant to the problem objective?
> - Does the student interpret the results of their model for purposes of inference?
> - Is domain knowledge demonstrated when interpreting results?
> - Does the student provide appropriate interpretation with regards to descriptive and inferential statistics?

### Conclusion and Recommendations

> - Does the student provide appropriate context to connect individual steps back to the overall project?
> - Is it clear how the final recommendations were reached?
> - Are the conclusions/recommendations clearly stated?
> - Does the conclusion answer the original problem statement?
> - Does the student address how findings of this research can be applied for the benefit of stakeholders?
> - Are future steps to move the project forward identified?
> - Organization and Professionalism

### Project Organization

> - Are modules imported correctly (using appropriate aliases)?
> - Are data imported/saved using relative paths?
> - Does the README provide a good executive summary of the project?
> - Is markdown formatting used appropriately to structure notebooks?
> - Are there an appropriate amount of comments to support the code?
> - Are files & directories organized correctly?
> - Are there unnecessary files included?
> - Do files and directories have well-structured, appropriate, consistent names?

### Visualizations

> - Are sufficient visualizations provided?
> - Do plots accurately demonstrate valid relationships?
> - Are plots labeled properly?
> - Are plots interpreted appropriately?
> - Are plots formatted and scaled appropriately for inclusion in a notebook-based technical report?

### Python Syntax and Control Flow

> - Is care taken to write human readable code?
> - Is the code syntactically correct (no runtime errors)?
> - Does the code generate desired results (logically correct)?
> - Does the code follows general best practices and style guidelines?
> - Are Pandas functions used appropriately?
> - Are sklearn and NLTK methods used appropriately?

### Presentation

> - Is the problem statement clearly presented?
> - Does a strong narrative run through the presentation building toward a final conclusion?
> - Are the conclusions/recommendations clearly stated?
> - Is the level of technicality appropriate for the intended audience?
> - Is the student substantially over or under time?
> - Does the student appropriately pace their presentation?
> - Does the student deliver their message with clarity and volume?
> - Are appropriate visualizations generated for the intended audience?
> - Are visualizations necessary and useful for supporting conclusions/explaining findings?
