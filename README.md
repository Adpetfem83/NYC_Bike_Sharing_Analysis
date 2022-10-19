# NYC_Bike_Sharing_Analysis

## OVERVIEW

Purpose:  The purpose of this analysis is to prepare visualizations that give potential investors a look into the highly-successful NYC Citibike bike-sharing program, so that they can see for themselves that a bike-sharing program in Des Moines is a solid business proposal.  Among others, we have prepared visualizations that:

(1) Show the length of time that bikes are checked out for all riders and genders. 
(2) Show the number of bike trips for all riders and genders for each hour of each day of the week. 
(3) Show the number of bike trips for each type of user and gender for each day of the week.


# Bike Sharing Project - Proposal for Des Moines
Create worksheets, dashboards and stories to visualize data using Tableau.

## Overview

![bike image](https://github.com/Adpetfem83/NYC_Bike_Sharing_Analysis/blob/main/Images/City_Bike_Preview.png)

The purpose of this analysis is to provide a business proposal that will convince investors that developing a bike-sharing program in Des Moines can be a profitable venture. Throughout the process, we use data that is publicly available from the NYC CitiBike program [archives](https://s3.amazonaws.com/tripdata/index.html) and `Tableau` to create visualizations. 

While the data is based on activity that occurred in New York City which is very different from Des Moines, we use our data expertise and critical thinking skills to build a story that can be presented to the investors. 

For our presentation, we decide to use data from August 2019 to build our analysis. It is assumed that there is more traffic or usage during the summer months compared to other times of the year in which weather can impact activity.

## Tableau Public Link

[Link to Dashboard](https://public.tableau.com/app/profile/adio.olufemi.peter/viz/)


## Results

# Total Rides, Customer Type and Gender Breakdown

![totalrides](https://github.com/Adpetfem83/NYC_Bike_Sharing_Analysis/blob/main/Images/Total%20Rides-User-Gender.png)

In NYC, there were over 2.3M trips that occurred during the month of August with 81% of the riders in the **"subscriber"** category and that **Men** were the primary user of this program (65%).


### Checkout Times for Users

![CheckoutTimes](https://github.com/Adpetfem83/NYC_Bike_Sharing_Analysis/blob/main/Images/Checkout%20Times%20for%20Users.png)

Almost all of the trips (99%) were under 60 minutes with 49% under 10 minutes (1.1M vs. 2.3M).


### Checkout Times by Gender

![checkoutgender](https://github.com/Adpetfem83/NYC_Bike_Sharing_Analysis/blob/main/Images/Checkout%20Times%20by%20Gender.png)

Male riders are the primary user of the bike share program making up 65% of the population, with the remaining being 25% female and 10% unknown.


### Trips by Weekday for Each Hour

![TripsWeekday](https://github.com/Adpetfem83/NYC_Bike_Sharing_Analysis/blob/main/Images/Trips%20by%20Weekday%20for%20Each%20Hour.png)

Most of the rides during the weekdays (Monday-Friday) occur during commuting hours of 8-9a and 5-7pm. It can be assumed that the bike sharing program is the preferred method for commuting to and from work. 


### Trips by Gender (Weekday per Hour)

![TripGender](https://github.com/Adpetfem83/NYC_Bike_Sharing_Analysis/blob/main/Images/Trips%20by%20Gender%20by%20Weekday.png)

Male riders are more inclined to use the bike sharing program to commute to and from work, as well as during the weekend.


### Trips by Gender by Weekday

![TripWeekGender](https://github.com/Adpetfem83/NYC_Bike_Sharing_Analysis/blob/main/Images/Trips%20by%20Gender.png)

Thursday was the highest usage day among subscribers with the most usage occurring on Saturday for non-subscribers.


### Top Ending Location

![TopEnding](https://github.com/Adpetfem83/NYC_Bike_Sharing_Analysis/blob/main/Images/Story%20for%20Top%20Ending%20Location.png)

Usage was more concentrated in Midtown and business areas which would suggest that bikes are primarily used for commuting.


## Summary

The results of this analysis have given insight into the utilization of bicycles in the NYC Citibike bike-sharing program. We've seen the patterns of usage by time and by gender.  Utilization rates can now be predicted based on time of day and location.  Weekday usage is heavily concentrated around the morning and afternoon commute.  Weekend usage is more evenly spread through the day. I think it is very important to recommend further analysis for a few reasons:  First and foremost, the analysis has shown that the vast majority of the trips are 30 minutes or less, we should perform further analysis to compare weekend trip durations to weekday trip durations.  We should also take a further look into the patterns of usage for the bicycles that see the heaviest use, perhaps preparing maps showing all of the starting/ending routes/locations for the heaviest use bikes.  We should also prepare a visualization to determine if there are specific locations that are completely unused.

