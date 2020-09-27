# Airbnb-Seattle Dataset- EDA
Airbnb is a popular homestay listing site. 
Seattle Airbnb dataset describes the Airbnb listing activity of home-stays in Seattle, WA.
# Project
This project is part of the requirement for 'Data Scientist Nanodegree' program on Udacity. The requirement is to follow the CRISP-DM process (Cross-industry standard process for data mining). 
The project aims to analyze the Seattle dataset and answer few business questions on the Airbnb renting scene in Seattle such as: the effect of location on price, 
effect of property type on price, how to become an effective host etc.
# Business Questions:
We will try to find answers for the following questions:
Q1. What are the most popular neighbourhood in Seattle using listing descriptions?
Q2. How the locality affects the price of the property?
Q3. Is there any relationship between price of the listing and the property- type such as how price of rentals varies with condominiums, apartments or house ?
# Data Overview:
For our analysis we will use its Seattle dataset. (https://www.kaggle.com/airbnb/seattle) 
This dataset describes the listing activity of homestays in Seattle, WA.
The following Airbnb activity is included in this Seattle dataset:
Listings, including full descriptions and average review score
Reviews, including unique id for each reviewer and detailed comments
Calendar, including listing id and the price and availability for that data.
# Data Prepartaion: 
We focused on 'Listing" data set. As a part of data preparation we checked for missing values. Fortunatels 'price' column in tha dataset had no missing values. 
But 'Price' column had a dolar sign ($) and therefore was represented as string object. Inorder to proceed further the '$' sign was removed and dtype of 'price' coumn was changed to float.
Then 'inferential statistics' was employed to answer the business questions.
# Installation Requirements:
This project requires Python 3.6 and the common Python libraries such as Numpy, Pandas, Mathplotlib and Seaborn.
# License
Under MIT license which means it's an open/public project, please feel free to download, make changes and give me feedback.
