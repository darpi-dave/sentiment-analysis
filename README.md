# Sentiment Analysis on Movie Reviews

This project develops a machine learning model to classify movie reviews as positive or negative, based on the sentiment expressed in the review text. Using a dataset from IMDb, the model has been trained and evaluated for sentiment analysis, providing useful insights into audience opinions. The final model can be used to automate review analysis, offering valuable sentiment insights for filmmakers, studios, and review aggregators.

## Project Overview

- **Goal**: Automatically classify movie reviews as either positive or negative based on the text.
- **Data**: IMDb movie reviews dataset from `nltk` library.
- **Techniques**:
  - **Preprocessing**: Text tokenization, lowercasing, stopword removal, lemmatization.
  - **Feature Engineering**: TF-IDF for text vectorization.
  - **Modeling**: Trained using Logistic Regression and evaluated using Support Vector Machines as an alternative.
  - **Evaluation Metrics**: Accuracy and F1-score for performance evaluation.

This repository contains the complete pipeline, from data preprocessing and feature engineering to model training and deployment.

## Project Structure

- `sentiment.ipynb` - Contains the main code for training the model, processing input reviews, and performing sentiment predictions.
- `sentiment_model.pkl` - Serialized trained model.
- `tfidf_vectorizer.pkl` - TF-IDF vectorizer used to preprocess review text.
- `README.md` - Project description.
