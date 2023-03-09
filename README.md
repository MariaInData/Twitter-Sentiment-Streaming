# Twitter-Sentiment-Streaming
Streaming Tweets and Determining the Sentiment
  ![Twitter Sentiment Graph](https://user-images.githubusercontent.com/125685678/223927759-eb930293-4a55-405c-a6cb-aeb7a020f93c.png)

# Business Goal
Create a Naive Bayes model and live stream tweets to do sentiment analysis in real-time   
# Overall Process  
1. Create a Naive Bayes model from a Kaggle dataset that has sentiment labels.
2. Connect Twitter's Streaming API to receive live tweets, assemble batches of tweents into JSON files, and put the batches in a directory so it can be used by PySpark's structured streaming.  
3. Write a streaming application and visualize the sentiment analysis.
