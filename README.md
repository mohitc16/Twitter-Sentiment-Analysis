# Twitter-Sentiment-Analysis
The goal of this project was to predict sentiment for the given Twitter post using Python. Sentiment analysis can predict many different emotions attached to the text, but in this report only 2 major sentiments were considered: positive and negative. The training dataset was quiet large(around 99989 examples) and the data within it was highly skewed, which greatly impacted on the difficulty of building good classifier. After creating a lot of custom features, utilizing bag-of-words representations and applying the Random Forest Classifier algorithm, the classification accuracy at level of 72% was achieved.
Data was pre-processed using pandas, nltk and numpy libraries and the learning/validating process was built with scikit-learn.

