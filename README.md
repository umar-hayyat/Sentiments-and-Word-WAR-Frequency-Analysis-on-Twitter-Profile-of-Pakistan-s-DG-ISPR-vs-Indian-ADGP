# Sentiments-and-Word-WAR-Frequency-Analysis-on-Twitter-Profile-of-Pakistan-s-DG-ISPR-vs-Indian-ADGP
Basically the idea behind was to discover the sentiment reflection of twitter profiles of Public Relations Representative of the most antagonistic nations of the world.

So two profiles were being considered for this analysis.
Major General Asif Ghafoor is Director-General of Inter-Services Public Relations (Pakistan)
Additional Directorate General of Public Information (India)

For this specific task I used the text mining approach to predict that what type of sentiments do the both of public representative have, either there are positive views, Negative views or Neutral views resembling to their tweets.And a word frequency analysis was being done on this data too. The word frequency analysis was done on the word WAR as it's been the most gut issue between these two countries since their creation.
Key Parts of Project:
(I) Requesting twitter for API Key
(2) Use Tweepy to scrap the Tweets
(3) Create a Panda DataFrame
(4) TextBlob Library for Sentiment Analysis
(5) WordCloud for Word frequency analysis
Step 1:
After your developer account approval you need API key, API secret, Access token and Access token secret.
Step 2:
Tweepy is a Python library for accessing the Twitter API. It is great for simple automation, creating twitter bots and extracting twitter data. You can simply install it by using command in your terminal: pip install tweepy
 Step 3:
Create a Pandas data frame and fetch the extracted tweets.
Step 4:
Sentiment Analysis Results:

Pakistan's DG-ISPR Sentiments

<p align="center">
  <img src="file:///F:/Data%20Science/Tweets%20Sentiment%20Analysis/DG-ISPR/Sentiments.png" width="350">
</p>



Indian ADGPI Sentiments

<p align="center">

  <img src="file:///F:/Data%20Science/Tweets%20Sentiment%20Analysis/DG-ISPR/India%20(1).png" width="350">
</p>



Step 5:
Word-WAR Frequency Analysis:
DG-ISPR has tweeted about WAR 47 times.
ADGPI has tweeted about WAR 219 times.
Most Frequent words used by DG-ISPR are as follow.

file:///F:/Data%20Science/Tweets%20Sentiment%20Analysis/DG-ISPR/Word%20frequesncy%20analysis.png
 
 (Pakistan's DG-ISPR)

Most Frequent words used by ADGPI are as follow.

file:///F:/Data%20Science/Tweets%20Sentiment%20Analysis/DG-ISPR/India%20(2).png

(Indian ADGPI)
