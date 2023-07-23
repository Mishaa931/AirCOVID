# COVID-19 Airport Traffic Analysis

## Table of Contents

1. Introduction
2. Dependencies
3. Data Loading and Preprocessing
4. Data Visualization

## 1. Introduction

The COVID-19 pandemic has significantly affected the aviation industry, leading to a drastic reduction in air travel. This project aims to explore and visualize the impact on airport traffic using Python and Plotly.

## 2. Dependencies

To run the code in this repository, you will need the following Python packages:

- numpy
- pandas
- plotly.graph_objects
- plotly.offline
- plotly.express

## 3. Data Loading and Preprocessing

The dataset is loaded using pandas from the 'covid_impact_on_airport_traffic.csv' file. We perform data preprocessing steps such as handling null values, parsing dates, and adjusting column names for better analysis.

## 4. Data Visualization

The repository includes various interactive visualizations created using Plotly. These visualizations include bar charts, histograms, pie charts, and scatter plots, providing insights into the daily records by weekday, monthly records, percent of baseline operation, airport record distribution, records by country, and geographic locations of airports.

- `daily_bar`: Bar chart showing total records by weekday.
  
  <p align="center">
  <img src="https://github.com/Mishaa931/COVID-19-Airport-Traffic-Analysis/blob/main/Graphs/graph1.png", alt=" Daily Bar Chart " width="50%" height="50%">
</p>

- `monthly_bar`: Bar chart displaying the total number of daily records by month.

<p align="center">
  <img src="https://github.com/Mishaa931/COVID-19-Airport-Traffic-Analysis/blob/main/Graphs/Graph2.png", alt=" Monthly Bar Chart " width="50%" height="50%">
</p>

- `hist`: Histogram showing the distribution of operation records running at a percentage of their pre-COVID baseline.
<p align="center">
  <img src="https://github.com/Mishaa931/COVID-19-Airport-Traffic-Analysis/blob/main/Graphs/Graph3.png", alt=" Histogram-Distribution of Operation Records " width="50%" height="50%">
</p>

- `airport_scatter`: Scatter plot depicting the operation record distribution by the airport.
<p align="center">
  <img src="https://github.com/Mishaa931/COVID-19-Airport-Traffic-Analysis/blob/main/Graphs/Graph2.png", alt=" Scatter Plot-Distribution of Operation Records " width="50%" height="50%">
</p>

- `country_piechart`: Pie chart representing flight records by country.
<p align="center">
  <img src="https://github.com/Mishaa931/COVID-19-Airport-Traffic-Analysis/blob/main/Graphs/Graph5.png", alt=" Piechart- Flight Records" width="50%" height="50%">
</p>

- `scatter_baseline`: Interactive scatter_geo plot with cross markers representing airports reporting operating activity during the ongoing COVID-19 pandemic.
<p align="center">
  <img src="https://github.com/Mishaa931/COVID-19-Airport-Traffic-Analysis/blob/main/Graphs/Graph6.png", alt=" scatter_geo plot" width="50%" height="50%">
</p>

## Conclusions
Presently, based on the analysis conducted in this notebook, the following conclusions have been drawn:

1. Tuesday and Wednesday emerged as the busiest weekdays, each recording a substantial 10,641,064 operations.
2. Conversely, Sunday exhibited the lowest activity with only 994,994 records.

Additionally, it was observed that the month of December had the least activity, with a mere 5,656 records.

Furthermore, a comparative analysis of record counts between countries revealed that the United States significantly surpassed all others, boasting a remarkable 44,414,441 records, nearly doubling the second-highest record count held by Canada, which stood at 23,112,311.

Upon considering the dataset's distribution and visualizing the active airports on a map projection, the evidence suggests that the containment measures implemented by the United States during the COVID-19 pandemic did not involve substantial restrictions on airport travel.


Please note that the code provided here is for demonstration purposes, and the dataset used may have been subject to updates or changes. Feel free to customize the visualizations and analysis to explore different aspects of airport traffic during the COVID-19 pandemic.

---
For any queries or further discussions, please contact misbahnoor2017@gmail.com.
