# Boston Housing Data
## Domain
This dataset describes hosuing value in the suburbs of Boston and was taken from the StatLib library at Carnegie Mellon University.

Past usage of the dataset incclude regression diagnostis used in Belsley, Kuh & Welsch, 'Regression diagnostics ...', Wiley, 1980 with various transformations of the data as well as in 1993 by R. Quinlan in 'Combining Instance-Based and Model-Based Learning'.


## Problem Statement
For a house with a given set of features we will use a regression model to predict the median value of the home.

In other words is it possible to predict the median value of a home in the suburbs of Boston by it's demographic and descriptive features with more certainty than using the mean or most common class.

## Dataset and Inputs
The dataset to be examined contains the following 13 features 'crime rate', 'land zone over 25k sqf', 'industrialization', 'river adjacent', 'nitrogen oxide level', 'rooms', 'age', 'distance to employment center', 'highway accessibility', 'tax', 'pupil-teacher ratio', 'proportion of blacks', and 'lower status of pop' in connection with the target, the 'median value of the home.

The dataset has 506 rows and 14 columns and uses up 48K GB in memory.

## Solution Statement
A solution to this problem will be a regression model such as a logistic regression, decision tree, random forest, gradient-boosted tree, multilayer perceptron, one-vs-rest.

## Benchmark Model
Given that we seek a regression model a good naive benchmark would be to guess the most common class or the mean value.

## Evaluation Metrics
The dataset is not evenly distributed as most median values of the home are between 100k-250k. We can use the success of the model measuring against the F-Score and determine if our model predicts the correct median value of the home more reliably than the F-Score.