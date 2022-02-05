# Overview of the project :
This analysis looks at different weather patterns around the global and offers insights to travelers who want to book a trip. There are three folders here that offer different levels of analysis: weather database, vacation search, and vacation itinerary.
# Weather Database :
Using Open Weather Map API, we extract the  weather information for the given cities around the world. The weather information consists of:

1. Maximum Temperature
2. Cloudiness
3. Wind Speed
4. Humidity
5. Current Weather Description, etc.

These different categories of weather information make it easy for travelers to choose exactly what they are looking for in their travel destination. This information is persisted into a csv file for further analysis. 

# Vacation Search :
This part of the analysis takes the information gathered in the weather database and uses Google Maps API to plot different travel destinations with a hotel information at each location. For example, the image below shows the locations of all the places in the database that have an daily maximum temperature between 75 and 90 degrees farinheit.
![World_Weather_Analysis)](/Vacation_Search/WeatherPy_vacation_map.png)

# Vacation Itinerary :
This part of the analysis takes the search information from the vacation search folder and uses Google Maps directions API to create a vacation itinerary. For example, the image below shows a 4 stop itinerary in Australia cities.
![World_Weather_Analysis)](/Vacation_Itinerary/WeatherPy_travel_map.png)

![World_Weather_Analysis)](/Vacation_Itinerary/WeatherPy_travel_map_markers.png)
