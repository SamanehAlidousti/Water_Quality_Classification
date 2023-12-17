# Water Quality Potability

This project aims to predict water potability based on water quality parameters by employing Machine Learning algorithms. This is a binary classification problem to determine if water is safe for human consumption.

## Dataset

The Dataset can be found in Kaggle [Water Quality Potability Dataset](https://www.kaggle.com/code/ragilhadip/water-quality-potability/input) which contains water quality metrics.

## Requirements
I run this project on Jupiter Notebook.

## Overview

Classification is a method of supervised learning that can identify new unseen instances and assign a given set of data to a particular class. In this project, I implemented 3 models for the prediction purpose. They are SVM (Support Vector Machine), Random Forest, and XGB (eXtreme Gradient Boosting)

### SVM:
A support vector machine is a supervised machine learning approach that finds a class border to categorize binary classes. The samples near the classifier boundary are called support vectors and the distance between support vectors and the hyperplane is called margin. The main task of SVM is to maximize this margin.

### Random Forest
A random forest (RF) classifier is an ensemble learning method that employs a random selection subset of training instances and attributes to generate numerous decision trees. The RF classifier is capable of handling large data dimensionality and multicollinearity while still being quick and resistant to overfitting.
### XGB
The Extreme Gradient Boosting model (XGB) is a tree boosting-based technique that uses incremental learning to combine numerous weak learners into powerful learners. To improve computational performance, parallel computing is introduced automatically during training. This method, like random forest, consists of multiple decision trees. Gradient boosting is an evolution of boosting technique that produces iteratively weak learners based on gradient descent optimization over a function.

