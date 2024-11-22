#  Seattle Airbnb Data Analysis & Predictions

## Table of Contents

1. [Installations](#installations)
2. [Purposes](#purposes)
3. [Descriptions](#descriptions)
4. [Summary](#summary)
5. [Acknowledgements](#acknowledgements)


### Installations

1. Collections
2. Matplotlib
3. NumPy
4. Pandas
5. Sklearn - linear regression model & metrics
6. Operating System (os)

### Purposes

The Seattle Airbnb Dataset (including listings.csv, calendar.csv, reviews.csv) list up AirBnB accommodations in Seattle, their availability and Airbnb users' reviews. Paying attention on this dataset, I set the following problems to be addressed in this notebook and presented on blogspot:

Understandings of Price Seasonal and Usage trend:
1. Highlighting the seasonal patterns in pricing and accommodation usage trends?
2. Which neighborhoods experience the highest and lowest prices throughout the year?
3. How do property types within neighborhoods influence prices, particularly in the most expensive neighborhoods and for the most common property types?

Price Prediction

4. Can we develop a model to predict the price of giving current list of accommodations & reviews?
5. Which listing factors show the strongest correlation with price?


### Descriptions

The Jupyter notebook showcases the analysis conducted to explore the dataset, including data preparation, management, and the creation and evaluation of predictive models to answer the posted questions posted.

For a detailed breakdown of the results, please refer to this blog (https://bnaduy.blogspot.com/2024/11/interesting-findings-of-seattle-airbnb.html).

The "Seattle" folder contains dataset from Kaggle (https://www.kaggle.com/airbnb/seattle) in "Seattle.zip", which includes three files:

* calendar.csv: Contains the availability and pricing of listings.
* listings.csv: Provides details about all available listings.
* reviews.csv: Includes user reviews for the listings.

### Summary

* The peak pricing months were June, July, and August, with August recording the highest prices.
* The highest volume of bookings occurred in January, followed by July and August. The lowest volume occured in Dec
* The neighborhood with the highest prices was Southeast Magnolia, followed by Portage Bay, Westlake, West Queen Anne, and so on. Meanwhile, the neighborhoods with the lowest prices were Rainier Beach, followed by North and South Delridge, Georgetown, and so on.
* Focus was given to the highest-priced neighborhoods, primarily analyzing houses and apartments as these are the most common property types.
* Portage Bay has the higest average house price, followed by West Queen Anne and Westlake. In Westlake, the average price of both houses and apartments are similar.
* The coefficient analysis shows that the most positive influential factors on the price were a combination of host details and descriptive listing information, including fields such as host acceptance rate, room type (entire or private room) where negative factors example are city of Seattle.

### Acknowledgements

The dataset was published by AirBnB and Kaggle follow this link `https://www.kaggle.com/airbnb/seattle`
