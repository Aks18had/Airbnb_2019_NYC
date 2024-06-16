# Airbnb_2019_NYC
**The Airbnb EDA of dataset Provided by ALMABETTER of year till 2019 data of country NYC.**

EDA or exploratory data analysis - where we will analyze the data using charts & statistics [if necessary]. This can help us finding valuable insights that we can use to make decisions that will help our organization to increase their profits.

**PROJECT SUMMARY :** 
* Airbnb, Inc. is an online marketplace for long & short term rental accomodations founded in 2008 by Brian Chesky, Nathan Blecharczyk, and Joe Gebbia.

* This Project will include all the process that is required to perform data analysis - Data Discovery & Understanding, Wrangling , visualization & statistical analysis when required.

* We analyzed the given dataset which had around 49000 listings. Our main objective is to find key factors that influence the properties listings & relationships between them. We will achieve this in various steps

* Data discovery - where we import the data & get some information about the data EDA or exploratory data analysis - where we will analyze the data using charts & statistics [if necessary]. This can help us finding valuable insights that we can use to make descisions that will help our organisation to increase their profits.

**PROBLEM STATEMENT :** Objective:Analyze the Airbnb NYC 2019 dataset to discover key insights that can help in understanding customer and host behavior, inform business decisions, and identify trends in the listings.

**BUSINESS OBJECTIVE:** Airbnb is a platform that connects travelers with hosts offering unique accommodations. With millions of listings, data analysis is crucial for security, business decisions, understanding user behavior, and enhancing the service.

 **MY Approach to the Problem Statement:**


* Understanding the Problem Statement: Clearly define the problem and identify the objectives of the analysis.

* Data Collection: Gather the relevant dataset, ensuring it is comprehensive and relevant to the problem at hand.Data Cleaning and Preprocessing: Prepare the data for analysis by handling missing values, correcting errors, and formatting it appropriately.

* Exploratory Data Analysis (EDA): Conduct a thorough analysis to understand the data's structure, relationships, and key characteristics & To Use visual tools to represent the data findings clearly and concisely.

* Solution to the Business Objective,Insights and Conclusion: To Draw meaningful Solutions From the Visualization and Statistical Data and some of the best  insights to  provide best Conclusion to this Project.


[1]**LET's BEGIN**

**Know Your Data** 

**IMPORTING Libraries**

**Dataset Loading**

**Dataset First View**

**Dataset Rows & Columns count**

**Dataset Information**

**Duplicate Values**

**Missing Values/Null Values**


**Data Understanding:** 
This step involves importing the dataset, & gaining some preliminary information. Used functions like describe() , info() to gain insights on the variables. Also found unique values per variable. The datset which Almabetter provided us to Do Project is the Airbnb Dataset of New York of the booking or review till yearr 2019. The dataset contains around 49,000 observations and 16 columns, with a mix of categorical and numeric values. The columns likely include information such as listing ID, name, host ID, neighborhood, room type, price, minimum nights, number of reviews, last review date, reviews per month, number of listings per host, availability, and more.

[2] **Understanding Your Variables**

**Variables Description**

**Check Unique Values for each variable.**

[3] **Data Wrangling**

**Data Wrangling Code**

**What all manipulations have you done and insights you found?**


[4] **Data Vizualization, Storytelling & Experimenting with charts : Understand the relationships between variables**

**CHART1**
  (1) Why did you pick the specific chart?
   (2) What is/are the insight(s) found from the chart?
   (3)  Will the gained insights help creating a positive business impact?
   
   
   **CHART2**
   .
   .
   .
   .
   .
   .
   .
   .
   .
   .
 
  
  **CHART10**
   .
   .
  
   
   **Chart 14 Correlation Heatmap**
   .
   
   
   **CHART 15 Pair Plots**


[5] **REMARKS for Each Analysis in VISUALIZATIONS :**

(More Precized)

* Price Distribution: Significant price variation exists across different neighborhoods, with Manhattan having the highest median prices.

* Room Type Distribution: Entire homes/apartments are the most common type of listing.

* Number of Listings per Host: The number of Listing per host is started decline after the First 50 to 100 Users.

* Reviews per Month: The Reviews are Done in the First 10 Days As maximum Users done reviewing the apartment of almost 400+ users as you can in the scatter plot.

* Availability by Neighborhood: In the Availability by neighborhood the 'Manhatten' & 'Brooklyn' is Booked and not available in the span of year. Whereas the states like 'Staten island' & 'Bronx' are Available in the Neighborhood still the 'Queens' is like Booked and Availble most of the same Time as 'Queens' is said to be busy in the Festivle periods.

* The Data Can be Seen the Diffrent forms of Visualization in UBM Rule.
   


[6] **STATISTICAL ANALYSIS**
* The Conclusion From the ANOVA is If the p-value in the ANOVA table is less than 0.05, we reject the null hypothesis and conclude that there are significant differences in mean prices across different neighborhood groups.

* So The p value is not less than 0.05 te we can't reject the null hypothesis.

* ANOVA: Helps understand if neighborhood influences the price significantly.

* Chi-Square Test: Helps identify if the distribution of room types varies by neighborhood.

* This statistical analysis provides a solid foundation for drawing insights from the data and supports decision-making processes.



[7] **Solution to Business Objective**

* Most of listings are in brooklyn or manhattan. If you want to rent out flats , then brooklyn & manhattan are the best places to do it

* Entire homes & private rooms are majority of listings. Seems like private rooms & entire homes are in demand

* Majority of listings lies between latitudes - 40.65 - 40.75. If you want to advertise your flat you can do it in these locations

* Majority of listings lie in longitude ranges - 74-73.9. this can help us to find where we should advertise our flats to rent

* Majority of listings have 0 to 10 min nights, theres also a a considerable number of 30 minimum nights. 0 to 10 minimum nights & 30 nights package seems to be the industry standards

* Majority of listings are available for 0-100 days per year , mosIf youre starting a rental business , then its advisable to make it available for weekends.t likely weekends [52 weeks per year ie 52 weekends ie around 100 days]. There are also a lot of listings that are available almost entire year.

* Staten Island & manhattan are the most expensive , then bronx & brooklyn. If you want to setup a high end apartment for rent theses are the places to do so - Staten islands , manhattan

* The prices & number of listings seems to be higher between latitudes 40.6 - 40.8. For advertising and setting up your rental business , the above latitude range is the best

* Majority of listings lie between longitude -74 to -73.9. The graph shows that the longitude range above has the highest number of renting opportunities & its the best for advertizement.

* Entire homes/apartmentys are the most expensive, followed by private rooms. For maximum profits , invest in entire apatments/rooms & private rooms.

* It seems like listings with lesser minimum nights seems to be more popular & charge more. seems like 30 nights plan are popular too , followed by 60 & 90 nights plans. Keep the minimum nights as less as possible while setting up your rental business. also include 30,60,90 days package.

* Shared rooms have the most availability , followed by entire home & private rooms. If you want to gain max profits , increase availability in entire rooms since theyre more expensive & hence more profitable.

* Listings in staten islands & bronx seems to have highest availability , followed by brooklyn & queens.



**Conclusion of the Project:**

Summarizing the key insights and their implications for Airbnb:

* Pricing strategies might need to be neighborhood-specific.

* Marketing efforts could focus on promoting less popular room types or areas.

* Hosts with multiple listings contribute significantly to the platform's supply.

* Reviews are crucial for understanding listing popularity and guest satisfaction

* The dataset contains around 49,000 observations and 16 columns, with a mix of categorical and numeric values.

* The columns likely include information such as listing ID, name, host ID, neighborhood, room type, price, minimum nights, number of reviews, last review date, reviews per month, number of listings per host, availability, and more.

* From the above data analysis process we can deduce that there are certain factors that impacts the properties of listings , like geographical locations , availability , minimum nights etc. The above visualizations displays these very factors & how they impacts the listings.

DONE.
