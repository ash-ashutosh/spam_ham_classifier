# Spam ham  Classifier
# Overview
This project aims to build an Email Spam Classifier using Natural Language Processing (NLP) techniques. The classifier distinguishes between spam and non-spam (ham) emails, assisting users in managing their email inboxes effectively.

# Features
- Cleans the dataset by removing duplicates and handling missing values.
- Utilizes Exploratory Data Analysis (EDA) to understand data distribution and patterns.
- Preprocesses text data through tokenization, stopword removal, and normalization.
- Implements various machine learning models for classification, including SVM, Naive Bayes, Decision Tree, Random Forest, etc.
- Improves model performance through hyperparameter tuning and ensemble learning techniques.
- Deploys the model as a web application using Flask, allowing users to input email content and receive real-time predictions on spam likelihood.

# Repository Structure
- README: Overview of the project.
- app.py: Flask application for deploying the model.
- model.pkl: Pickle file containing the trained model.
- templates/: HTML templates for the web interface.
- sms-spam-detection.ipynb: Jupyter file showing the various features such as data cleaning, EDA, Model building has been performed
- vectorizer.pkl: Pickle file where raw text data transformed into numerical representations (vectors) that can be processed by machine learning models

# Credits
- Dataset: SMS Spam Collection Dataset from Kaggle.
- Libraries: Utilizes various Python libraries including Numpy, Pandas, Seaborn, Flask, scikit-learn, etc.
