# Day 1 – Linear Regression with Python (Data Science Workshop)

Welcome to **Day 1** of the Data Science Workshop!  
Today’s session focused on building a **Linear Regression model from scratch** using Python, along with essential exploratory data analysis (EDA) techniques and model evaluation metrics.

---

## Objective

The goal of this exercise was to:
* Understand the structure of a real-world dataset
* Perform basic exploratory data analysis
* Build and train a Linear Regression model
* Evaluate model performance using standard metrics

---

## Libraries Used

The following Python libraries were used throughout the session:

* **pandas** – data loading and manipulation  
* **numpy** – numerical computations  
* **seaborn** – statistical data visualization  
* **matplotlib** – plotting graphs  
* **scikit-learn** – model building, training, and evaluation  

---

## Dataset Overview

* Dataset: **USA_Housing.csv**
* Target variable: **Price**
* Features used:
  - Avg. Area Income  
  - Avg. Area House Age  
  - Avg. Area Number of Rooms  
  - Avg. Area Number of Bedrooms  
  - Area Population  

Initial inspection included:
* Viewing first and last records
* Checking dataset shape
* Reviewing column names
* Understanding data types and missing values
* Statistical summary using `describe()`

---

## Exploratory Data Analysis (EDA)

To understand relationships and distributions:
* **Pairplot** was used to visualize relationships between all numeric features
* **Distribution plot** of house prices helped observe price spread and skewness

These visualizations provided insight into feature correlations and overall data behavior.

---

## Model Training – Linear Regression

### Feature Selection
Independent variables (X) were selected based on numeric housing attributes, while **Price** was used as the dependent variable (Y).

### Train-Test Split
* Data was split into **70% training** and **30% testing** sets
* This ensured fair evaluation on unseen data

### Model Creation
* A Linear Regression model was initialized using `LinearRegression()`
* The model was trained using the training dataset

---

## Model Evaluation

### Coefficients Analysis
* Model coefficients were extracted and displayed in a tabular format
* This helped interpret how each feature influences house prices

### Predictions
* Predictions were generated for the test dataset
* Actual vs predicted values were compared visually using a scatter plot

### Performance Metric
* **Root Mean Squared Error (RMSE)** was calculated to measure prediction accuracy
* RMSE provided an understanding of average prediction error in price units

---

This concludes **Day 1** of the Data Science Workshop.


