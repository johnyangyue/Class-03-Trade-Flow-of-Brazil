# Foreign Trade Flow of Brazil

## Introduction
This project utilizes Dask to load and process a sizeable international trade dataset from 2012 to 2018. By mapping the six-digit product designations to two-digit sector designations, it highlights the highest value sectors in the sample period. The project also presents the top 10 traded products in terms of both value and quantity for Brazil. 

Using the country shapefile, the project calculates the distance in kilometers between the centroid of Brazil and all the other centroids. It then evaluates the correlation between exports and distance for both value and quantity. The primary objective of this exercise is to apply the gravity equation relationship to the international trade setting and see how it fits. 

Finally, linear regressions are performed on the trade flow data. 
