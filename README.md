# Final-Project-Statistical-Modelling-with-Python

## Project/Goals
This project focuses on gathering, analyzing, and correlating data related to bike stations in Vancouver. The primary objectives include retrieving bike station information using the CityBike API, exploring Points of Interest (POI) with Yelp and Foursquare APIs, performing Exploratory Data Analysis (EDA), and building a predictive model to investigate the correlation between the number of bikes in use and the surrounding POI.

## Process
1. API Calls:
Utilized the CityBike API to obtain comprehensive data on bike stations in Vancouver.
Invoked Yelp and Foursquare APIs to gather information about Points of Interest in the vicinity.

2. Data Exploration:
Conducted Exploratory Data Analysis (EDA) on the collected data to unveil insights and patterns.

3. Correlation Modeling:
Built a predictive model to investigate potential correlations between the number of bikes in use at a station and the surrounding Points of Interest.

## Project Highlights:

1. Data Sources:
CityBike API for bike station details.
Yelp and Foursquare APIs for Points of Interest information.

2. Analytical Approach:
Explored the dataset using statistical and visual analysis techniques.
Implemented machine learning techniques to quantify relationships between variables.

3. Insights and Findings:
Uncovered patterns and correlations within the data.
Provided insights into how the availability of bikes may be influenced by the surrounding points of interest.

## Results
Model Performance: Despite thorough exploration and analysis, the predictive model did not yield a significant correlation between the number of bikes in use and the surrounding Points of Interest. The R-squared value, a metric representing the goodness of fit, was found to be very low.

## Challenges 
Data Context: The data was collected specifically for a weekend during the winter season, which might impact the overall biking activity and the correlation with Points of Interest.

Dataset Size: The dataset comprised only 248 lat long pairs, which could limit the model's ability to capture nuanced patterns. A larger dataset might provide more robust insights.

Seasonal Variations: Seasonal variations, especially during winter, might influence both bike usage and the presence of people at Points of Interest.

## Future Goals
Extended Data Collection: Consider collecting data over an extended period, including different days of the week and seasons, to capture a more comprehensive picture. Expanding the dataset by collecting more samples could enhance the model's ability to generalize and identify patterns.

Additional Features: Incorporating additional features or external variables (e.g., weather conditions, events) may contribute to a more nuanced understanding.

## Project Structure:
/data:
Contains datasets and files used in the analysis.

/notebooks:
Jupyter notebooks detailing the data exploration, analysis, and modeling steps.

/images:
Holds visualizations and charts generated during the analysis.

## Dependencies:
Python 3.x
Jupyter Notebooks
Required Python libraries (specified in the project documentation)
