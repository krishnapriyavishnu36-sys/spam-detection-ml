
# Spam Detection Using Machine Learning

## Project Overview

This project classifies text messages as spam or ham
(not spam) using supervised machine learning.

## Objectives

- Understand binary classification.
- Convert text into numerical features using TF-IDF.
- Train a Logistic Regression classifier.
- Evaluate predictions on test data.
- Predict the category of new messages.

## Technologies Used

- Python
- Pandas
- Scikit-learn
- TF-IDF Vectorization
- Logistic Regression

## Machine Learning Workflow

1. Load and inspect the dataset.
2. Separate text messages and labels.
3. Split the dataset into training and testing sets.
4. Convert messages into numerical features using TF-IDF.
5. Train the Logistic Regression model.
6. Predict labels for test messages.
7. Evaluate model performance.

## Dataset

The dataset contains text messages labeled as:
- ham: a non-spam message
- spam: an unwanted or spam message

## How to Run

1. Install Python.
2. Install the required libraries:

   pip install -r requirements.txt

3. Run the program:

   python spam_detection.py

## Results

Test accuracy: Add your measured accuracy here.

The reported accuracy applies to the test split
of this dataset and may not represent performance
on real-world messages.

## What I Learned

- Supervised machine learning
- Binary classification
- Training and testing data
- TF-IDF feature extraction
- Logistic Regression
- Model evaluation

## Future Improvements

- Test on a larger, realistic dataset.
- Compare Logistic Regression with other classifiers.
- Improve preprocessing and model evaluation.
- Build a simple web interface for predictions.
