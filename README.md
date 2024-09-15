# Pfizer Vaccine Sentiment Analysis Report
This analysis focuses on understanding public sentiment surrounding the Pfizer COVID-19 vaccine by analyzing textual data from various sources.

# Table of contents 

**Project Objective**  
The goal is to identify key sentiment trends, categorize opinions, and provide insights into how the vaccine is perceived across different demographics and platforms. 
This analysis provides valuable insights that can inform public health campaigns, address public concerns, and promote vaccine adoption strategies based on prevailing sentiment trends.

**Methods Used**  
The project involved the following steps:  
o Data Cleaning  
o Text Preprocessing: Tokenization, stopword removal, stemming, and lemmatization were employed to break down text into meaningful components for analysis.  
o Sentiment Analysis: Natural Language Processing (NLP) techniques to determine the sentiment (positive, negative, neutral) of the comments or feedback related to the Pfizer vaccine.  
o Data Visualization: Graphs and visual representations to present sentiment trends and demographic influences.

**Technologies Utilized**  
o Python  
o Natural Language Toolkit (NLTK)  
o Pandas  
o Matplotlib & Seaborn  
o Sklearn  

**Project Description**  
This project utilized a dataset containing feedback or reviews related to the Pfizer COVID-19 vaccine. The dataset contains various columns such as:  
o id: A unique identifier for the tweet. It corresponds to the tweet's ID on Twitter.  
o user_name: The username of the person who posted the tweet.  
o user_location: The location of the user as provided on their Twitter profile.  
o user_description: A short description or bio provided by the user on their Twitter profile.  
o user_created: The date and time when the user's Twitter account was created.  
o user_followers: The number of followers the user has at the time of the tweet.  
o user_friends: The number of accounts the user is following at the time of the tweet.  
o user_favourites: The number of tweets the user has marked as favorites/liked.  
o user_verified: A boolean value indicating whether the user’s account is verified on Twitter (True if verified, False otherwise).  
o date: The date and time when the tweet was posted.  
o text: The actual content of the tweet, which may include comments, hashtags, and mentions.  
o hashtags: A list of hashtags included in the tweet, enclosed in square brackets.  
o source: The platform or device used to post the tweet (e.g., "Twitter for Android", "Twitter Web App").  
o retweets: The number of times the tweet has been retweeted.  
o favorites: The number of times the tweet has been liked.  
o is_retweet: A boolean value indicating whether the tweet is a retweet (True if it's a retweet, False otherwise).

**Key Findings**  
The overall sentiment towards the Pfizer vaccine was mixed(neutral), with a significant portion of feedback showing positive sentiment.  
