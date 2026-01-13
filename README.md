Predicting Student Productivity Using Screen Time Data

Module: MACHINE LEARNING (CPU6100-20)
Programme: BSc (Hons) Creative Computing
Student: Lauren Cua
Assessment: Assessment 2 – Machine Learning Model & Supporting Documentation

📌 Project Overview

This project applies supervised machine learning techniques to predict student productivity levels (Low, Medium, High) based on daily digital habits. With the increasing reliance on digital devices for learning and entertainment, understanding how screen time, study duration, sleep, and notifications affect productivity is an important real-world problem.

Using a real dataset from Kaggle, multiple classification models were trained and evaluated to identify patterns in student behavior. The project follows a complete machine learning pipeline, from data preprocessing and feature engineering to model evaluation and reflection.

🎯 Objectives

To analyse the relationship between digital habits and student productivity

To engineer a productivity label based on logical behavioural thresholds

To train and compare multiple classification models

To evaluate model performance using appropriate metrics

To reflect critically on results, limitations, and future improvements

📂 Dataset

Source: Kaggle – 90 Days Student Screen Time Tracker

Type: Daily behavioural data

Key Features:

Screen time (hours)

Study hours

Sleep duration

Notification count

The productivity label was not provided in the dataset and was created through feature engineering to ensure realism and transparency.

🧠 Machine Learning Approach

Problem Type: Multiclass Classification

Target Variable: Productivity_Level (Low, Medium, High)

Models Implemented:

Logistic Regression

K-Nearest Neighbors (KNN)

Random Forest Classifier

Random Forest achieved the strongest overall performance and was selected as the final model.

📊 Evaluation Metrics

Accuracy

Precision

Recall

F1-score

Confusion Matrix

These metrics were used to ensure balanced evaluation across all productivity classes.

ools & Technologies

Python 3

Pandas, NumPy

Scikit-learn

Matplotlib, Seaborn

Jupyter Notebook (Kaggle)

🔍 Key Findings

Screen time and study hours are the most influential features in predicting productivity

Random Forest provides robust performance for behavioural data

Overlapping behaviour patterns make Medium and High productivity harder to distinguish
