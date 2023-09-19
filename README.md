# Airbnb Exploratory Data Analysis 

Airbnb is a for-profit service that links homeowners with travellers searching for lodging. Airbnb encourages its hosts to set the pricing for their units with the aid of a few guidelines that allow hosts to compare their listings to others in the area to decide a reasonable price.

This exploratory data analysis showcases area traffic, different comparison between prices and localities in the New York region. This study also gives relationships between parameters such as reviews, minimum nights spent and prices spent by travellers in comparison to selective locality in New York.

As a result, the most popular and busy area observed is Manhattan, with average price of $150 , “Entire home/Apt” or “Private Room” in room listing type. Generally travellers prefer to stay in areas with lower prices.

To obtain above conclusions data analysis is done by grouping and sorting relevant parameters. For behavioural observations different plots have been marked. This EDA challenges hosts and Airbnb to focus on most traffic making areas and how they can improve business in least busy areas.
Data Summary

__All columns and type of information stored in the csv file is as follows__

* Id -unique id in the dataset
* name- name which is listed on Airbnb as “home/apt”,” private room”,” shared room”
host_id- unique id of the host in Airbnb Dataset
host_name- name of host
Neighbourhood_group - areas in New York
Neighbourhood - sub-areas that are located inside areas
latitude- location latitude on Earth's surface
longitude- location longitude on Earth's surface
room_type- listed room type [‘home/apt’, ’private room’, ‘shared room’]
price- price per night
minimum_nights - sub areas which are located inside areas
number_of_reviews- total count of reviews for listed name
last_reviews- last reviews for listed name
Reviews_per_month - reviews received per month
calculated_host_listings_count - count of total number of listings for that host
availability_365 - number of available days in a year (365 Days) 

### Conclusions

Airbnb is a for-profit service that links homeowners with travellers searching for lodging. Airbnb encourages its hosts to set the pricing for their units. This study gives relationships between parameters such as reviews, minimum nights spent and prices spent by travellers in comparison to selective localities in New York.

To do exploratory data analysis, we have received 49000 rows and 16 columns of csv data from Airbnb New York. Airbnb is interested in learning more about its services and service providers. We can see the data details in the data summary.

We used Numpy, Pandas, Matplotlib, Seaborn, and Folium packages for this EDA. The first inspection was performed after importing data into Pandas. We discovered some missing values. Then we cleaned up the data because missing values are treated as integer 0.

This EDA concentrated on the busiest and least busy areas, as well as hosts. We also targeted traffic in various areas. We plotted this traffic on a street view map using latitude and longitude data. We discovered the most and least preferred room types. We also learned about prices, areas, and reviews from the provided dataset.

_These are the important conclusions made out of this EDA._

The properties have large differences in prices.
Separating the dataset by price categories is useful for the analysis.
The most interesting variables regarding price prediction are:
Location
Room type
calculated_host_listings_count
Number of review
Price prediction models are not performing well
Best score is 0.55
Prediction are nore accurate for price under $175 (75% of the dataset)
Using categorical ecnoded data did not improve the model
Possible next steps
The next step could be to transform continuous variables into categorical variables as it can help capture non-linear relations.
I doubt a neural network would be useful here because the number of observations is limited.
