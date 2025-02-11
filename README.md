Pollution Analysis Project

Overview
This project analyzes pollution levels across the top 1,000 most populated cities worldwide, providing insights into air quality through various pollutants, including SO2, NO2, PM10, PM2.5, O3, and CO. The project integrates data visualization techniques to explore pollution trends, correlations, and geographic distribution.

Objectives
Identify the top 100 most and least polluted cities per pollutant.
Analyze the correlation between pollution levels and population size.
Provide interactive visualizations, including scatter plots, bar charts, heatmaps, and geographical maps.
Enable user interaction through dropdown filters for pollutant selection.

Tech Stack
Programming Language: Python
Data Handling: Pandas
APIs Used: OpenWeather API (for pollution data)
Visualization Libraries: Matplotlib, Seaborn, Plotly, hvPlot
Interactive Widgets: ipywidgets

Dataset
The dataset contains:
City and country names
Population size
Latitude and longitude
Air pollutant concentration levels (SO2, NO2, PM10, PM2.5, O3, CO)

Features & Methodology

Data Collection:
Uses OpenWeather API to retrieve real-time pollution data for major cities.
Stores data in a Pandas DataFrame for further processing.

Data Processing:
Cleans and renames columns for consistency.
Identifies the top 100 most and least polluted cities per pollutant.
Computes correlation matrices to explore relationships between pollutants.

Visualization & Interaction:
Scatter Plots: Show pollution levels vs. population.
Bar Charts: Display the top 10 most and least polluted cities for each pollutant.
Heatmaps: Illustrate the global distribution of pollution levels.
Geospatial Maps: Provide an interactive way to explore pollution data by city.

How to Run the Project
Install Dependencies:
pip install requests pandas matplotlib seaborn plotly hvplot ipywidgets citipy

Set Up API Keys:
Obtain an API key from OpenWeather.

Store it in an api_key.py file:
geoapify_key = "your_geoapify_api_key"
weather_api_key = "your_openweather_api_key"

Run the Jupyter Notebook:
Open and execute each cell in the provided Jupyter Notebook to generate visualizations.

Contributors
Anna Howell
Caleb Schmitt
Diana Gibson
Michael Bowman 
Kanchan Ratan
Caleb 2.0

Reference:
Chat GPT