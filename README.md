# Data Science Complex System Performance Prediction: Project Overview
* Utilized R to implement supervised machine learning techniques for comparing two system processes that influence mostly the component probability of fail.
* Engineered features from the economic indicators to de-trend the value put on python, excel.
* Optimized the system by using Binary classification model(Logistic regression, Neural network, Random forest, Gradient boosted tree).

## Code and Resources Used
**R Version:** 4.0  
**Packages:** tidyverse, dplyr, ggplot2, caret

## EDA
* Checked the variables are missing
* Visualized the distribution of the variables
* Visualized the summary statistics
* Visualized the relationships between the inputs, between outcome and inputs.

## Model Building
There are two system processes. One of several steps in processes is countinuous outcome, so we need to use regression models. We trained and tuned Linear additive model, Regularized regression with Elastic net, Partial Least Squares, Neural network, Random forest, Gradient boosted tree, and SVM. The output of these two system are binary outcomt, so eventually we trained and tuned Logistic regression with additive terms, Regularized regression with Elastic net, Naive Bayes, Neural network, Random forest, Gradient boosted tree, and SVM.     

## Model performance
In regression models, I use Mean Absolute Error, Root Mean Squared Error, ans Rsquared as regression models' performance matries. In binary classification models, I use ROC curve as classification models' performance matries. Eventually, Random Forest is our best model to find optimal system process. 
