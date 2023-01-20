# Capital_Bikeshare_Analysis

## Introduction
In this project, we used R to analyze the [Bike Sharing Dataset](https://archive.ics.uci.edu/ml/datasets/Bike+Sharing+Dataset) from UCI Machine Learning Repository. The dataset contains the hourly and daily count of rental bikes between 2011 and 2012 in Capital bike-sharing system with the corresponding weather and seasonal information.  

## Questions of Interest
We used statistics and data analysis to answer the following questions:
1. Is there a general growth in bike rentals from 2011 to 2012? Specifically for casual or registered users?
2. What hour of a day is the most popular time for bike rental? Specifically for casual and registered user?
3. How does temperature, based on the current weather situation, affect the number of bike rentals?

## Findings
1. Using a two-sample t-test, we concluded that there is a significant growth in the bike rental user-base for both casual and registered users from 2011 to 2012.  
2. We used visualizations to show that 8am, 5pm, and 6pm are the most popular hours, mainly because registered users are commuting to / off work in these hours. As for casual users, they like to use rental bikes in the noon and afternoon hours, possibly for recreational purposes.  
3. Using the interaction linear regression model, We found that the higher the temperature is, the more people will use rental bikes. Cloudy/mist and light rain/light snow weathers negatively influences on bike rentals, but they do not have a significant impact on how temperature affects bike rentals.  

  
The detailed process and result of our analysis can be found [here](report.pdf).
