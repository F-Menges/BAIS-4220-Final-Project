# BAIS-4220-Final-Project
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)  ![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=Databricks&logoColor=white)  ![Spark](https://img.shields.io/badge/Apache_Spark-FFFFFF?style=for-the-badge&logo=apachespark&logoColor=#E35A16)

Contributors: Felix Menges, Jet Chanchom, & Jenna Anderson

## Project Overview
Final Project for BAIS:4220 Adv Database Mgt & Big Data analyzing liquor sales activity in Iowa City from January 1st, 2023, to March 31st, 2025, using data from the [Iowa Department of Revenue](https://data.iowa.gov/Sales-Distribution/Iowa-Liquor-Sales/m3tr-qhgy/data_preview). The dataset tracks liquor orders made by Iowa Class "E" licensees, meaning it reflects how **stores purchase and restock liquor**, not direct consumer sales. This distinction allows us to analyze supply-side behavior, revealing patterns in how different stores restock their liquor inventory throughout the year.

The original statewide dataset spans from 2012 to the present, but we filtered it to focus on Iowa City for the most recent two-year period. Our final dataset includes 127,067 rows and 24 columns. Our analysis aimed to answer the following questions:
- What are the top-selling types and brands of liquor in Iowa City?
- Are there trends in liquor sales, such as certain days of the week or seasons?
- Is there a relationship between liquor prices and purchasing behavior?
- Which stores are the top sellers of liquor in Iowa City? Which type of store (i.e., grocery store, liquor store, gas station)?
- Is there a revenue difference between stores located near the university campus and stores not located near the university campus? 

## Instruction to run the application
1. Click this [link](https://proud-island-051e4ba10.6.azurestaticapps.net) to view the project and our analysis of our findings
2. Or download Adv_Database_Project_-_Jenna_Felix_Jet.html

## Technical Skills Gained 
This class focused on using DataBricks for working with large datasets (>100k rows). We used PySpark SQL and other PySpark functions to perform exploratory data analysis to answer our analysis questions. We used matplotlib and the built-in DataBricks graphing functions to create bar charts, line charts, histograms, box plots, and interactive maps. We also learned how to use PySpark to preprocess data and create machine learning models. In this project, we created a clustering model to group liquor stores by location and an association rule mining model (Frequent Pattern Growth) to find hidden relationships in liquor purchasing behavior.
