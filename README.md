# Time Series Analysis on Automobile Fuel Efficiency 

## Objective
Explore and predict automobile fuel efficiency (measured in miles per gallon or mpg) using historical data.

## Data Source
Utilized the "Auto MPG" dataset from the UCI Machine Learning Repository. The dataset provides features such as vehicle displacement, horsepower, weight, acceleration, and model year.

## Key Steps
- **Data Preparation:** Initial data exploration revealed missing values and anomalies, which were subsequently handled to prepare a clean dataset for modeling. missing values and anomalies to ensure a clean dataset.
- **Exploratory Data Analysis:** Comprehensive EDA was conducted to understand the distribution, correlation, and potential relationships within the dataset.
- **Modeling:** A linear regression model was chosen for its simplicity and interpretability. This model was trained to predict the target variable (mpg) based on the aforementioned vehicle features.
- **Performance Evaluation:** The model's predictions were assessed using Mean Squared Error (MSE), yielding a value of 10.5024.
- **Baseline Comparison:** The model's performance was benchmarked against a baseline model that predicts the mean mpg for all observations. Our model showcased significantly better results than the baseline MSE of 51.6203.

## Conclusion
This project establishes a foundational model for predicting automobile fuel efficiency. While outperforming a simple mean-based prediction, potential exists for further model refinement and accuracy enhancement. The insights gleaned are of value to both automobile consumers and industry stakeholders.
