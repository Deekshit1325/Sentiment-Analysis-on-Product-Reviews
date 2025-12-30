# Sentiment-Analysis-on-Product-Reviews

## Overview
This project performs **sentiment analysis on product reviews** to classify them as **Positive** or **Negative** using machine learning techniques. The model analyzes textual reviews and predicts customer sentiment automatically.

## Problem Statement
Online platforms receive a large number of product reviews daily. Manually analyzing customer sentiment is inefficient. This project aims to build an automated system to understand customer sentiment from review text.

## Dataset
- **Dataset:** Amazon Product Reviews (FastText format)
- **Source:** Kaggle
- **Labels:**
  - `label-1` → Negative
  - `label-2` → Positive
- A **sampled subset** of the dataset was used for efficient training.

## Technologies Used
- Python  
- Google Colab  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib  
- Streamlit (for deployment demo)

## Machine Learning Approach
- **Text Vectorization:** TF-IDF (Term Frequency–Inverse Document Frequency)
- **Algorithm Used:** Logistic Regression

### Why Logistic Regression?
- Works well with high-dimensional text data
- Simple, fast, and interpretable
- Commonly used in real-world NLP applications

## Model Evaluation
The model was evaluated using:
- Accuracy
- Confusion Matrix
- Precision
- Recall
- F1-Score

Visualizations were created to analyze dataset distribution and model performance.

## Deployment
A simple **Streamlit application** (`app.py`) was created to demonstrate real-time sentiment prediction by allowing users to input a product review and get instant results.

## Conclusion
The project successfully demonstrates an end-to-end NLP pipeline for sentiment analysis using real-world data. TF-IDF combined with Logistic Regression provided effective and reliable sentiment classification results.
