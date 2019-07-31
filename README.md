# Sentimental-Analysis
The project's objective was to segregate latest social media reactions on any topic.  
For this, We chose twitter as our target social media and used Twitter API and Tweepy, Open Source Python library to work efficiently with Twitter API. 
Using the Twitter API and tweepy, last 200(Can change the number) tweets are streamed in and then,tweets are cleaned using Regex library.
Further, Cleaned Tweets are converted into Textblob objects so that Sentiment Polarity can be judged of a string. 
There can be three cases:Positive, Negative and Neutral polarity. Finally, After each Textblob string object has been processed, Percentages of positivewith, neutral and negative tweets encountered are shown along with few examples of tweets of positive and negative polarity are shown for a better experience. 
This type of quick analysis can help an organization work on its social media profiles and look to drive themselves towards content that people tend to appreciate positively.
