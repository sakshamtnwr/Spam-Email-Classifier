# Spam Email Classifier

## Introduction
This project is a machine learning-based email classifier that can detect whether an email is spam or not. It uses a labeled dataset of emails to train a model capable of making predictions on new messages.

## Overview
The classifier processes email text, converts it into numerical features, and trains a model to differentiate spam from non-spam emails. Once trained, the model can classify any new email text accurately.

## Technologies Used
- **Python** – main programming language  
- **scikit-learn** – for machine learning model training and evaluation  
- **pandas** – for data manipulation and preprocessing  
- **pickle** – for saving and loading the trained model and vectorizer  

## How It Works
1. Load the dataset (`spam.csv`) containing email texts and labels.  
2. Preprocess the text and transform it into numerical vectors using the saved vectorizer (`vectorizer.pkl`).  
3. Train a machine learning model or use the existing trained model (`model.pkl`) to predict whether an email is spam or not.  
4. Use the model to classify new emails in Python by loading the model and vectorizer.

## Structure
Spam-Email-Classifier/
─ spam.csv # Dataset containing emails and labels
─ model.pkl # Trained machine learning model
─ vectorizer.pkl # Saved vectorizer for converting text to numerical features
─ minor_project.ipynb # Jupyter notebook with the code and training process
─ README.md # This file