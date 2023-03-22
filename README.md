# sentiment_analysis
Sentiment Tweet Analysis
This repository contains code for performing sentiment analysis on tweets. The code is written in Python and utilizes several popular libraries such as NLTK, TextBlob, and Pandas.

Installation
To use this code, you will need to have Python 3 installed on your machine along with the following libraries:

NLTK
TextBlob
Pandas
Tweepy
You can install these libraries using pip, for example:


pip install nltk textblob pandas tweepy
Usage
Clone this repository to your local machine.

Navigate to the root directory of the repository and create a new file called config.py. In this file, add your Twitter API credentials in the following format:

python

CONSUMER_KEY = 'your_consumer_key'
CONSUMER_SECRET = 'your_consumer_secret'
ACCESS_TOKEN = 'your_access_token'
ACCESS_TOKEN_SECRET = 'your_access_token_secret'
Run the sentiment_analysis.py script using the command:

python sentiment_analysis.py
This will prompt you to enter a keyword or phrase to search for on Twitter. Once you have entered your search term, the script will retrieve a list of tweets containing that term and perform sentiment analysis on each tweet.

The sentiment analysis results will be displayed in the console and saved to a CSV file in the data directory.

Contributing
If you would like to contribute to this project, please open an issue or submit a pull request. We welcome contributions from the community.

License
This project is licensed under the MIT License - see the LICENSE file for details.
