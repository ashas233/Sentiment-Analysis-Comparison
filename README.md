# Sentiment-Analysis-Comparison
Overview

Comparison of three sentiment analysis methods: Logistic Regression (TF-IDF), TextBlob, and VADER, plus an n-gram text generator.

Features

Logistic Regression (TF-IDF): Trainable, accurate for custom datasets

TextBlob & VADER: Rule/lexicon-based, fast but less nuanced

N-gram Model: Generates synthetic text

Metrics: Accuracy, precision, recall, speed

Installation

pip install textblob vaderSentiment scikit-learn pandas nltk

Usage

Run sentiment_analysis.ipynb to:

Train & test Logistic Regression

Compare TextBlob & VADER

Generate text with n-grams

Results

Logistic Regression: Best accuracy

TextBlob/VADER: Faster, less nuanced

Speed: LR & TextBlob > VADER (small data)

Dataset

Includes labeled text samples (positive, negative, neutral).
