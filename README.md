# Distributed Machine Learning Regression using PySpark
# Project Overview
This project implements a Distributed Regression Model using PySpark to analyze large-scale taxi trip data. The goal is to apply distributed computing techniques for big data processing and evaluate regression model performance efficiently.

The project was developed and executed using Google Colab.

#  Information for Dataset
The dataset used in this project is larger than 1GB, so it cannot be uploaded directly to GitHub.

You can download the dataset from the official NYC Taxi & Limousine Commission source:

🔗 https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page

Download Instructions:

Go to 2012 → Yellow Taxi Trip Records (PARQUET/CSV).
Download all monthly files (January 2012 – December 2012).
Files are typically in Parquet format (~100MB+ per month).
Create a folder named:
dataset/

Place all downloaded files inside this folder.
Upload the folder to your Google Drive.

# Technologies Used
- Python

- PySpark

- Google Colab

- Tableau (Data Visualization)

# Workflow for the project

The project follows a structured big data pipeline:

1.Data Loading (Parquet format)
2.Data Cleaning & Preprocessing
3.Feature Engineering
4.Regression Model Training (PySpark MLlib)
5.Model Evaluation
6.Performance Comparison
7.Visualization (Tableau)


# Model Evaluation Metrics

The regression models were evaluated using:
1.RMSE (Root Mean Squared Error)
2.MAE (Mean Absolute Error)
3.R² (R-Squared Score)

These metrics measure prediction accuracy and overall model performance.

# Learning Outcomes
1.Understanding distributed machine learning concepts
2.Processing and managing large-scale datasets
3.Implementing regression models using PySpark
4.Evaluating model performance using multiple metrics
5.Building reproducible big data workflows

# Author
Student Name: Uma Naguru

Course: MSc Data Science

Module: 7006SCN-Machine Learning and Big data 

University: Coventry University
