# project_1
Sentiment Analysis - Amazon Food Review Dataset 

What is Sentiment Analysis ?
Sentiment analysis is a technique through which you can analyze a piece of text to determine the sentiment behind it. It combines machine learning and natural language processing (NLP) to achieve this.
Using basic Sentiment analysis, a program can understand whether the sentiment behind a piece of text is positive, negative, or neutral.

In this notebook we will be using 2 different techniques for Sentiment Analysis:
1.VADER (Valence Aware Dictionary and sentiment Reasoner) - Bag of words approach
2.Roberta Pretrained Model from 🤗

1.VADER ( Valence Aware Dictionary for Sentiment Reasoning) is a model used for text sentiment analysis that is sensitive to both polarity (positive/negative) and intensity (strength) of emotion. It is available in the NLTK package and can be applied directly to unlabeled text data. VADER sentimental analysis relies on a dictionary that maps lexical features to emotion intensities known as sentiment scores. The sentiment score of a text can be obtained by summing up the intensity of each word in the text.
![image](https://github.com/yashvi3009/project_1/assets/148530170/ca5faac5-450a-431e-b616-d6f2d66d83bd)

2.The Roberta model from Hugging Face's Transformers library can be used for sentiment analysis tasks. You first load the pretrained Roberta model and tokenizer. Then you tokenize your input text and pass it through the model to get sentiment predictions. Finally, you interpret the prediction to determine the sentiment (negative, neutral, or positive) of the input text.
