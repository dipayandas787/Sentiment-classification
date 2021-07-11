# Sentiment-classification
Text Classification With Machine Learning and SpaCy.
In this project, sentiment analysis was done using natural language processing on the online reviews prevalant for various items on amazon,yelp and imdb which were lablelled. Using the spacy package of python to preprocess the data before, each individual review has been tokenized, lemmatized, filtered for stop words and vectorized inorder to prepare the data viable for the machine learning model. A pipeline was created which vectorized the preprocessed data using count vectorization or tfidf vectorizer, which is then split into training and testing datasets and were then used to train the machine learning model (support vector machine) and evaluate the accuracy.
The accuracy was 78%
