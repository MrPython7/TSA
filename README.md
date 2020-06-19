# twitter-sentiment-analysis
Sentiment Analysis is a term that you must have heard if you have been in the Tech field long enough. It is the process of predicting whether a piece of information (i.e. text, most commonly) indicates a positive, negative or neutral sentiment on the topic. In this article, we will go through making a Python program that analyzes the sentiment of tweets on a particular topic. The user will be able to input a keyword and get the sentiment on it based on the latest 100 tweets that contain the input keyword.
Introducing Sentiment Analysis
Also known as “Opinion Mining”, Sentiment Analysis refers to the use of Natural Language Processing to determine the attitude, opinions and emotions of a speaker, writer, or other subject within an online mention.
Essentially, it is the process of determining whether a piece of writing is positive or negative. This is also called the Polarity of the content.
As humans, we are able to classify text into positive/negative subconsciously. For example, the sentence “The kid had a gorgeous smile on his face”, will most likely give us a positive sentiment. In layman’s terms, we kind of arrive to such conclusion by examining the words and averaging out the positives and the negatives. For instance, the words “gorgeous” and “smile” are more likely to be positive, while words like “the”, “kid” and “face” are really neutral. Therefore, the overall sentiment of the sentence is likely to be positive.
A common use for this technology comes from its deployment in the social media space to discover how people feel about certain topics, particularly through users’ word-of-mouth in textual posts, or in the context of Twitter, their tweets.
Prerequisites
Basic programming knowledge
Although Python is highly involved in this mini-project, it is not required to have a deep knowledge in the language, as long as you have basic programming knowledge.
Installed tools
For this program, we will need Python to be installed on the computer. We will be using the libraries twitter, nltk, re, csv, time, and json. You are likely to have to install the first two libraries. The rest already come with the Python interpreter. It doesn’t hurt to check that they’re up-to-date though.
Data set splitting concept
This is critical to fully understand the process pipeline. You only need to know the difference between Training and Test data sets, and in what context each one is used.
Basic RESTful API knowledge
This is not crucial, but it could help. We will be using the Twitter API here and there in the code, making normal calls to the API and dealing with the JSON objects it returns. In case you need it, you can find the official Twitter API documentation here.
Process Description
Section A: Preparing The Test Set
Step A.1: Getting the authentication credentials
Step A.2: Authenticating our Python script
Step A.3: Creating the function to build the Test set
Section B: Preparing The Training Set
Section C: Pre-processing Tweets in The Data Sets
Section D: Naive Bayes Classifier
Step D.1: Building the vocabulary
Step D.2: Matching tweets against our vocabulary
Step D.3: Building our feature vector
Step D.4: Training the classifier
Section E: Testing The Model
Before We Start:
Twitter can sometimes take a few days to approve your application to use the Twitter API. However, it usually takes less that 24 hours.
It can take 10+ hours to download the Training set (this will be explained later on).
The tutorial was adopted from the Udemy course: From 0 to 1: Machine Learning, NLP, and Python-cut to The Chase.
