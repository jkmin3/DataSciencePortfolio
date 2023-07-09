# Breadsmith_Reviews

### The Data
My parents own a bakery that's a part of a small franchise called Breadsmith. I wanted to use some unique data that meant something to me, so I pulled the google reviews from my parent's Breadsmith store using an API. However, you are only allowed to pull 5 reviews if you are not the owner, so I had to get access as the owner and I was able to download the reviews, because the API seems to be broken or I can't figure it out. I tried for hours. 

### About The Project
With all of this interesting data, I wanted to grab a lot of useful insights from it using different kinds of sentiment analysis and a lot of EDA. The accuracy of the sentiment analysis wasn't all that great, because there were 73 reviews, but only 47 of them had any text. Also, 83 percent of that data had a positive sentiment and that was what all of the models' accuracy were. Another challenge about this was that some of the reviews would talk greatly about the product, but poorly about the service and therefore gave it a 1 star, which obviously confused the model. However, although the models were no better than guessing, I was able to pull a lot of insight from this project.

### NLP Libraries
* [Scikit Learn](https://scikit-learn.org/stable/)
* [NLTK](https://www.nltk.org/)
* [TextBlob](https://textblob.readthedocs.io/en/dev/)
* [WordCloud](https://pypi.org/project/wordcloud/)
* [Spacy](https://spacy.io/)
* [Keras](https://keras.io/)

### Acknowledgments
* [What are Embedding Layers in Keras](https://www.youtube.com/watch?v=OuNH5kT-aD0)
* [Aspect-Based Sentiment Analysis Using Spacy & TextBlob](https://towardsdatascience.com/aspect-based-sentiment-analysis-using-spacy-textblob-4c8de3e0d2b9)
* [NLP: Gaining insights from text reviews](https://towardsdatascience.com/nlp-gaining-insights-from-text-reviews-94ef955c58c0)
* [Sentiment Analysis using TextBlob](https://towardsdatascience.com/my-absolute-go-to-for-sentiment-analysis-textblob-3ac3a11d524)
* [Word embeddings for sentiment analysis](https://towardsdatascience.com/word-embeddings-for-sentiment-analysis-65f42ea5d26e)
* [Twitter Sentiment Analysis Notebook](https://www.kaggle.com/code/paoloripamonti/twitter-sentiment-analysis)
