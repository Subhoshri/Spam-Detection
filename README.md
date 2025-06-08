# Spam Detection Project

## Overview
This project implements a machine learning model to classify text messages as **spam** or **not spam** (ham). It uses natural language processing (NLP) techniques and classification algorithms to detect unwanted or malicious messages, enhancing communication security.

## Features
- Text preprocessing and cleaning
- Feature extraction with TF-IDF vectorization
- Spam detection using Multinomial Naive Bayes and Logistic Regression classifiers
- Model evaluation with accuracy, precision, recall, and F1-score
- Command-line prediction script for testing new messages

## Dataset
The project uses the [SMS Spam Collection Dataset](https://archive.ics.uci.edu/ml/datasets/SMS+Spam+Collection), a public dataset containing labeled SMS messages.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/spam-detection.git
   cd spam-detection
2. Install required dependencies:
```pip install -r requirements.txt```

## Results
- Logistic Regression model performed best with 98.09% accuracy.

- Detailed classification reports available after training.

## Future Improvements
- Incorporate deep learning models (LSTM, BERT) for improved accuracy.

- Build a web or mobile app for real-time spam filtering.

- Expand dataset and implement advanced preprocessing techniques.
