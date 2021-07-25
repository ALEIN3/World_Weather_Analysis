# World_Weather_Analysis

## Overview of Project
This project is to show the ability to use APIs to Visualize Weather Data.
I am creating an interactive app that allows customers to choose their temperature preferences. The cities will get filtered to match the temperature preference of the imaginary customer, and the outcomes will be showing the route between the chosen cities, a marker for each city showing the nearest hotel, the country, the weather condition, and the temperature.
The project consists of three folders which uploaded to the repository as follows:
### The Weather_Database folder with the following:
o	The Weather_Database.ipynb file

o	The WeatherPy_Database.csv file
### The Vacation_Search folder with the following:
o	The Vacation_Search.ipynb file

o	The WeatherPy_vacation.csv file

o	The WeatherPy_vacation_map.png image
### The Vacation_Itinerary folder with the following:
o	The Vacation_Itinerary.ipynb file
o	The WeatherPy_travel_map.png image
o	The WeatherPy_travel_map_markers.png image

I used for this project Anaconda,  Jupyter Notebook, Gmaps, Pandas, Python APIs and Python.
## summary
### Weather_Database.ipynb file the 
I generated a set of 2,000 random latitudes and longitudes, retrieved the nearest city, and performed an API call with the OpenWeatherMap. In addition to the city weather data I gathered in this module, I used API skills to retrieve the current weather description for each city. Then, I created a new DataFrame containing the updated weather data, and I export them as CSV file

### The Vacation_Search.ipynb
I used input statements to retrieve imaginary customer weather preferences, then used those preferences to identify potential travel destinations and nearby hotels. Then I showed those destinations on a marker layer map with pop-up markers

### The Vacation_Itinerary.ipynb 
I used the Google Directions API to create a travel itinerary that shows the route between four cities chosen from the customer’s possible travel destinations. Then, I created a marker layer map with a pop-up marker for each city on the itinerary.
