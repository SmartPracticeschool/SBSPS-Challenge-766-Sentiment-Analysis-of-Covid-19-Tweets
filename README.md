# Twitter_Analysis
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/pramod-Paratabadi/Twitter_Analysis/master)


#### Problem Statement:
## Sentiment Analysis of Covid-19 Tweets - Visualization Dashboard


## Working of Application 
###### Vedio Link: [Twitter Sentiment Analysis](https://www.youtube.com/watch?v=ogJoGAY_KV4&t=4s)
 
#### So why do we want to focus on this topic?
We all know that corona virus is spreading widely in the world, so in general, we would pay more attention to people’s physical health.  However, according to academic studies and news, people are faced with serious mental problems as well.
As the examples shown here, suicide mortality is increasing in the US, nurse suicides rise in Europe, and suicide hotlines see a surprising increase in calls.  It’s obvious that mental health needs to be paid more attention now. So our group focuses on this topic, and this is realized by analyzing tweets on twitter.

#### Solution:                                                                                      	
Our objective is to ensure people’s mental health in the special COVID-19 pandemic.  And we will give detailed suggestions to people who feel mental discomfort during the quarantine period.
This is the logic of our project :
Our data source is Tweets with the hashtag #StayHome on Twitter,  and our main analysis method is to understand the emotions of people and identify possible factors that influence their emotions, like a specific topic or activity.
The main tool we use is NLP, including sentiment analysis, word clouds, and topic modeling.
#### Novelty:
Based on the analysis on topics and single word, we give the following suggestions to people who feel mentally discomfort.
There are several popular that are proved to be very positive: including listening to and singing songs, watch movies or TV series, virtually connecting with your closed ones even though you are physically distant, and workout.
Besides, we also found several activities that are surprisingly very helpful to your emotions:
First, help others, whether sharing free food or donating money helps you feel better
Second, say a prayer does help release your emotional discomfort
Third, ordering food online rather than cooking has a more positive effect on your emotion, where you can enjoy more delicious food
Last but not the least, Stop playing games all day. It’s not a very good way to make you happy.

 
#### Social Impact:
Besides the sentiment of topics, we are also curious about what activities people do across different cities. So we listed the top3 activities in each city based on the number of tweets related to the topic. We got several interesting findings:
Watch videos, workout and delivery are the popular activities in many cities.
People in New York prefer staying with their friends and family, people in LA most like watching shows and movies
Communication through word, message and picture is very popular in Boston.
People in different cities do have preferred activities!

 ![Test Image 3](/3DTest.png)
#### Technology Stack:
Language: Python
Library: NLP, Textblob
API: Twitter API
 
#### Scope:
We started from conducting sentiment analysis on our data. We analyzed the tweets and tried to understand people’s opinion expressed by the text. Using the textblob library in Python, we can quantify the sentiment behind each tweet with a positive or negative value, called polarity. 
We also plotted the average sentiment score over time, and we can see that generally people’s tweets are becoming more and more positive.
After dividing the tweets into positive, negative, and neutral categories based on polarity, we calculated the word frequencies for positive tweets and negative tweets separately and drew a word cloud for each of the two categories.
From the first word cloud, we can see that positive tweets often contain positive words like “safe”, “great”, “happy”. There are also words like “video”, “music” that imply positive activities.
###### Topic Modeling
From selected  13 related activities topics, we calculated the average polarity of each topic, and here is the TreeMap. The area and color are determined by the polarity of each topic, which means the larger the area and the darker the color, the more positive the topics are.
Therefore, activities at the top-left are the most positive ones. Like: watch videos, donate, communication though word and message.
