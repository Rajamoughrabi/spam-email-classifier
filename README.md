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
### Confusion Matrices

**Gaussian Naive Bayes**
![Gaussian Naive Bayes Confusion Matrix](results/confusion_matrix_gnb.png)

**PyTorch Fully Connected Neural Network**
![PyTorch Confusion Matrix](results/confusion_matrix_pytorch_fc.png)

**Random Forest**
![Random Forest Confusion Matrix](results/confusion_matrix_rf.png)

### ROC Curve
![ROC Curve](results/ROC.png)


## How to Run
```bash
pip install -r requirements.txt
python src/random_forest.py
