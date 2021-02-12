# Best Vacation Locations 

## Scope part 1 (vacationpy)
![map1](images/locations.png)
This repository uses weather API's to find loactions with the ideal weather for a vacation. Using python locations were filtered to be sure that they had:

    1. A max temperature lower than 80 degrees but higher than 70.


    2. Wind speed less than 10 mph.


    3. Zero cloudiness.

Then aftering finding and mapping these locations hotels were found for each location to give users options of where to stay. 

![hotel-table](images/hotels.png)

## Technolgies Used 
Pandas - Used to clean data and seach through listings for hotels and plot thier locations

API's - Used to access weather data and googles search data

GMAPS and JSON - used to access data and plot it on a map

## Scope part 2 (weatherpy)
![chart1](images/lat-temp.png)

Using a weather data API python and pyplot was used to compare waather in different reagions and find any correlations between the them. The considerations for weather correlations were:

    1. Temperature (F) vs. Latitude

    2. Humidity (%) vs. Latitude

    3. Cloudiness (%) vs. Latitude

    4. Wind Speed (mph) vs. Latitude

As well as thier hempispheric locations:

    1. Northern Hemisphere - Temperature (F) vs. Latitude

    2. Southern Hemisphere - Temperature (F) vs. Latitude

    3. Northern Hemisphere - Humidity (%) vs. Latitude

    4. Southern Hemisphere - Humidity (%) vs. Latitude

    5. Northern Hemisphere - Cloudiness (%) vs. Latitude

    6. Southern Hemisphere - Cloudiness (%) vs. Latitude

    7. Northern Hemisphere - Wind Speed (mph) vs. Latitude

    8. Southern Hemisphere - Wind Speed (mph) vs. Latitude
![chart2](images/lat-cloud.png)

## Technologies Used
Pandas - cleaning and filtering the data

API - to access and read in the weather data ([OpenWeatherMap API](https://openweathermap.org/api))

Plotly - useed to plot the data and analze for it for any correalations

## Findings

1.	As expected, the closer to the equator (latitude 0) a city is the hotter its temperature is and the further from it the colder its temperature. This was what the expected results were when starting the project and the data has backed that up. It also seems that cities between 0-20 degrees latitude are the warmest overall though also not surprising as it is still summer in those regions. 
2.	A more surprising observation from the data is that proximity to the equator has no bearing on humidity. When one thinks of areas near the equator you think of tropical rainforests that tend to be extremely humid. While there were fewer less humid cities near the equator overall if did the distribution was fairly even regardless of the latitude of the cities. 
3.	A final interesting observation is cloud cover. While it did not have as stark a contrast as the temperature did, there is certainly more cities with cloudy weather nearer the equator than in at points further nor or south. This would likely be beneficial to the people living there as it can give them some shade and a degree of a respite from the heat of the sun. 

