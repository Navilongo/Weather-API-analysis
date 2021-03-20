# python-api-challenge

## Background

As part of the json and api practice, we have been tasked with demonstrating our ability to pull information from the online databases and compile it to show meaningful
information. In this instance, we are tasked to prove important geography facts like, does it really get hotter the closer you are to the equator, and is there greater wind currents the further away you are from the equator? 

## Preparation

Using information from the OpenWeatherMap API, we pulled a large number of cities at random at varying distances from the equator. These cities we used to find the information for both parts of the assignment (WeatherPy and VacationPy). 


## Part I - WeatherPy

The first requirement is to create a series of scatter plots to showcase the following relationships:

* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

After each plot, there is a small analysis of the information. 

The second requirement is to run linear regression on each relationship. This time, separate the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude):

* Northern Hemisphere - Temperature (F) vs. Latitude
* Southern Hemisphere - Temperature (F) vs. Latitude
* Northern Hemisphere - Humidity (%) vs. Latitude
* Southern Hemisphere - Humidity (%) vs. Latitude
* Northern Hemisphere - Cloudiness (%) vs. Latitude
* Southern Hemisphere - Cloudiness (%) vs. Latitude
* Northern Hemisphere - Wind Speed (mph) vs. Latitude
* Southern Hemisphere - Wind Speed (mph) vs. Latitude

### Part II - VacationPy

For this section of the assignment I attempted to do the following:

* Create a heat map that displays the humidity for every city from Part I.

* Narrow down the DataFrame to find your ideal weather condition. For example:

  * A max temperature lower than 80 degrees but higher than 70.

  * Wind speed less than 10 mph.

  * Zero cloudiness.

  * Drop any rows that don't contain all three conditions. You want to be sure the weather is ideal.

 * Using Google Places API to find the first hotel for each city located within 5000 meters of your coordinates.

* Plot the hotels on top of the humidity heatmap with each pin containing the **Hotel Name**, **City**, and **Country**.

