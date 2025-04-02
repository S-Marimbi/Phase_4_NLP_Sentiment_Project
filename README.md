# Phase_4_NLP_Sentiment_Project
# TWITTER-SENTIMENT-ANALYSIS

![image1](https://github.com/user-attachments/assets/920b4154-4d03-4d99-b757-a406c1edfa2f)

![image1](https://github.com/user-attachments/assets/e93d8925-7975-4307-955d-8ab4fe4aa7f2)
![Banner](image1.jpeg)
Authors:   
 - [Calvince Kaunda](https://github.com/CalvinceKaunda)   
 - [Samuel Marimbi](https://github.com/S-Marimbi)  
 - [Sharon Paul](https://github.com/Sharzyp)  
 - [Brenda Mutai](https://github.com/Brendamutai)


     
## Overview
Not only does a business launch a new product but also evaluates the performance of the  product. Performance may be in terms of profits or how it is received by the target market. It is necessary to consider customer feedback in order to improve the quality of the product and have better products in general in the market. A useful technique for analysing the reviews of the product is through social media reviews. Businesses can evaluate how customers feel regarding the product via analysis of posts, tweets and threads about the product.

## Business Understanding
Apple would like to review customer sentiments from Twitter about their products. To address this they are interested in a Natural Language Processing machine learning model that will analyse tweets about Apple products in order to monitor brand perception and respond to customer feedback efficiently

The Goal of this project is to build a model that classifies tweets as positive, negative or neutral in order to automate sentiment analysis

## Data Understanding
The dataset used for this project is from Kaggle: [Apple Twitter Sentiment (CrowdFLower)](https://www.kaggle.com/datasets/slythe/apple-twitter-sentiment-crowdflower)
The dataset contains multiple features such as the date of the tweet, confidence of the sentiment, sentiment of the tweet/text, and text/tweets, among others. Our target is the sentiment and we would like to predict the sentiment based on the text/tweet 

## Data Preparation
The dataset was cleaned, relevant features extracted and relevant transformations applied to preprocess the data and ensure it is ready for modelling.
The dataset was split into a train set(80% of original dataset) and a test set(20% of original dataset)

## Modelling
The dataset had imbalanced features and techniques such as SMOTE were applied to balance the class distributions and in turn improving model performance.


