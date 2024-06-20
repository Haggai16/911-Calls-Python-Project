## Project Overview
The 911 Calls Project is a comprehensive analysis of emergency calls data. The dataset contains information about emergency calls made to the 911 service. The primary objective of this project is to uncover insights and trends within the data, such as the frequency and distribution of different types of emergencies, temporal patterns, and geographic analysis.

## Dataset
The dataset used in this project includes the following features:

- lat: Latitude coordinate of the call
- lng: Longitude coordinate of the call
- desc: Description of the emergency call
- zip: ZIP code where the call was made
- title: Title of the emergency
- timeStamp: Timestamp of the call
- twp: Township where the call was made
- addr: Address of the emergency
- e: Dummy variable (always 1)

## Analysis and Visualizations
In this project, I performed the following analyses and visualizations:

1. Data Cleaning and Preprocessing: Handling missing values, parsing dates, and feature engineering.
2. Exploratory Data Analysis (EDA):
- Distribution of emergency call types.
- Temporal analysis to find patterns over time (hourly, daily, monthly).
- Geographical analysis using scatter plots and heatmaps.
3. Visualizations:
- Bar plots, line plots, and heatmaps to visualize trends and patterns.
- Interactive maps to show the geographic distribution of calls.

## Results
Some of the key findings from the analysis include:

- Most Common Emergency Types: The top categories of emergencies were traffic-related incidents, followed by fire and medical emergencies.
- Temporal Patterns: Analysis revealed peak times for emergency calls, showing higher frequencies during certain hours of the day and specific days of the week.
- Geographic Distribution: Certain areas had higher concentrations of emergency calls, highlighting potential hotspots for specific types of incidents.
  
## Tools and Libraries Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Plotly
Jupyter Notebook
