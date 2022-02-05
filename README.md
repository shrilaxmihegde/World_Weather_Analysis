# Overview of the project :
This analysis looks at different weather patterns around the global and offers insights to travelers who want to book a trip. There are three folders here that offer different levels of analysis: weather database, vacation search, and vacation itinerary.
# Weather Database :
This folder uses Open Weather Map API to pull weather information on over  different cities around the world. That information consists of:

Maximum Temperature
Cloudiness
Wind Speed
Humidity
Current Weather Description

These different categories of information make it easy for travelers to choose exactly what they are looking for in a travel destination.

# Vacation Search :
This folder takes the information gained in the weather database and uses Google Maps API to plot different travel destinations with a hotel at each location. For example, the image below shows the locations of all the places in the database that have an daily maximum temperature between 75 and 90 degrees farinheit.
![World_Weather_Analysis)](/Vacation_Search/WeatherPy_vacation_map.png)

# Vacation Itinerary :
This folder takes the search information from the search folder and uses Google Maps directions API to create a vacation itinerary. For example, the image below shows a 4 stop itinerary in Australia cities.
[World_Weather_Analysis)](/Vacation_Itinerary/WeatherPy_travel_map.png)
[World_Weather_Analysis)](/Vacation_Itinerary/WeatherPy_travel_map_markers.png)