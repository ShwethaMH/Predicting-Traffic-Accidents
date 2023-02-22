# Predicting-Traffic-Accidents
## Introduction
Traffic accidents are a major concern globally and cause significant loss of life, property damage and disrupt the transportation system. Despite efforts by governments, organizations and individuals to reduce the number of traffic accidents, they still remain a persistent problem. In this project, we aimed to use machine learning and traffic data to detect and mitigate traffic accidents.
## Project Overview
Traffic accidents are a complex and multifaceted phenomenon that can result from numerous factors. To identify the causes of these accidents and implement measures to mitigate them, and aim to employ various Data Analysis and Machine Learning techniques. The project objectives are as follows:
- Analyze the datasets provided by the Ministry of Transportation to determine the primary causes of traffic accidents.
- Perform comprehensive data preprocessing and analysis to gain insights into the causes of accidents.
- Develop either a traditional machine learning or deep learning model that can predict traffic accidents.
- Use test data to carry out inference with the trained model.
- Based on the information gathered from the provided datasets, offer recommendations on ways to reduce traffic accidents.
## Datasets
The Ministry of Transportation of Jordan provided us with three tabular datasets that include records of accidents from various areas of Jordan. The datasets are named "م 2021 .xlsx", "احداثيات 2021 .xlsx", and "NEWcrash data2.xls". These datasets contain information about the accidents, including accident ID, accident location, timestamp, and other relevant details.
To obtain further insights into the causes of traffic accidents in Jordan, we scraped additional data on the weather and holidays in Amman, Jordan from the internet.
## METHODOLOGY & TOOLS
- Translation of datasets from Arabic to English using Google Translate API for Python.
- Data quality check and data pre-processing.
- Exploratory data analysis (EDA)
- Cluster analysis: Scikit-Learn library
- Web scraping
## Conclusion 
Upon conducting a thorough analysis of the Dataset, several issues were identified:
- There was no information provided by the stakeholders regarding the data gathering and recording process.
- The dataset was incomplete and lacked sufficient recorded accident data for Aug 2014, Jan 2015, and May 2018.
- The dataset lacked columns with information relevant to the problem statement, with only Accident_Date, Latitude, and Longitude columns being significant. Year, -  Month, Day, Time, and Street columns were deemed irrelevant, and the meaning of some columns (C, B, A, K, O, On_Peop, Crash, Pedes, Run_off) remains unknown, hence unusable for analysis.
- Relevant columns in the 2021 dataset (e.g., Number_of_injuries, Number_of_deaths, Number of Casualties per accident, Surface_Condition, Road_Type, Road Lighting conditions, Speed of the vehicle at the time of accidents, Road_Characteristic, Vehicle Type, Number_of_Vehicles involved in the accidents, Cause of the accident (Driver_Mistake)) were absent from the New Crash data.
A lack of information about the circumstances surrounding the accidents made it difficult to draw causal inferences and identify confounding factors. Therefore, modeling was not conducted on the dataset to avoid producing biased and skewed results.
