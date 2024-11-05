# Stress-Detection
Stress Detection Using Machine Learning
Project Overview
This project focuses on detecting stress in textual data using machine learning techniques. The goal is to classify text data into two categories: "Stress" and "No Stress." The dataset used in this project is preprocessed, vectorized, and modeled to achieve accurate stress detection.

Key Features
Data Cleaning and Preprocessing: Custom functions are used to clean text data, removing noise such as punctuation, numbers, and URLs.
Feature Extraction: Utilizes CountVectorizer to transform text into feature vectors for model training.
Modeling: Implements the Naive Bayes algorithm (specifically, BernoulliNB) to classify text as either stressed or non-stressed.
Evaluation: The model is trained and evaluated on a split dataset to ensure reliable performance.
Technologies Used
Programming Language: Python
Libraries:
pandas for data manipulation
numpy for numerical operations
re for text preprocessing
scikit-learn for machine learning model building and vectorization
