# Spam Message Classifier 📨

This is a basic spam detection model using Natural Language Processing (NLP) techniques and a Naive Bayes classifier. The model classifies text messages as either **ham (not spam)** or **spam**.

## Features
- Text preprocessing (tokenization, stopword removal, lemmatization, stemming)
- TF-IDF vectorization
- Random oversampling to balance the dataset
- Multinomial Naive Bayes classifier
- Evaluation metrics: Accuracy, Classification Report, ROC AUC, Confusion Matrix

## Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/yourusername/spam-detector.git
cd spam-detector
pip install -r requirements.txt
