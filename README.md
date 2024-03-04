# Spam-Mail-Prediction Using Logistic Regression
This repository demonstrates how to build and evaluate a spam mail prediction model using logistic regression in Python. Below is a detailed summary of the project including data preprocessing, model training, and evaluation metrics.

## Project Overview
The goal of this project is to classify emails as spam or ham (non-spam) using the logistic regression algorithm.

## Dataset
1. The dataset consists of 5572 email messages, each labeled as either 'spam' or 'ham'.
2. It contains two columns: Category and Message.
3. The dataset does not contain any missing values.
## Data Preprocessing
1. Label Encoding: Emails labeled as 'spam' are encoded as 0, and those labeled as 'ham' are encoded as 1.
2. Separating Data: The dataset is divided into two parts: the message content (x) and the labels (y).
3. Train-Test Split: The dataset is split into training and testing sets with an 80-20 ratio, using a random state of 2 for reproducibility.
4. Feature Extraction: Text data is transformed into feature vectors using TfidfVectorizer with English stop words removed. This process converts the text into a format that can be used as input for the logistic regression model.
## Model Training
1. The model is trained using LogisticRegression from the sklearn library.
2. The training process involves fitting the model on the feature vectors of the training data and their corresponding labels.
## Model Evaluation
1. The model's performance is evaluated on both the training and testing datasets using accuracy as the metric.
2. Training Data Accuracy: 96.84%
3. Testing Data Accuracy: 95.25%
## Predictive System
1. The model is capable of predicting whether a new email is spam or ham. An example input email is classified correctly by the model.
2. The feature extraction process used during training is applied to the new email before making a prediction.
## Contributions
Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please feel free to open an issue or create a pull request.
