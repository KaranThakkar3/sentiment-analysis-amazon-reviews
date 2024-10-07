# Amazon Reviews Sentiment Analysis

## Overview
This project focuses on sentiment analysis of Amazon customer reviews using deep learning techniques. The goal is to classify reviews as positive or negative based on their text content. The project employs text preprocessing, tokenization, and Convolutional Neural Networks (CNNs) for sentiment classification.

## Features
- **Text Preprocessing**: Cleans and normalizes review texts by removing non-alphanumeric characters and converting to lowercase.
- **Tokenization and Padding**: Converts texts into sequences of integers and pads them to ensure uniform input length.
- **Model Building**: Implements a CNN model using Keras for sentiment classification.
- **Performance Evaluation**: Evaluates model performance using metrics such as Accuracy, F1-Score, and ROC AUC.

## Dataset
The dataset consists of Amazon customer reviews in text format. Each review is labeled as positive or negative based on customer ratings.

- **Training Data**: `train.ft.txt`
- **Test Data**: `test.ft.txt`

You can download the dataset from https://www.kaggle.com/datasets/bittlingmayer/amazonreviews
