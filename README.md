# simple-document-classification-system-
This project demonstrates a simple document classification system using scikit-learn and pandas.

Project Overview
The goal of this project is to classify short text documents into predefined categories such as 'Invoice', 'Purchase Order', 'Mill Test Certificate', 'Drawing', and 'Report'. A machine learning pipeline is built to achieve this classification.

Components
Data Generation: A small, synthetic dataset is created containing various document-like texts and their corresponding labels.
Data Splitting: The dataset is divided into training and testing sets to evaluate the model's performance on unseen data.
Model Pipeline: A TfidfVectorizer is used for text feature extraction, converting text into numerical representations. This is combined with a LogisticRegression classifier within a Pipeline for streamlined processing.
Model Training: The pipeline is trained on the prepared training data.
Model Evaluation: The model's performance is assessed using a classification report, providing metrics like precision, recall, and f1-score.
Prediction: The trained model can predict the class and confidence for new, incoming documents.
Model Persistence: The trained model is saved to disk using joblib for future use without retraining and can be loaded back when needed.
