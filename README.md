# Multiple-Linear-Regression - Petrol Consumption Prediction

This project focuses on predicting petrol consumption using multiple regression analysis. The dataset contains features like petrol tax, average income, paved highways, population, and driver's license percentage.

**Overview**
This project utilizes Python with Pandas, NumPy, and Matplotlib for data manipulation, analysis, and visualization. The goal is to predict petrol consumption based on various features.

**Dataset**
The dataset (petrol_consumption.csv) contains information about petrol consumption and related features. It consists of 48 samples with 5 columns.

**Exploratory Data Analysis (EDA)**
We began by exploring the dataset's basic statistics and visualizing the relationships between features and the target variable.

**Feature Relationships**
We examined the correlations between features and petrol consumption. Notably, "Petrol Tax" and "Average Income" showed significant negative correlations.

**Multiple Regression Model**
We built a multiple regression model to predict petrol consumption based on the selected features. The model incorporates petrol tax, average income, paved highways, population, and driver's license percentage.

**Feature Importance**
We determined the feature importance by analyzing the coefficients. "Population Driver Licence (%)" emerged as the most influential feature.

**Model Evaluation**
The model was evaluated using Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared (R2) score. The R2 value of 0.62 suggests a reasonable fit.

