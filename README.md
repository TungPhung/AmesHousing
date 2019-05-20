### Project 2 - Predicting the price of houses in Ames, Iowa
Project By: Tung Phung - Data Scientist

## Goals
The goal of this project is to utilize housing data from Ames, Iowa residential real estate transactions
to build a meaningful linear regression model to predict home prices. We will have access to a training data set with the complete data (including sale prices) and another test dataset missing the sale prices so we
can simulate an actual unknown and study the effects of possible over/under-fit models and their real-world applicability.

## Methods
Using Python, pandas and dataframes as the primary mode of analysis as well as Python-based dependencies matplotlib, seaborn, and numpy to complete the analysis. Analysis is completed in Jupyter Notebook form and all suggestions are contained within the Jupyter Notebook. Will utilize Linear Regression models native to sci-kit learn (sklearn) package as well as Lasso/Ridge/ElasticNet regularization penalty functions. Scores will be cross-validated and optimal parameters are primary found using GridSearchCV.

## Conclusions
The final model relied on mostly numerical columns to get the best fit according to Kaggle RMSE scoring. However, this was proven not to be the method following the revealing the final full hold-out data set and subsequent rescoring of results. This reveals a significant amount of overfit to the provided data. Future work must work to advance feature engineering and probably increase use of regularization methods. As suspected early in the study, there may be many predictors in the saleprice which were not truly indepedent. As they were factored into the final results of the study, future work would seek to carry out more analysis to determine correlated predictors and their impact on the final results of the study.

## Reference Sources
http://jse.amstat.org/v19n3/decock/DataDocumentation.txt
