# NLP_NYT_comments

Project for the ENSAE course "Machine Learning for Natural Language Processing".

Using the New York Times Comments dataset ([https://www.kaggle.com/aashita/nyt-comments](https://www.kaggle.com/aashita/nyt-comments)), we want to analyze who are the most popular editorialists, based on the comments left by the readers. We train a BERT on a labelled training set, the Twitter US Airline sentiment dataset, and apply it to our dataset. For each comment, we consider only the sentences containing the author's name, to capture the sentiment towards the journalist, and not towards the whole article.

This repo contains our final report and our code in Python (Google Colab).
