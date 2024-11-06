# Sentiment Analysis on Amazon Reviews using LSTM
This project demonstrates how to perform **Sentiment Analysis** on Amazon product reviews using **LSTM (Long Short-Term Memory)** networks, achieving **a 95% accuracy**. The goal is to predict the sentiment of reviews, classifying them as positive or negative, using deep learning techniques.

## Steps Overview

### 1.	Load the dataset
  Load the Amazon reviews dataset for sentiment classification.
### 2.	Data Exploration
  Explore the dataset to understand its structure, distribution, and key features.
### 3.	Text Cleaning
  Clean the text data by removing unnecessary characters.
### 4.	Shuffling, Batching, and Splitting
  Perform shuffling to randomize the dataset for better training, split the data into training, validation, and test sets and organize it into batches for efficient training.
### 5.	Configure the datasets for performance
  Optimize the data pipeline for better training speed and performance.
### 6.	Prepare the dataset for training
  Tokenize and pad the text data, converting it into a suitable format for training the LSTM model.
### 7.	Model Building and Training
-	Sentiment Classifier without RNN Architecture: Build a simple neural network model for sentiment classification.
-	Bidirectional LSTM Sentiment Classifier: Build and train a Bidirectional LSTM model to capture sequential dependencies in the reviews.
### 8.	Model Evaluation
  Evaluate the model on the validation and test datasets to assess performance using accuracy.
### 9.	Results Analysis
  Analyze the results, compare the performance of the models, and suggest potential improvements.

### Installation

**Prerequisites**

To run this project, you’ll need Python 3.x and the following libraries:
  -	TensorFlow.
  -	Numpy.
  -	re.
  -	Matplotlib.
