# WHOLifeExpectancyAnalysis

## Table of content

- [Project Overview](#project-overview)
- [Highlight](#highlight)
- [Data Source](#data-source)
- [Tools](#tools)
- [Techniques](#techniques)
    - [Data Preparation](#data-preparation)
    - [Exploratory Data Analysis](#exploratory-data-analysis)
    - [Predictive Modeling](#predictive-modeling)
    - [Tableau Dashboard](#tableau-dashboard)
- [Insights](#insights)
- [Limitations](#limitations)


## Project Overview

This project involved an extensive exploratory data analysis leveraging various techniques to explore global trends and patterns influencing life expectancy based on the WHO dataset. Life expectancy is a crucial indicator of a nation, and significant disparities persist between high-income and low-income countries. Identifying the factors that influence life expectancy is essential for evidence-based policymaking and health interventions. This project employs data analysis and visualization to explore global health inequalities, providing insights for targeted interventions to improve health outcomes worldwide.

## Highlight
- Exploratory data analysis - statistical analysis, missing value treatment, outlier detection, and treatment visualizations (univariate, bivariate, and multivariate analysis) and time series analysis
- Correlation analysis - to study relationships between features
- Regression modeling - multiple linear regression used for modeling and prediction
- Clustering - k-means clustering to group countries
- Tableau dashboards - for interactive data visualization

## Data Source

The dataset Life Expectancy Data.xlsx was obtained from Kaggle and it includes health, social, and economic indicators from the World Health Organization for 193 countries, with yearly observations from 2000-2015

## Tools

- Excel - Initial Exploration
- Python - Data Cleaning, Analysis and Modelling 
- Seaborn - Visualization
- Matplotlib - Visualization
- Plotly - Visualization
- Tableau - Dashboard Report

## Techniques 
### Data Preparation:

- Loading and cleaning the dataset.
- Handling missing values.
- Renaming columns.

### Exploratory Data Analysis:
Questions
1. Which countries and regions have experienced significant changes in life expectancy, and what factors might be responsible?
2. How do socio-economic and health factors influence life expectancy differences between and within countries?

- Univariate analysis for examining the distribution of health indicators, socioeconomic indicators, and healthcare access.
- Bar charts for comparing life expectancy between developed and developing countries.
- Time series charts for visualizing changes in life expectancy over time.
- Scatterplots for bivariate analysis.
- Heatmaps for visualizing correlations between features.

### Predictive Modeling:

- Multiple Linear Regression.
- Feature Selection.
- Principal Component Analysis (PCA) for dimensionality reduction.
- K-means Clustering for categorizing countries based on life expectancy.

### Tableau Dashboard: 
Creating visualizations to explore life expectancy and related factors across continents.      

## Insights

- Analysis revealed that factors like schooling, income composition, and adult mortality significantly influence life expectancy. 
- Analysis also revealed global health disparities between developed and developing countries with developed countries having higher life expectancy but developing countries showing a higher growth rate. 
 - K-means clustering identified distinct groupings, including a cluster for India due to its large population and high under-five deaths and countries with high HIV/AIDS prevalence and low life expectancy.
- Predictive modeling using principal component analysis gave the highest accuracy of 80% in predicting life expectancy
- The insights can inform evidence-based policies and interventions to address health inequalities.

## Limitations 
Addressing data quality concerns, including missing values and outliers, posed challenges. As a result, I made the decision to remove the BMI column since it contained extreme outliers, making it difficult to verify the data's accuracy.
