#  Seattle Airbnb Dataset

## Table of Contents

1. [Installations](#installations)
2. [Motivation](#motivation)
3. [Descriptions](#descriptions)
4. [Summary](#summary)
5. [Acknowledgements](#acknowledgements)


### Installations

1. Collections
2. Matplotlib
3. NLTK
4. NumPy
5. Pandas
6. Seaborn
7. Sklearn

### Motivation

To gain a deeper understanding of the Seattle Airbnb dataset, we can explore and answer several key questions related to the data:

Understandings of Price Seasonal and Usage trend:
1. Highlighting the seasonal patterns in pricing and accommodation usage trends?
2. Which neighborhoods experience the highest and lowest prices throughout the year?
3. How do property types within neighborhoods influence prices, particularly in the most expensive neighborhoods and for the most common property types?

Price Prediction

4. Can we predict the price of a given listing? Which listing factors show the strongest correlation with price?


### Descriptions

The Jupyter notebook showcases the analysis conducted to explore the dataset, including data preparation, management, and the creation of predictive models to answer the questions posed. Markdown cells are utilized to document the processes and present the results of each analysis.

For a detailed breakdown of the results, please refer to this blog (https://bnaduy.blogspot.com/2024/11/interesting-findings-of-seattle-airbnb.html).

The "seattle" folder contains the dataset from Kaggle (https://www.kaggle.com/airbnb/seattle) and includes three files:

* calendar.csv: Contains the availability and pricing of listings.
* listings.csv: Provides details about all available listings.
* reviews.csv: Includes user reviews for the listings.

### Summary

* The peak pricing months were June, July, and August, with August recording the highest prices.
* The highest volume of bookings occurred in January, followed by July and August.
* The neighborhood with the highest prices was Southeast Magnolia, followed by Portage Bay, Westlake, West Queen Anne, and Montlake.
* The neighborhoods with the lowest prices were Rainier Beach, followed by North and South Delridge, Georgetown, and Olympic Hills.
* Focus was given to the highest-priced neighborhoods, primarily analyzing houses and apartments as these are the most common property types.
* Portage Bay has the most expensive houses, followed by West Queen Anne and Westlake. In Westlake, both houses and apartments are similarly priced.
* The most influential factors on price are the combination of host details and descriptive information about the listing, such as host details and descriptive listing information, including host acceptance rate, host response time, property type, bed type.

### Acknowledgements

Thanks to the AirBnB dataset published by AirBnB and Kaggle, the dataset link is ttps://www.kaggle.com/airbnb/seattle
