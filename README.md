# IIITD-MIDAS
## Python Problem
**Requirements:**
tweepy==3.3.0
pandas

**Installation:**
pip install tweepy==3.3.0
pip install pandas

**Functionalities:**
(1) Fetch all the tweets(as many as allowed by Twitter API) done by a user twitter handle and dump the responses into        
JSONlines file.

(2) The other part of your script should be able to parse these JSONline files to display the following for every tweet in a 
tabular format.
  
  ● The text of the tweet.

  ● Date and time of the tweet.

  ● The number of favorites/likes.

  ● The number of retweets.

  ● Number of Images present in Tweet. If no image returns None.


(3)Preprocess Text:
  
  ● Remove URLs,hashtags etc.
  
  ● Replace @username with username
