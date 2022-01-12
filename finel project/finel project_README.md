  # Specialty-Coffee-Prediction
rawan mohammed althumali


# Abstract

This project aimed to o predict the total cup point value, where 
this value determines whether a coffee product can be considered specialty coffee.
The used data in this project is  originally uploaded from Coffee Quality Database, was re-posted to Kaggle.
There are three datasets available: arabica_data_cleaned, robusta_data_cleaned and merged_data_cleaned. . I used the merged dataset as it is the combined dataset of the other two.
 I considered it a regression problem.
 with sklearn library SVM regression model was trained and  the mean squared error : 3.27 , coefficient of determination : -0.03
 
 # Design
 
Model the relationship between predictors in an outcome of interest and using the models to predict a future outcome.

# Data

The dataset is provided in .csv format. It contains
1300 raw , 43 columns

The data obtained is still in the form of raw data containing attributes such as 
company, mill, farm name, and the others.
The features used as input are the country of origin, , processing method, moisture, 
color, and the plantation's altitude. These attributes were chosen according to the 
characteristics, varieties, and processing methods because these attributes were 
considered to describe the quality of the coffee beans...

# steps and Algorithms:

1- Data preprocessing:

* Drop first column
* Select target columns
* Select important columns
* Convert categorical data to numerical data.

2- Data Visualization:

* Relationship between Altitude and target:The increase of Altitude was not affect in the target very much.

* Relationship between Moisture and target:The increase of Moisture was not affect in the targetso there is no relationship

* Relationship between Processing method and target:The increase of processing was not affect in the targetso there is no relationship.

* Relationship between Harvest.year and target:The increase of year was not affect in the targetso there is no relationship.

3- Splitting Dataset to training and testing with 80% for training

4- Build Linear regression model

5- Evaluate Linear regression model

6- Build SVM regression model

7- Evaluate SVM regression model

8- Comparing the modeles 


# Tools

Pandas for data manipulation , clean data.
sklearn for preprocessing
andsklearn  Linear Regression ,SVM rgressior for modeling .
Matplotlib for plotting .












