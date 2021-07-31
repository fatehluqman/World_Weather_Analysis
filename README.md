# World_Weather_Analysis

## Summary
The World Weather Analysis consists of three parts 1. World Weather Data 2. Vacation Travel Search 3. Vacation Travel Itinerary

### World Weather Data
World Weather Data generates weather data for a random set of latitudes and longitudes.  Initially a set of 2,000 random latitudes and longitudes are generated from which the nearest cities are retrieved.  Once the Cities are retrieved an API call is performed on OpenWeatherMap. 
The API call captures the current weather description for each city. Finally, the data is us used to create a new DataFrame containing the updated weather data and saved as a csv file.

### Vacation Travel Search
Vacation Travel Search uses the data generated from the World Weather Data and allows the user to provide their weather preferences in terms of acceptable min and max temps. 
Then use those preferences to identify potential travel destinations and nearby hotels. These destinations are then shown on a marker layer map with pop-up markers.

### Vacation Travel Itinerary
Vacation Travel Itinerary uses the Google Directions API to create a custom travel itinerary that shows the route between four cities chosen from the customer’s possible travel destinations. 
Additionally a marker layer map with a pop-up marker for each city on the itinerary is created.
