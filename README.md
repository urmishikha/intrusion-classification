# intrusion-classification

# 📌 Project Overview

This project analyzes a Network Intrusion Detection Dataset to classify network traffic as benign or malicious using Random Forest. The dataset is downloaded from Kaggle, preprocessed, and the top 10 features are selected using SelectKBest. Finally, a Random Forest Classifier is trained and evaluated using accuracy, classification report, and a confusion matrix.

# 📥 Data Preprocessing

Download Dataset: Using kagglehub to fetch the dataset.
Load Data: Reads multiple CSV files and combines them.
Clean Data: Handles missing values and converts categorical labels to numeric.
Feature Selection: Selects the top 10 features using SelectKBest.


# 🔍 Model Training & Evaluation

Splitting Data: Uses train_test_split (80% train, 20% test).
Train Model: Trains a Random Forest Classifier.
Predictions: Generates predictions for the test set.
Evaluation:
Accuracy score
Classification report
Confusion matrix (visualized with seaborn)

# 📊 Results

Accuracy Score: Displays model accuracy.
Classification Report: Shows precision, recall, and F1-score.
Confusion Matrix: Visualizes model performance.
