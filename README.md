# Intelligent-Traffic-Management-System

## Project Description
The ITMS project is an innovative solution designed to tackle urban traffic congestion using a network of IoT sensors, edge computing, and machine learning algorithms. The system collects real-time traffic data, analyzes it to predict traffic patterns, and optimizes signal timings to enhance traffic flow and reduce congestion. The repository contains all the development files, including datasets, analysis notebooks, and the machine learning models used in the project. The goal is to provide city planners and traffic managers with advanced tools for real-time traffic analysis and signal optimization, ultimately improving the commute for city dwellers.

## Dataset
The dataset is sourced from Kaggle. It can be accessed at:
https://www.kaggle.com/datasets/fedesoriano/traffic-prediction-dataset/data
The dataset was collected from real-time sensors placed at 4 junctions, capturing vehicle count data. The dataset comprises 48,120 instances.

Dataset Variables:
- `DateTime`: The date and time when the vehicle count was recorded.
- `Junction`: Identifier for the location where the data was collected.
- `Vehicles`: The number of vehicles detected.
- `ID`: A unique identifier for each data entry.


## Repository Contents

- `Intelligent Traffic Management System Report`: The comprehensive report detailing the project's scope, methodology, and findings.
- `Data.csv`: The dataset used in the project, encompassing traffic counts across multiple urban junctions.
- `Exploratary Analysis and Data Cleaning`: Code that walks through the initial data analysis and preprocessing steps.
- `Deep Learning Model`: Deep Learning model used for predicting traffic patterns.
- `Time Series Model`: The Time Series model developed to forecast future traffic trends.
- `Tableau Dashboard`: A visualization tool developed in Tableau to present insights and predictions from the models.
