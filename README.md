## 🚕 Automatidata – Taxi Fare Regression Model (Course 5)

A multiple linear regression project completed as part of Course 5: Regression Analysis: Simplify Complex Data Relationships in the Google Advanced Data Analytics program.
This project builds a predictive model for NYC Yellow Taxi fares using engineered features derived from trip characteristics. 
The analysis includes data cleaning, outlier handling, feature engineering, correlation assessment, model training, and evaluation to understand how trip attributes influence fare amounts and to create a model that can generalize well to new taxi ride data.


### 📌 Project Objectives
* Perform exploratory data analysis (EDA) to understand patterns in fare, distance, and trip duration


* Identify and correct data quality issues, including extreme outliers and invalid entries


* Engineer features such as mean distance and time-based indicators


* Build a multiple linear regression model to predict fare amount


* Evaluate model performance using R², MAE, and RMSE


* Interpret model coefficients to understand the impact of key predictors on fare amounts


* Summarize insights and assess model limitations



### 🧰 Technologies Used
* Python 3


* pandas, NumPy


* matplotlib, seaborn


* scikit-learn


* Jupyter Notebook



### 📊 Key Insights
* Data quality issues such as negative fares, negative durations, and extreme outliers were present and required correction for reliable modelling.


* Trip behavior varies by route, and route-level features such as mean distance and mean duration proved highly predictive of fare amount.


* The final model showed strong linear relationships between fare, distance, and duration, confirming that linear regression is a suitable method for this dataset.


* Evaluation metrics (R², MAE, RMSE) indicate that the model captures most of the meaningful variance in fare prices, though some unexplained variability remains due to factors not included in the dataset (traffic, tolls, weather, etc.).


* Regression coefficients highlight the practical effect of each predictor, with distance- and duration-related features contributing the most to fare amount.


* The model performs well overall but may benefit from additional features, geographic information, or alternative modelling techniques for increased predictive accuracy.

