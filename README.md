Description
This script uses a regression model to analyze automobile data and predict a target variable (likely the price). The process involves data preprocessing, model training, and evaluation.

Key Functionalities:
Dataset Handling:

Loads an automobile dataset (_autos - regression - autos.csv) using pandas.
Handles missing values by filling numerical columns with the median.
Encodes categorical variables using one-hot encoding, creating dummy variables to prepare data for machine learning.
Feature and Target Definition:

The script defines the independent features (X) and the target variable (y). Here, the target variable is assumed to be price, which the model will predict.
Data Splitting:

Splits the dataset into training and testing sets using train_test_split from sklearn.model_selection, ensuring proper evaluation of the model's performance.
Model Training:

Implements Linear Regression using sklearn.linear_model.LinearRegression to build a predictive model.
Model Evaluation:

Evaluates the trained model using:
Mean Squared Error (MSE): Measures the average squared difference between predicted and actual values.
R² Score: Indicates how well the independent variables explain the variability of the target variable.
Libraries Used:
pandas and numpy: For data manipulation and preprocessing.
sklearn.model_selection: For data splitting into training and testing sets.
sklearn.linear_model: For building a linear regression model.
sklearn.metrics: For evaluating model performance.
Applications:
Price Prediction: Predict automobile prices based on features like engine size, horsepower, or brand.
Regression Analysis: Gain insights into which factors influence price the most.
Decision Support: Aid car dealers or buyers in pricing strategies.
