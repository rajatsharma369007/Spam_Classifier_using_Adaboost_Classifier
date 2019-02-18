# Spam Classifier using Adaboost Classifier

## Introduction
An AdaBoost classifier is a meta-estimator that begins by fitting a classifier on the original dataset and then fits additional copies of the classifier on the same dataset but where the weights of incorrectly classified instances are adjusted such that subsequent classifiers focus more on difficult cases. In this notebook, I have implemented the adaboost classifier using the scikit learn.

<img src="https://cdn-images-1.medium.com/max/1600/0*paPv7vXuq4eBHZY7.png" >

## Dataset
Have a look at the dataset [link](https://github.com/rajatsharma369007/Spam_Classifier_using_Adaboost_Classifier/blob/master/SMSSpamCollection)  
Dataset contains first columns as classification label and second column is the e-mail content.

## Installation
* Pandas  
<code>conda install pandas</code>
* Scikit-learn  
<code>conda install -c anaconda scikit-learn</code>

## Accuracy
* Accuracy score = 0.98
* Precision score = 0.96
* Recall score = 0.90
* F1 score = 0.93

## Issue/Bug
Please open issues on github to report bugs or make feature requests.

## Contribution
If you are interested in improving the code, please open an issue first to describe the task you are planning to do. For small fixes (a few lines of change) feel free to open pull requests directly.

