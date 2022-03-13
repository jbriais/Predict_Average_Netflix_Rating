# Predict_Average_Netflix_Rating
Group and individual project to predict the average Netflix movie rating using Machine Learning Algorithms on Python.

Data Source: https://www.kaggle.com/netflix-inc/netflix-prize-data

This project had two parts: one in a group on Google Colab and an individual part on Google Colab and Jupyter.

In the group part, we performed data preprocessing and Exploratory Data Analysis (EDA).

In the individual part, I cleaned and transformed the data, by doing feature engineering, imputing the missing values for numerical and categorical values, creating dummy variables with OneHotEncoder, and scaling the data.

I also built a scatter matrix with pandas to visualise the correlations between the target variable and the main independent variables.

I built the 5 models below and picked the best one, by comparing them against the baseline Root Mean Squared Error (RMSE):
1. Linear Regression 
2. Decision Trees 
3. Random Forest 
4. Support Vector Regression 
5. AdaBoost

For some models, I tuned the hyperparameters using GridSearch and I sometimes used cross validation.

Libraries used: numpy, pandas, seaborn, matplotlib, scikitlearn (train-test split, imputers, OneHotEncoder, scaling, cross validation, Random Grid Search...).
