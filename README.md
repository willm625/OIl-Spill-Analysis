# Oil-Spill-Analysis

## Dataset
This dataset was obtained from kaggle at the link https://www.kaggle.com/datasets/sudhanshu2198/oil-spill-detection. The data was developed from satellite images from the ocean that either contained oil spills or did not. 

## Objective
The objective of this analysis is to find the most accurate classification model that determines whether an ocean patch contains an oil spill or not.

## Method
First some basic classification models should be tested, like Random Forest, K-Nearest Neighbors, Support Vector Machines, Logistic Regression and Decision Trees. Then each model will have its hyperparameters tuned to improve performance. Neural Networks will also be applied and used in the same order.

## Results
Here is a table containing all the model's performance scores (Accuracy, R2, etc.) The best model turned out to be the Decistion Tree Classifier with an accuracy of 0.989, very close to 99%. Originally the Decision Tree model test accuracy was 96.8% and training accuracy was 100%. Since there was overfitting, the depth of the tree was cut by one and some features were ignored. 
