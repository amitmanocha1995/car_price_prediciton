# car_price_prediciton

## Initial Focus 

The purpose of this project is to create a model using car characteristics to predict the The Manufacturer Suggested Retail Price (MSRP) in the United States.

## Background Information

In the case of car prices prediction, companies could use this model to determine the prices of new cars that they produce which will help them to set the most accurate prices for their cars based on the market value. As a result, optimal prices for cars could be set leading to better growth and outcomes for car manufacturers respectively. Based on existing data, the aim is to use machine learning algorithms to develop models for predicting car prices.

#### 

<img src="https://i.ibb.co/z5C4m1W/ultra.jpg" alt="ultra" border="0"></a>

#### 

## Proposal

The price of a car depends on a lot of factors like the goodwill of the brand of the car, features of the car, horsepower and the mileage it gives and many more. Here are the list of features that can be used to predict The Manufacturer Suggested Retail Price (MSRP).

> - MSRP: Target Variable



| Feature          	| Descriptions                              	|
| :---              | :---                                          |
| Make:         	| Name of the car Manufacturers                	|
| Model:      	    | Model of the car                          	|
| Year: 	        | Year of Manufactur                        	|
| Engine Fuel Type: | Fuel type used in the car                 	|
| Engine HP: 	    | The horsepower an engine produces in pounds   |
| Engine Cylinder:  | Number of Cylinders in the Engine         	|
| Transmission Type:| The Type of Transmission                  	|
| Driven_Wheels:    | Types of drivetrain                       	|
| Number of Doors:  | Number of Doors                           	|
| Market Category:  | Market Category of the car                	|
| Vehicle Size:     | Vehicle size (Compact, Midsize or Large)    	|
| Vehicle Style:   	| Vehicle Style of the car                  	|
| highway MPG:      | Highway Mileage                           	|
| city mpg:        	| City Mileage                              	|
| Popularity:       | Popularity of the car                     	|
| MSRP:         	| The Manufacturer Suggested Retail Price      	|

## Specification

- Python: 3.9.12
- Pandas: 1.4.3
- Seaborn: 0.11.2
- sklearn: 1.1.2.
- Numpy: 1.21.5

This data contains 1000s of automobiles (each record represents an actual car) and their attributes.  The target variable of interest is MSRP (manufacturer suggested price).  The data was provided as a part of our CIS: 508 Assignment.


## Table of Contents: <a class="anchor" id="steps"></a>
- [1. Libraries & Custom Functions](#libraries)
- [2. Data Wrangling](#wrangle)
   - [2.1 Data Gathering](#gather)
   - [2.2 Data Assessment](#assess)
   - [2.3 Data Cleaning](#clean)

- [3. Exploratory Data Analysis](#eda)
   - [3.1 Univariate Analysis](#univariate)
   - [3.2 Outlier Analysis & Treatment](#outlier)
   - [3.3 Bivariate Analysis](#bivariate)
- [4. Feature Selection](#feature)
- [5. Model Building](#model)
    - [5.1 Model 1](#model001)
    - [5.2 Model 2](#model002)
    - [5.3 Model 3](#model003)
- [6. Conclusion](#conclusion)
