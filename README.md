README for WeatherPy and VacationPy

Overview
This repository contains two Jupyter Notebook files: WeatherPy.ipynb and VacationPy.ipynb. These Python scripts perform weather data analysis and create visualizations to support travel planning based on weather conditions. The project uses APIs and data visualization libraries to gather and process data.

WeatherPy

Purpose:
Collect weather data for multiple cities worldwide and analyze correlations between weather parameters such as temperature, humidity, wind speed, and latitude.

Main Features:
Generates a random list of geographic coordinates.
Retrieves weather data for each location using the OpenWeatherMap API.

Creates scatter plots to analyze the relationships between:
Latitude and temperature
Latitude and humidity
Latitude and cloudiness
Latitude and wind speed
Saves weather data and visualizations to local files.

Key Libraries:
pandas
numpy
matplotlib
citipy
requests

Required Setup:
Obtain an OpenWeatherMap API key.
Install necessary Python libraries using pip (if not already installed).

Output Files:
CSV file of weather data
PNG files of scatter plot visualizations

VacationPy

Purpose:
Build on WeatherPy’s data to identify ideal vacation spots based on specific weather criteria.
Generate a map of potential vacation destinations with markers for nearby hotels.

Main Features:
Filters WeatherPy’s data based on user-defined weather conditions (e.g., temperature range).
Uses the Google Maps API to locate hotels near the selected locations.
Creates a heatmap of humidity across the filtered destinations.
Plots vacation spots and hotel information on an interactive map.

Key Libraries:
pandas
matplotlib
gmaps
requests

Required Setup:
Obtain API keys for both OpenWeatherMap and Google Maps.
Install necessary Python libraries using pip (if not already installed).

Output Files:
Interactive map visualization
Heatmap of humidity
Usage Instructions
Clone the repository or download the notebook files.
Ensure Python and Jupyter Notebook are installed on your machine.

Install the required libraries using pip:
pip install pandas numpy matplotlib requests gmaps citipy
Add your OpenWeatherMap and Google Maps API keys where indicated in the notebooks.
Run each notebook cell by cell in Jupyter Notebook to reproduce the analysis and visualizations.

Notes
Ensure a stable internet connection as the scripts fetch data from APIs.
Large datasets may result in longer processing times.
Save your API keys securely and avoid sharing them publicly.



