# Book Popularity Prediction

This project builds a machine learning model to predict whether a book will be popular in an online bookstore.

## Problem

Popular books generate higher revenue and play an important role in stock management.  
The goal is to predict book popularity using product metadata and customer review information.

## Dataset

The dataset contains the following attributes:

price  
review/summary  
review/text  
review/helpfulness  
authors  
categories  
popularity (target variable)

dataset link : https://drive.google.com/drive/folders/1tbC4tP8zRj-ThG83sJ4MZOoCK_qk3RzK?usp=sharing

## Method

Feature engineering is applied using:

Text features
- review summaries
- review text

Numerical features
- price
- review helpfulness

Text data is converted into numerical vectors using TF-IDF.

A Logistic Regression classifier is trained to predict whether a book will be popular or not.

## Workflow

1 Load dataset  
2 Filter rare categories  
3 Apply TF-IDF to review text  
4 Combine text and numerical features  
5 Train classification model  
6 Evaluate model accuracy


## Libraries

pandas  
scikit-learn  
seaborn  
matplotlib
