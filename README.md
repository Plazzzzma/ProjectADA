# Project ADA - Chicagoan Restaurants
Beyond the menu: where to eat in Chicago?

## Abstract

Ranking third in the list of the United States’ most populous cities, Chicago is renowned for witnessing the nascence of the most popular dishes in North-American cuisine. The city has built itself a solid reputation in the food-related field with the quite numerous restaurants and food establishments it features. Yet, it is not always easy to know, neither for locals nor for tourists, where to eat best by Lake Michigan!
Relying on the results of the Department of Public Health’s inspection and on a sentiment analysis in online reviews, we intend to establish an interactive map that enables us to know where the safest options to eat in Chicago are. Moreover, the data will be paired with the locations of reported incidents of crime in order to understand whether there is, or not, a pattern that links the quality of food provided to the safeness of a neighborhood. 

## Research questions
The work will be directed in a way to answer the following questions:

* Is there an observable pattern in the spatial distribution of food establishments presenting low (resp. high) risk rates in the city of Chicago? * If that is the case, has it evolved over time?

* Is there any correlation between the quality of food provided in an establishment and the crime rate in the surrounding neighborhood? * Do the comments and reviews on open online platforms reflect the results of the inspection undertaken in the corresponding establishment?

## Datasets

In order to provide answers to the above listed questions, we will rely on the following datasets:

#### Chicago Food Inspections:
This dataset presents the results of inspections undertaken by the Chicago Department of Public Health’s Food Protection Program since 2010 up until today. Having both the address and the exact geographical coordinates for each inspected establishment, we will try and visualize the spatial distribution of restaurants that offer food of good (resp. poor) quality. 

#### Crimes – 2001 to present
The data being presented both as a dataset and a map, we will exploit them in order to determine whether there is or not a correlation between the quality of food provided and the crime rate in a certain neighborhood. Only incidents reported in the relevant period of time will be taken into consideration. 

#### Reviews and comments on [platform]
The data will be sorted in a sentiment analysis in order to see if the public opinion on a specific restaurant is in adequacy or not with the results of its inspection.

## A list of internal milestones up until project milestone 2

We sure want the work to be done, until then we will try and progressively achieve the following milestones:

#### Prepare the data

* Download datasets

* Collect data for the sentiment analysis

* Filter and clean data in order to keep results issued in the same timespan

#### Visualize the data

* Establish an interactive map of food establishment showing the inspection results

* Add the crime hotspots to that same map

* Figure out a way to pair results of both inspection and sentiment analysis

#### Notebook

* Keep track of the progression of the work

* Analyze and interpret results

* Make analysis understandable for anyone

## Achievements made by milestone 2
Many things have changed since the initial discussions concerning the project. Indeed, it all seems more concrete and achievable by now. 
Here is a little summary of the intermediary goals that were achieved:

#### Prepare the data

The Food Inspection and the Crime Records datasets being downloaded, we got to be more familiar with the data they contain. We got to understand how they are structured and managed to sense the information that is relevant within the scope of this project and how to deal with it. For both datasets, we have dug into the categories that we are interested in order to elaborate strategies and perceive the limitations vis-à-vis the interactive visualization we inted to establish. Concerning the sentiment analysis on the online comments, we have collected a partial dataset. The issues inherent to its nature are discussed in the notebook. 

#### Visualize the data

For both the Food Inspections and the Crime Records datasets, we have generated maps showing the relevant information respectively for restaurants and crime hotspots. We still have to merge them in a synthetic way. Concerning the sentiment analysis, further discussion with TAs will be required. 

#### Notebook

All the steps we have undertaken are shown and described in the notebook, same goes for the results we have interpreted. The next stages and further actions are described at the end of the notebook. 

## A list of internal milestones up until the final report

This refect how we intend to procees in order to reach our final goal: 

* Our first aim is to be able to advise people where to eat in Chicago. In order to do so, we want to analyze the quality of restaurants based on inspections they have went through and their results, previous customers' opinions (Yelp) and finally their environment in which they are located (crime). 
Through the study that appears in the notebook, we have realized that inspections did not necessarily reflect the health quality of a restaurant. In order to answer our initial question properly, we must go further than just analyzing the features provided by Chicago. Therefore, we intend to generate additional features that will help us create clusters containing restaurants of even quality. 

* Moreover, the purpose of the final report is to first compare the maps obtained in milestone 2 in order to observe a spatial correlation between the crime  and the restaurants densities per district. We want to finally obtain a numerical value of their correlation. This will allow us to define the risks associated to a restaurant and the demographic questions that are related to it. It will also allow us to establish a feature related to the security of a restaurant, thus answering the initial question of the project.

* Then, if possible, we would like to study the reviews and create a prestigious label for restaurants. This may be a challenge. Indeed we are waiting for TAs' input for the use of reviews. However, the low number of restaurants implies that we will have to combine the reviews by spatiality to be able to label as many restaurants as possible. 

* It will then be necessary to review the inspection dataset in order to transform features into numerical values ('risk','violations', etc.) that allows quantitatively defined specifications on the quality of a restaurant. The aim is also to continue the temporal analysis we have started. It enables us to quantify the evolution of the inspection results for each restaurants over the period 2010 to 2019. 

* Finally, this feature creation should lead us to unsupervised Machine Learning. We will try to spatialize the distribution of restaurants using numerical features generated to create a clustering to correctly group restaurants by their quality levels. 
This clustering can be accompanied by the creation of a network in order to obtain a clustering that will suit us by spectral analysis.


## Question for TAs

Discuss the issues concerning the dataset for the sentiment analysis
