# Twitter_Sentiment_Analysis
Twitter Sentiment Analysis Using NLP Models

- Sentiment analysis has been applied to the Twitter dataset, which was sourced from Kaggle.

- The initial dataset consisted of 1.65 million records, which was further reduced during text preprocessing based on the length of the tweets.

- Implemented models like CBOW (Continuous Bag of Words), Skip-Gram, CountVectorizer, and TF-IDF to predict the sentiment of the tweets.

- Since the dataset is almost balanced, accuracy metrics have been used for model evaluation.

  
Sr No	Method	Train_accuracy	Test_accuracy
0	CBOW+Log_Reg_10	0.688	0.688
1	skip_gram	0.690	0.690
2	Countvectorizer	0.756	0.732
3	tfidf_vectorizer	0.754	0.731
4	SentimentIntensityAnalyzer_overall_accuracy	0.615	-
5	huggingface_overall_accuracy	0.750	-
6	LSTM_accuracy	0.715	-

