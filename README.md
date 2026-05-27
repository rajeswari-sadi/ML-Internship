# Machine Learning Demo Projects

This repository contains three simple demo projects for learning classification using Python and scikit-learn.  
Each project uses a synthetic dataset to demonstrate how machine learning models work.

## Projects Included

### 1. Movie Genre Classification
Predict the genre of a movie based on its plot description.  
Dataset: Synthetic text samples (Sci-Fi, Thriller, Romance, Action, Comedy).  
Model: TF-IDF + Naive Bayes.

### 2. Credit Card Fraud Detection
Detect fraudulent transactions based on amount and time.  
Dataset: Synthetic numeric samples (100 transactions, 20% fraud).  
Model: Random Forest Classifier.

### 3. Spam Email Detection
Classify emails as Spam or Ham (not spam).  
Dataset: Synthetic text samples (50 spam + 50 ham).  
Model: CountVectorizer + Naive Bayes.

## Requirements
Install dependencies before running:
```bash
conda install numpy=1.26 pandas=2.2.2
pip install scikit-learn "protobuf<6" "pyarrow>=21.0.0"
