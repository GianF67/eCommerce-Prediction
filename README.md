# eCommerce Review Popularity Prediction 
This repository contains the Machine Learning project aimed at predicting the popularity of product reviews for a leader eCommerce. The prediction is based on the number of likes a review is expected to receive, utilizing various textual features of the reviews such as the subject, sentiment, and word counts. The task is formulated as a regression problem, where the goal is to predict the integer value of likes for each review.

## Dataset
The project involves two datasets:
- model.csv: Contains 28,000 reviews with textual features and the target variable likes.
- predictions.csv: Comprises 10,000 reviews without the target variable, intended for generating predictions.

## Features
The model considers several features extracted from the reviews, including:
- Number of words in title and content
- Rate of unique and non-stop words
- Subjectivity and sentiment polarity of the content
- Number and type of multimedia elements such as images and links

## Repository Contents
- EDA
- Model Development: Scripts for training the regression models.
- Predictions: Script for generating predictions on the predictions.csv dataset.
- Visualization: Notebooks that include data visualizations to support business strategy proposals.
