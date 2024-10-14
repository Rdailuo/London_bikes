# London Bike Rides Analysis Dashboard

This project leverages Python for data gathering, exploration, assessment, and manipulation using the pandas library. The final visualization is achieved through Tableau, employing set actions, user-defined dynamic parameters, and calculated fields to create an interactive and impactful dashboard.

## Project Objectives
The objective of this project is to provide actionable insights into London bike ride patterns based on weather conditions. It serves as a tool for urban planners, researchers, and cycling advocates to better understand factors influencing bike usage and inform decisions related to urban mobility and infrastructure development.

## Project Overview
The dataset, sourced from Kaggle, consists of various weather and bike ride metrics recorded in London. It includes:

- timestamp: Timestamp field for data grouping.
- cnt: Count of new bike shares.
- t1: Real temperature in Celsius.
- t2: "Feels like" temperature in Celsius.
- hum: Humidity in percentage.
- wind_speed: Wind speed in km/h.
- weather_code: Category of weather conditions.
- is_holiday: Boolean field indicating holiday (1) or non-holiday (0).
- is_weekend: Boolean field indicating weekend (1) or weekday (0).
- season: Meteorological season category (0-spring, 1-summer, 2-fall, 3-winter).

## Data Source and Preparation
The dataset was extracted from Kaggle, preprocessed in Python to ensure data accuracy and integrity, and then visualized in Tableau. Python's pandas library facilitated data exploration and manipulation, preparing it for Tableau's visualization capabilities.

## Technical Details
**Tools Used:** Python (pandas), Tableau

**Data Preprocessing:** Python scripts were used for data cleaning, handling missing values, and preparing aggregated datasets for visualization.

**Visualization Techniques:** Tableau features like set actions, user-defined dynamic parameters, and calculated fields were employed to enhance interactivity and insight generation within the dashboard.

## Dashboard Visuals
**-  Total Rides:** Displays the cumulative number of bike rides recorded within the selected time range.

**- Moving Average:** A line graph showing daily bike rides with a moving average line to smooth short-term fluctuations and highlight longer-term trends. The moving average period can be adjusted using the control box to explore trends over different intervals.

**- Temperature vs. Wind Speed Heatmap:** A matrix heatmap that visualizes the number of bike rides in relation to temperature (°C) and wind speed (kph). Darker shades represent higher numbers of bike rides, enabling quick identification of weather conditions with the highest bike activity.

Feel free to explore the dashboard! [London Bikes Ride with Python and Tableau](https://github.com/Rdailuo/London_bikes/blob/main/London%20Bikes%20Rides%20Tableau%20Dashboard.twbx)

**Credits**
This project was created by following the guidance from Mo Chen https://mochen.info/. Special thanks for providing an insightful tutorial on using Python and Tableau for data analysis and visualization.


