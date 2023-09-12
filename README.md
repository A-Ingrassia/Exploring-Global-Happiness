# Exploring Global Happiness

## Tableau Storyboard
[Link](https://public.tableau.com/app/profile/andrew5395/viz/WorldHappinessReport_16936795111390/Story1)

## Overview
This repository contains the analysis and visualization of the World Happiness Report (WHR) data. The WHR is an annual publication that ranks countries based on various factors contributing to overall happiness and well-being. This project aims to explore the data, identify patterns, and draw insights into the key variables affecting happiness scores.

## Objectives
The primary objectives of this project, guided by the initial research objective, are as follows:

1. **Data Wrangling:** Clean, wrangle, and combine nine years of World Happiness Report data (2015 - 2023) to prepare it for analysis.

2. **Exploratory Analysis:** Conduct Principal Component Analysis (PCA) to understand the dataset's structure and obtained Explained Variance Ratios (EVRs) to identify key variables contributing to happiness scores.

3. **Regression Modeling:** Perform train/test split, train a linear regression model, and make predictions to quantify the impact of key variables on overall happiness scores.

4. **Cluster Analysis:** Use k-means clustering to categorize countries into distinct clusters based on their similarity in key variables related to happiness scores. Determine the optimal number of clusters and visualize the outcomes to gain insights into variable impacts over time.

5. **Temporal Analysis:** Examine temporal trends in happiness scores, conduct decomposition using rolling mean method, stationarize clusters, and check for autocorrelations to understand happiness dynamics over time.

6. **Data Visualization:** Create informative visualizations in Tableau to summarize and present the analysis process and results effectively.

## Tools
**Language**: Python

**Libraries**: Pandas, Numpy, Seaborn, Plotly, Matplotlib, Scipy, sykit-learn, statsmodels, and geopandas

**Software**: Jupyter Notebooks, Excel, and Tableau

## Skills Demonstrated
- Data Cleaning and Wrangling
- Principal Component Analysis (PCA)
- Linear Regression Modeling
- Unsupervised Learning (k-means Clustering)
- Time Series Analysis
- Data Visualization with Tableau
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Machine Learning and Predictive Modeling
- Statistical Testing (Dickey-Fuller Test)
- Interpretation of Explained Variance Ratios (EVRs)
- Model Evaluation and Result Visualization
- Geospatial Analysis

## Sources
- World Happiness Report Data: https://worldhappiness.report/archive/
- GeoJSON Data: https://datahub.io/core/geo-countries#python

## Data
Data is listed according to the order in which it was either used or created. 

- **2015_whr1.csv - 2023_whr1.csv:** Original data pulled directly from the WHR website (one for each year)
- **whr_combined_whr1.csv:** Cleaned/Wrangled and combined version of the original 9 dataframes
- **whr_df_whr2.csv:** "whr_combined_whr1.csv" with the addition of class columns
- **countries.geojson:** Unmodified geojson file containing country data
- **simplified_geojson.geojson:** Simplified version of "countries.geojson" (original version was too large)
- **country_geo.json:** Data used to create the choropleth map in WHR3 (country name discrepancies resolved)
- **df_data_whr3.csv:** Dataframe containing country names shared by WHR data and "country_geo.json" (discrepancies resolved) as well as happiness scores and years
- **standardized_df_whr4.csv:** Dataframe containing standardized versions of key variables (pulled from "whr_df_whr2.csv")
- **heatmap_df_whr4.csv:** Dataframe created in order to produce the heatmap in WHR4
- **regression_df_whr4.csv:** Dataframe containing actual vs predicted happiness scores
- **standardizied_df_modified_whr5.csv:** Data used to produce WHR5 cluster scatterplots
- **df_clusters_whr5.csv:** Dataframe created to identify the country/year combinations associated with each cluster
- **df_stats_whr5.csv:** Dataframe containing descriptive statistics for each cluster
- **merged_data_whr6.csv:** Dataframe used to produce the WHR6 line plots comparing average yearly happiness scores between clusters
- **merged_data_stationary_whr6.csv:** Stationarized version of "merged_data_whr6.csv" (created to check autocorrelations)

