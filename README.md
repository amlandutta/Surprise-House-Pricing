# Surprise-House-Pricing
# Project: Predictive Modeling for Housing Market Entry

## General Information
- The project aims to assist a housing company, Surprise Housing, in entering the Australian market by developing predictive models for housing prices.
- The business problem revolves around identifying significant predictors of house prices and understanding their impact to make informed investment decisions.
- The dataset used contains information on various features of houses along with their corresponding sale prices.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## Conclusions
- The analysis identified the top 5 predictor variables for both Ridge and Lasso regression models.
  - For Ridge regression, the top predictors include 'Condition1_Artery', 'KitchenQual_Gd', 'Neighborhood_BrDale', 'Functional_Maj1', and 'Condition1_RRAn'.
  - For Lasso regression, the top predictors include 'Condition1_Artery', 'Neighborhood_BrDale', 'HeatingQC_Ex', 'CentralAir_N', and 'KitchenQual_Gd'.
- The optimal value of alpha for Ridge and Lasso regression was determined through cross-validation techniques, ensuring optimal model performance.
- Based on the specific characteristics of the dataset and modeling objectives, either Ridge or Lasso regression can be chosen. Ridge regression is preferred for multicollinear predictors, while Lasso regression is suitable for feature selection with many predictors.
- Ridge Regression - R-squared on Test Set: 0.88 and Lasso Regression - R-squared on Test Set: 0.89

## Technologies Used
Python 3.11.5 | packaged by Anaconda, Inc. | (main, Sep 11 2023, 13:26:23) [MSC v.1916 64 bit (AMD64)]

## Acknowledgements
- This project was inspired by the need for data-driven decision-making in the real estate industry.
- The analysis was based on techniques learned from various online courses and tutorials.

## Contact
Created by catalystamlan@gmail.com - feel free to contact me!
