# Machine Learning Demo Projects

This repository showcases hands-on machine learning projects demonstrating practical skills in python, data analysis, and model development.Each project focuses on solving real-world classification problem relevant to software and fintech industries.

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
