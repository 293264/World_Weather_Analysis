# Overview

## Purpose of the Analysis ##
PlansMyTrip is a leading provider of internet-based services for the hotels and lodging industry. Although beta testers have praised the new app, there are a few suggestions that they believe will elevate it to the next level. These suggestions include:
  
   * The addition of weather description to the weather.
   * Input statements that allows beta testers to filter data by their preferred weather preferences, which can be used to identiify potential travel destinations and nearby hotels. 
   *  From the list of potential travel destinations, the beta testers will be able to choose four cities to create a travel itinerary.
   *  Finally, map the route between the four cities using the Google Map Directions API, as well as add marker layers to the map. 


## Results ##

The following steps were necessary to complete this analysis: audit, including the new results, as well as a clearly written description of the methods used during the audit. 

  1. Retrieve Weather Data 
   
     * For this process, I generated 2,000 random latitudes and longitutdes, retrieved the nearest city, and obtained weather data using the OpenWeatherMap API. Then, I retrieved current weather descriptions for each city utilizing the API. As a final step, I created a new DataFrame containing the new weather data. 
     


  2. Create a Customer Travel Destination
  
     * The next step was to use input statements to revtrieve customer weather preferences, then use those preferences to find potential travel destinations and hotels nearby. I then desplayed these destionations as pop-up markers on a a map. 


  3. Creaate a Travel Itinerary Map 
  
     * My final step was to use the Google Direction API to create a travel itinerary showing the route between four cities from the customers possible travel destinations. Next, I create a map with a pop-up marker for each city on the itinerary.
