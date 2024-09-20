# Twitter Sentiment Analysis

This project is focused on performing sentiment analysis on Twitter data related to various entities. The goal is to classify tweets into four sentiment categories: **Positive**, **Negative**, **Neutral**, and **Irrelevant**. 

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Installation](#installation)

## Project Overview
This project uses machine learning techniques to analyze the sentiment of tweets towards specific entities like companies, products, and more. Various models are implemented including Naive Bayes, Logistic Regression, Random Forest, Decision Tree, and Artificial Neural Networks. The project also involves clustering using K-Means++ for exploratory data insights.

## Dataset
The dataset consists of two CSV files:
1. `twitter_training.csv`: Used for training the models.
2. `twitter_validation.csv`: Used for validation purposes.

Each dataset contains the following columns:
- `ID`: Tweet identifier
- `Entity`: The entity being mentioned in the tweet
- `Sentiment`: Sentiment label (Positive, Negative, Neutral, Irrelevant)
- `Message`: The tweet content

## Installation
To run this project locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/twitter-sentiment-analysis.git
    ```
   
2. Navigate into the project directory:
    ```bash
    cd twitter-sentiment-analysis
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
