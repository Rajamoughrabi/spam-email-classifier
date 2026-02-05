# Email Spam Classifier

## Overview
This project compares three machine learning models for email spam classification:
- Gaussian Naive Bayes
- Fully Connected Neural Network (PyTorch)
- Random Forest

## Dataset
UCI Spambase Dataset (4601 samples, 57 features)

## Models
- Naive Bayes
- PyTorch Neural Network
- Random Forest

## Evaluation
- Accuracy
- Precision
- Recall
- F1-score
- ROC Curve
- Confusion Matrix

## Results
Random Forest achieved the best overall F1-score.

## How to Run
```bash
pip install -r requirements.txt
python src/random_forest.py
