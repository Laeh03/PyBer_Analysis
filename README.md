# Pyber_Analysis

## Project Overview
The purpose of this project was to perform an analysis and visualization of Pyber ride sharing data in order to gain an understanding of ridership and fare metrics by the types of cities in which Pyber operates. By creating visualizations of rideshare data, PyBer helped improve access to ride-sharing services and determine affordability for underserved neighborhoods.

## Resources
- Data Source: city_data.csv, ride_data.csv
- Software: Jupyter Notebook 6.3.0, Python 3.8.8

# Results

### Total Ride Shares
More than 2/3 of the total rides in 2019 were realized in urban cities. Suburban areas count for over 26% of the total rides and rural cities have the smallest proportion with only for 5.3%
![Fig6](https://user-images.githubusercontent.com/64225504/128621413-c8fa9d24-5cac-4a4e-ba56-0f68712a8aa7.png)

### Total Drivers
Urban cities drivers were by far in majority with 80.9% of the company's drivers force in 2019. Surbuban and rural drivers were 26.3% and 5.3% of the total drivers in 2019.
We can start to notice a trend with a very small proportion of drivers in rural areas.
![Fig7](https://user-images.githubusercontent.com/64225504/128621479-f98d42f9-d4df-4b7e-b34d-1b9168958195.png)

### Total Fares 
We can notice the influence of urban areas in the company's business model. 
Close to 63% of the 2019 total fares was in urban cities. 
Surbuban activity counted for about 31% and the smallest proportion was in rural neighborhoods at 7%.
![Fig5](https://user-images.githubusercontent.com/64225504/128621501-6e866611-a740-41c8-924e-6b31d7f31098.png)

### Average Fare Ride and Driver by City
In conculsion, We can notice that the average fare tends to decrease as the total number of rides per city increases. This is a negative relationship.
As the driver count per city, it appears that the bubbles get larger when the average fare decreases and/or when the total number of rides increases.
Rural areas have the least number of drivers and rides per city and its fare ranges from high to middle prices. 
It is difficult to see the relation between those parameters. 
Other inputs like population size, ride distances, and cellphone coverage would be interesting to analyze to determine any correlation.

The following bubble chart shows the relationship between the average fare price and the number of rides and drivers categorized by the different city types.

![Fig1](https://user-images.githubusercontent.com/64225504/128621569-cd4d12d8-97f0-4870-b88d-8ed3019cf305.png)

### Total Fare by City
![PyBer_fare_summary](https://user-images.githubusercontent.com/64225504/128621621-ca07d194-d7ea-4a5d-8228-e22252a5098b.png)

From the data above and overall analysis, we can see that the urban weekly total fare is around 9 and 2.25 times higher than rural and surburban ones respectively.

### Summary
Based on the analysis, my business recommendations to Pyber would be to:
Increase the amount of drivers in Rural areas to ensure there are enough drivers to meet ride demand. 
Data for rural cities shows that the average fare per ride and average fare per driver is much higher than Suburban and urban cities.This can indicate that rural area based riders are taking trips over a longer distance.
This can result in a majority of drivers being occupied with current trips and loss in potential revenue when there are peaks in business.

Suburban drivers were only about 17% of the total drivers but accounted for more than 30% of the total fares and just above a quarter of the rides.
Improving access to PyBer service in those areas will imply finding the right balance between incentives for more riders to join in and for the right fare charge.
That'll  motivate riders to pick PyBer app as the first choice for their travels.
Additional analysis including geographic size, population and social conditions, travel distances would also be interesting to get a better understanding.

And finally, In the most underserved neighborhoods, we notice some urban cities with low number of drivers and low average fare but pretty high count of rides.
Analyzing the average number of drivers against the population and infrastructure and economic activity in those cities would help understand those disparities.

