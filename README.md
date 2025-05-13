# Movie-Review-Sentiment-Analysis
This project uses Natural Language Processing (NLP) and machine learning to classify IMDb movie reviews as positive or negative. It includes data cleaning, TF-IDF vectorization, and model training using Logistic Regression and Naive Bayes. A simple input function is also provided to predict sentiment on custom reviews in real time.
The Python script used in this project carries out sentiment analysis on movie reviews with the help of machine learning approaches. It starts by importing the IMDb dataset and carrying out general data exploration, including checking the dataset shape, looking at column names, and displaying the distribution of sentiment labels via Seaborn.

To preprocess the text data for machine learning, reviews are cleaned by converting them to lower case, stripping punctuation, and English stopwords removal via the NLTK library.
Cleaned reviews are further converted to a numerical representation using TF-IDF vectorization, taking into account the most important 5000 words.

The sentiment tags are converted into binary form (1 for positive and 0 for negative) and the dataset is divided into training and testing sets. Two classification models, Logistic Regression and Multinomial Naive Bayes, are trained to make predictions about unseen reviews. The models are measured using metrics like accuracy, confusion matrix, and classification report.

Finally, the project incorporates an interactive user functionality that takes a personalized movie review as input, processes it in real time, and estimates its sentiment, an interactive and useful application of sentiment analysis.
