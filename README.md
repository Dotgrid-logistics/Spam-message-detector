# Spam Message Detector

A machine learning project that classifies text messages as Spam or Not Spam 
using a Multinomial Naive Bayes classifier, built in Python with scikit-learn.

## Dataset
60 labeled SMS-style messages (30 spam, 30 not spam).

## Approach
- Text preprocessing and label encoding
- Train/test split (80/20, stratified)
- Feature extraction using CountVectorizer
- Model training with Multinomial Naive Bayes
- Evaluation using accuracy, precision/recall, and confusion matrix

## Results
~92% accuracy on the test set. See the notebook for full evaluation and 
discussion of limitations.

## Files
- `spam_detector.ipynb` — full notebook with code, results, and explanations
- `message.csv` — dataset used for training/testing
