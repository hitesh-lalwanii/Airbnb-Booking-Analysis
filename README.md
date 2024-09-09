# Airbnb-Booking-Analysis
Exploratory Data Analysis of Airbnb NYC 2019 data

## Project Overview 

This project involves the exploration and analysis of an Airbnb dataset containing approximately 36,334 observations and 16 columns. The dataset is a mix of categorical and numeric values, and the analysis aims to uncover key insights that can aid in various business decisions. These insights can be used to enhance security, guide marketing strategies, improve customer and host experiences, and support the implementation of innovative services on the platform.


## Business Context 

Since its inception in 2008, Airbnb has revolutionized the way people travel, offering unique and personalized experiences around the world. With millions of listings available globally, data analysis has become a critical tool for understanding customer and host behavior, driving business decisions, and ensuring the platform's continued growth and security.

This project focuses on analyzing Airbnb listing data to uncover trends and patterns that can inform business strategies, optimize operations, and enhance the overall experience for both guests and hosts.


## Objectives 

The main objectives of this project are :

1. Understand the key factors that influence pricing and customer behavior on Airbnb.
2. Identify popular neighborhoods and room types that are in high demand.
3. Provide actionable insights that can be used to enhance Airbnb’s marketing strategies, improve customer satisfaction, and optimize host performance.
4. Highlight any potential security concerns or risks based on the data that could hinder business growth.
5. Offer insights and recommendations to overcome obstacles impeding business growth and to enhance revenue and efficiency.


## Dataset Description



The dataset used in this project includes the following fields:

- id: Unique identifier for the listing
- name: Name of the listing
- host_id: Unique identifier for the host
- host_name: Name of the host
- neighbourhood_group: Location of the listing (broader area)
- neighbourhood: Specific area within the broader location
- latitude: Latitude coordinate of the listing
- Longitude: Longitude coordinate of the listing
- room_type: Type of listing (e.g., entire home/apt, private room, shared room)
- price: Price of the listing per night
- minimum_nights: Minimum number of nights required for booking
- number_of_reviews: Total number of reviews received by the listing
- last_review: Date of the last review
- reviews per month 
- calculated host listing count
- availability 365


#### Libraries used 

The following Python libraries are used for data analysis and visualization:

- Pandas: For data manipulation, aggregation, and cleaning.
- NumPy: For efficient numerical operations and calculations.
- Matplotlib: For creating static visualizations of the data.
- Seaborn: For creating more advanced and aesthetically pleasing visualizations.

## Methodology 

### Data Wrangling 

- Dropping Null Values - Dropped all null values from the following columns: name,     host_name, last_review, and reviews_per_month.

  


- Data Type Conversion -: Converted the last_review column to a datetime object.




- Dropping Irrelevant Columns -: Latitude and Longitude


- Final Dataset - : After data wrangling, the data frame now contains 30,510 rows and 14 columns.



## Analysis and visualization 

The project includes a thorough exploratory data analysis (EDA) to identify patterns, trends, and outliers within the dataset. At least five different types of visualizations are used to understand the distribution of data, correlations between variables, and behavior concerning the target variable (e.g., price or number of reviews). These visualizations may include:


- Bar Charts: To analyze categorical data, such as room type, neighborhood group and neighborhood.
- Pie Chart: To show the percentage of room type availability
- Heatmaps: To visualize correlations between multiple variables.
- Box Plots: To identify some bunch of numbers like how much availability of room type of AIRBNB in each and every neighbourhood group.
- Pair plot - : A pairplot can be a valuable tool for data analysis when trying to understand and analyze the relationships between different variables and identify patterns and trends in the data.


## Solution to Business Objective 

### 1. High Pricing with Low Bookings
Certain hosts have less than 5 bookings per year but charge a high booking amount. The company should investigate these listings or consider removing them to ensure fair pricing.

### 2. Neighbourhood Analysis
I have found the total number of Airbnb listings in each neighbourhood group. **Staten Island** has the fewest listings. The company should identify the reason for this and consider building more Airbnbs with the most preferred room type at reasonable prices.

### 3. Host Engagement and Sentiment Analysis
The top 5 most engaged hosts, who received the highest number of reviews, were identified. The company should perform sentiment analysis to determine whether these reviews are positive or negative. If most reviews are negative, the company should remove or address the listings with the most negative feedback by contacting the host to resolve any issues.

### 4. Room Type Demand
I identified which room type is the least available (most popular) in each neighbourhood group. The company should build more Airbnbs featuring these popular room types.

### 5. Host Rewards
After sentiment analysis, hosts who have received more positive reviews should be rewarded. This will encourage hosts to further improve the quality of their Airbnbs.


## Conclusion 

From Above analysis I conclude that

- Amoung all different area Manhattan and Brooklyn has maximum airbnb and Staten Island has least airbnb.

- On a average Entire Home/ Appartment is most loved category among visitors.

- Maya is considered to be as most engaged host ( Most number of reviews)

- Price which airbnb offer in Manhattan is more than others.







