# SpamOrNot | Email Spam Classifier
A machine learning model that classifies emails/SMS messages as Spam or Ham (not spam) using TF-IDF vectorization and a trained classification model (scikit-learn).

## Overview
This project builds an end-to-end text classification pipeline:
Loads and explores a labeled email/SMS dataset (email.csv)
Preprocesses and vectorizes text using TfidfVectorizer
Trains and evaluates a classification model
Saves the trained model and vectorizer for reuse (SpamOrNot.pkl, TfidfVectorizer.pkl)
Runs predictions on new, unseen messages.

## Project Structure
```text
SpamOrNot/
├── SpamOrNot.ipynb# Main notebook   # EDA, preprocessing, training, evaluation
├── email.csv     # Dataset (Category, Message)
├── SpamOrNot.pkl     # Trained model (pickled)
├── TfidfVectorizer.pkl    # Fitted TF-IDF vectorizer (pickled)
└── README.md
```
## How It Works
Data Loading & EDA - Load the dataset and explore the distribution of spam vs. ham messages.
Text Vectorization - Convert raw text into numerical features using TfidfVectorizer.
Model Training - Train a classification model on the vectorized data.
Evaluation - Assess performance using a confusion matrix and classification metrics.
Inference - Load the saved model/vectorizer and classify new messages.


## Tech Stack
• Python

• Pandas

• scikit-learn

• seaborn, matplotlib

