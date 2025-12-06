IMDB Sentiment Analysis using SVM & TF-IDF

This project performs sentiment analysis on the IMDB Movie Reviews Dataset using NLTK-based preprocessing, TF-IDF vectorization, and a Support Vector  Machine (SVM) classifier & LogisticRegression.

Project Workflow
1. Text Preprocessing (NLTK)
  Lowercasing
  Removing special characters
  Tokenization
  Lemmatization with WordNet
  Join tokens back into cleaned text

3. Feature Extraction: TF-IDF
Using:
  max_features = 5000
  ngram_range = (1, 2)
  TF-IDF converts text into meaningful numerical vectors.

4. Model Selection:
  SVM (LinearSVC) & LogisticRegression
  Both performs extremely well with sparse text data
  Fast and scalable for large datasets
  Gives 89% accuracy on IMDB reviews

5. Evaluation
  We evaluate using:
  Accuracy : 0.8938186951699103
  Confusion matrix
