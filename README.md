# Project timeline

ToDo:
- JSON from tweepy
    - Run sentiment analysis on each tweet.text
    - Add columns (+rows) to overall dataframe
    - Save csv to local storage

- JSON from Alpaca
    - Keep storing live data into local storage (to be read soon)
    - Save complete csv to local


Analysis-1 
- Run a basic code in notebook
- Get inferences on a limited number of tweets [100] (1 model - roBERTa)
- Add as many models as possible: to get multiple features on 100 tweets
- Increase number of tweets to 100k [Twitter API]
- Add followers data to each tweet
- Get finance data for this timeline [alphavantage]
- Perform causality test to check which features actually work 

Analysis-2
- Start models based training on this data

Analysis-3
- Make it realtime

Important links
- https://docs.tweepy.org/en/stable/api.html
- https://developer.twitter.com/en/portal/projects/1554803000358551552/apps
- https://developer.twitter.com/apitools/query?query=KHRlc2xhIEw6ZW4pIE9SICh0c2xhIEw6ZW4p
- https://developer.twitter.com/en/docs/twitter-api/data-dictionary/introduction
- https://developer.twitter.com/en/docs/twitter-api/tweets/search/introduction
