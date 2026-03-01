This repository contains a comprehensive machine learning and deep learning pipeline for classifying news articles as "Real" or "Fake." The project explores data preprocessing, feature engineering, and a comparison of various classification algorithms.

project Overview:
The analysis is performed on a dataset of 20,000 entries featuring news titles, full text, authors, and sources. (pp. 1-2) The primary goal is to evaluate the effectiveness of traditional NLP techniques (TF-IDF) against deep learning architectures (LSTM).

Key Features:
Balanced Dataset: The dataset is nearly perfectly balanced with an Imbalance Ratio of 1.01 (50.3% Fake vs. 49.7% Real), ensuring unbiased model training.
Comprehensive Preprocessing: Includes NLTK-based tokenization, stop-word removal, and case normalization.
Hybrid Feature Extraction: Utilizes both TF-IDF Vectorization for keyword-driven analysis and Word Embeddings for semantic understanding.

Technologies Used:
Languages: Python
Data Analysis: Pandas, NumPy
Visualization: Matplotlib, Seaborn
Machine Learning (Scikit-Learn): Logistic Regression, Random Forest, Decision Trees, Multinomial Naive Bayes, Stacking Classifier 
Deep Learning (TensorFlow/Keras): Sequential API, LSTM, Embedding layers 
NLP: NLTK (Tokenization, Stopwords) 

Usage:
Preprocessing: Run the cleaning scripts to handle missing values in 'author' and 'source' columns. 
Training: Execute the model cells to generate TF-IDF vectors and train the classifiers.
Prediction: Use the predict_title() function to test custom news headlines. 

Necessary libraries and dependencies identified from the import statements
# Data Manipulation & Math
pandas
numpy

# Visualization
matplotlib
seaborn

# Machine Learning (Scikit-Learn)
scikit-learn

# Deep Learning
tensorflow

# Natural Language Processing
nltk
