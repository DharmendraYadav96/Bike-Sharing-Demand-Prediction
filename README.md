# Bike-Sharing-Demand-Prediction
## Objective
The objective of this project is to predict bike-sharing demand at each hour for the stable supply of rental bikes in a city based on historical data. By building a predictive model, we aim to help bike-sharing companies optimize their bike allocation and better meet customer demand, ultimately improving the efficiency and user experience of their services.

## Dataset
The dataset used for this project contains historical information about bike rentals, includes features:
- **Date**: Current date
- **Rented Bike Count**: Dependent variable
- **Hour**:
- **Temperature(°C)**: (Numerical) Temperature at the time of booking in °C.
- **Humidity(%)**:
- **Wind speed (m/s)**: (Numerical) Wind speed.
- **Visibility (10m)**: (Numerical)
- **Dew point temperature(°C)**: (Numerical)
- **Solar Radiation (MJ/m2)**: (Numerical)
- **Rainfall(mm)** : (Numerical)
- **Snowfall (cm)** : (Numerical)
- **Seasons** : (Categorical)
- **Holiday** : (Categorical)
- **Functioning Day** : (Categorical)

## Data Wrangling
Data wrangling is an essential step in preparing the dataset for analysis and modeling. This phase involves cleaning, transforming, and structuring the data to make it suitable for further analysis. Common data wrangling tasks include handling missing values, encoding categorical variables, and feature engineering.

## EDA (Exploratory Data Analysis)
Exploratory Data Analysis is a crucial step in understanding the dataset and gaining insights from it. In this project, we perform EDA to:

### Numerical Analysis
Calculate summary statistics for numerical variables to understand their distributions.
Visualize numerical data using histograms, box plots, and scatter plots to identify patterns and outliers.
Explore correlations between numerical variables to understand their relationships.
### Categorical Analysis
Analyze the distribution of categorical variables using bar charts and count plots.
Explore how categorical variables impact bike-sharing demand.
Identify trends and patterns in categorical data that may affect predictions.
By conducting thorough EDA, we aim to uncover valuable information about the dataset that will guide feature selection, engineering, and model building, ultimately leading to more accurate predictions of bike-sharing demand.
