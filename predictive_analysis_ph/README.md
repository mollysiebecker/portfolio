# Predicting pH in Beverage Manufacturing
This project explores the use of machine learning to predict the pH levels of beverages based on manufacturing variables at a hypothetical beverage company. This collaborative project was completed as part of a data science course focused on predictive analysis and machine learning models. 

## Project Summary
Objective: Understand which manufacturing factors most strongly influence pH and develop a reliable model to predict pH using available production data.

Dataset: The dataset included 33 production-related variables across four different beverage brands, with missing values imputed using standard industry methods.

Business Context: Proper pH control is essential for meeting FDA safety guidelines, avoiding contamination, and maintaining a stable product.

## Key Findings
Top Predictor: Manufacturing flow rate (speed of production line) was the most influential variable, negatively correlated with pH.

Missing Data: All variables contained some degree of missingness (up to 8.25%), requiring careful cleaning and imputation.

Modeling: After comparing five models, one emerged as the most accurate and interpretable.

## Models Tested
MARS (Multivariate Adaptive Regression Spline)

SVM (Support Vector Machine)

Neural Network (NNet)

Gradient Boosting Machine (GBM)

Random Forest (RF)

Each model was tuned and evaluated using standard performance metrics (e.g., RMSE, MAE, R²). The best-performing model was analyzed further to identify the strongest predictors of pH.

## Tools & Techniques
R, caret, earth, gbm, randomForest, xgboost, e1071, nnet, DMwR, summarytools, ggplot2, janitor, mice

## Collaborators
This was a group project completed in collaboration with:

Banu Boopalan

Jonathan Burns

Daria Dubovskaia

Marley Myrianthopoulos

Molly Siebecker

## Reports & Output
[Non-Technical Summary Report](./non_technical_report.pdf)

[Rendered Technical Report on RPubs](https://rpubs.com/exprmcg/1257279)

