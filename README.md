In this project we compare the performance of different Machine Learning algorithms for classification in the South African heart dataset.

The datset has 462 observations of 11 variables: patient ID, sbp (systolic blood pressure), tobacco (cumulative tobacco in kg), ldl (low density lipoprotein cholesterol), 
adiposity (not recorded in source, maybe another measurement of obesity similar to BMI), famhist (family history of heart disease (Present, Absent)), typea (type-A behavior),
obesity (a measure of obesity), body mass index (is consistent with Rossouw et al. (1983). Having BMI >= 30 scored as "obese" by Rossouw et al. (1983)), alcohol (current alcohol
consumption), age (age at onset), chd (coronary heart disease (response variable, binary with levels 1 and 0)).

In this jupiter notebook, the following classification methods are tested, in the following order:
- Naive Bayes
- Linear Discrimination Analysis
- Quadratic Discrimination Analysis
- Logistic Regression
- Decision Tree Classifier
- Bagging
- Random Forest
- Adaboost
- Gradient Boosting
- Stacking

We decided to not use K-Nearest-Neighbor classifier because the euclidean distance loses its discrimination ability in high dimensional spaces.
