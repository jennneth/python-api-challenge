# python-api-challenge
What's the weather like as we approach the equator?  I'll answer this question while using API calls to public datasets, and python methods for manipulating data and plotting graphs.

The project consists of two modules:

WeatherPy randomly selects at least 500 cities and pulls current and max temp weather data from a public dataset.
The maximum temperature, humidity , wind speed and cloudiness are plotted against the latitude of each city.
A regerssion analysis is performed and plotted to analyze the correlation between  the variables and an analysis is provided.

VacationPy takes the city and weather data from WeatherPY and maps via Google Maps API the locations and a heatmap based on humidity.
Then I input my personal weather criteria for locating a vacation spot, reduce the dataset to identify which cities meet those criteria.
A hotel is found near each of those acceptable vacation cities, and plotted on the heatmap.
