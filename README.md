# Human-Activity-Recognition-Analysis
Practical Machine Learning Exercise

# Summary
In this project I have performed analysis on Human activity recognition using the WLE dataset: http://groupware.les.inf.puc-rio.br/har#dataset. I first loaded the dataset into R. Then, I performed basic EDA on the dataset discovering the large number of missing values.I performed some cleansing and imputing operations.I then split the dataset into training and test tests. I trained 3 models -  Random Forest (rf), Neural network and Gradient boosting machine(gbm) on the training set. After evaluating their prediction accuracy on the test set, I selected the gbm model as my final model
 
 # Background:
Using devices such as Jawbone Up, Nike FuelBand, and Fitbit it is now possible to collect a large amount of data about personal activity relatively inexpensively. These type of devices are part of the quantified self movement – a group of enthusiasts who take measurements about themselves regularly to improve their health, to find patterns in their behavior, or because they are tech geeks. One thing that people regularly do is quantify how much of a particular activity they do, but they rarely quantify how well they do it. In this project, your goal will be to use data from accelerometers on the belt, forearm, arm, and dumbell of 6 participants. They were asked to perform barbell lifts correctly and incorrectly in 5 different ways. More information is available from the website here: http://groupware.les.inf.puc-rio.br/har 

## Goal: The goal of the project is to predict the manner in which they did the exercise -  classe variable 

## Please use the HAL_analysis_report file to view the project report. 
