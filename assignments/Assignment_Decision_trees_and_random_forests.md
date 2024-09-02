# Assignment: Decision trees and random forests

## Objectives

The objectives of this assignment are:
1.	to learn to use decision trees to build a transparent, human-readable predictive model.
2. to learn to use random forests for improved predictive performance.

## Setup

In the assignment, use the Phishing dataset that is available at the UCI Machine Learning Repository: [Phishing Websites Data Set](https://archive.ics.uci.edu/ml/datasets/phishing+websites).
The target variable `Result` indicates whether a website is a phishing site or not.

**Note:** As the interpretation of the -1’s and 1’s in the Result column seems to be missing from
the document, it may be helpful to know that a ‘1‘ corresponds to a phishing site and a ‘-1’ to a
legitimate site.

**Hint:** Click the Download in Python button for quick access to the dataset. In addition, click the Download button 
to gain access to the dataset description.


## Task

Your goal is to find out whether it is possible to reliably predict whether a website is a phishing site or not 
based on the 
easily obtainable information about the website. Based on the outcome, it may become possible to construct an 
automated system that warns users when they are about to visit a phishing website.

### Part 1: Decision tree

Your initial goal is to construct a small yet useful decision tree that predicts whether a website is a
phishing site or not.

The outcome should contain the following:
1. An image of the final decision tree.
2. Evaluation metrics for the decision tree.
3. Written instructions for an internet analyst to manually make the decision of whether the website
is likely to be a phishing site or not. The instructions must match one-to-one with your
decision tree, and be written in a way that is understandable to an engineer who is aware of the basics of internet technologies.

### Part 2: Random forest

As the ultimate goal is to build an automated system, you don't have to stick to a single, relatively simple decision tree.

Try to tweak the performance of the decision tree by replacing it with a random forest. You may also try to tune the 
hyperparameters of the random forest to improve the performance.

Be sure to include the validation results in your report.

> In real life, when you tune the hyperparameters based on the validation results, you should have yet another 
> data set that is not used for tuning the hyperparameters, but applied only once after the tuning of the 
> hyperparameters to obtain the final performance estimate of the tuned model.
> That is, there should be three sets: training, validation, and test sets. On this course, you may skip the need for the third set.

## Deliverables

Submit a GitHub permalink that points to the Jupyter notebook as instructed in Oma. The submitted notebook must contain the problem analysis written in accordance with the CRISP-DM process model, complete with Markdown blocks and comments that clearly explain what has been done. 

