# Airbnb_2019_NYC
**The Airbnb EDA of dataset Provided by ALMABETTER of year till 2019 data of country NYC.**

EDA or exploratory data analysis - where we will analyze the data using charts & statistics [if necessary]. This can help us finding valuable insights that we can use to make decisions that will help our organization to increase their profits.


**PROBLEM STATEMENT :** Objective:Analyze the Airbnb NYC 2019 dataset to discover key insights that can help in understanding customer and host behavior, inform business decisions, and identify trends in the listings.

**BUSINESS OBJECTIVE:** Airbnb is a platform that connects travelers with hosts offering unique accommodations. With millions of listings, data analysis is crucial for security, business decisions, understanding user behavior, and enhancing the service.

**All Steps Done : I Divided this EDA Project in 9 STEPS.**

**Step 1: Problem Statement:** Analyze the Airbnb NYC 2019 dataset to discover key insights that can help in understanding customer and host behavior, inform business decisions, and identify trends in the listings.

**Step 2: Business Context:** 
Entire homes & private rooms are the majority of listings. Seems like private rooms & entire homes are in demand
Majority of listings lie between latitudes - 40.65 - 40.75. If you want to advertise your flat you can do it in these locations
The majority of listings lie in longitude ranges - 74-73.9. this can help us to find where we should advertise our flats to rent
The majority of listings have 0 to 10 min nights, there's also a considerable number of 30 minimum nights. 0 to 10 minimum nights & 30 nights package seems to be the industry standards
the majority of listings are available for 0-100 days per year , mosIf you're starting a rental business , then it's advisable to make it available for weekends.t likely weekends [52 weeks per year i.e. 52 weekends i.e. around 100 days]. There are also a lot of listings that are available almost entire year.
Staten Island & Manhattan are the most expensive , then Bronx & brooklyn. If you want to set up a high end apartment for rent theses are the places to do so - Staten islands , manhattan
the prices & number of listings seems to be higher between latitudes 40.6 - 40.8. For advertising and setting up your rental business , the above latitude range is the best
Majority of listings lie between longitude -74 to -73.9. The graph shows that the longitude range above has the highest number of renting opportunities & its the best for advertising.


**Step 3: Data Understanding :** 
This step involves importing the dataset, & gaining some preliminary information. Used functions like describe() , info() to gain insights on the variables. Also found unique values per variable. The datset which Almabetter provided us to Do Project is the Airbnb Dataset of New York of the booking or review till yearr 2019. The dataset contains around 49,000 observations and 16 columns, with a mix of categorical and numeric values. The columns likely include information such as listing ID, name, host ID, neighborhood, room type, price, minimum nights, number of reviews, last review date, reviews per month, number of listings per host, availability, and more.


**Step 4: Data Loading and Cleanup :** this step involves cleaning the data so that it becomes fit for analysis. Includes imputing missing values , removing useless columns. For imputing , we used median [for numerical variables] & ‘null’ [for categorical variables] 

**Step 5: Listing Hypothesis/Assumptions** ( IF ANY NEED) : Price Distribution: Prices vary significantly across different neighborhoods.

Room Type Popularity: Certain room types (e.g., entire home/apartment) are more popular.

Host Activity: Most active hosts have multiple listings.

Review Patterns: Listings with more reviews tend to be more frequently booked

Availability: Listings with higher availability might be less popular or newly listed.

Till then Executed STEPS 1,2,3,4 Till now

**Step 6: Visualizations :** here Done on the Data Visualization Part of Step 6 On the DATASET OF AIRBNB
    Price Distribution Across Neighborhoods: (1) **BOXPLOT**
    Room Type Distribution: (2) **COUNT CHART**
    Number of Listings per Host: (3) **HISTOGRAM** 
    Reviews per Month: (4) **SCATTER PLOT**
    Availability by Neighborhood: (5) **BOXPLOT**

**Step 7: Statistical Analysis :** ANOVA: Helps understand if neighborhood influences the price significantly.
Chi-Square Test: Helps identify if the distribution of room types varies by neighborhood
This statistical analysis provides a solid foundation for drawing insights from the data and supports decision-making processes.

**Step 8: Remarks for Each Analysis :** Price Distribution: Significant price variation exists across different neighborhoods, with Manhattan having the highest median prices.

Room Type Distribution: Entire homes/apartments are the most common type of listing.

Number of Listings per Host: The number of Listing per host is started decline after the First 50 to 100 Users

Reviews per Month: The Reviews are Done in the First 10 Days As maximum Users done reviewing the apartment of almost 400+ users as you can in the scatter plot

Availability by Neighborhood: In the Availability by neighborhood the 'Manhatten' & 'Brooklyn' is Booked and not available in the span of year. Whereas the states like 'Staten island' & 'Bronx' are Available in the Neighborhood still the 'Queens' is like Booked and Availble most of the same Time as 'Queens' is said to be busy in the Festivle periods.

The Data Can be Seen the Diffrent forms of Visualization in UBM Rule 
(a) Univariate Analysis - Univariate analysis explores each variable in a data set, separately. It was done on neighborhood group & neighborhood, Count of room type , Latitude , longitude, minimum nights, availability 365.
 (b) Bivariate Analysis - Avg Price per neighborhood group & neighborhood, Price vs latitude,Price vs longitude,Avg price per room_type,Price vs minimum nights, avg Availability per room type, Availability per neighborhood group [& neighborhood].


**Step 9: Conclusion of the Project:**

Summarizing the key insights and their implications for Airbnb:
Pricing strategies might need to be neighborhood-specific.

Marketing efforts could focus on promoting less popular room types or areas.

Hosts with multiple listings contribute significantly to the platform's supply.

Reviews are crucial for understanding listing popularity and guest satisfaction

The dataset contains around 49,000 observations and 16 columns, with a mix of categorical and numeric values.

The columns likely include information such as listing ID, name, host ID, neighborhood, room type, price, minimum nights, number of reviews, last review date, reviews per month, number of listings per host, availability, and more.

DONE.
