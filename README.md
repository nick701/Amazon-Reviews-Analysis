# Amazon Review Sentiment Analysis

## Project Overview
This project involves building and fine-tuning a logistic regression model to perform sentiment analysis on Amazon app reviews from the Google Play Store. The goal is to classify reviews as positive or negative based on the text content, helping to gauge customer sentiment towards the Amazon app.

## Dataset
The dataset used for this analysis is the "Amazon Shopping Reviews (Daily Updated)" dataset available on Kaggle. It contains a large number of Amazon app reviews from the Google Play Store, including various metadata about the reviews. You can find the dataset at [Kaggle: Amazon Shopping Reviews](https://www.kaggle.com/datasets/ashishkumarak/amazon-shopping-reviews-daily-updated).

## Features
The dataset includes the following features:
- **reviewID**: Unique identifier for each review.
- **userName**: Username of the reviewer.
- **userRatings**: The rating given by the reviewer.
- **reviewText**: Text of the review.
- **thumbsUpCount**: Number of likes the review received.
- **reviewDate**: Date of the review.

## Analysis Steps
The analysis involves several key steps:
1. **Data Preprocessing**: Cleaning and preparing text data for analysis.
2. **Exploratory Data Analysis (EDA)**: Analyzing the distribution and characteristics of reviews.
3. **Feature Engineering**: Extracting meaningful features from the text data.
4. **Model Building**: Using logistic regression to classify reviews.
5. **Model Evaluation**: Assessing model performance with metrics like accuracy, precision, recall, and F1-score.

## Visualizations
- **Confusion Matrix**: Visual representation of the model's performance.
- **ROC Curve**: Demonstrating the model's ability to classify the sentiments accurately.
- **Precision-Recall Curve**: Highlighting the trade-off between precision and recall.

## Requirements
This project requires Python and the following Python libraries:
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- NLTK