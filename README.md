# Sentiment Analysis on Financial Tweets

## Project Overview

This project performs **Sentiment Analysis** on financial tweets using Natural Language Processing (NLP) and Machine Learning techniques.
The goal is to classify tweets into **Positive, Negative, or Neutral** sentiments.

---

## Objective

* Analyze financial tweet data
* Convert text into numerical features
* Train a machine learning model
* Evaluate model performance

---

## Tools & Technologies Used

* Python
* Pandas
* Scikit-learn
* Matplotlib
* Seaborn

---

## Dataset

* Dataset: Financial Tweets Sentiment Dataset
* File: `tweet_sentiment.csv`
* Columns:

  * `cleaned_tweets` → tweet text
  * `sentiment` → sentiment label (-1, 0, 1)

---

## ⚙️ Methodology

### 1. Data Loading

* Loaded dataset using Pandas

### 2. Preprocessing

* Converted text to lowercase
* Removed unwanted characters
* Handled missing values

### 3. Label Conversion

* Converted numerical labels:

  * -1 → Negative
  * 0 → Neutral
  * 1 → Positive

### 4. Feature Extraction

* Used **TF-IDF Vectorization** to convert text into numerical features

### 5. Model Training

* Used **Logistic Regression** algorithm
* Split data into training and testing sets

### 6. Evaluation

* Accuracy Score
* Classification Report (Precision, Recall, F1-score)
* Confusion Matrix

---

## Results

* The model successfully classified tweet sentiments
* Achieved good accuracy on test data
* Confusion matrix shows performance across all classes

---

## Conclusion

This project demonstrates how machine learning can be used to analyze public sentiment in financial markets.
It provides insights into how users react to market trends through tweets.

---
