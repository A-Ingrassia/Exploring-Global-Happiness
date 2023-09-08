# Exploring Global Happiness

## Tableau Storyboard
https://public.tableau.com/app/profile/andrew5395/viz/WorldHappinessReport_16936795111390/Story1

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
