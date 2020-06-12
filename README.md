# Airbnb Data Seattle!

<img src="https://www.visittheusa.co/sites/default/files/styles/hero_m_1300x700/public/images/hero_media_image/2017-03/f3d1f001ce1e4f874adc9a88fd9fb095.jpeg?itok=DHjISMr_">

This repository contains the study of Airbnb data, which has been provided to us by the Kaggle platform.  
This data will help us to answer 3 questions that we have about Airbnb in Seattle and I also encourage to get interesting data to all who are watching this repository.  

## Libraries
To start this repository contains the following libraries:
* **numpy** : The fundamental package for scientific computing with Python.
* **re** : The solution is to use _Python's_ raw string notation for _regular expression_ patterns.
* **pandas** :  fast, powerful, flexible and easy to use open source data analysis and manipulation tool, built on top of the _Python_ programming language.
*  **matplotlib.pyplot** : _Matplotlib_ is a comprehensive library for creating static, animated, and interactive visualizations in Python.
* **sklearn.linear_model (LinearRegression)** : Simple and efficient tools for predictive data analysis. Create Linear Regression .
* **sklearn.model_selection (train_test_split)** : Split of data in train and test.
* **sklearn.metrics (r2_score, mean_squared_error)** : Make a scorer from a performance _metric_ or loss function.
* **wordcloud (WordCloud, STOPWORDS, ImageColorGenerator)** : Generating _WordClouds_ in Python.
* **nltk** : leading platform for building _Python_ programs to work with human language data.
* **nltk.sentiment.vader (SentimentIntensityAnalyzer)** : Setiment Analyzer to split positive and negative.

## Files
This repository contains the following files :
* **calendar.csv** : File that contains the availability of each house along with cost depending on the date.
* **listings.csv** : File containing all the details of each house, such as number of beds, bedrooms, average price, type of availability, description.
* **reviews.csv** : File containing all the reviews of each house.
* **Seattle Airbnb.ipynb** : Notebook of jupyter, where is all the code that I have made with the due exits and all the comments of the obtained results.
* **requirements.txt** : It contains the requirements of all the libraries I have used.
## Motivation

Airbnb is a company that facilitates the rental of houses to third parties, obtaining an affordable accommodation for the taste of anyone.  
Therefore, this company has improved tourism to other countries and also gives the facility to register your house to get extra money.  
This repository is in charge of analyzing this data from Seattle 2016 and getting a better understanding of the situation of Airbnb in Seattle and the possible variables that can make your rental go better.


## Summary of results

The interesting data that I have obtained when analyzing these data has been that the neighborhoods in which you put your house to rent is very important since this influences that the visitors want to go to your house, since some neighborhoods have low levels of occupation of houses and in addition they received serious critics of the bad state of the neighborhood and to have been conflicting.  
Another important fact is that the temporal evolution of Airbnb in these data is very worrying because the evolution is decreasing constantly as a function of time, but has a season of rebound that helps the business is not at risk. These upturns will be made in clear seasons of increased tourism in Seattle, another thing to keep in mind is that the type of room you rent has much to do with the demand for that house, because if you rent a whole house has a high demand but if you rent a shared room has a very low value.  
Finally, I wanted to find out if there was a correlation between the characteristics and the price of the apartment and thus obtain which variables give greater value, namely the price of a rent in airbnb and therefore, I analyzed that if the room is shared, it is normal that if a room is shared the price of it is lower than a complete house.  
And another factor to take into account was that the price of the house also has a correlation with the neighborhood you are in and the number of bathrooms and beds you have.
