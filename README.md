# Communicate Data Findings

## Dataset
Ford GoBike is the Bay Area's new bike share system. (The name of this service/app had been changed to 'LYFT')  
The dataset(s) provided to us by Ford contain the following major fields:
 - User Type (Subscriber or Customer)
 - Member Birth year
 - Member Gender
 - Bike ID
 - Duration Seconds
 - Start Time
 - End Time
 - Station Latitude
 - Station Longitude
 - Station ID
 - Station Name

I'll use the data from Jan 2017 to Apr 2019 , as their columns or attributes are almost identical. (after May 2019, the file name changed , so did the columns)

  - `df_0628.csv` : Used for presentation, It is result data after data cleansing and wrangling.

## Summary of Findings

- `Usage Trend`  
The general trend of it's growth is noticable.  
What's unusual is that demand has dropped pretty a lot for a while in November 2018 for two month.

- `Bike rides usage Per Weekday `  
Bike is used more on weekday compared to weekend.

- `Bike rides per hour in a day`  
people use the serivce for the commute as the peak hour seems to same as usual rush hour(8-9am, 4-6pm)

- `Duration by Gender and Type of user`  
Female have longer duration of bike trip compare to Male's.  
Duration for customer is longer than subscriber.

- `Mean Duration per Hour and User type`  
It is surprsing fact that the hour in which subscriber's average trip is longest is 2~3am. on the contrary, The hour between 11 and 15 is the time when customers trip in the longest duration.


## Key Insights for Presentation


### Usage by group
First, I'll show the rides counts (usage) and proportions by 3 different user groups.

- `1.User Type`  
 Subscriber is customers with a regular subscription, accounting for 89% of all usage.
 The rest are customers who use the service sometimes, accounting for 12 percent of total usage.
- `2. Gender`  
 Male are account for 74 percent of the total, which is about three times more than female's of 24 percent.

- `3. Age Group   `  
 I divided users into six age groups : 10s,20s,30s,40s,50s and 60 to 80.
 Most are between the ages of 20 and 50.

### Montly Duration Trend by User Group
I studied how the duration changes by the different user factor.

- `1.Gender`  
It always shows that the duration of women is longer than that of men.

- `2.User Type`  
The duration of customer over the entire period is longer, and th he duration of subscribers is more constant.

### Hourly Usage during Weekdays for Customers and Subscribers
Subscribers ride bike on work days , Monday to Friday , whereas customers use the service during day on weekends , namely from 11 to 16 on saturday and sunday.
