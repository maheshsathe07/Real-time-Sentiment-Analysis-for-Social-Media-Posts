# Real-time Sentiment Analysis for Social Media Posts

This code demonstrates a simple implementation of a real-time sentiment analysis model for social media posts. It utilizes the NLTK Twitter dataset for training a Naive Bayes classifier to categorize tweets into positive, negative, or neutral sentiment categories.

## Requirements

- Python 3.x
- NLTK (Natural Language Toolkit)
- scikit-learn

## Installation

1. Install Python 3.x from [python.org](https://www.python.org/downloads/).
  
2. Install NLTK and scikit-learn using pip:
`pip install nltk scikit-learn`

3. Download NLTK resources:
`import nltk`
`nltk.download('twitter_samples')`
`nltk.download('stopwords')`
`nltk.download('wordnet')`


## Usage

1. Clone or download the repository.
2. Run the `realtime_sentiment_analysis.py` script.
3. The script trains the classifier on the NLTK Twitter dataset and evaluates its performance on a test set.
4. After training, the script provides an example of making predictions on sample tweets to demonstrate the model's functionality.

## Files

- `realtime_sentiment_analysis.py`: Main Python script containing the code for training the sentiment analysis model and making predictions.
- `README.md`: This file providing information about the project and instructions for usage.
- `LICENSE`: License information for the code.

## Acknowledgments

- NLTK Twitter dataset: This code utilizes the NLTK library for sentiment analysis, which includes a dataset of positive and negative tweets.
