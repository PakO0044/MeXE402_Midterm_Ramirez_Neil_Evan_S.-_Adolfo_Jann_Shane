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

# Methodology

## Linear Regression - Real State.csv

### Data Loading:

* Loaded the "Real Estate.xlsx" dataset containing real estate transaction information.

### Data Exploration:

* Reviewed the first few rows of the dataset to understand its structure and content.
* Checked for missing values and data types to ensure data quality.

### Descriptive Statistics:

* Calculated descriptive statistics for each attribute to gain insights into the real estate data.

### Data Visualization:

* Created a scatter plot to visualize the relationship between house prices and the distance to the nearest MRT station.
* Generated a bar chart to show the distribution of houses based on the number of convenience stores nearby.

### Linear Regression Analysis:

* Utilized linear regression to predict house prices based on factors like house age, distance to MRT stations, and number of convenience stores.
* Split the data into training and testing sets.
* Trained the linear regression model using the training data and evaluated its performance on the test data.

## Logistic Regression - Wine.csv

### Data Loading:

* Loaded the "Wine.csv" dataset containing chemical properties of wines.

### Data Exploration:


* Reviewed the first few rows of the dataset to understand its structure and content.
* Checked for missing values and data types to ensure data quality.

### Descriptive Statistics:

* Calculated descriptive statistics (mean, median, standard deviation, etc.) for each attribute to understand the distribution of chemical properties.

### Data Visualization:

* Created a box plot for each chemical property to visualize the spread of data and identify any outliers.

### Linear Regression Analysis:

* Applied linear regression to predict wine quality based on chemical properties.
* Split the data into training and testing sets.
* Trained the model using the training data and evaluated its performance on the test data.


# Discussions

## Real Estate Dataset (Real Estate.csv):

**Regression Method**: Linear Regression

**Results**:

* Linear regression models the relationship between predictors like house age, distance to the nearest MRT station, number of convenience stores, etc., and the house price per unit area.
* The model predicts house prices based on the given features.

**Limitations**:

* Linear regression assumes a linear relationship between the features and the target variable, which may not always hold.
* It may not capture complex relationships in the data without feature engineering or using more advanced models.

## Wine Dataset (Wine.csv):

**Regression Method**: Regression analysis on wine quality or price

**Results**:

* Regression analysis could predict wine quality or price based on features like acidity levels, residual sugar, etc.
* The model aims to understand how these features affect the wine's quality or price.

**Limitations**:

* Wine quality or price may be influenced by a wide range of factors beyond the ones provided in the dataset.
* Non-linear relationships between features and wine quality may not be captured by simple linear regression models.

### Comparison

**Data Characteristics**:

* The real estate dataset deals with pricing of properties, while the wine dataset focuses on quality or price of wines.
* Real estate data may have more diverse features influencing prices (location, amenities), while wine data may focus more on chemical composition.

**Regression Methods**:

* Linear regression is a common choice for both datasets, but more complex models like polynomial regression or decision tree regression could be considered for the wine dataset.

**Interpretability**:

* Linear regression provides straightforward interpretations of feature coefficients, which can be valuable in real estate analysis.

**Performance**:

* The performance of the regression models will depend on the quality and quantity of data, feature selection, and the relationship between features and the target variable.

### Limitations

**Feature Selection**:

* Limited features in the datasets may restrict the models' ability to capture the full complexity of the underlying relationships.

**Overfitting**:

* Including irrelevant features or using overly complex models can lead to overfitting, especially in datasets with limited samples.

**Assumptions**:

* Linear regression assumes a linear relationship between features and the target variable, which may not be valid in all cases.

**Dataset Size**:

* Small datasets may limit the model's ability to generalize well to unseen data.

# References:

* https://www.kaggle.com/code/shirokaito1412/real-estate-prediction
* https://www.kaggle.com/code/kavishahaswani/eda-and-linear-regression/notebook
* https://www.kaggle.com/code/d4rklucif3r/red-wine-quality-eda-models

