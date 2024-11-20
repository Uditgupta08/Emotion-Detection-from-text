# Emotion Detection Model

This project demonstrates the process of building, training, and evaluating an emotion detection model using machine learning techniques. It uses text data to classify emotions into six categories: sadness, joy, love, anger, fear, and surprise. The model is built using Scikit-Learn and is evaluated on training, validation, and test datasets.


## Features

- Trains six different machine learning models: Logistic Regression, Random Forest, SVM, Naive Bayes, XGBoost, Decision Tree.
- Preprocessing of text data with tokenization and Lemmatizer using NLTK.
- Evaluation of models on validation and test datasets.
- Visualization of prediction probabilities for a given sentence.
- Interactive user input to predict the emotion of custom text.

## Model Performance

- Logistic Regression Validation Accuracy: 76.45%
- Random Forest Validation Accuracy: 87.6%
- SVM Validation Accuracy: 88.55%
- Naive Bayes Validation Accuracy: 75.2%
- XGBoost Validation Accuracy: 87.95%
- Decision Tree Validation Accuracy: 83.8%
- Combination of SVM and XGBoost model Validation Accuracy: 89.2%
- Test Accuracy of the best model (Combination of SVM and XGBoost): 89.2%

## Setup

1. Clone this repository:
   ```bash
   git clone https://github.com/Uditgupta08/Emotion-Detection-from-text.git
   cd Emotion-Detection-from-text
   
