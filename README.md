# Real-Estate-Price-Analysis
A comprehensive data analysis and predictive modeling project on house pricing using Python, Pandas, Scikit-learn, and Ridge regression

House Price Analysis- 

This repository contains a comprehensive data analysis and predictive modeling project on house pricing using various machine learning techniques. The dataset used is from King County, including Seattle, and covers house sales between May 2014 and May 2015.

Introduction
This project aims to explore, analyze, and predict house prices using various features such as square footage, number of bedrooms, number of bathrooms, and other significant attributes. We employ different statistical and machine learning techniques to develop and evaluate predictive models.

Dataset
The dataset contains house sale prices for King County, including Seattle. It includes homes sold between May 2014 and May 2015. The dataset was slightly modified for the purposes of this course.

Variable Description

id : A notation for a house

date : Date house was sold

price : Price is prediction target

bedrooms : Number of bedrooms

bathrooms : Number of bathrooms

sqft_living : Square footage of the home

sqft_lot : Square footage of the lot

floors : Total floors (levels) in house

waterfront : House which has a view to a waterfront

view : Has been viewed

condition : How good the condition is overall

grade : Overall grade given to the housing unit, based on King County grading system

sqft_above : Square footage of house apart from basement

sqft_basement : Square footage of the basement

yr_built : Built Year

yr_renovated : Year when house was renovated

zipcode : Zip code

lat : Latitude coordinate

long : Longitude coordinate

sqft_living15 : Living room area in 2015 (implies some renovations)

sqft_lot15 : LotSize area in 2015 (implies some renovations)


Modules

Module 1: Importing Data

Importing the necessary libraries
Downloading and loading the dataset

Module 2: Data Wrangling

Handling missing values
Dropping irrelevant columns
Displaying data types and obtaining statistical summaries

Module 3: Exploratory Data Analysis

Counting the number of houses with unique floor values
Visualizing house prices with and without waterfront views
Determining the correlation between square footage above ground and price

Module 4: Model Development

Fitting linear regression models
Developing models using multiple features
Creating and evaluating polynomial and ridge regression models

Module 5: Model Evaluation and Refinement

Splitting the data into training and testing sets
Performing polynomial transformations
Evaluating models using R² scores

Results

Linear regression model using sqft_living yielded an R² of 0.4929.

Linear regression model using multiple features yielded an R² of 0.6577.

Polynomial regression with Ridge regularization yielded an R² of 0.7040.

Usage

To run this project, ensure you have Python installed along with the required libraries:

pandas

numpy

matplotlib

seaborn

scikit-learn

Clone the repository and run the Jupyter Notebook to see the step-by-step analysis and model development.


git clone https://github.com/yourusername/House-Price-Analysis.git
cd House-Price-Analysis
jupyter notebook
