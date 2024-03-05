# House Price Prediction

## Overview

This project is dedicated to enhancing house price prediction by addressing missing values, transforming variables, and extracting insightful features from the dataset. Advanced techniques such as XGBoost and Ridge Regression are employed to build models that capture the complexity of housing market dynamics.

## Objective

The primary objectives of this project include:

1. **Handling Missing Values:** Implement strategies to address missing values in the dataset effectively, ensuring a more robust and accurate predictive model.

2. **Feature Extraction:** Extract insightful features from the dataset to enhance the model's ability to capture relevant information influencing house prices.

3. **Modeling with XGBoost and Ridge Regression:** Apply advanced machine learning techniques, specifically XGBoost and Ridge Regression, to build predictive models for house price estimation.

4. **Performance Evaluation:** Evaluate the performance of the models using key metrics, with XGBoost excelling in R-squared (0.866979) and Ridge Regression demonstrating superiority in RMSLE (Root Mean Squared Logarithmic Error) with a value of 0.037812.

## Project Highlights

- **Data Preprocessing:** Comprehensive handling of missing values and transformation of variables to create a clean and feature-rich dataset for modeling.

- **Feature Engineering:** Identification and extraction of meaningful features from the dataset to improve the models' predictive capabilities.

- **XGBoost Excellence:** XGBoost, a powerful gradient boosting algorithm, emerges as the top performer with an impressive R-squared value of 0.866979, showcasing its effectiveness in capturing intricate patterns within the data.

- **Ridge Regression's RMSLE Superiority:** Ridge Regression, known for handling multicollinearity, excels in predicting house prices with a low RMSLE of 0.037812, indicating accurate logarithmic error metrics.

- **Variable Information:** Refer to the `data_description.txt` file for detailed information about each variable in the dataset.

## Repository Structure

- **/data:** Contains the dataset used for analysis and also the dataset obtained after EDA.
  
- **/notebooks:** Jupyter notebooks detailing the step-by-step process of data preprocessing, feature engineering, and model development.


## Variable Information

Details about each variable in the dataset can be found in the `data_description.txt` file.

## Conclusion

This project provides valuable insights into house price prediction by employing advanced techniques like XGBoost and Ridge Regression. The achieved R-squared and RMSLE metrics highlight the effectiveness of the models in accurately estimating house prices, laying the foundation for informed decision-making in real estate scenarios.
