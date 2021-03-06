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
1. What are the most common room types in the Boston Airbnb listing?
2. What features highly influence the price of Airbnb?

### Data Preparation <a name="data-preparation"></a>
The data sets contain listing price, location, amenities, bedroom, room type and more than 70 features of Airbnb listing property

Three datasets are provided by Starbucks for this project:
1. listings.csv - contains listing price, location, amenities, bedroom, room type and etc.

### Results<a name="results"></a>
As a brief summary of my findings:
#### i. Question 1: What are the most common room types in the Boston Airbnb listing?
Answer: The most common room type for Boston Airbnb would be Entire home/apt which is around 62% of the entire type, followed by Private room 36%. Fewer than 1% are Hotel rooms and Shared rooms.
For Property type, the Entire rental unit is about 40% of the entire property, followed by a Private room in a rental unit of 18%, a Private room in a residential home of 8%, and others.
So if you want to be a Boston Airbnb property owner and find a room or property area that still has low competition in the market, maybe building some Houseboat that has a shared room could be the one!

#### ii. Question 2 findings - What features highly influence the price of Airbnb?:
Answer: From the analysis, we can see that some features dominate others like
- room_type_Private room
- room_type_Entire home/apt
- property_type_Room in hotel
- bathrooms
- gym
- bedrooms
Therefore, if you want to be an Airbnb property owner and want to set the listing price of your asset higher to gain more revenue, you need to consider these features in your exploration.

The main observations of the code are published [here](https://medium.com/@pspnjitta/machine-learning-experiment-predicting-listings-prices-for-boston-airbnb-221ef23ca393).

### Licensing, Authors, Acknowledgements, etc.<a name="license"></a>
I would like to thank [Udacity](https://eu.udacity.com/) for this project, and [Kaggle](https://www.kaggle.com/airbnb/boston) for providing the data.
