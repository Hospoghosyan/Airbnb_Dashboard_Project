## As a BI Analyst, i aim to provide a comprehensive, user-friendly interface that integrates various data sources, delivering actionable insights that align with the company's objectives and drive continuous improvement.


## About Dataset
##### New York City Airbnb Data Cleaning

Airbnb, Inc is an American company that operates an online marketplace for lodging, primarily homestays for vacation rentals, and tourism activities. Based in San Francisco, California, the platform is accessible via website and mobile app. Airbnb does not own any of the listed properties; instead, it profits by receiving commission from each booking. The company was founded in 2008. Airbnb is a shortened version of its original name, AirBedandBreakfast.com.


##### Context

Since 2008, guests and hosts have used Airbnb to travel in a more unique, personalized way. As part of the Airbnb Inside initiative, this dataset describes the listing activity of homestays in New York City

##### Content

The following Airbnb activity is included in this New York dataset:

Listings, including full descriptions and average review score Reviews, including unique id for each reviewer and detailed comments Calendar, including listing id and the price and availability for that day


## First, I cleaned the data using Python and handled missing values.Then through Python I connected to the Postgresql database, created tables there, and then in PowerBi I connected to the PostgreSQL database and created a Dashboard.

## Main Page
The main page features filters and primary visualizations that provide an overview of the data. In addition to the visualizations, there are cards displaying key metrics.

### Filters:

Cancellation Policy
Neighborhood
Room Type
Availability (0 to 365 days)
Price ($50 to $1200)
### Key Metrics:

Total Reviews: 3M
Total Houses: 102.06K
Average of Reviews per Month: 1,16
### Visualizations:

* Average of Price by Neighborhood: A bar chart showing the average prices in various neighborhoods.
* Total Neighborhoods by Group: A pie chart displaying the distribution of neighborhoods by group (Manhattan, Queens, Staten Island, Bronx, Brooklyn).
* Top 10 Houses by Total Reviews: A bar chart listing the top 10 houses based on the number of reviews.
* Total Listing by Neighborhood and Room Type: A bar chart showing the distribution of listings by neighborhood and room type (Entire home/apt, Hotel room, Private room, Shared room).
* Average Price by Neighborhood Group and Room Type: A table showing average prices by neighborhood group and room type.
* Total Houses by the Construction Year: A bar chart showing the total number of houses built per year.

![image](https://github.com/user-attachments/assets/5e76a76c-e5b0-4c44-8a81-8b5b5f2d6b84)

## Listings Page
### The listings page has filters, a table and a map. The size of the Bubble on the map shows the average house price at that location

![image](https://github.com/user-attachments/assets/a1557bb3-22ee-4181-83b8-ae279db3daf2)

### If we click on Bubble, the table will display information about this datapoint and if we just hold the mouse on the Bubble, information will also be displayed for the given datapoint, which by the way I created with a tooltip

![image](https://github.com/user-attachments/assets/1adfe1bf-6b0f-4ffb-97a2-a49d6d55324e)

## Neighbourhoods Page
![image](https://github.com/user-attachments/assets/92578c64-546f-4701-bd0b-07ed307c5e97)


## KPI Page
![image](https://github.com/user-attachments/assets/b38bc158-4dc1-42c3-b99a-376f9a860eac)

![image](https://github.com/user-attachments/assets/fc60c134-3b39-4a31-b4e8-b114cbdce0f1)
