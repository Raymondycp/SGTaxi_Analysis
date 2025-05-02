# **Singapore Taxi Availability Analysis**

## Overview
This project analyzes real-time taxi availability data in Singapore using the [Data.gov.sg API](https://data.gov.sg/). The notebook explores patterns in taxi availability, performs business analysis, and includes predictive modeling.

## Key Features

* Data Collection: Fetches live taxi GPS coordinates from the government API  
* Time Series Analysis: Examines hourly/daily patterns and weekday vs weekend differences  
* Geospatial Visualization: Plots taxi locations on an interactive Singapore map  
* Predictive Modeling: Uses Prophet \+ LightGBM hybrid model to forecast taxi demand  
* Statistical Analysis: Includes ANOVA tests and distribution analysis

## Usage

1. Run the notebook cells sequentially  
2. For mapping, ensure you have a valid Google Maps API key set as an environment variable GMAP  
3. The analysis can be adapted by modifying the date ranges in the time series functions

## Packages

- pandas  
- numpy  
- requests  
- matplotlib  
- seaborn  
- bokeh  
- prophet  
- lightgbm  
- scipy

## Data Sources

* Primary API: [https://api.data.gov.sg/v1/transport/taxi-availability](https://api.data.gov.sg/v1/transport/taxi-availability)  
  * Sample dataset included covers Jan-Apr 2024

## Findings

1. Taxi availability follows clear daily patterns with morning/evening rush hours  
2. Weekends show different availability patterns than weekdays

## Files

* taxi\_data.csv: Processed dataset (optional)  

