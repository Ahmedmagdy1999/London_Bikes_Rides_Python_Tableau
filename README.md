# London Bike Sharing Data Analysis & Visualization

## Project Overview

This project analyzes the London Bike Sharing Dataset from Kaggle, transforming raw data into meaningful insights using Python (Pandas) and Tableau. The goal is to explore patterns in bike usage based on weather conditions, time factors, and other key variables, ultimately creating interactive visualizations to uncover trends.

## Tools & Technologies Used

Python (Pandas for data cleaning and preprocessing)

Tableau (For visualization and dashboard creation)

Excel (For exporting the cleaned dataset)

## Dataset Information

Source: Kaggle – London Bike Sharing Dataset

Columns:

time: Timestamp of data collection

count: Number of bikes rented

temp_real_c: Actual temperature (°C)

temp_feels_like_c: Feels-like temperature (°C)

humidity_percent: Humidity level (%)

wind_speed_kph: Wind speed (kph)

weather: Weather conditions

is_holiday: Whether the day is a holiday (Yes/No)

is_weekend: Whether it’s a weekend (Yes/No)

season: Season of the year

## Data Cleaning & Preprocessing

Using Pandas, I performed the following:

Loaded the dataset into a Pandas DataFrame.

Explored the data to check for missing values, unique values, and overall structure.

Selected relevant columns for analysis.

Renamed columns for better readability.

Converted humidity values to percentage format.

Mapped categorical values:

Converted numeric season codes into descriptive labels (e.g., Winter, Spring, Summer, Fall).

Mapped numerical weather codes into their respective descriptions.

Changed data types of categorical columns to string format.

Exported the cleaned dataset as an Excel file for use in Tableau.

## Data Visualization & Dashboard Creation

Using Tableau, I designed an interactive dashboard with the following insights:

 Moving Average Line Chart:

Includes filters for moving average duration, period, and timeline.

🌡️ Temperature & Wind Speed Analysis:

Created temperature and wind speed bins.

Developed a heatmap showing temperature vs. wind speed across different periods.

☁️ Weather Bar Chart & Hourly Rides Tooltip:

Bar chart displaying bike usage trends across different weather conditions.

Hourly breakdown tooltip for deeper insights.

## Dynamic Dashboard:

Combined all visualizations into a final, interactive dashboard for deeper exploration.

## Key Skills Demonstrated

✅ Data Cleaning & Transformation (Pandas, Python)
✅ Data Visualization & Dashboarding (Tableau)
✅ Data Mapping & Encoding (Replacing categorical values with meaningful labels)
✅ Feature Engineering (Creating bins, calculated fields, and filters)
✅ Storytelling with Data (Translating raw data into actionable insights)

## Conclusion

This project demonstrates end-to-end data analysis, from data wrangling in Python to building a dynamic Tableau dashboard. The insights gained can help city planners optimize bike-sharing systems based on weather conditions and peak usage times.

## Check out the full project on GitHub: https://github.com/Ahmedmagdy1999

## Check out My Linkedin: https://linkedin.com/in/ahmed-magdy-yahia-0b456a1a6

## Check out the dashboard on Tableau public: https://public.tableau.com/views/LondonBikesRides_17412667406820/Dashboard1?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

