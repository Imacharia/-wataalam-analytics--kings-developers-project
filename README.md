# PHASE 2 HOUSING PROJECT.


# $Authors$ 
( Ian Macharia , Pauline Njeri , Dennis Mwanzia , Samuel Igecha , Pamela Awino )

# Project Introduction & Overview.

The aim of this project is to put into practice our newly aqcuired skills in data science to formulate and solve a real business problem. In this project, we are given a raw dataset which is the house sales prices in Northwestern County and we are supposed to formulate a real business case study and use the data to solve the business problem and provide a useful business advisory which can be used to formulate real and valuable business decisions. Unlike in phase 1, we are not given the business problem, its upon us to formulate it.


# Data Understanding 
* Data
We utilized the following dataset to help make predictions of house prices in Kings County 
King County House Data: a dataset that we were provided at the onset of the project. This file contains data for 21,597 homes built in King County, Seattle from 1900 to 2015. Each home in the set contains information regarding features such as number of bedrooms/bathrooms, number of floors, square footage, zip code, condition, and more.

### We have been given a dataset that contains the following variables;
* id
* date
* price 
* bedrooms 
* bathrooms 
* sqft_living 
* sqft_lot
* floors
* waterfront
* view
* condition
* grade
* sqft_above
* sqft_basement
* yr_built
* yr_renovated
* zipcode
* lat
* long
* sqft_living15
* sqft_lot15


# Business Problem

The business problem is to provide guidance to Kings Wajenzi Developers, a prospective real estate developer in King County, on the most profitable types of properties to target in the current market. The guidance will include recommendations on optimal locations to develop properties, features most desired by customers and have the greatest impact on prices of properties, and season of year when homeowners are most likely to purchase properties. Our objective as Wataalamu Analytics Advisors is to analyze house sales data in King County which was collected between May 2014 and May 2015 and leverage the insights generated to guide the developer in selecting the most profitable properties to develop and maximize their profits. With King County's population on the rise and income stabilizing after the COVID-19 pandemic, demand for new homes in the area is at an all-time high.

### Objectives 

1. To determine whether the time of year affects the price of a house and identify the most profitable seasons/months.

2. To investigate whether location affects house prices in King County and identify the areas that attract the highest prices.

3. To determine which features/attributes have the highest impact on the sales price of houses/properties in King County and identify the features that developers should focus on when developing upcoming projects in the area.

### Guiding Questions

1. Does the time of the year affect the price of an house? If yes, which seasons/Months are most profitable?
2. Does Location affect prices? If yes, which locations within King county attract highest price of houses?
3. Which features/Attributes have the highest impact on sales price of houses/properties? Which features should the developer focus on when developing their upcoming projects in King County


### Approach

This project follows the OCEMiN Data Science framework for data analysis

1. Obtain/import data
* We will import dataimport data from King County House Data provided as csv, using Pandas library.
2. Clean/ Scrub data
* We will employ several data cleaning methods to modify and prepare the dataset for analysis.
3. Explore data/EDA
* Analyzing and visualizing the cleaned data to gain insights, identify patterns and relationships, and formulate hypotheses.
4. Model/Develop the predictive Model
* Develop and evaluate predictive models using the data.
5. Interpret Data
* Draw conclusions and make decisions based on the results of the analysis.


# Results

### Checking for outliers

![image](https://user-images.githubusercontent.com/54464999/233315076-a4228a9f-6d21-4e70-a423-68aafc7cb748.png)

![image](https://user-images.githubusercontent.com/54464999/233315611-2d92ffc7-32d5-4523-83e2-a0a0ba8fb71d.png)


### Explaratory Data Analysis

![image](https://user-images.githubusercontent.com/54464999/233314417-f544d713-d688-4b6b-a7e9-93e603e5c373.png)

*How do different Priced houses relate with the number of bedrooms?

![image](https://user-images.githubusercontent.com/54464999/233318619-baf7924b-9661-4229-a988-748f54cebdf1.png)

*How do different Priced houses relate with the number of bathrooms?

![image](https://user-images.githubusercontent.com/54464999/233319184-998bdaad-99e1-4c2c-a7b9-431b7b15124f.png)




