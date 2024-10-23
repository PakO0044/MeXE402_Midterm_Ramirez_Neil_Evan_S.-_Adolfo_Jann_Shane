# MeXE402_Midterm_Ramirez_Neil_Evan_S./Adolfo_Jann_Shane



# Introduction


## Overview of Linear Regression

### Linear Regression 

**Purpose**:

* Linear Regression is used to predict a continuous outcome (predicting house prices, sales, or temperatures) by establishing a linear relationship between the independent variables (features) and the dependent variable (target).

**Evaluation Metrics:**

* Mean Absolute Error (MAE): Average of absolute differences between predicted and actual values.
* Mean Squared Error (MSE): Average of squared differences between predicted and actual values.
* Root Mean Squared Error (RMSE): Square root of MSE, providing an error metric in the same unit as the target variable.
* R-squared : Measures the proportion of variance in the dependent variable that is explained by the independent variables. An R-squared value close to 1 indicates a good fit.

**Applications**:

* Predicting house prices based on features like size, location, number of rooms, etc.
* Estimating a company's future sales based on past data.
* Forecasting stock prices or trends in financial markets.

### Overview of Logistic Regression

**Purpose**:

* Logistic Regression is used for classification tasks, where the goal is to predict the probability of an outcome belonging to a particular class (spam or not spam, purchase or no purchase).

**Types**:

* Binary Logistic Regression: For two possible outcomes (pass/fail, yes/no).
* Multinomial Logistic Regression: For more than two classes (predicting which type of flower a sample belongs to).
* Ordinal Logistic Regression: For ordered outcomes (rating scales like poor, average, good).

**Evaluation Metrics:**

* Accuracy: Proportion of correct predictions.
* Confusion Matrix: Shows true positives, true negatives, false positives, and false negatives.
* Precision, Recall, F1-Score: Useful for evaluating models with imbalanced classes.
* AUC-ROC Curve: Measures the model's ability to distinguish between classes at various threshold settings.

**Applications**:

* Predicting whether a customer will buy a product (yes/no).
* Diagnosing a disease based on patient data (disease/no disease).
* Identifying whether an email is spam or not.

# Dataset Description

### Real State.csv Dataset

* This dataset seems to include details about real estate properties. The columns provided in the document include information like transaction date, house age, distance to the nearest MRT station, number of convenience stores nearby, latitude, longitude, and the price of the house per unit area.
* "House price of unit area" is a critical variable in real estate datasets because it provides a standardized measure of the price of a property relative to its size or area, allowing for fair comparisons between different properties. This variable is essential for evaluating the affordability, investment potential, and market value of real estate properties. Understanding the price per unit area helps buyers, sellers, investors, and real estate professionals assess property values accurately, identify trends in housing markets, make informed decisions regarding property purchases or sales, and conduct financial analyses such as return on investment calculations or property valuation assessments.

### Wine.csv Dataset

* In this dataset it appears to contain information related to various attributes of wines. The columns listed in the document are likely features or characteristics of the wines, such as fixed acidity, volatile acidity, citric acid, residual sugar, chlorides, free sulfur dioxide, total sulfur dioxide, density, pH, and possibly a target variable 's' which is not explicitly defined in the provided excerpt.
* The variable "color" in a wine dataset is crucial because it distinguishes between different types of wines, specifically red and white wines. The color of wine is a fundamental characteristic that directly influences various aspects of its composition, taste, aroma, and overall quality. Red and white wines are typically produced using different grape varieties and fermentation processes, leading to significant differences in flavor profiles and characteristics. Analyzing and categorizing wines based on their color helps wine enthusiasts, producers, and researchers understand the distinct features and nuances of each type, enabling better classification, recommendation systems, and targeted analysis for specific preferences or studies.

# Project Objectives

### Data Cleaning and Preprocessing:

* Clean and preprocess the datasets to handle missing values, normalize data, and ensure consistency for accurate analysis.
* Standardize features to enable fair comparisons and improve model performance.

### Model Evaluation and Optimization:

* Compare different machine learning models (e.g., Linear Regression, Logistic Regression, Decision Trees) for predictive accuracy.
* Optimize the models using hyperparameter tuning to enhance performance.

### Visual Storytelling and Reporting:

* Create a series of visualizations and reports that clearly communicate the insights derived from the data analysis to stakeholders.
* Provide actionable insights and recommendations based on the analysis to guide decision-making in real estate investment or wine production and marketing.
