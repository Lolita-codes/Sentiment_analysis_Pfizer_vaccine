# Pfizer Vaccine Sentiment Analysis Report
This project focuses on analyzing a dataset containing vaccination-related tweets to understand user demographics, engagement patterns, and the overall sentiment toward vaccination-related topics.

# Table of contents 

## Project Objective
The goal is to identify key sentiment trends, categorize opinions, and provide insights into how the vaccine is perceived across different demographics and platforms. 
This analysis provides valuable insights that can inform public health campaigns, address public concerns, and promote vaccine adoption strategies based on prevailing sentiment trends.

## Methods Used  
The project involved the following steps:  
- Data Cleaning
- Data Preprocessing
- Text Preprocessing: Tokenization, stopword removal, stemming, and lemmatization.
- Sentiment Analysis: Natural Language Processing (NLP).
- Data Visualization

## Technologies Utilized
- Python
- Natural Language Toolkit (NLTK)
- Pandas
- Matplotlib & Seaborn
- WordCloud  

## Project Description  
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

## Key Findings  
- A significant proportion of tweets were from non-verified users, indicating that everyday users contribute heavily to vaccination discussions.
- Top user locations included metropolitan regions, highlighting concentrated engagement from urban areas.
- Most users fell into the "1-1000" followers category, indicating a prevalence of individual contributors rather than influencers.
- Common sources included mobile devices and web applications, showcasing platform diversity.
- The overall sentiment towards the Pfizer vaccine was mixed(neutral), with a significant portion of feedback showing positive sentiment.  

## Recommendations 
- Leverage trending hashtags to amplify message reach.
- Engage with verified users to enhance the credibility of vaccination discussions.
- Collaborate with health experts to create engaging and factual content addressing vaccine safety, benefits, and common misconceptions.
- Use insights from location analysis to design region-specific campaigns addressing unique public health concerns.
-  Monitor frequently used hashtags and create campaigns around them to ride the wave of trending discussions.
  
