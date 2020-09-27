# python-api-challenge

## Background

I used two API's two solve WeatherPy (OpenWeatherMap API) and VacationPy (Google Places API).

**WeatherPy** I created a random list of 500+ cities by using the CitiPy library and OpenWeatherMap API. The nearest city to the coordinates gave me an output city. I used Jupyter notebook and Pandas. My API key is in config.py. I also output that data to cities.csv. I saved each of the 4 scatter plots in the images folder.

![image](WeatherPy/Images/max_temp_plot.png)
![image](WeatherPy/Images/windspeed.png)
![image](WeatherPy/Images/cloudiness.png)
![image](WeatherPy/Images/humidity.png)

**VacationPy**
We are planning a future vacation using ideal temps. I had to find a hotel in each city using the Google Place API. Used a simalir process in the WeatherPy example. I used mapbox to create a scatterbox. 
![image](VacationPy/Images/xxxxxx.png)


## Analysis

**Tempeture** As obvious as it seems, the weather temperatures were higher near the equator.There is a higher presence of humidity in the Northern Hemisphere.Cloudiness is evenly spread through out both hemispheres. Windspeed is pretty consistent around 15 mph or less. As you move higher in the norhtern hemisphers there are a couple outliers recording high wind speeds.