# Assignment: Data preprocessing

## Objectives

The objectives of this assignment are:
1.	to get familiar with the Jupyter Notebook environment
2.	to learn the basics of manipulating data frames

## Setup

In the assignment, use the CKD dataset that is available at [https://archive.ics.uci.edu/dataset/336/chronic+kidney+disease](https://archive.ics.uci.edu/dataset/336/chronic+kidney+disease).


## Task

Load the CKD dataset into a single data frame and read its description. Construct a pipeline for modifying the data frame.

The modified data frame should meet the following requirements:

- It should include exactly the following columns:
  - age
  - blood pressure
  - specific gravity
  - albumin
  - sugar
  - blood glucose random
  - blood urea
  - sodium
  - potassium
  - hemoglobin
  - packed cell volume
  - white blood cell count
  - red blood cell count
  - class

- The hemoglobin values should be expressed in g/l. In the original data set, they are expressed as g/dl.

- The values of the class column should be recoded as a or c (affected or control).

- Rows with three or more missing values should be removed. Indicate the number of rows left in the modified data frame.

Next, split the data frame into two data frames, one for the affected individuals and one for the control individuals. Display the data frames, and indicate the number of rows in each data frame.

For each data frame, calculate the basic statistics for each column, and provide clear, readable histograms for each numerical column. Do you see any outliers? If so, how would you handle them?

Finally, calculate the correlation matrix and visualize it for each data frame. Clearly describe the results and your interpretation for it.


## Deliverables

Submit a GitHub permalink that points to the Jupyter notebook as instructed in Oma.
The submitted notebook must contain the step-to-step analysis pipeline, complete with Markdown blocks and comments that clearly explain what has been done. 

