# Sentiment Analysis

## Introduction
Due to the rapid development of technology, most people have at least one mobile device to access the Internet. People not only use mobile devices to accomplish certain things or needs, but they can also entertain their time, such as accessing social media through Facebook, and watching videos through YouTube and others. Some people like to share their daily activities, emotions, opinions and others on social media. There are some businesses that wish to confirm their satisfaction with their products by collecting posts on social media. They hope to use a system to help busy business owners easily analyze those posts. Therefore, my teammates and I made a prototype of the sentiment analysis system to full field the requirement.


## Objectives/aims

❖	The system allows business owners to perform sentiment analysis on product after-sales evaluation.

❖	The system allows business owners to enter the keyword and the quantity of the post in Twitter that wants to perform sentiment analysis.

❖	The system has a high accuracy of the result of the sentiment analysis, which must be more than 95%.

❖	The system should provide a user friendly interface and be able to perform the result in the form of the graphs.

## Motivation
With the advancement of technology, e-commerce is now the primary option for the new generation of business. Many merchants who are still using traditional sales methods have also switched to e-commerce to attract more customers. Some of these customers will comment on the good and bad reviews of the goods or services provided by the merchant on the merchant's webpage. In addition, some customers will post their opinions and comments on other social media or platforms. Some owners may be busy with their own business and do not have time to check all the reviews one by one, which may lead to the loss of part of the customer flow or the inability to improve their products and services. Moreover, it takes a lot of energy and time to check customer reviews, and even spend money to hire employees to complete this task. Therefore, this sentiment analysis system can easily help owners to simplify this work. This system can crawl on its own social media or platform posts about keywords entered by the owner, analyze it, and finally present it to the owner in a simple and easy-to-understand way. With the operation of this system, owners can save time to complete other business tasks, or improve their own products and services. This helps the owners to compete with their peers in business and attract more customers.

## Description of dataset
This sentiment analysis is using twitter_samples dataset to train the machine to analyze the sentiment. The dataset is taken from the nltk.corpus library. There are 3 sets of the Tweets corpus, which are positive_tweets.json, negative_tweets.json and tweets.20150430-223406.json. In the prototype of this system we will only use the first two sets to train machine learning to analyze whether the content of the tweets is positive or negative. 

## Application of algorithms
In this sentiment analysis application, the system has used tweepy for the tweet crawling function. Since the system needed to request the tweet content in Twitter, and it was having robots.txt protocol, which is the page that shows only what or which type of web crawler can request the content. Our development team decided to use Tweepy, the Twitter officially approved method to accomplish this task. Our development team successfully applied for the Twitter API, and jointly used the Tweepy library to complete the work of crawling tweets.

In addition, our team also uses the Naive Bayes Classifier in the nltk library in this system. This classifier uses the Bayes’ rule algorithm to train machine learning to classify and analyze sentiment. SVMs and Logical Regression library can also be used for sentiment analysis, but compared to Naive Bayes Classifier, the classifier chosen by our team only needs less training data.
