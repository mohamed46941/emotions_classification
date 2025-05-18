# Emotion Classification using Machine Learning and Deep Learning

## Project Overview
This project focuses on classifying emotions from text data using both traditional machine learning algorithms and deep learning models. The goal is to predict multiple emotion classes such as joy, sadness, anger, fear, love, and surprise from input text.

## Dataset
The dataset consists of text samples labeled with multiple emotion categories. Text preprocessing includes tokenization and vectorization using TensorFlow’s TextVectorization layer.

## Models Implemented

### Machine Learning Models
- **Logistic Regression**
- **Support Vector Machine (SVM)**
- **Random Forest**
- **Naive Bayes**

These models use classic feature extraction techniques such as TF-IDF vectorization to convert text data into numerical features.

### Deep Learning Model
- **LSTM (Long Short-Term Memory)** network with:
  - Embedding layer
  - SpatialDropout1D for regularization
  - LSTM layer to capture temporal dependencies
  - Dense layers with dropout
  - Softmax output layer for multi-class classification

## Technologies Used
- Python
- TensorFlow / Keras
- scikit-learn
- Matplotlib / Seaborn
