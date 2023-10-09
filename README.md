# Project Report: Predicting Falcon 9 Rocket Landing Success

**By: Kshitij Sahu**
**Date: 6th October 2023**

## Table of Contents:
1. [Executive Summary](#executive-summary)
2. [Introduction](#introduction)
3. [Methodology](#methodology)
4. [Results](#results)
5. [Conclusion](#conclusion)
6. [Appendix](#appendix)

## 1. Executive Summary:
This project leverages various data collection methods, exploratory data analysis, interactive visual analytics, and machine learning to predict the success of Falcon 9 rocket landings. Data was collected from SpaceX API and web scraping of Wikipedia, followed by data wrangling and visualization. Interactive maps and dashboards were created, and predictive analysis using classification models was performed. The Decision tree classifier emerged as the best-performing model.

## 2. Introduction:
This project aims to predict the success of Falcon 9 rocket landings, which has a significant impact on launch costs. By analyzing factors that influence successful landings, this information can be valuable for potential competitors bidding against SpaceX. Key problems addressed include identifying the factors determining landing success, understanding interactions among various features, and specifying operating conditions for successful landings.

## 3. Methodology:
- **Data Collection:** Data collected through SpaceX API and web scraping.
- **Data Wrangling:** Cleaned and prepared data, created landing outcome labels.
- **Exploratory Data Analysis:** Visualized relationships between various factors.
- **Interactive Visual Analytics:** Created interactive maps and dashboards.
- **Predictive Analysis:** Built and tuned classification models, evaluated using accuracy.

## 4. Results:
- EDA revealed insights such as a positive correlation between flight amount and success rate at a launch site.
- Success rate increased from 2013 to 2020.
- Certain orbits (ES-L1, GEO, HEO, SSO, VLEO) had high success rates.
- KSC LC-39A had the most successful launches.
- Decision tree classifier yielded the highest classification accuracy.

## 5. Conclusion:
In conclusion, this project provided valuable insights into Falcon 9 rocket landing success factors. It highlighted the importance of flight amount, launch site, and orbit type. The Decision tree classifier proved to be the best model for predicting landing success.

## 6. Appendix:
- Data collection notebooks: [SpaceX API](https://github.com/Kodezilla0725/IBM_Data_Science_Capstone_SpaceX/blob/main/Data%20Collection%20API.ipynb), [Web Scraping](https://github.com/Kodezilla0725/IBM_Data_Science_Capstone_SpaceX/blob/main/Data%20Collection%20with%20Web%20Scraping.ipynb)
- Data wrangling notebook: [Data Wrangling](https://github.com/chuksoo/IBM-Data-Science-Capstone-SpaceX/blob/main/Data%20Wrangling.ipynb)
- EDA notebooks: [Data Visualization](https://github.com/chuksoo/IBM-Data-Science-Capstone-SpaceX/blob/main/EDA%20with%20Data%20Visualization.ipynb), [SQL](https://github.com/chuksoo/IBM-Data-Science-Capstone-SpaceX/blob/main/EDA%20with%20SQL.ipynb)
- Interactive maps: [Folium](https://github.com/chuksoo/IBM-Data-Science-Capstone-SpaceX/blob/main/Interactive%20Map%20with%20Folium.ipynb)
- Interactive dashboard: [Plotly Dash](https://github.com/chuksoo/IBM-Data-Science-Capstone-SpaceX/blob/main/app.py)
- Predictive analysis notebook: [Machine Learning Prediction](https://github.com/chuksoo/IBM-Data-Science-Capstone-SpaceX/blob/main/Machine%20Learning%20Prediction.ipynb)

This project provides actionable insights into rocket landing success and lays the foundation for further analysis and decision-making in the aerospace industry.
