# Predicting Iris flower category
This problem can also be called Machine Learning - 101. Everyone who wants to get started in Machine Learning can start with this very-basic problem. The problem aims at predicting the species of iris flower - "Iris-setosa", "Iris-versicolor", and "Iris-virginica", from four different features - 'sepal-length', 'sepal-width', 'petal-length', and 'petal-width'. The main coding can be found at: https://github.com/akshaybhaskaran/iris_ML-101/blob/master/IrisNotebook.ipynb , and a high-level introduction to each of the steps involved can be found here.

## Setting the stage
Before we begin the modelling, we need to import the necessary libraries, and set the paths. Some of the python packages needed - os, sys, pandas, numpy, matplotlib, sklearn. 

## Understanding the input
After we have the necessary libraries imported, we need to read the input using pandas.read_csv method. Once read, we need to understand how the dataset looks actually, the different classes to predict, and the statistical description of the dataset. 

## Visualization
After we've got a basic understanding of the dataset, we need to visually represent the dataset. This can be done with the help of the 'matplotlib' library to plot box-plots, and graphs to get a further insight into the data. Visualization is an important part in building a model as that can help us various useful information hiding inside the dataset. 

## Preparation
Now, it is time for us to get the data ready to be used in building our model. We need to verify the datatypes of each of the features, check if there is any missing values in the dataset for each of the features, and assign the proper data to X and Y. X - is the input features that is used for predicting the output, Y - is the actual prediction target. 

## Train-and-test data
In this dataset, we just have one bulk data, and there is no separate dataset for testing our model. Any model, after it is built, should be tested on a new data that it has never seen during the training - that's the reason we'd be splitting the input dataset into two sets - 'training-set' and 'testing-set'. We train the model using the training data, and run the model on test data to see its performance on unseen data. 

##


