# Python-API-Challenge

![image](https://github.com/RaphaelSheikh/python-api-challenge/assets/166172978/9537dc8c-e7b0-41d2-818b-4f706f474631)

# Background

Data's true power is it's ability to definitively answer questions. So, let's take what I have learned about Python requests, APIs, and JSON traversals to answer the fundamental question: "What is the weather like as we approach the equator?"

Now, I know what you're thinking: “That’s obvious. It gets hotter.” But, if pressed for more information, how could I prove that?

# Part 1: WeatherPy

In this deliverable, I'll create a Python script to visualize the weather of over 500 cities of varying distances from the equator. I'll see the citipy Python libraryLinks to an external site., the OpenWeatherMap APILinks to an external site., and your problem-solving skills to create a representative model of weather across cities.

## Requirement 1: Create Plots to Showcase the Relationship Between Weather Variables and Latitude
To fulfill the first requirement, I'll use the OpenWeatherMap API to retrieve weather data from the cities list generated in the starter code. Next, I will create a series of scatter plots to showcase the following relationships:

* Latitude vs. Temperature

* Latitude vs. Humidity

* Latitude vs. Cloudiness

* Latitude vs. Wind Speed

## Requirement 2: Compute Linear Regression for Each Relationship
To fulfill the second requirement, computing the linear regression for each relationship. Separating the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude).

Creating the following plots:

* Northern Hemisphere: Temperature vs. Latitude

* Southern Hemisphere: Temperature vs. Latitude

* Northern Hemisphere: Humidity vs. Latitude

* Southern Hemisphere: Humidity vs. Latitude

* Northern Hemisphere: Cloudiness vs. Latitude

* Southern Hemisphere: Cloudiness vs. Latitude

* Northern Hemisphere: Wind Speed vs. Latitude

* Southern Hemisphere: Wind Speed vs. Latitude

# Part 2: VacationPy
In this deliverable, I will use weather data skills to plan future vacations. Also, I'll use Jupyter notebooks, the geoViews Python library, and the Geoapify API.

The main tasks will be to use the Geoapify API and the geoViews Python library and employ my Python skills to create map visualizations.

To succeed in this deliverable of the assignment, need to open the VacationPy.ipynb starter code and complete the following steps:

* Create a map that displays a point for every city in the city_data_df DataFrame. The size of the point should be the humidity in each city.

* Narrow down the city_data_df DataFrame to find the ideal weather condition. For example:

  * A max temperature lower than 27 degrees but higher than 21

  * Wind speed less than 4.5 m/s

  * Zero cloudiness

* Create a new DataFrame called hotel_df to store the city, country, coordinates, and humidity.

* For each city, use the Geoapify API to find the first hotel located within 10,000 meters of your coordinates.

* Add the hotel name and the country as additional information in the hover message for each city on the map.

# References

* citipy Python library (https://pypi.org/project/citipy/)
  
* OpenWeatherMap API (https://openweathermap.org/api)

* Geoapify API (https://www.geoapify.com/)

* geoViews Python library (https://geoviews.org/)

* Python Pandas Convert (https://stackoverflow.com/a/75222939/21871037)

