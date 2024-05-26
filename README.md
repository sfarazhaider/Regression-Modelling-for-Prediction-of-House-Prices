# Regression Modelling for Prediction of House Prices 

This project uses data set of sales of houses with different features as data metrics. The relationship between the features of the houses and the price of the houses are analyzed as well as any outliers. Then, regression model is applied to predict the price of a house with certain features.

**Data Source:** 

The data set is taken from the IBM course series for Data Analysis

https://s3-api.us-geo.objectstorage.softlayer.net/cf-courses-data/CognitiveClass/DA0101EN/coursera/project/kc_house_data_NaN.csv

**House Sales in King County, USA**

This dataset contains house sale prices for King County, which includes Seattle. It includes homes sold between May 2014 and May 2015.

_Columns Info_

id : A notation for a house

date: Date house was sold

price: Price is prediction target

bedrooms: Number of bedrooms

bathrooms: Number of bathrooms

sqft_living: Square footage of the home

sqft_lot: Square footage of the lot

floors :Total floors (levels) in house

waterfront :House which has a view to a waterfront

view: Has been viewed

condition :How good the condition is overall

grade: overall grade given to the housing unit, based on King County grading system

sqft_above : Square footage of house apart from basement

sqft_basement: Square footage of the basement

yr_built : Built Year

yr_renovated : Year when house was renovated

zipcode: Zip code

lat: Latitude coordinate

long: Longitude coordinate

sqft_living15 : Living room area in 2015(implies-- some renovations) This might or might not have affected the lotsize area

sqft_lot15 : LotSize area in 2015(implies-- some renovations)

# The Following are the Tasks of this project

****Question 1:****
**Display the data types of each column using the attribute dtype**


**Question 2: 
Drop the columns "id" and "Unnamed: 0" from axis 1 using the method drop(), then use the method describe() to obtain a statistical summary of the data**

**Question 3:
Use the method value_counts to count the number of houses with unique floor values, use the method .to_frame() to convert it to a dataframe.**

**Question 4:
Use the function boxplot in the seaborn library to determine whether houses with a waterfront view or without a waterfront view have more price outliers.**

**Question 5:
Use the function regplot in the seaborn library to determine if the feature sqft_above is negatively or positively correlated with price.**

**Question 6:
Fit a linear regression model to predict the 'price' using the feature 'sqft_living' then calculate the R^2**

**Question 7:
Fit a linear regression model to predict the 'price' using the list of features:**

**Question 8:
Use the list to create a pipeline object to predict the 'price', fit the object using the features in the list features, and calculate the R^2.**

**Question 9:
Create and fit a Ridge regression object using the training data, set the regularization parameter to 0.1, and calculate the R^2 using the test data.**

**Question 10:
Perform a second order polynomial transform on both the training data and testing data. Create and fit a Ridge regression object using the training data, set the regularisation parameter to 0.1, and calculate the R^2 utilising the test data provided**
