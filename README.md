# Twitter Sentiment Analysis

## Project Overview
This project performs sentiment analysis on Twitter data using various machine learning algorithms. The goal is to classify tweets as **positive (1)** or **negative (0)** based on the sentiment expressed in the text.

The project applies Natural Language Processing (NLP) techniques for text preprocessing and feature extraction, followed by training multiple machine learning models to achieve accurate sentiment classification.

## Features
- Text preprocessing using NLP techniques
- Stopword removal and tokenization
- Feature extraction using text vectorization
- Training multiple machine learning models
- Model evaluation and performance comparison
- Visualization of text data using WordCloud

## Dataset
The dataset contains labeled tweets used for training and testing the models.

Files used:
- `train_tweet.csv` – Training dataset
- `test_tweets.csv` – Testing dataset

Each tweet is labeled as:
- **1 → Positive Sentiment**
- **0 → Negative Sentiment**

## Technologies Used

Python Libraries:

- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn
- nltk
- gensim
- wordcloud
- xgboost
- tqdm

## Machine Learning Models Used

The following classification algorithms were implemented and evaluated:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Support Vector Classifier (SVC)
- XGBoost Classifier

## Project Structure

Twitter-Sentiment-Analysis
│
├── twitter_sentiment.py → Main Python code
├── train_tweet.csv → Training dataset
├── test_tweets.csv → Testing dataset
└── README.md → Project documentation


## Workflow

1. Data Collection
2. Data Preprocessing
3. Feature Extraction
4. Model Training
5. Model Evaluation
6. Sentiment Prediction

## Output

The trained model predicts whether a tweet expresses **positive or negative sentiment**.
