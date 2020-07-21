# Predict Cab Booking Cancellations
Various classification models are built in R to predict the cancellation of the cab due to unavailability.

## Abstract

The aim of the project is to analyze the booking data that is provided by YourCabs.com and build a model to predict whether the ride would get cancelled because of the cab’s unavailability.

The business faced a problem of ride cancellation by the cab drivers. Such a cancellation has an associated cost to the company, not to mention the customer’s dissatisfaction and possible loss of business. A model to predict the event before it happens not only allows for a reduction of cost but also helps improve the business’s customer service. Since the aim of the project is to predict if a ride would be cancelled or not, this is a classification problem. The business would be able to manage the drivers and customer relationships better by handling cancellations before any escalations.

The key objectives in the task include – 
•	Explore the dataset and analyze the features present
•	Build supervised models on the dataset to classify the ride as cancelled or complete
•	Evaluate the model’s performance and validate the model on the testing dataset


## Background

YourCabs.com is a company (currently possibly defunct) based out of Bangalore to bring the owners and vehicles together. The company provides a platform for the individual customers to book a cab, thus maintaining a real time demand for the supply. The service involves connecting the cab owners with the end customers, and YourCabs.com maintains the technology platform, charging a fee for each ride. 

The business provides the customers with options to book point-to-point rides, long distance rides or rent a cab on an hourly basis. The business also provides an online platform, a mobile site, and the traditional way of hailing cabs. Most times, the cancellations occur at the last minute before the scheduled pick up time or is a “no show”.

Kaggle.com is an online platform, quite popular amongst the data science community, to learn and compete on data projects. Companies and organizations can sponsor and create competitions for people around the world to compete against on pending business problems. YourCabs.com and Indian School of Business (ISB) came together to sponsor this contest to have participants develop predictive models to classify if a cab booking would be cancelled due to the unavailability of cabs.


## Executive Summary

The project involved analyzing the ride information presented by YourCabs.com and ISB hosted via a Kaggle competition and building a classification model to predict a ride cancellation through cab unavailability (by the driver). The steps followed in building the process are as follows – 
1.	EDA on the data to understand the values and feature engineering to create the required variables for modelling process
2.	Creating a stratified sample (balanced) dataset and a SMOTE resampled dataset. Splitting the dataset into a train and test split (70-30) for modeling purpose
3.	Model building and validation through key diagnostic measures. A range of modeling techniques were used including **logistic regression (with and without automated variable selection), CART, Random Forest, SVM and Neural Nets**

The results of the various models built are presented in detail in the report. Random forest tuned for its hyper parameters performs the best on the testing data based on the misclassification rate (thought the FNR is higher than that of the SVM or Neural Network model). 
 
The models were rebuilt using the SMOTE resampled dataset and the results (produced in a later section) are comparable.

