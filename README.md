# Sentiment Analysis with LLMs

## Overview  
This project classifies Vietnamese user comments from e-commerce platforms (Tiki, Lazada) into three sentiment categories: **0**: Negative, **1**: Neutral, **2**: Positive.  
- **Input**: A Vietnamese comment collected from Tiki or Lazada.  
- **Output**: Y ∈ {0, 1, 2}:    

## Features  
- **Word Embedding**: Tf-Idf, fastText, phoBERT, RoBERTa  
- **Models**: SVM, Logistic Regression, XGBoost, Random Forest, LightGBM, RoBERTa  
- Achieved **F1-score: 80%** on a dataset of 30,000+ comments.

## Setup  
1. Use **Google Colab** (enable GPU for deep learning models).  
2. Update dataset file paths in the script.  
3. Run scripts for preprocessing, training, and evaluation. 
