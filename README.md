# Credit Card Fraud Detection

**Credit Card Fraud Detection** is a project aimed at detecting fraudulent credit card transactions. Using machine learning techniques, especially the Logistic Regression classifier, this work analyzes transaction data to detect fraudulent activity. The model is trained on transaction data, distinguishing between legitimate and fraudulent transactions based on various features.
Additionally, a **Streamlit** web application is built to provide an interactive platform where users can input transaction details and receive immediate classification results. 

## Features:
**Machine Learning Model:** Uses a Logistic Regression classifier trained on historical transaction data to classify transactions as legitimate or fraudulent.
**Streamlit Web Application:** A simple, user-friendly interface where users can input transaction features and receive predictions in real-time.
**Dataset:** The dataset is preprocessed by undersampling legitimate transactions to balance the classes, ensuring that the model is effectively trained to detect fraud. Dataset used `creditcard.csv`.
**Predictive Analysis:** The model evaluates transaction data, returning a classification of either legitimate (Class = 0) or fraudulent (Class = 1).

## Prerequisites
Before running the app, you need to install the required dependencies. You can install them using `pip`:
Python 3.x
Streamlit
Scikit-learn



