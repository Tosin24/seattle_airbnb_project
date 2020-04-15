# Analysis of Seattle Airbnb Market

## Table of Contents
1. Brief Introduction
2. List of libraries
3. Project Motivation
4. File Description
5. Conclusion
6. References

## Brief Introduction
Airbnb, Inc. is an online marketplace for arranging or offering lodging, primarily homestays, or tourism experiences. The company does not own any of the real estate listings, nor does it host events; it acts as a broker, receiving commissions from each booking. It basically connects people looking to rent their homes with people who are looking for accommodations.

## List of libraries
1. Calendar
2. Collections
3. Numpy
4. Pandas
5. Matplotlib
6. Seaborn
7. Sklearn

## Project Motivation
For this project, I was interested in exploring Seattle's airbnb data set. I wanted to understand the factors that contribute to the prices of the listings, and the price trends throughout the year. The following questions were answered in this project:
1. What is the effect of the number of bedrooms, the number of bathrooms, and the number of beds on the price of the listings?
2. What is the average price of listings based on the number of bedrooms?
3. What is the average price of listings based on the type of room?
4. Which neighborhoods are the top 10 most expensive and what is the review ratings for listings in these neighborhoods?
5. What is the price trend over the months and what season is the listing prices the highest?
6. What factors are responsible for the price of the listings?

## File Description
The files used for this project was downloaded from [Kaggle](https://www.kaggle.com/airbnb/seattle/data). The data set consists of three file:
-  Listings, including full descriptions and average review score.
- Reviews, including unique id for each reviewer and detailed comments.
- Calendar, including listing id and the price and availability for that day.

## Conclusion
After concluding the analysis, the following conclusions were made:
- There is a positive correlation between the number of bedrooms, number of bathrooms, number of beds, and the listings prices. This means that number of bedrooms, bathrooms, and beds that a listing offers impact of determine the price of the listing to a certain degree.
- The number of bedrooms in the Seattle Airbnb market listings ranges from 1 to 7. The higher the number if bedrooms, the higher the price. However, the analysis revealed that the average price of a 6 bedroom is more expensive.
- The analysis revealed that the average listing price of an entire home/apartment is higher than the average listing price of a private room or a shared room. While the average listing price of a private room is higher than the average listing price of a shared room.
- After exploring the top 10 most expensive cities in Seattle and their review scores rating, the analysis showed that while there is no rating scores data for the most expensive neighborhood, the ratings scores for the other neighborhood reveals that the most expensive neighborhoods have rating scores greater than 90. However, the distribution of the rating scores amongst these neighborhood shows that the least expensive neighborhood with an average listing price of $175 has a very high rating of 97.5.
- The analysis of the price trend throughout the year reveals that the month when the listing price is at the highest is July, the listing price is overall high between July and August, this means that during the summer, the prices usually go up, and the prices are at the lowest between January and March.
- After fitting the linear regression model, The rsquared on the training data was 0.605, while the rsquared on the test data was 0.556.
- The coefficient analysis reveals that the features of the house like property type, room type were determinants in the listings prices.

## References
- The blog post for this project can be found on [Medium](https://medium.com/@obisanoluwatosin/exploring-the-airbnb-market-in-seattle-3ea45eba38ce).
- The data set used for this project was downloaded from [Kaggle](https://www.kaggle.com/airbnb/seattle/data).
