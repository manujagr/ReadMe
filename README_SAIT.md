# Sentiment Analysis in Trading

In this course, you have learned how to code to create an API object, fetch tweets,  in Python. You have also calculated Beta, expected returns using the Fama French three-factor model and created a strategy using momentum and short-term reversal factors in Python. All these codes are provided in this downloadables folder.

## This readme file has the following sections:
1. Prerequisites
2. Installing packages
3. Running the code
4. Folder structure
5. Authors

## Prerequisites:
Before running these notebooks, you need to setup a Python environment on your local machine. If already present, make sure the Python version is 3.6.8. To change the Python version, open the Anaconda prompt and type the following command: 

	conda install python=3.6.8

## Installing packages:
We have used the following Python libraries in the course. Kindly ensure you have these libraries installed with the same versions as mentioned below. To install the same version on your local system, type these commands on IPython notebook.

	!pip install tabulate==0.8.2
	!pip install tweepy==3.7.0
	!pip install vaderSentiment==3.2.1
	!pip install botometer==1.3
	!pip install webhoseio==0.5
	!pip install nltk==3.4
  
## Running the code:
Once you have your system in place, you can run the notebooks using Jupyter interface and Python codes using the Spyder Interface. This is installed along with Anaconda. You need to update the API keys for the following in the 'sentiment_analysis_quantra.py' file in each folder given below. Kindly fetch the API keys according to the instructions provided in the corresponding PDFs. You can then paste the keys in the respective functions

Functions:
1. get_twitter_tokens() - Get the Twitter API keys by following the steps given in the 'Get Twitter API Keys - Guide.pdf' and 		   paste in this function
2. get_rapid_api_key() - Get the Rapid API key by following the steps given in the 'Get Botometer API Key - Guide.pdf' and paste 	    in this function
3. get_webhoseio_key() - Get the Webhoseio API key by following the steps given in the 'S12 Fetching news articles.ipynb' under 	   'Getting API key'

## Folder structure:
This folder contains 8 subfolders divided based on the sections of the course. Each subfolder contains the IPython notebooks, Python codes and the data required to run them in that particular section.

	1. Know the Twitter API:
		a. Create an API object.ipynb
		b. sentiment_analysis_quantra.py

	2. Coding in Python to get tweets:
		a. Section 5-1 Fetch Tweets Search Method.ipynb
		b. Section 5-2 Fetch Tweets by User _ Date Range.ipynb
		c. sentiment_analysis_quantra.py
		
	3. Cursor method:
		a. Section 6 Cursor Method.ipynb
		b. sentiment_analysis_quantra.py

	4. Identify and remove twitter bot accounts:
		a. Section 7-1 Identify Bot Accounts.ipynb
		b. Section 7-2 Identify Bot Accounts - Strategy.ipynb
		c. Tweet IDs Sample.xlsx
		d. sentiment_analysis_quantra.py

	5. Calculating sentiment score in Python:
		a. Section 10-1 VADER - Add New Words.ipynb
		b. Section 10-2 VADER - Practice.ipynb
		c. Section 10-3 VADER Score Calculations - Strategy.ipynb
		d. Prices_AMZN.xlsx
		e. Tweet IDs Sample.xlsx
		f. sentiment_analysis_quantra.py

	6. Building the strategy:
		a. Twitter Sentiment based Trading Strategy_Jan _1-7.ipynb
		b. Twitter Sentiment based Trading Strategy_Jan _8-12-Copy1.ipynb
		c. daily_sentiments.csv
		d. Prices_AMZN.xlsx
		e. Tweet IDs Nov18 to Jan19.xlsx
		f. sentiment_analysis_quantra.py

	7. Qualitative analysis:
		a. Fetching news articles .ipynb
		b. Qualitative Analysis.ipynb
		c. sample_apple_data.xlsx
		d. sentiment_analysis_quantra.py

	8. Challenges in calculating sentiments of news:
		a. S13 Calculating sentiments of news articles.ipynb
		b. sentiment_analysis_quantra.py
	
	9. twitter_on_IB.py:
		Twitter sentiment based trading model to deploy on Interactive Broker's TWS using IBridgepy. 
		Place this file in the Strategies folder of the IBridgepy Installation folder. 
		Update the bar frequency, repBarFreq = 60 in the RUN_ME.py file in the IBridgepy Installation folder
	
## Author:
Quantra by QuantInsti
