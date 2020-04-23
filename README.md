# yelp_text_mining_R

Apply yelp dataset to do text mining in R
This is a subset of Yelp's businesses, reviews, and user data.
Only focus on useful review in 2014 (the most recent data)


Text Pre-processing:
1.Lower Casing: Transform review text into lower case
2.Punctuation and stop words: Remove all punctuation and stop words in the review text 
3.Frequent and rare word: Remove selected frequent and rare words in the review text 
4.Tokenization: Dividing review text  into a sequence of words or sentences
5.Stemming: Remove suffices
6.Lemmatization: Converts review text  into its root word


Analysis:
1. Word Frequency Analysis: 
  For different restaurant cuisine, we could know what aspects customers most focus on the most frequent keyword (Unigram) in each cuisine.
2. Sentiment Analysis: 
  For different restaurants cuisine, food and service are important so I only do sentiment analysis on keywords “food” and “service”.
3. Bigram Analysis: 
  To get top ranking five star restaurants and related food they provide in each cuisine, I conducted bigram analysis on our review data.
  
This text analysis can help customers and business achieve the following goals:
Help businesses improve their strategy by reading reviews
Help business holders keep up with the popular cuisines and hot topics in the current catering industry
Help  food lovers target the restaurants and dishes to have a satisfactory experience

I also attach r files doing text analytics in order to be clear.
