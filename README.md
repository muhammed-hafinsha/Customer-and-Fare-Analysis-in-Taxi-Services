# Customer-and-Fare-Analysis-in-Taxi-Services

## Overview
This project performs Exploratory Data Analysis (EDA) and Data Preprocessing on a Taxi Fare dataset. The goal is to identify patterns in taxi trips, understand factors affecting fare amounts, and visualize relationships between trip features such as distance, passengers, payment methods, tips, and total fare.

## Dataset Information

The dataset contains taxi trip records with features related to passengers, distance traveled, fare charges, payment methods, tips, and total trip cost.

### Features

| Column | Description |
|----------|-------------|
| passengers | Number of passengers in the taxi |
| distance | Distance traveled during the trip |
| fare | Base fare amount |
| tip | Tip paid by the passenger |
| payment | Payment method used |
| total | Total trip cost |

## Project Objectives

- Perform data cleaning and preprocessing.
- Detect and handle missing values.
- Identify and analyze outliers.
- Explore relationships between trip distance and fare.
- Analyze payment method preferences.
- Visualize fare and tip distributions.
- Study correlations among numerical variables.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Data Preprocessing

### Steps Performed
- Checked dataset structure and data types.
- Identified missing values.
- Removed duplicate records.
- Detected outliers using boxplots and IQR.
- Prepared clean data for analysis.

## Exploratory Data Analysis

### Univariate Analysis
- Histogram distributions
- Boxplots for outlier detection
- Pie charts for categorical variables

### Bivariate Analysis
- Distance vs Total Fare
- Fare vs Tip
- Payment Method vs Total Fare
- Scatterplots with regression lines
- Violin plots for fare distribution

### Multivariate Analysis
- Correlation Heatmap
- Feature relationship analysis
- Impact of distance and fare on total amount

## Key Findings

- Trip distance has a strong positive relationship with total fare.
- Fare amount increases as travel distance increases.
- Credit card payments are more common than cash payments.
- Tips contribute significantly to the total fare amount.
- Fare and total charges exhibit strong positive correlation.
- Passenger count has minimal impact on fare compared to trip distance.

## Visualizations Included

- Histograms
- Boxplots
- Pie Charts
- Scatter Plots
- Regression Plots
- Violin Plots
- Correlation Heatmaps
- Bar Charts

## Conclusion

The analysis reveals that distance traveled is the primary factor affecting taxi fares. Payment methods and tips also influence total revenue, while passenger count shows relatively low impact. Visualizations provide clear insights into fare behavior and customer payment preferences.

## Author

**Muhammed Hafinsha M**  
B.Tech Artificial Intelligence & Data Science  
KTU University

---
⭐ If you found this project useful, consider giving it a star.
