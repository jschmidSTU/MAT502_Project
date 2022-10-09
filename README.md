# MAT502_Project

Problem: How has climate change influenced weather statistics in global cities?
Climate change is a ubiquitous topic all around the world. The scope of this project is the investigation of climate trends. It is crucial to find and analyze weather data from previous years. Here it is important not just to consider the weather of recent years, but also continuous data reaching up to 50 years ago. With the aid of statistical analysis methods in python, we can perform a descriptive analysis of weather data between different metropoles in the US and determine correlations and trends. Using this knowledge, we can also make forecasts for upcoming years. All the mentioned files and code are found in GitHub (https://github.com/jschmidSTU/MAT502_Project).

The first part of this project is to investigate weather trends beginning from the mid-20th century in the US. It is interesting to see if there is a statistically significant difference between recent weather data and weather data collected decades ago. In this project, the US cities Miami, New York, and Los Angeles are considered.

1. Compare the mean average temperature for period 1 (1961 – 1970) and period 2 (2011 – 2020)
Files: Miami.csv, NY_JFK.csv, LAX.csv
Code: avg_temperature_comparison.ipynb

2. Investigate if there is a correlation between the maximum temperatures. 
Files: Miami.csv, NY_JFK.csv, LAX.csv
Code: max_temperature_correlation.ipynb

3. Compare the precipitation for period 1 (1961 – 1970) and period 2 (2011 – 2020) 
Files: Miami.csv, NY_JFK.csv, LAX.csv
Code: precipitation_comparison.ipynb


The second part then asks the question of whether climate catastrophes such as droughts can be predicted using available weather data. This will be done through a linear regression approach.
File: drought.csv (https://www.kaggle.com/datasets/cdminix/us-drought-meteorological-data, the file is called “validation_timeseries.csv”)
Code: regression_drought.ipynb
