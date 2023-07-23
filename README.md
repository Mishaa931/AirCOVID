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
- `monthly_bar`: Bar chart displaying the total number of daily records by month.
- `hist`: Histogram showing the distribution of operation records running at a percentage of their pre-COVID baseline.
- `airport_scatter`: Scatter plot depicting the operation record distribution by airport.
- `country_piechart`: Pie chart representing flight records by country.
- `scatter_baseline`: Interactive scatter_geo plot with cross markers representing airports reporting operating activity during the ongoing COVID-19 pandemic.

Please note that the code provided here is for demonstration purposes, and the dataset used may have been subject to updates or changes. Feel free to customize the visualizations and analysis to explore different aspects of airport traffic during the COVID-19 pandemic.

---
For any queries or further discussions, please contact [your_email@example.com].
