# Wildfire Analysis and Prediction (1992-2015)

## Project Overview
- This project involves a detailed analysis and prediction of wildfires in the United States from 1992 to 2015. Utilizing a dataset with over 1.88 million records, the study focuses on understanding the patterns and causes of wildfires and developing machine learning models to predict the duration and likely causes of these events.

## Introduction
- Wildfires are a significant natural hazard with extensive ecological, economic, and societal impacts. This project aims to analyze wildfire data from 1992 to 2015 to understand trends, causes, and impacts of wildfires and to address challenges in wildfire prediction and management.

## Dataset Overview
- The dataset used in this project is a spatial database covering wildfires in the United States from 1992 to 2015, containing 1.88 million records and covering 140 million acres burned. The data was sourced from federal, state, and local reporting systems and standardized according to the National Wildfire Coordinating Group (NWCG) standards.

## Key Attributes
- FIRE_YEAR: Year when the fire was discovered.
* DISCOVERY_DATE: Exact date when the fire was discovered.
+ FIRE_SIZE: Size of the fire in acres.
- FIRE_SIZE_CLASS: Categorical size class of the fire.
* STAT_CAUSE_DESCR: Descriptive cause of the fire.
+ LATITUDE, LONGITUDE: Geolocation of the fire.
- STATE: US state where the fire occurred.
* COUNTY: County where the fire occurred.

## Key Insights
- Wildfire Distribution Over the Year: Analysis showed that wildfires are more frequent during late spring and summer (April to August).
- Causes of Wildfires: Human-related activities were identified as the primary cause for approximately 85% of wildfires.
- Wildfire Size Class Distribution: Distribution of fire sizes revealed varying patterns, with significant occurrences in certain size classes.
- Trends Over the Years: The data indicated trends in fire sizes and causes over the 24-year period.
- Geographic Distribution: California, Texas, and Colorado emerged as the most wildfire-prone states, contributing to nearly 40% of all incidents.
- Season-wise Distribution: Wildfires showed distinct seasonal patterns, with significant differences between weekdays and weekends.

## Predictive Modeling
Machine learning models were developed to predict:

1 Fire Size
2 Fire Duration (Time to Contain the Fire)
3 Cause of the Wildfire
