# Natural Language Processing with Disaster Tweets
Twitter has emerged as a vital communication channel during emergencies, enabling real-time reporting of incidents by individuals. Consequently, various agencies, including disaster relief organizations and news agencies, are keen on programmatically monitoring Twitter to identify and respond to emergencies promptly.

However, discerning whether a tweet genuinely pertains to a disaster is not always straightforward.

# Overview
This repository contains two Jupyter Notebook files:

1. data_preprocessing.ipynb: This notebook encompasses various preprocessing techniques commonly employed in Natural Language Processing (NLP) tasks, along with Exploratory Data Analysis (EDA). The preprocessing steps include:
- Target distribution analysis
- Text cleaning procedures such as lowercase conversion, removal of special characters and URLs
- Tokenization
- Part-of-speech (POS) tagging
- N-gram generation (unigram, bigrams, and trigrams)
2. disaster_tweets-nlp.ipynb: In this notebook, the preprocessed data is utilized to train and evaluate several machine learning models for disaster tweet classification. The models explored include Naive Bayes, Random Forest, Bidirectional LSTM, CNN, and a basic Transformer model. Among these, the Naive Bayes model exhibits the highest accuracy.

# Conclusion
The objective was to classify disaster-related tweets using various NLP techniques and machine learning models. After preprocessing the data and experimenting with different algorithms, the Naive Bayes classifier emerged as the most accurate. However, further optimization and exploration of advanced techniques could enhance performance. Overall, this underscores the importance of NLP in disaster management and demonstrates the efficacy of machine learning in analyzing crisis-related tweets on Twitter.
