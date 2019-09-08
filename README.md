# Austin AirBnB Data Analysis


### Team Members:
Quynh Tran, Ryan Burdick, Jesse Dymond & Upendra Addepalle

### Project Description:
We will be analyzing AirBnB data to find trends in Austin

### Research Questions to Answer:
* Are ratings influenced by proximity or neighborhood. 
* Are there ertain neighborhoods that have higher concentration of rentals. 
* Does higher ratings indicative of price of a rental.
* What percent of room types are offered in a neighborhood.
* What percent of room types are more popular in a neighborhood
* Determine demand in any given month.
* Is Airbnb popularity increasing in the Austin area.
* What rental types are most popular/available


### Datasets to be Used:

<a href="http://insideairbnb.com/get-the-data.html" target="_new">Austin, Texas, United States</a>
The primary data used for our analysis of Airbnb consisted  of zip codes, pricing, reviews, and type of room. The data was gathered from csv files specific to Austin Airbnb on their website. 


### Breakdown of Tasks

* Get the Calendar Data
* Analyze Calendar by year month and average price
* Analyze the same during a weekday
* Get the reviews data and analyze it by count of reviews and year
* Analyze reviews by each room type offered.
* Get the listings data and analyze it by zip code grouped by room type offered
* Analyze listings by price, room type and zipcode
* Check the reviews by month
* Plot the neighborhoods in gmaps using geo coordinates and number of reviews
* Highlight the most popular neighborhood.
* Analyze the reviews based on the avegage price of a listing.


![Alt text](images/Airbnb_pricing_trend_in_a_given_month.png?raw=true "Title")

We can see that the average prices are consistent over the months except for March where average prices for Airbnb prices is the highest. It could be due to the fact that South By South West (SXSW) happens in March

![Alt text](images/Airbnb_weekday_pricing.png?raw=true "Title")

* As you would expect, Friday and Saturday are the most expensive days of the week! 
* With prices slightly higher on Thursday than Sunday  that could mean that more people are willing to take off Friday from work than a Monday to extend their weekend. 

![Alt text](images/Year_vs_Number_of_Reviews_for_Austin_AirBNB.png?raw=true "Title")

Our dataset did not specifically list the number of bookings so we used the number of reviews for each year to show the popularity of Airbnb in Austin increasing quite dramatically year over year from just under 20,000 in 2014 to a projected 120,000+ in 2019

![Alt text](images/Average_Number_of_Reviews_for_each_Room_Type.png?raw=true "Title")

Renting the Entire Home/Apt was by far the most available and reviewed room type in Austin

![Alt text](images/Stacked_bar_Chart_01.png?raw=true "Title")

Zipcode 78704 has the most listings and also can be seen in shaded area on the heat map below.

![Alt text](images/Stacked_bar_Chart_02.png?raw=true "Title")

The most expensive zip code (78746) relates to the West Lake Hill area of Austin, TX

![Alt text](images/Bar_Chart_Ratings_in_month_03.png?raw=true "Title")

* The number of reviews in each month is pretty consistent across the board except for lower counts in February and higher counts in October. 
* The F1 race typically takes place in October of each year so that is a potential explanation of the October increase. 

![Alt text](images/Geo_Plot_Austin_and_neighbourhood_popular.png?raw=true "Title")

Zipcode 78704 has the most listings and is the shaded area on the heat map

![Alt text](images/Geo_Plot_Austin_and_neighbourhood.png?raw=true "Title")

Heat Map of Zip Codes and Ratings


## Conclusion
* Through our combined analysis it was interesting to see that things you would assume about Austin Airbnb such as the downtown area having the most listings, prices being higher on the weekend, and the overall popularity of the service increasing were confirmed by the data available. 

* Although (78746) the West Lake Hills area is the most expensive, it had a relatively low number of listings for the area. 
The number of reviews in each month could be used to estimate demand for rentals and be very beneficial in terms of maximizing the price you list your rental for in each month if you are on the renting side of the transaction. 

* If you are visiting the Austin area, you may get a better deal for an extended weekend if you book Saturday – Monday rather than Thursday – Sunday.

* Some of the finding were inconclusive because of the bias of reviews did not contain factual data of statisfactory index in a specific neighborhood, but overall it seems to become more and more popular alternative to visit Austin.

## Disclaimer: 
This is not real travel advice and to be biased to a particular neighborhood. Its serves a means to understand data available from AirBnB and how it affects the perspective of a Trend in Rentals.
