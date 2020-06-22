# World_Weather_Analysis
world weather analysis
# Retrieve basic information with API call

Data added to the dataframe. Deliverable retrieves Latitude and longitude,Maximum temperature,Percent humidity,Percent cloudiness,Wind speed,Weather description from the API call.

# Used the Try-Except block

Saved the dataframe as a csv.added the amount of rain and snow in the analysis. I have shown the amount of rainfall in inches  from the API using a try-except block. In the try-except block, if there is no rain then i have displayed the amount of rain as 0 inches.Similarly I have used the try-except block, if there is no snow then the amount will show 0 inches.


# Used if/elif/else statements

Used if/elif/else statements to filter the city_data_df DataFrame based on the minimum and maximum temperature, and whether it is either raining and snowing or not to get the cities that meet the customer criteria.
The code will prompt the customer to get the following information The minimum temperature preference, The maximumtemperature
preference, If they want it to be raining or not, If they want it to be snowing or not.

# Created a New Dataframe with Hotel Information Using Google API Places and try/except block

I have written the code to search for a hotel using a Google API and the JSON data is retrieved. I have used the try/except block to add the hotel to the new DataFrame, and the IndexError is resolved.I have saved and uploaded the DataFrame to a CSV file.


# Created a pop-up marker with city and weather data and hotel name

I have created a marker layer map with a pop-up marker for each city that includes: Hotel name, City, Country, Current weather
description with the maximum temperature. I have saved and uploaded the new marker layer map as PNG

# Created a directions layer map to travel between citie

I have written the code to filter the vacation DataFrame for four cities to travel to.
I have written the code to get the latitude and longitude pairs for each city to visit.
I have created an itinerary map between the cities 
I have saved and uploaded the directions layer map as PNG.

# Created a pop-up marker for each city on the itinerary

I have craeted a new DataFrame that contains the cities in the itinerary.
I have craeted a marker layer map with a pop-up marker for the cities in the directions layer map which has the following information:
● Hotel name
● City
● Country
● Current weather description with the maximum temperature
I have saved and uploaded the new marker layer map for the four cities as PNG
