# AI/ML Internship Tasks

## Task 1: Exploring and Visualizing the Iris Dataset

### Objective

To learn how to load, inspect, analyze, and visualize a dataset using Pandas, Matplotlib, and Seaborn.

### Dataset Used

Iris Dataset

### Libraries Used

* Pandas
* Matplotlib
* Seaborn

### Tasks Performed

* Loaded the dataset
* Inspected dataset structure
* Generated summary statistics
* Created scatter plots
* Created histograms
* Created box plots

### Key Findings

* Dataset contains 150 records.
* Three species are present: Setosa, Versicolor, and Virginica.
* Petal measurements help distinguish species more clearly.
* Data distributions are generally well-behaved with limited outliers.

# Task 2: Predict Future Stock Prices (Short-Term)

## Objective

To predict the next day's stock closing price using historical stock market data and machine learning techniques.

## Dataset Used

Yahoo Finance Stock Market Data (AAPL - Apple Inc.)

## Libraries Used

* Pandas
* Matplotlib
* yfinance
* Scikit-learn

## Tasks Performed

* Downloaded historical stock data using yfinance
* Inspected and cleaned the dataset
* Created a target variable for the next day's closing price
* Selected Open, High, Low, and Volume as features
* Split data into training and testing sets
* Trained a Linear Regression model
* Generated predictions on test data
* Evaluated model performance using MAE, MSE, and R² Score
* Visualized Actual vs Predicted Closing Prices

## Key Findings

* Historical stock data was successfully retrieved from Yahoo Finance.
* Open, High, Low, and Volume showed strong relationships with the next day's closing price.
* The Linear Regression model was able to capture short-term price trends.
* Predicted values were generally close to actual closing prices.
* The comparison plot demonstrated the model's effectiveness in forecasting future stock prices.

# Task 3: Heart Disease Prediction

## Objective

To build a machine learning model that predicts whether a person is at risk of heart disease based on their health-related attributes.

## Dataset Used

Heart Disease UCI Dataset

## Libraries Used

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

## Tasks Performed

* Loaded the dataset
* Inspected dataset structure and summary statistics
* Checked and handled missing values
* Removed duplicate records
* Performed Exploratory Data Analysis (EDA)
* Visualized data using count plots, histograms, box plots, and correlation heatmap
* Converted the target variable into binary classes
* Split the dataset into training and testing sets
* Applied feature scaling
* Trained a Logistic Regression model
* Evaluated the model using Accuracy Score, Confusion Matrix, Classification Report, ROC Curve, and ROC-AUC Score
* Analyzed feature importance

## Key Findings

* The dataset contains patient health information related to heart disease risk.
* Exploratory Data Analysis helped identify relationships between features and the target variable.
* Logistic Regression successfully classified patients into heart disease and non-heart disease categories.
* ROC Curve and ROC-AUC Score demonstrated the model’s classification performance.
* Features such as chest pain type, maximum heart rate achieved, ST depression, and number of major vessels showed significant influence on prediction outcomes.
* The model achieved an accuracy of XX% and an ROC-AUC Score of XX (replace with your actual results).

