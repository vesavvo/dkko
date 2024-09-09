# Assignment: Linear and logistic regression

## Objectives

The objectives of this assignment are:
1.	to learn to use linear regression for predicting continuous target variables 
2.	to learn to use logistic regression for binary classification

## Setup

In this assignment, use the Real Estate Valuation dataset that is available at [https://archive.ics.uci.edu/dataset/477/real+estate+valuation+data+set](https://archive.ics.uci.edu/dataset/477/real+estate+valuation+data+set). The data is collected from New Taipei City, Taiwan. 

## Task

The assignment consists of constructing two separate models for predicting the real estate prices in the dataset: one with linear and one with logistic regression.

1. **Linear regression model**: construct a linear regression model for predicting the continuous target variable "Y house price of unit area" in the dataset.
2. **Logistic regression model**: convert the target variable into a binary-valued one depending on whether the original target value is above or below the average house price of unit area (according to the contents of the training set), and construct a binary classifier for predicting its value with logistic regression.

Divide the labeled data into separate subsets for training and testing, and validate both models with appropriate metrics. 

Remember to draw conclusions from your results and interpret your findings! Could you e.g. estimate which of the input variables has the most important role when predicting the house prices, and which ones are less important? Also, give some thought to whether the data should be standardized before modeling or not. 

Prepare a Jupyter notebook containing a full account of the problem treatment. Construct your notebook to include sections for each of the six separate stages in the CRISP-DM model, with appropriate contents (include subsections for the two separate tasks in "Modeling" and "Evaluation").

## Deliverables

Submit a GitHub permalink that points to the Jupyter notebook as instructed in Oma. The submitted notebook must contain the problem analysis written in accordance with the CRISP-DM process model, complete with Markdown blocks and comments that clearly explain what has been done. 

