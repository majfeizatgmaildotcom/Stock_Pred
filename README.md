<img src="images/Stock_Pred.png">

# US Stock Trading Prediction Model
From Majid Feiz, ML model for Stock prediction\
**Project Status: Completed**
<br>
<a href="https://github.com/majfeizatgmaildotcom/Stock_Pred/blob/fea91ec6e898279e076d3201eddbc526dcfb90e0/1-PreProcess.pdf"> 1-PreProcess Jupyter Notebook Viewer</a>\
<a href="https://github.com/majfeizatgmaildotcom/Stock_Pred/blob/fea91ec6e898279e076d3201eddbc526dcfb90e0/2-Feature_Calculation.pdf"> 2-Feature_Calculation Jupyter Notebook Viewer</a>\
<a href="https://github.com/majfeizatgmaildotcom/Stock_Pred/blob/fea91ec6e898279e076d3201eddbc526dcfb90e0/3-Feature_Selection.pdf"> 3-Feature_Selection Jupyter Notebook Viewer</a>\
<a href="https://github.com/majfeizatgmaildotcom/Stock_Pred/blob/fea91ec6e898279e076d3201eddbc526dcfb90e0/4-LinearModel_Gen.pdf"> 4-LinearModel_Gen.pdf Jupyter Notebook Viewer</a>

## Project Objective
This project aims to create a ML model to predict the daily stock return for the US stocks
trading. In this project, a subset of the Quandl Wiki data used to create a range of features that 
capture information about the future returns. The quality of these features has been evaluated. 
Features that have correlated with each other’s eliminated from the feature selections, and 
those that have highly correlated with the daily return are used as inputs to the machine learning 
models. Linear Regression with Ridge and Lasso regularization strategy selected to train the 
model and relative performance evaluated over the 16 fold cross-validation.
There are four main steps in this project:
1) Pre Processing the data
2) Features Calculations
3) Feature Selections
4) Building Linear Regression based on Ridge and Lasso and optimizing for the 
regularization
