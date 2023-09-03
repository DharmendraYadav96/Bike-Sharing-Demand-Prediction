# Bike-Sharing-Demand-Prediction
## Objective
The objective of this project is to predict bike-sharing demand at each hour for the stable supply of rental bikes in a city based on historical data. By building a predictive model, we aim to help bike-sharing companies optimize their bike allocation and better meet customer demand, ultimately improving the efficiency and user experience of their services.

## Dataset
The dataset used for this project contains historical information about bike rentals, includes features:
- **Date**: Current date
- **Rented Bike Count**: Dependent variable
- **Hour**: Hour of the day (0-23)
- **Temperature(°C)**: (Numerical) Temperature at the time of booking in °C.
- **Humidity(%)**: Humidity measure
- **Wind speed (m/s)**: (Numerical) Wind speed.
- **Visibility (10m)**: (Numerical) Visibility measure
- **Dew point temperature(°C)**: (Numerical) Dew point temperature measure
- **Solar Radiation (MJ/m2)**: (Numerical) Solar radiation measure
- **Rainfall(mm)** : (Numerical) Rainfall in mm
- **Snowfall (cm)** : (Numerical) Snowfall in mm
- **Seasons** : (Categorical) 4 seasons
- **Holiday** : (Categorical) Whether a holiday or not
- **Functioning Day** : (Categorical) Whether a functional day or not

## Data Wrangling
Data wrangling is an essential step in preparing the dataset for analysis and modeling. This phase involves cleaning, transforming, and structuring the data to make it suitable for further analysis. Common data wrangling tasks include handling missing values, encoding categorical variables, and feature engineering.

## EDA (Exploratory Data Analysis)
Exploratory Data Analysis is a crucial step in understanding the dataset and gaining insights from it. By conducting thorough EDA, we aim to uncover valuable information about the dataset that will guide feature selection, engineering, and model building, ultimately leading to more accurate predictions of bike-sharing demand.

### Numerical Analysis
- Calculate summary statistics for numerical variables to understand their distributions.
- Visualize numerical data using histograms, box plots to identify patterns and outliers.
- Explore correlations between numerical variables to understand their relationships.
### Categorical Analysis
- Analyze the distribution of categorical variables using bar charts and count plots.
- Explore how categorical variables impact bike-sharing demand.
- Identify trends and patterns in categorical data that may affect predictions.

Following plots are drawn: 
1. Histogram (with median and mean lines) and Boxplot
2. Q-Q plot
3. Scatter plot 
4. Bar graphs
5. Correlation heatmap
6. Pair Plot
