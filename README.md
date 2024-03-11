# Module 6 - API - Challenge

## Location of files
This assisgment has two parts. Part 1 is a WeatherPy exercise and part 2 is VacationPy exercise. Both of the excerises has been stored in the GitHub folder called **'main_code'**. The output for the part 1 has been stored in **'output_data'** rather than inside the 'main_code' folder for convenince.  The **'research'** folder has a .json output file, which was used to understand the heirrachy of information to know where specific returned infomation from the API can be extracted from.

## WeatherPy Exercise
In this exercise the numpy module was used to generate random latitude and longitude coordinates. These were in turn used in the **citypy** library to find the nearest city in thse coordinates.

In this exercise we contined to use the numpy generated coordinates however the exact city coordinates may have been another way of having done this excerise. Meaning the names of the cities could have been quired using the Geoapify to find the city coordinates.

The OpenWeather API was used to extract the weather information for each of the cities and added to the 'city_data' dataframe. The output dataframe was saved to a .CSV file in the 'output_data' folder.

Using the dataframe a series of scatter plots were completed using 'matplotlib' module in python. A regression analysis was also completed for each of these scatter plots. As part of the rehression analysis the regression line was plotted and the equation of the line annotated to the chart.  The R and R squared value was calculated and displayed. A brief discussion about the linear relationship of the set of scatter plots for borthern and sourthen hemisphere has been provided.

## VacationPy Exercise
In this exercise the dataframe created in the WeatherPy exercise was used to plot the cities on a world map with the size of the dots representing the humidity.  The 'Holoviews' module was used for these plots.

A second dataframe called 'hotel_df' was created using the primary cities dataframe to include cities with ideal holiday conditions (personal preferrences). This new dataframe was used to locate the closest hotel in that area using the Geoapify API. Any location which did not return a hotel name in a 10,000 meter radius was dropped. 

Using the locations in the 'hotel_df' a new map was created showing the location with the name of the hotel and the country in the hover information.

## API Keys
Both the [OpenWeatherMap API](https://openweathermap.org/api) and the [Geoapify API](https://www.geoapify.com/) require keys. Please use the hyperlinks for more information.