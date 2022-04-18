# World Weather Analysis 
Weather Analysis and building of a travel app for customers of 600+ cities around the world.

## Project Overview
In this project, a travel app for customers is built using weather data of 600+ cities along with the data to recommend ideal hotels based on clients’ weather preferences.The analysis shows weather data including temperature, humidity, cloudiness, wind speed, etc, and performs regression analysis divided by southern and northern hemispheres as well as heat mapping the data onto a map. The analysis can be found in the WeatherPy.ipynb file.

## Tools
* Python
* citipy
* Pandas
* Google Maps API, Google Places API, OpenWeatherMap API
* Jupyter Notebook

## Deliverable 1:Retrieve Weather Data 
### Figures

A collection of figures made from the data are displayed below.  The data and figures can be found in the weather_data folder.

#### Weather Figures by Latitude

Latitude vs Temperature
![Latitude vs Temperature](https://github.com/Tifarahani/World_Weather_Analysis/blob/main/weather_data/Fig1.png)

Latitude vs Humidity
![Latitude vs Humidity](https://github.com/Tifarahani/World_Weather_Analysis/blob/main/weather_data/Fig2.png)

Latitude vs Cloudiness
![Latitude vs Cloudiness](https://github.com/Tifarahani/World_Weather_Analysis/blob/main/weather_data/Fig3.png)

Latitude vs Wind Speed
![Latitude vs Wind Speed](https://github.com/Tifarahani/World_Weather_Analysis/blob/main/weather_data/Fig4.png)

#### Linear Regression Analysis By Hemisphere

Latitude vs Temperature Northern Hemisphere
![Latitude vs Temperature](https://github.com/Tifarahani/World_Weather_Analysis/blob/main/weather_data/Fig5.png)

Latitude vs Temperature Southern Hemisphere
![Latitude vs Temperature](https://github.com/Tifarahani/World_Weather_Analysis/blob/main/weather_data/Fig6.png)

Latitude vs Humidity Northern Hemisphere
![Latitude vs Humidity](https://github.com/Tifarahani/World_Weather_Analysis/blob/main/weather_data/Fig7.png)

Latitude vs Humidity Southern Hemisphere
![Latitude vs Humidity](https://github.com/Tifarahani/World_Weather_Analysis/blob/main/weather_data/Fig8.png)

Latitude vs Cloudiness Northern Hemisphere
![Latitude vs Cloudiness](https://github.com/Tifarahani/World_Weather_Analysis/blob/main/weather_data/Fig9.png)

Latitude vs Cloudiness Southern Hemisphere
![Latitude vs Cloudiness](https://github.com/Tifarahani/World_Weather_Analysis/blob/main/weather_data/Fig10.png)

Latitude vs Wind Speed Northern Hemisphere
![Latitude vs Wind Speed](https://github.com/Tifarahani/World_Weather_Analysis/blob/main/weather_data/Fig11.png)

Latitude vs Wind Speed Southern Hemisphere
![Latitude vs Wind Speed](https://github.com/Tifarahani/World_Weather_Analysis/blob/main/weather_data/Fig12.png)

#### Heat Maps

Temperature
![Temperature](https://github.com/Tifarahani/World_Weather_Analysis/blob/main/weather_data/Fig13.png)

Humidity
![Humidity](https://github.com/Tifarahani/World_Weather_Analysis/blob/main/weather_data/Fig14.png)

Cloudiness
![Cloudiness](https://github.com/Tifarahani/World_Weather_Analysis/blob/main/weather_data/Fig15.png)

Wind Speed
![Wind Speed](https://github.com/Tifarahani/World_Weather_Analysis/blob/main/weather_data/Fig16.png)
## Deliverable 2: Create a Customer Travel Destinations Map
### Vacation Search

The first program uses all of the data collected from openweathermap API to create a map of cities that shows the most popular accommodation, the city and country, and the current weather and temperature. The files, data and image can be found in the vacation_search folder.  Sample output is shown below. 

Vacation Search Sample Output
![Vacation Search Sample Output](https://github.com/ForTheGold/World_Weather_Analysis/blob/main/vacation_search/WeatherPy_vacation_map.png)


## Deliverable 3: Create a Travel Itinerary Map
### Vacation Itinerary

In the second program, the user inputs the weather that they would like for their next vacation.  The program outputs a sample itinerary consisting of four cities that are all nearby and within the same country.  The output of the cities is randomized and will vary if the program is run several times.

The program outputs the navigation map necessary to drive between the cities, and always ends in the same city that trip started in for ease of plane trips, car rentals, etc.  The program also outputs information on accommodations and weather for each of the cities in the recommended itinerary.

This program along with sample images can be found in the vacation_itinerary folder.  Sample output is shown below.

Vacation Itinerary Navigation Map
![Vacation Itinerary Navigation Map](https://github.com/ForTheGold/World_Weather_Analysis/blob/main/vacation_itinerary/WeatherPy_travel_map.png)

Vacation Itinerary Accommodation and Weather Map
![Vacation Itinerary Accommodation and Weather Map](https://github.com/ForTheGold/World_Weather_Analysis/blob/main/vacation_itinerary/WeatherPy_travel_map_markers.png)

## Summary

- The Travel App allows customers to search for locations they want to travel based on their temperature preferences. 

- Once the customers have filtered the database (DataFrame) based on their temperature preferences, a heatmap will be showed to them for the maximum temperature 
for the filtered cities around the world.


![alt text](image/map_markers.png)


- A notation is in the search criteria to indicate if it is raining or snowing for customers who are making travel decisions in real-time.

- A weather description to the pop-up markers will be displayed for customers so that they know what the weather is as they are traveling.



![alt text](image/WeatherPy_vacation_map.png)



- A map that shows the directions between multiple cities for customers’ travel itinerary will be displayed.



![alt text](image/WeatherPy_travel_map.png)



- A map that shows the directions between multiple cities with the details of the nearest hotel for customers’ travel itinerary will be also be displayed if selected by the customer.



![alt text](image/WeatherPy_travel_map_markers.png)
