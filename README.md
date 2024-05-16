# Credit Risk Classification Report

## Overview of the Analysis
The purpose of this analysis is to build and train a model that can predict the creditworthiness of individuals, to show if they will be potential low risk or high risk customers. 

### Data Source
The data used for the analysis is based on historical lending activity from a peer-to-peer lending services company. The data under consideration was their pre-existing creditworthiness ('loan status' column) which is either 0 (healthy) or 1 (default risky). The independent variables used to determine creditworthiness are: loan size,	interest rate, borrower income,	debt to income,	number of accounts,	derogatory marks, totaldebt.

### Stages of building the Machine Learning 
<u>Step 1</u>: Import the libraries (numpy, pandas, sklearn.metrics)
<u>Step 2</u> Import the data and create the y labels which are 0 for "healthy" and 1 for "default risk". Also create the x features.
<u>Step 3</u> Split the data into the Training and Testing data sets
<u>Step 4</u> I used the Logistics Regression model to train the train data and then use same on the test data with the same random state.

## Results

The <u>healthy loan</u> class predictions are 100% correct meaning that every instance (18,759) of the predictions of healthy is correct. This is as a result of a 100% <u>precision</u>, which shows the ratio of correctly predicted all positive observations to the total predicted positives. Also a 100% recall which is the ration of correctly predicted positive observations to all actual positives.

The <u>default risk</u> class predictions were  87% and 89% for precision and recall respectively giving an overall default_risk class score of 88%. This is still reliable but if more accuracy is needed here, then we can train the model more.
