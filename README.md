# IMDB-reviews-Sentiment-Analysis-LSTM
## Overview
This project implements sentiment analysis on the IMDB movie reviews dataset using a Long Short-Term Memory (LSTM) network. The goal is to classify reviews as either positive or negative based on their textual content. LSTMs are particularly effective for this task because they capture long-range dependencies in text, making them well-suited for natural language processing (NLP) applications.

## Features
- Preprocessing & Tokenization

  - Convert text reviews into sequences of numerical tokens.

  - Apply padding and truncation for uniform input size.

  - Use word embeddings (such as pre-trained GloVe or trainable embeddings).

- LSTM-Based Sentiment Classification

  - Employ a deep learning model with LSTM layers.

  - Incorporate dropout and batch normalization to prevent overfitting.

  - Utilize binary cross-entropy loss for training.

- Training & Evaluation

  - Train on the IMDB dataset using TensorFlow/Keras.

  - Track accuracy and loss across epochs.

  - Evaluate performance using precision, recall, F1-score, and confusion matrix.

- Visualization & Insights

  - Plot training loss and accuracy curves.

  - Display word frequency distributions.

  - Generate sample predictions on test reviews.

## Dataset
The dataset used is the IMDB Large Movie Review Dataset, which contains 50,000 reviews (25,000 for training and 25,000 for testing). Each review is labeled as positive (1) or negative (0).

## Tech Stack
Programming Language: Python

Deep Learning Framework: TensorFlow/Keras

Data Handling: NumPy, Pandas

Visualization: Matplotlib, Seaborn

Text Preprocessing: NLTK, Tokenizer
