# World Weather Analysis

## Weather Database

**Objective** 

* The weather database script is built to generate 2,000 random [Lat, Lng] coordinates.  Of the 2,000 coordinates generated I utilized citipy to generate a list of cities near the coordinates which eliminated coordinates that could have generated in a body of water or uninhabited area. 
* Once the cities have been identified a DataFrame > .csv was created showing the cities particular weather data.

## Vacation Search

**Objective**

* The vacation search allows a user to input their desired minimum and maximum temperature for their upcoming vacation.  These inputs will filter the weather database to cities meeting these particular conditions.
* Within this same search my Python script identifies hotels within 5,000 meters or 3.1 miles of the [Lat, Lng].  The script will drop any cities that do not return a hotel within our specified radius.
* In the script's current state the hotel rating and/or price level is not a condition of the filter.

The below image is a zoomed output of the Vacation Search.

![]('Vacation_Search/WeatherPy_vacation_map.png')
