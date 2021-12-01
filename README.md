# Boston-Airbnb-Price-Prediction

This repository has all the code and report for my Udacity Data Scientist Nanodegree Write-a-Data-Science-Blog-Post project.

## Write-a-Data-Science-Blog-Post: Using Boston Airbnb to create price prediction model

## Table of Contents
1. [Installation](#installation)
2. [Project Overview](#project-overview)
3. [Project Motivation](#project-motivation)
4. [File Descriptions](#files)
5. [Results](#results)
6. [Licensing, Authors, Acknowledgements](#license)

### Installation <a name="installation"></a>
For running this project, the most important library is Python version of Anaconda Distribution. It installs all necessary packages for analysis and building models. 

### Project Overview <a name="project-overview"></a>
In this project, I will perform a data-driven analysis with data science, machine learning, and data visualization techniques to analyze and predict the price of listings on Boston's Airbnb dataset. Helping us understand more about what features influenced listing price.

### Project Motivation <a name="project-motivation"></a>
The purpose of this article is more to illustrate the workflow and extract the relevant information from the datasets by using the Airbnb Boston dataset from Kaggle. Mainly to answer the 2 main questions which are:
1. How to create Boston's Airbnb Price prediction model?
2. What features highly influence the price of Airbnb?

### Data Preparation <a name="data-preparation"></a>
The data sets contain listing price, location, amenities, bedroom, room type and more than 70 features of Airbnb listing property

Three datasets are provided by Starbucks for this project:
1. listings.csv - contains listing price, location, amenities, bedroom, room type and etc.

### Results<a name="results"></a>
As a brief summary of my findings:
#### i. Question 1 findings - How to create Boston's Airbnb Price prediction model?:
As we can see our step to create a prediction model is to divide our workflow into mainly 3 sections:
- 1) Data Exploration 
    -> In this step, we start to explore the dataset and visualize some of the crucial features to make us understand on how some features interact to others.
- 2) Data Pre-Processing 
    -> From data exploration, there are some format and type of the dataset that we need to do some cleansing and imputing step.
- 3) Building Prediction Model 
    -> Building Machine Learning Model with sklean module, I've implemented 2 types of ML which is Ridge Regression and XGBoosting model

#### ii. Question 2 findings - What features highly influence the price of Airbnb?:
From the analysis, we can see that some features dominate others like
- room_type_Private room
- room_type_Entire home/apt
- property_type_Room in hotel
- bathrooms
- gym

The main observations of the code are published [here](https://medium.com/@pspnjitta/machine-learning-experiment-predicting-listings-prices-for-boston-airbnb-221ef23ca393).

### Licensing, Authors, Acknowledgements, etc.<a name="license"></a>
I would like to thank [Udacity](https://eu.udacity.com/) for this project, and [Kaggle](https://www.kaggle.com/airbnb/boston) for providing the data.
