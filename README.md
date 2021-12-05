# Data Analytics Final Project 
Team Name: CriticalZero <br> 
Muskan Kothari (PES1UG19CS284) <br>
Neha Arun Angadi (PES1UG19CS294) <br>
Shreyas Raviprasad (PES1UG19CS468)

# Problem Statement
The purpose of this project is to analyse the various approaches inherited to solve the problem of predicting the critical temperature of superconductors to formulate a model that can best predict the critical temperature. The elemental chemical properties of superconductors are many. Various models aim to narrow it down to the most contributing features that yield the closest prediction. A close look at the correlations between the features and Tc enables a thorough analysis of pitfalls and contributions. Various approaches deal with statistical machine learning models, featureless approach, Bayesian Neural Network approach and the like for nearly optimized predictions.

# Dataset
For the purpose of predicting the critical temperature of a superconductor, we have chosen the SuperCon database maintained by Japan’s National Institute for Materials Science (NIMS). 
The database contains two datasets which had no missing values. One dataset was related to the formula of the superconductor while the other had details regarding its chemical properties like thermal conductivity and atomic mass.

# Approach
Our approach to the problem statement is as follows. We are combining the two datasets obtained from the NIMS database to train the model instead of the usual usage of only the dataset containing the chemical properties.
We make use of various models such as Linear Regression, Ridge Regression, Decision Tree Regressors and applied PCA to see if it had any significant impact. Our solution includes using three different parts. <br>
1. Using only the one dataset with the chemical properties
2. Combining both datasets
3. Using the top 20 correlated features

# Results
![](https://github.com/SRP457/DataAnalytics/blob/main/table1.png?raw=true)   ![](https://github.com/SRP457/DataAnalytics/blob/main/table2.png?raw=true)
![](https://github.com/SRP457/DataAnalytics/blob/main/table3.png?raw=true)   
![](https://github.com/SRP457/DataAnalytics/blob/main/figure1.png?raw=true)
