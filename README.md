Car Price Prediction - Machine Learning Project
Overview
This project aims to predict car prices using machine learning techniques. The dataset consists of various car attributes, and the goal is to build a predictive model by preprocessing the data, performing exploratory data analysis (EDA), and training a regression model.
Dataset
The dataset used in this project is CarPrice_Assignment.csv. It contains multiple features such as:
Car specifications (fuel type, engine location, body type, etc.)
Performance metrics (horsepower, engine size, etc.)
Price as the target variable
Preprocessing Steps
Data Loading: Read the dataset using Pandas.
Handling Missing Values: Checked for missing values and ensured data completeness.
Data Cleaning: Dropped irrelevant columns (e.g., CarName).
Encoding Categorical Variables: Converted categorical features such as fueltype, carbody, and fuelsystem into numerical representations using one-hot encoding.
Feature Scaling: Applied StandardScaler to normalize numerical features.
Train-Test Split: Split the dataset into training and testing sets (80-20 ratio) using train_test_split.
Exploratory Data Analysis (EDA)
Descriptive Statistics: Used describe() and info() to understand the dataset.
Correlation Analysis: Identified relationships between features using a heatmap.
Visualizations: Created histograms, scatter plots, and box plots to explore data distributions and outliers.
Model Training & Evaluation
Feature Selection: Dropped unnecessary columns and selected relevant features for training.
Linear Regression Model: Trained a regression model to predict car prices.
Performance Metrics: Evaluated the model using RMSE, MAE, and R² score.
Insights Gained
Engine size and horsepower are strongly correlated with car price.
Fuel type and engine location also impact the pricing.
Data preprocessing significantly improves model performance.
Future Improvements
Experiment with different models (e.g., Decision Trees, Random Forest, XGBoost).
Hyperparameter tuning for better accuracy.
Feature engineering to extract more meaningful insights.
Requirements
Install dependencies using:
pip install pandas numpy matplotlib seaborn scikit-learn
Running the Project
Load the dataset.
Run the preprocessing and EDA steps.
Train the model and evaluate performance.
Conclusion
This project demonstrates how machine learning can be applied to predict car prices based on various attributes. Further improvements can enhance model accuracy and robustness.






