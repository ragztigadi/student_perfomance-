## Student Performance Indicator 

1) Problem Statement
This project aims to understand how various factors affect students' test scores. The features include gender, ethnicity, parental level of education, lunch type, and whether the student completed a test preparation course.

2) Data Collection
Dataset Source: Kaggle - Students Performance in Exams
Dataset Information: The dataset consists of 8 columns and 1000 rows.

3) Exploratory Data Analysis (EDA)
Following the data checks, exploratory data analysis was conducted to visualize relationships and trends within the data. Various plots were generated to illustrate the performance of students across different demographic groups.

4) Data Pre-Processing
Data pre-processing steps were implemented to prepare the dataset for model training, including:

5) Handling missing values
Encoding categorical variables
Normalizing/standardizing numerical features if necessary

4) Model Training
Different machine learning models were trained to predict students' performance based on the provided features. The models included:

Linear Regression
Ridge Regression
Lasso Regression
Random Forest Regressor
XGBoost Regressor
AdaBoost Regressor
CatBoosting Regressor
Model Performance Metrics
For each model, performance was evaluated using metrics such as:

Root Mean Squared Error (RMSE)
Mean Absolute Error (MAE)
R² Score

5) Results
The model results were summarized to highlight the best-performing models based on R² Score and other metrics. The findings from the analysis provided insights into how different factors influence student performance.

6) Technologies Used
Python Libraries: pandas, numpy, seaborn, matplotlib, scikit-learn, catboost, xgboost, Flask
