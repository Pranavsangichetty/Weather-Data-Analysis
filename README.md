🌦️ Weather Data Analysis & Temperature Prediction

Time-Series Analysis & Regression

📝 Project Overview

This project focuses on exploratory data analysis (EDA) and temperature prediction using historical weather data. It analyzes long-term temperature trends and builds a regression model to forecast future temperature values.

The goal is to showcase data cleaning, time-series trend analysis, and predictive modeling using real-world environmental data.

📂 Repository Contents

File Name	Type	Description

weather_analysis.ipynb	Python Notebook	EDA, trend visualization, and regression modeling

daily_min_temp.csv	Dataset	Historical daily minimum temperature data

README.md	Documentation	Project explanation and usage guide

⚙️ Tech Stack

Component	Tool / Library	Purpose

Data Analysis	Pandas, NumPy	Data cleaning and preparation

Visualization	Matplotlib	Trend and comparison plots

Machine Learning	Scikit-Learn	Regression modeling

Programming Language	Python	Core implementation

🏗️ Data Preparation & Analysis

1️⃣ Data Cleaning

Handled malformed CSV rows

Standardized column names

Converted temperature values to numeric format

Removed missing or corrupted entries

2️⃣ Exploratory Data Analysis

Analyzed temperature trends over time

Visualized seasonal and long-term patterns

Identified anomalies and data consistency issues

🤖 Predictive Modeling

Model Used

Linear Regression

Features

Time index (Day sequence)

Historical temperature values

Evaluation Metrics

R² Score

Mean Absolute Error (MAE)

📊 Output & Insights

Visual comparison of actual vs predicted temperatures

Identifies long-term warming or cooling trends

Demonstrates regression-based forecasting on time-series data
