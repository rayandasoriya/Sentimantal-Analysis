Sentimental Analysis (Twitter)
=========

This tool is an implementation of the Twitter Sentiment analysis tool as described on [Laurent Luce's blog][1].

Pre-requisites
------------
The project requires the nltk package for Regression and Naive Byes tools.

Usage
----------

1. Clone this project
```
git clone git://github.com/rayandasoriya/Sentimental-Analysis.git
```
2. Install NLTK (if it is not installed)
```
pip install nltk
```
3. Run the classifier
```
python classifier.py
```

Training data
-------------

The training data for this project is scraped using the Twitter Search API with the help of keywords like 
`I am happy` and `I am sad` for happy (positive) and sad (negative) tweets.
There are 160 tweets used for training (80 / 80 distribution).

If you want to add more training data, add in new _happy_ tweets to `happy.txt` and _sad_ tweets
to `sad.txt` using one line for each new tweet.


Test data
---------

Test data are separated into `test_happy.txt` and `test_sad.txt`. A total of
20 tweets are used for the test (10 / 10 distribution).

To add more test data, add in new _happy_ tweets to `test_happy.txt` and _sad_
tweets to `test_sad.txt` using one line for each new tweet.

Result
---------
With the use of the above-mentioned data, we have calculated the accuracy of the sentimental analysis to be 90% which can be further improved with the use of some different packages and tools.

Wish you a **Happy Programming**

[1]: http://www.laurentluce.com/posts/twitter-sentiment-analysis-using-python-and-nltk/

