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


# Task 4: General Health Query Chatbot (Prompt Engineering Based)

## Objective

To build a chatbot that can answer general health-related questions using a Large Language Model (LLM) while ensuring responses are friendly, informative, and safe.

## Model Used

Llama 3 8B (via Groq API)

## Libraries Used

Groq

## Tasks Performed

Installed and configured the Groq API client

Created a conversational chatbot interface

Designed prompts using prompt engineering techniques

Implemented safety filters for emergency and high-risk medical queries

Generated clear and user-friendly health information responses

Added error handling for API requests

## Features

Provides general health information

Uses prompt engineering to guide model behavior

Prevents harmful medical advice

Detects emergency-related keywords and displays safety warnings

Supports continuous conversation until the user exits

## Example Queries

What causes a sore throat?

Is paracetamol safe for children?

How can I improve my sleep quality?

What are common symptoms of dehydration?

## Safety Measures

The chatbot does not diagnose medical conditions.

The chatbot does not prescribe medications.

Users are encouraged to consult healthcare professionals for serious concerns.

Emergency-related queries trigger a warning message advising immediate medical assistance.

## Key Findings

Prompt engineering significantly improves response quality and consistency.

Safety filters help reduce the risk of providing potentially harmful medical guidance.

The chatbot can effectively answer general health-related questions in a clear and friendly manner.

Combining LLM capabilities with safety rules creates a more reliable conversational health assistant.
