TITLE: ""Gas and Oil Production Prediction in Argentine Productive Basins Using Linear Regression"

PROJECT OVERVIEW
This project applies Machine Learning techniques, specifically Linear Regression models, to predict gas and oil production volumes. Using an open-access dataset with hydrocarbon production data from 2006 to 2017, an Exploratory Data Analysis (EDA) was performed, followed by data cleaning. Two linear regression models (Standard Linear Regression and Ridge Regression) were developed to study the relationship between production variables.

DATASET
The dataset used was obtained from the Secretariat of Energy of Argentina. It includes hydrocarbon production variables such as gas, oil, and water volumes, filtered by different productive formations. The focus was primarily on the Precuyo productive formation.

HYPOTHESIS
The central hypothesis is that production variables (gas volume, oil volume, and water volume) have very low correlation with each other because they are influenced by the type of basin, field, productive formation (conventional, unconventional, tight), and specific geological factors (e.g., structural position, presence of faults, etc.).

EDA and DATA CLEANING
The exploratory analysis included: Univariate and bivariate analysis. The correlation between production variables was evaluated, revealing a strong linear relationship between gas and oil volumes when filtered by the Precuyo formation.
Outliers were removed, specifically where gas production exceeded 800 units, which broke the linear relationship with oil production.

LINEAR REGRESSION MODELS:
Two Linear Regression models were developed using Pandas, Numpy, Seaborn, Matplotlib, and Scikit-Learn libraries:
1) Standard Linear Regression Model (RL.fit)
2) Ridge Regression Model (Ridge.fit)

METRICS
Cost function: The models were evaluated using Mean Squared Error (MSE) and Root Mean Squared Error (RMSE).

CONCLUSIONS
The correlation between production variables varies significantly depending on the productive formation and other geological characteristics.
In the Precuyo formation, a good correlation between gas and oil was observed in predominantly gas-producing wells. However, when oil volume is low, gas tends to be very high, which led to the need to remove outliers.
The applied Linear Regression models achieved reasonable predictions, but moderate errors (MSE and RMSE) suggest that linearity does not hold across the full data range.

TECHNOLOGIES USED
Languages: Python
Libraries: Pandas, Numpy, Seaborn, Matplotlib, Scikit-Learn

HOW TO USE THIS PROJECT
https://github.com/juancat78/Gas_Petroleum_Production_2006-2017

CONTACT
For more information or inquiries, feel free to reach out to me via my LinkedIn profile:
www.linkedin.com/in/juan-pablo-catalano-8108b23b
