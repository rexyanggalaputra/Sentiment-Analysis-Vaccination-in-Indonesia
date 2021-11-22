# Sentiment Analysis Vaccination in Indonesia
Covid-19 vaccine is something that is highly anticipated all over the world. One of them is Indonesia. However, the presence of the Covid-19 vaccine for now has many pros and cons. The government is currently very aggressive in pushing the presence of a Covid-19 vaccine as soon as possible. Due to the impact caused by Covid-19, it can greatly worsen the condition of the Indonesian economy.
With the current presence of the Covid-19 vaccine, there has been an extraordinary response from the community. Some of these responses were also conveyed through social media such as Twitter, Instagram, Facebook, etc 
## Data Understanding
* The datasets is about vaccination in Indonesia from Twitter started on 1/11/20 using #vaksin and #vaksinasi hastags

* The dataset consist of 13491 rows and 17 columns taken from [Kaggle](kaggle.com) platform

* [Source Data](https://www.kaggle.com/rpnugroho/indonesian-vaccination-tweets)

* Data Dictionary
  - id                : Unique id of users
  - date              : Date of tweets
  - text              : The tweets
  - hashtags          : Hashtag used
  - user_name         : Username of user
  - user_location     : Location of user
  - user_description  : Description of user
  - user_created      : Date of user account creation
  - user_followers    : Followers of user
  - user_friends      : Friends of user in Twitter
  - user_favorites    : Favorite of user
  - user_verified     : Is user verified or not
  - source            : Browser used by user
  - retweets          : How many retweets
  - is_retweet        : Is retweet or not
  - reply_to_status   : Reply

## Data Preparation
* Code Used      : Jupyter Notebook
* Library(es)    : Pandas, Numpy, NLTK, Sastrawi, Scikit-Learn, Wordcloud

## Case Understanding
This sentiment analysis aims to find out how the public reacts to vaccination in Indonesia.

Project has some case question using the data:
1. How do people react to the vaccination program?
2. What policies should be carried out by the government?

## K-Means Clustering
* Finding the Optimal Number of Clusters Using Elbow Method

![download](https://user-images.githubusercontent.com/85033777/142930899-3df3616a-8e61-4a78-9ade-a6078574da67.png)

The cluster value where this decrease in inertia value becomes constant can be chosen as the right cluster value for our data. Looking at the above elbow curve, we can choose any number of clusters between 2 to 4.

## Result
* Comparison Of The number Of Clusters

![download (1)](https://user-images.githubusercontent.com/85033777/142931087-b711fc88-e2db-4985-a0aa-9138189efa5e.png)

* Cluster(s) Analysis
  - Cluster 0
 
![klaster 0](https://user-images.githubusercontent.com/85033777/142931160-afa7d091-3006-4847-a423-cd46ee357186.png)

Cluster 0 shows that there are many words that have a 'negative' connotation. This means that there are still many people who are hesitant or do not support vaccination in Indonesia 

  - Cluater 1

![klasster 1](https://user-images.githubusercontent.com/85033777/142931181-86958b1a-543d-4b04-bb01-1535bf13c3be.png)



![klaster 2](https://user-images.githubusercontent.com/85033777/142931178-95cedfbd-315c-467e-8895-c6927b40ecb7.png)


