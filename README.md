# Udacity-Projects
Differing projects performed during the Udacity Data Analyst Nanodegree Programme
Using Python through jupyter notebooks various analysis were peformed as projects to fulfill the requirements for the course.
Here are two of the projects:
- Twitter Dogs
- Ford GoBike System Data Exploration

## Twitter Dogs
### Dataset
> For this case study, the data source comes off the back of Twitter specifically using an API to get raw data off of the (@WeRateDogs) twitter account which rates various breeds of dogs.

### Summary of Findings
>Assesing the data, shown below are the various quality issues as well as the untidiness found across the 3 datasets. All three were merged to create a singular data set containing as much cleaned information as possible. This file is based off of a twitter archive of the (@WeRateDogs) profile and the tweets made by them within a specific time. Using the Tweepy Library to query the Twitter's API, This can be done by creating a twitter developer's account, set up some code to create an API object, Query various Tweet Id's and write its JSON data to a text file [tweet-json.txt].
**The analysis was performed: [here](https://github.com/mr-williams/Udacity-Projects/blob/main/twitter%20dogs/wrangle_act.ipynb)**

### Key Insights for Presentation
- The average numerator rating is at 12.28
- Dogs with no names contribute to over 27%
- The top 3 dog types are the Golden retriever, Lambrador retriver and Pembroke
- The minimum amount of likes(favorite) is at 81 likes while the most liked is at over 132k likes


## Ford GoBike System Data Exploration
### Dataset
> The data consists of information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area. The dataset can be found through this link provided: 
[here](https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv)


### Summary of Findings
> The data provided required some cleaning as the dataset was dirty and there were missing values which could alter the outcome of the analysis. The main feautures of this analysis centered around the duration of each bike ride & the type of users(Customer & Subscriber). Other features included which stations were mostly used, which day of the week featured the most rides, which period of the day had the most ride count.
There were 16 columns, one of which was removed during the Data wrangling process to make way for a few more columns. The Start and End time column type had to be changed to calculate the days of the week and Period of day. This was also used to calculate the Age of the Bike riders.
**The analysis was performed: [here](https://github.com/mr-williams/Udacity-Projects/blob/main/Ford%20GoBike%20System%20Data%20Exploration/Part_I_exploration_template.html)**



### Key Insights for Presentation
> It is shown that for both Customer & Subscribers, there is a significant amount of male users compared to female users.
 Across the week it looked as though weekdays had high turnout for ride duration with the highest being on thursday.
 Subscribers tend to spend more ride minutes as compared Customers.
 Morning and Evening periods are where bike rides are at their highest.
