#  Seattle Airbnb Dataset

## Table of Contents

1. Installations
2. My Project Motivation
3. File Descriptions
5. Summary
5. Acknowledgements

### Installations

1. Collections
2. Matplotlib
3. NLTK
4. NumPy
5. Pandas
6. Seaborn
7. Sklearn

### My Project Motivation

Choosing the Seattle Airbnb dataset, I would like to have better understanding of this data by answering the following questions:

Understandings of Price Seasonal and Usage trend:
    1. Indicating the seasonal pattern of Price and Accommodation Usage trend?
    2. Which neighborhoods the price reach the highest and lowest in a year?
    3. How does property types within neighborhoods impact price for the most expensive neighborhoods and most common property types?
Price Prediction
    4. Can we predict price for a given listing? What factors of the listing correlate best for predicting price?


### File Descriptions

The Jupyter notebook displays the analysis performed to investigate the dataset, including preparing and managing data, and constructing prediction models to address the questions posed. Markdown cells are used to document the steps taken and communicate the results of each analysis.
The seattle folder contains the dataset from Kaggle (https://www.kaggle.com/airbnb/seattle). It contains 3 files:
* calendar.csv: calendar availability of listings and price
* listings.csv: information about all the available listings
* reviews.csv: listing reviews by the users

### Summary Of The Results

* The peak months of the price were june, july and august. The price reached the highest in August.
* The highest number of bookings was in January, following by July and August.
* Neighborhood had the highest price was Southest Mangolia, followed by Portage Bay, Westlake, West Queen Anne, Montlake
* Neighborhoods had the lowest price was Rainer Beach, followed by North and South Delridge, GeorgeTown, Olympic Hills.
* Mainly focus the highest-priced neighborhoods listed in the previous analysis and primarily focusing on houses and apartments as they constitute a significant proportion of the property types.
* Portage Bay has the most expensive houses, followed by West Queen Anne and Westlake. Besides, in Westlake, both houses and apartments are priced similarly.
* The combination of host details and descriptive information about the listing such as host_name, has_availability, transit, space, host_about, notes, neighborhood_overview etc has the most impact on the price.
 

### Acknowledgements

Credit to the AirBnB dataset published by AirBnB and Kaggle for hosting it, the dataset here: https://www.kaggle.com/airbnb/seattle
