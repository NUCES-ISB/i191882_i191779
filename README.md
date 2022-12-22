# Banglore_House_Price_Prediction

## Introduction

Creating a Machine Learning model to predict the home prices in Bangalore, India. We are going to use the dataset from Kaggle.com. We are also going to create a single page website which will provide the front end to access our model for predictions.

Below data science concepts are used in this project

* Data loading and cleaning
* Outlier detection and removal
* Feature engineering
* Dimensionality reduction
* Gridsearchcv for hyperparameter tunning
* K fold cross validation

Technology and tools used in this project

* Python
* Numpy and Pandas for data cleaning
* Matplotlib for data visualization
* Sklearn for model building

## Steps ##

- Step#1: Import the required libraries

- Step#2: Load the data

- Step#3: Understand the data

        - drop unnecessary columns

- Step#4: Data Cleaning

        - Check for na values
        - Verify unique values of each column
        - Make sure values are correct (eg. 23 BHK home with 2000 Sqrft size is worng)        
        - Feature Engineering        
        - Dimesionality Reduction
        - Outlier removal using domain knowledge (2bhk price < 3bhk price, size per bhk >= 300 sqft)
        - Outlier removal using standard eviation and mean
        - One Hot encoding

- Step#5: Build Machine Learning Model

- Step#6: Testing The model

## Dataset Reference##

* [Bengaluru House price data](https://www.kaggle.com/datasets/amitabhajoy/bengaluru-house-price-data)
* I have also uploaed the csv file in this repository [Bengaluru_House_Data.csv](https://github.com/Jaydeep9596/Banglore_House_Price_Prediction/blob/main/Bangalore%20House%20Price%20Prediction/Bengaluru_House_Data.csv)

Reference [codebasics](https://www.youtube.com/watch?v=rdfbcdP75KI)
