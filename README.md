## NYC Airbnb Exploratory Data Analysis

### Overview
### This dataset, sourced from Kaggle, contains detailed information about Airbnb listings in New York City. It includes various attributes of each listing, such as host information, geographic location, room types, pricing, and reviews. The data consists of 48,895 observations and 16 columns, featuring both categorical and numerical values. This dataset is useful for analyzing trends and patterns in user preferences and host behaviors in the New York City Airbnb market.

## Dataset Information
### Usability: 10.00
### License: CC0: Public Domain
### Expected Update Frequency: Never
### Tags: Hotels and Accommodations

## Project Objective
### The objective of this analysis is to explore the Airbnb market dynamics in New York City, focusing on occupancy rates, price distribution, and review patterns. This information can aid hosts in optimizing their listings and help guests make informed booking decisions.

## About this File
### The dataset can be utilized to explore various aspects of the Airbnb market in New York City. It includes information about listings, hosts, geographic location, room types, pricing, and reviews. This dataset is instrumental in understanding the dynamics of the short-term rental market and can aid in making informed decisions for both hosts and guests.

## Pre-Processing Steps
### Handling Missing Values:

### Filled missing values in the 'name' and 'host_name' columns with 'N/A'.
### Filled missing values in the 'last_review' column with 'N/A'.
### Filled missing values in the 'reviews_per_month' column with -1.

## Data Filtering:

### Focused on essential columns for analysis: 'neighbourhood_group', 'neighbourhood', 'room_type', 'price', 'minimum_nights', 'number_of_reviews', 'last_review', 'reviews_per_month', 'calculated_host_listings_count', and 'availability_365'.
### Datetime Conversion:
### Ensured the 'last_review' column is in datetime format for time-based analysis.

## Analysis and Visualizations
### Key Questions Explored

### Occupancy Rates:
#### Analyzed how room type, price, and minimum nights stay impact the occupancy rate across different neighborhoods in New York City.

### Price Distribution:
#### Examined the distribution of prices across various listings to understand the pricing trends.

### Trends Over Time:
#### Investigated the average price and number of reviews over time to identify seasonal patterns and trends in user engagement.

### Key Findings
#### Occupancy Rate by Neighborhood and Room Type:
### Visualized the occupancy rates across different neighborhood groups and room types.
### Shared rooms in Staten Island have the highest occupancy rate, while private rooms in Staten Island have the lowest.

### Conclusion
#### This exploratory data analysis of the NYC Airbnb dataset provides valuable insights into the short-term rental market in New York City. The pre-processing steps ensured data quality, and the analysis highlighted key trends in occupancy rates, price distributions, and review patterns. These findings can help hosts and guests make informed decisions in the Airbnb market.

### Future Work
#### Further analysis could include:

#### Sentiment analysis of review comments to gauge guest satisfaction.
#### Predictive modeling to forecast future trends in occupancy rates and prices.
#### Comparative analysis with other cities to benchmark New York City's Airbnb market.
