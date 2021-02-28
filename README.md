# Credit_Risk_Analysis
Module 17- Supervised Machine Learning

## Overview of the Analysis
The purpose of this analysis is to use various machine learning models to predict credit card risk. Credit card risk data is provided by the Lending office and is inherently unbalanced. We will use Random Oversampling, SMOTE, ClusterCentroids and SMOTEENN algorithms to resample the data and evaluate the results using logistic regression. We will also evaluate the data using two other ensemble learning algorithms: Balanced Random Forest Classifier and Easy Ensemble AdaBoost Classifier to predict risk and compare all six algorithms for the best result.


## Results
Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.

### Random Oversampling
    - Accuracy Score: 0.6358810167733331

<img src="images/random_oversampling_report.png"></img>
 - The balance accuracy score gives us an overall success rate of just under two thirds of the time

### SMOTE Oversampling
    - Accuracy Score: 0.6482835929757615
<img src="images/SMOTE_report.png"></img>

### Cluster Centroids Undersampling
    - Accuracy Score: 0.5442661782548694
<img src="images/cluster_centroids_report.png"></img>
### SMOTEENN Resampling
    - Accuracy Score: 0.6501490011021682
<img src="images/SMOTEENN_report.png"></img>

## Ensemble Learning
### Balanced Random Forest Classifier
    - Accuracy Score: 0.7782071705767397

<img src="images/brf_report.png"></img>

### Easy Ensemble AdaBoost Classifier
    - Accuracy Score: 0.9326539909603683

<img src="images/eec_report.png"></img>

## Summary
Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.