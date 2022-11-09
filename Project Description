Predictive Maintenance System for Industrial Equipment
Task: 
To predict failure and failure type for industrial machinery based
on multiple features such as temperature, torque, etc.

Approach:
The EDA is conducted to find insights in dataset. The data has two target 
features; one is binary and the other is class label. Therefore it is a 
supervised learning classification problem. 
It is observed that the data provided is noisy data. Checked for duplicates, 
missing values and outliers. Descriptive analysis as well as data visualization
is conducted to understand the data.
The data is unbalanced that means one class is in majority i.e. no failure.
two approaches are used to address the aforementioned problem; resampling using 
oversampling technique SMOTE for predicting failure i.e. binary classification and 
class weight balancing for forecasting failure type i.e. multi-classs classification.
Multiple algoriths are evaluated, as data science is an empirical field, for both
binary and multi-class classification.
For binary classification state-of-the-art stacking classifier approach is used
with random forest, gradient boosting and support vector machine are used as base
models where as final estimator is adaboost which is a reknown binary classifier.
For multi-class classification support vector machine is optimised after evaluating
various models such as k-nearest neighbours, stochastic gradient descent classifier, etc.
The hyperparameter that played vital role was 'rbf' kernel. The reason for using this 
model with the said kernel is that it creates hyperplanes in hyperdimensions for every class
and the kernel 'rbf' is a combination of polynomial and linear kernel. Thus resulting
in segregated class boundaries.

Results:
F1-recall is used as result metric with score higher than 80%. The recall is more important as
true failure prediction is necassry for creating predictive maintenace schedule.

For full dissertation research:
https://docs.google.com/document/d/1ecZka8KRYgvSzzWilOWWTnDyaDcH0lxt/edit?usp=sharing&ouid=115794582737327663051&rtpof=true&sd=true
