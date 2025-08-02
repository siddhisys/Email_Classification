# Email Spam Classifier

This is a machine learning project that detects whether an email is **Spam** or **Ham (not spam)** using natural language processing (NLP) and classification techniques.

## Features

- Preprocessing of email text (lowercasing, punctuation removal, stopword filtering)
- Feature extraction using **TF-IDF Vectorizer**
- Spam/Ham classification using **Logistic Regression**
- Simple and clean implementation
- Final test: classify a custom input message

## Dataset

The dataset used is a collection of email messages labeled as spam or ham. It was preprocessed and split into training and test sets for evaluation.

## Tech Stack

- Python
- NumPy, Pandas
- Scikit-learn
- NLTK (for stopword removal)
- Jupyter Notebook

## Machine Learning

- **Vectorization**: TF-IDF (Term Frequency-Inverse Document Frequency)
- **Model**: Logistic Regression
- **Evaluation**: Accuracy Score, Confusion Matrix

## Results

The classifier shows high accuracy on the test set and performs well in distinguishing spam from legitimate messages.

## How to Use

1. Clone the repository  
   ```bash
   git clone https://github.com/siddhisys/email-spam-classifier.git
   cd email-spam-classifier

