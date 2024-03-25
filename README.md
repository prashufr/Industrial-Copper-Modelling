# Industrial-Copper-Modelling

Problem Statement:

The copper industry deals with less complex data related to sales and pricing. However, this data may suffer from issues such as skewness and noisy data, affecting the accuracy of manual predictions. Dealing with these challenges manually can be time-consuming and may not result in optimal pricing decisions. A machine learning regression model can address these issues by utilizing advanced techniques such as data normalization, feature scaling, and outlier detection, and leveraging algorithms that are robust to skewed and noisy data.

Another area where the copper industry faces challenges is in capturing leads. A lead classification model is a system for evaluating and classifying leads based on their likelihood to become a customer. The solution aims to predict the likelihood of success (WON) or failure (LOST) based on the STATUS variable.

Solution Overview :

The solution includes the following steps:

Exploratory Data Analysis (EDA): Explore skewness and outliers in the dataset.
Data Preprocessing: Transform the data into a suitable format, handle missing values, treat outliers, and encode categorical variables.
Regression Model: Develop a machine learning regression model to predict the continuous variable Selling_Price.
Classification Model: Build a machine learning classification model to predict the status (WON or LOST) based on lead data.
Streamlit GUI: Create an interactive page using Streamlit, where users can input column values and get predicted Selling_Price or Status (WON/LOST).

Approach:

Data Understanding: Identify variable types and distributions, treat reference columns as categorical variables, and handle rubbish values.
Data Preprocessing: Handle missing values, treat outliers, and address skewness in the dataset.
EDA: Visualize outliers and skewness before and after preprocessing.
Feature Engineering: Engineer new features if applicable and drop highly correlated columns.
Model Building and Evaluation: Split the dataset, train and evaluate regression and classification models, optimize hyperparameters, and interpret model results.
Model GUI: Use Streamlit to create an interactive page for model predictions.

Learning Outcomes:

Proficiency in Python programming and data analysis libraries.
Experience in data preprocessing techniques.
Understanding and visualizing data using EDA techniques.
Learning and applying advanced machine learning techniques.
Building and optimizing machine learning models.
Experience in feature engineering.
Developing a web application using Streamlit.
Understanding challenges and best practices in the manufacturing domain.
