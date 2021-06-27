# Boston Bluebikes Riding Patterns: Before and During COVID-19 Pandemic EDA and Data Visualization

This repository contains the code to perform Exploratory Data Analysis and Visualization over all of Bluebikes bike-sharing rides that occurred between January 1st 2019 and December 31st 2020. 

## 1. Introduction

Bluebikes is a bike-sharing system that operates in the Boston Metro Area and surrounding communities. It consists of a fleet of bikes that are distributed in the city across a network of docking stations. Users can unlock bikes from one station and return them at any other station which makes the service useful for one-way trips.

The bike-sharing system has succesfully grown since its opening in 2011 and has become a vital commuting method for many Boston residents, which rely on it to move around the city without dealing with the hassle of using public transportation or owning a vehicle in highly populated areas.

The motivation to perform this project is because as a resident of Boston, the service has personally become one of my preferred methods to perform short commutes around the busy city. In that sense, the goal of this project is to understand at a broad scale the program's operation and how the COVID-19 pandemic has affected it.

## 2. Business Questions

Seeing things from a pretended point of view of one of this company's Data Analyst the goal stated above could be broken down into the following business questions:

* Which are the most used routes?
* How do holidays influence bike sharing?
* How does weather influence bike sharing?
* How has the pandemic changed bike sharing patterns?

## 3. Data Collection

To answer the questions above, three datasets from the following sources were used:
* Bluebikes Trip History Data [(url)](https://www.bluebikes.com/system-data)
* US Holiday Data [(url)](https://www.timeanddate.com/holidays/us/) (Federal Holidays Only)
* Boston Historic Weather Data (NOAA Database) [(url)](https://www.ncdc.noaa.gov/cdo-web/search)

## 4. Data Wrangling

To know more about this stage of the project explore the jupyter notebook located inside this repo's files.

## 5. Exploratory Data Analysis and Visualization

To know more about this stage of the project explore the jupyter notebook located inside this repo's files.

## 6. Conclusions

### 6.1 Most Used Routes

Due to the large number of possible routes, I will focus on the top 10 most frequent dock to dock paths. In first place, overall, on the 2019 – 2020 period the ten most used routes were:

![image](https://user-images.githubusercontent.com/60116541/123551073-34e06f00-d73e-11eb-8bc6-527c5e8fc01d.png)

It is possible to see that the busiest route between docking stations is the one from MIT Pacific St at Purrington St to Ames St at Main St. These are located as follows:

![image](https://user-images.githubusercontent.com/60116541/123551088-44f84e80-d73e-11eb-80af-4fcf649a569e.png)

### 6.2 How do Holidays influence Bike Sharing?

![image](https://user-images.githubusercontent.com/60116541/123551152-9a346000-d73e-11eb-9292-a41d641bacf3.png) 

Before the pandemic, non-holidays registered an average of 6500 rides per day, while on holidays there were 4000 average rides per day approximately.

![image](https://user-images.githubusercontent.com/60116541/123551165-a3253180-d73e-11eb-8276-2bd4a02d81ca.png)

On the other hand, during the pandemic non-holiday days still registered a greater number of average rides per day. However, it is possible to see that the gap between both kinds of days is much smaller showing an average of 6000 daily rides on non-holidays and around 5500 average rides per day on holidays.

### 6.3 How does Weather influence Bike Sharing?

In terms of how weather conditions influence bike sharing, it is possible to see the following trends:

* Precipitation: 

![image](https://user-images.githubusercontent.com/60116541/123552719-55f88e00-d745-11eb-9df3-0b5302629208.png)

There are on average 5300 rides on rainy days, while non-rainy days registered on average 7000 rides.

* Snowfall:

![image](https://user-images.githubusercontent.com/60116541/123552727-67da3100-d745-11eb-9617-9a6ea5703e6b.png)

There is less riding volume on days with snowfall, at around 2000 average rides. Days with no snowfall registered 6500 rides on average.

### 6.4 How has the Pandemic changed Bike Sharing Patters?

The pandemic has changed bike-sharing patterns across Boston in the following ways:

* **Trip Duration**:

The Blue Bikes service is mainly used in the city of Boston and surrounding metro areas for short trips. Both before and during the pandemic, the majority of rides registered are of a duration of 20 minutes or less, which suggests that bikes are used for what is called “Last Mile Transportation” (last stretch of a trip).
Now, there was a big decrease in the “less than 30 minutes” ride segment during the pandemic which is probably due to the work-from-home measures implemented (less riders commuting to work or college). However, despite that decrease the frequency of other trip duration riding segments actually sustained or even increased during the pandemic. One hypothesis to explain this behavior is that even though users were not riding bikes for day-to-day commuting, they may have increased their use for recreational purposes.

* **User Type**:

Before and during the pandemic the highest frequency user type are Subscribers, which are the kind of users that buy either monthly or annual memberships due to the expected high use rate. 
On year 2020 (during the pandemic) there was a large decrease in the number of rides performed by Subscribers, however the Casual user segment did not register a large difference with respect to 2019. This again, suggests that riders were not commuting as much but they did use the service for recreational purposes.

* **Month**:

After visualizing the number of rides made per month it is possible to conclude that the time of the year with most bike demand is between July and October in both pre-pandemic and pandemic timeframes. The pandemic did not affect the seasonality of the rides; however, it did decrease the overall number of monthly trips.

* **Day of the Week**:

Before the pandemic there was greater rider traffic during weekdays. On the other hand, during the pandemic the behavior has completely reversed. This again shows the increased recreational use of the bikes, and how work-from-home measures have drastically modified customer behavior.

* **Hour of the Day**:

Before the pandemic the distribution of rides per hour of the day was bimodal, having the first peak at 8:00 am and the second at 5:00 pm. Both of these riding hours coincide with the times when people are going to and coming from work. On the other hand, during the pandemic the distribution seems to have become unimodal, registering 5:00 pm as the hour with more riding demand. This reflects on the fact that users are not leaving for work almost the entire day, and then at the end of the day the volume picks up.

* **Routes**:

As mentioned before, pre-pandemic the most popular route was the one from MIT Pacific St at Purrington St to Ames St at Main St (in red). On the other hand, during the pandemic the most popular start and end point is at the Mugar Way & Beacon St dock (in black).

![image](https://user-images.githubusercontent.com/60116541/123552196-0ca73f00-d743-11eb-9c84-e382f1ff5267.png)

In my own experience, as a resident of Boston I have witnessed a high volume of recreational rides that start or end at the Mugar Way & Beacon St dock (black) since it is conveniently located to connect with some of the city’s most notable sight-seeing places such as the Charles River Esplanade, the Public Garden, the Boston Common, Back Bay, etc.

## 7. Installation

* Clone this repo into your computer.
* Switch your devices directory to the the local repository folder path.
* Run the python code using python 3 (if not installed yet )

## 8. Usage
