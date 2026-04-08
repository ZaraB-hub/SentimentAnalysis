Twitter Sentiment Analysis
Entity-level sentiment classification of tweets using NLP and traditional ML models.

Dataset
Twitter Sentiment Analysis — Kaggle

74,682 tweets across 4 sentiment classes
Entity-level: sentiment is judged relative to a specific entity mentioned in the tweet
Labels: Positive, Negative, Neutral, Irrelevant


Pipeline

Text Cleaning — removed URLs, mentions, hashtags, punctuation, lowercased
Stopword Removal — removed common words using NLTK
TF-IDF Vectorization — converted text to numerical features (39,605 unique words)
Model Training — trained and compared 3 classifiers
Evaluation — weighted F1 and accuracy on validation set


Results
ModelAccuracyF1 (weighted)Logistic Regression0.8520.851Naive Bayes0.7770.772SVM (LinearSVC)0.8630.862