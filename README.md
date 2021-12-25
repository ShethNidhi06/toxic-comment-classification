# toxic-comment-classification
Classification of user generated tweets into positive or negative texts.
## Abstract 
Sentiment Analysis is increasing gaining importance as social media platforms are now a source for identity theft and a medium to post hateful and toxic comments. In this project, we aim to create a dataset from user generated tweets using Tweepy to train and test a deep learning sentiment analysis model that classifies the tweets to positive or negative tweets. In our approach, we used a single layered bi-LSTM model and achieved an F1-score of 0.81

## Prerequsites 
- Twitter developers account : Create an app using Twitter developers account and get the authorisation token required for tweet extraction.
- [Tweepy] (https://www.tweepy.org/)

To install tweepy exhecute the below command in cmd:
```bash
 pip install tweepy
```
- Glove6B.50d.txt word embedding file 
You can download the same from :

https://www.kaggle.com/rtatman/glove-global-vectors-for-word-representation?select=glove.6B.50d.txt

## Functional Requirements:
Input- Unlabelled Dataset
Output- Classified tweets


