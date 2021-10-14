# ford_used_cars_analysis

As the price of new model cars skyrocket, more and more people are opting to purchase used cars. This dataset includes information on such resold cars of differents models of Ford cars during the year 1996 and 2020. This repository contains a csv file of the dataset used for the analysis and a Jupyter Notebook of data visualization (ford_used_cars_EDA) code of correlation analysis and distribution of observations in the dataset, and ML model (Ford_used_cars_ML) for price prediction of the cars. The dataset contains 17964 observations (rows) and 8 attributes (columns). 

The attributes of the dataset are: 
  - **model** - model of the car
  - **year** - year of manufacture
  - **price** - price of the car
  - **transmission** - type of transmission in the car (Automatic, Manual and Semi-automatic)
  - **mileage** - mileage of the car
  - **fuelType** - type of fuel used in the car (Petrol, Diesel, Electric, Hybrid and Others)
  - **mpg** - miles the car run per gallon
  - **engineSize** - size of the engine used in the car

**Data processing and cleaning:**
1. Importing necessary python packages
2. Reading the excel (.csv) file and naming the new dataFrame
3. Finding the number of rows and columns
4. Finding the data types and missing values
5. Descriptive Statistics of the dataset

**Data Analysis Objectives** 
1. Visualising the dataset using barplots.
2. Finding the relationship between Price and Mileage.
3. Finding the Change in Price and Mileage, based on fuel types
4. Visualizing Price Distribution
5. Visualizing Empirical Cumulative Distribution Function (ECDF) of Price
6. Visualizing Statistical Summary of Price based on Transmission Types
7. Finding and Visualizing Data for Average Price, Total Price and Frequency of resold cars based on ar Models
8. Finding and Visualizing Data for Average Price, Total Price and Frequency of resold cars based on types of Transmission
9. Finding and Visualizing Data for Average Price, Total Price and Frequency of resold cars based on Fuel-type

**Data Visualisation**
In this project, the dataset has been visualised to find correlations between various factors, and distribution using barplot, scatter plot, regression plot, distribution plot, ECDF and boxplot. The following is the list of the figures in the notebook. 

- Fig 1. Categorical variables in the Ford used cars dataset
- Fig 2. Relationship between price and mileage
- Fig 3. Change in Price and mileage, based on fuel types
- Fig 4. Price distribution
- Fig 5. ECDF of Price
- Fig 6. Price for Transmission Types
- Fig 7. Barplots of the Ford Used Cars based on Model
- Fig 8. Barplots of the Ford Used Cars based on Transmission
- Fig 9. Barplots of the Ford Used Cars based on FuelType

**Price Prediction Model**
1. Identifying the feature and target variable
2. Splitting the train and test set
3. Running Linear Regression Model
4. Finding the Root Mean Squared Error (RMSE)

**Reference:**
<br>Dataset Source: https://www.kaggle.com/aishwaryamuthukumar/cars-dataset-audi-bmw-ford-hyundai-skoda-vw
