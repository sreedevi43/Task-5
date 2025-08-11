Titanic Dataset – Exploratory Data Analysis (EDA)

Overview
-----------
This project is part of Data Analyst Internship – Task 5.
The aim was to perform Exploratory Data Analysis (EDA) on the famous Kaggle Titanic dataset to uncover patterns, trends, and key factors that influenced passenger survival.

Dataset
--------
Source: Kaggle Titanic Competition

File Used: train.csv

Size: 891 rows × 12 columns

Features:
-----------

Numerical: Age, Fare

Categorical: Sex, Pclass, Embarked

Missing Values:
---------------

Age – 177 missing entries

Cabin – ~687 missing entries

Embarked – 2 missing entries

Tools & Libraries
-----------------
Python – core programming language

Pandas – data manipulation and cleaning

Matplotlib – basic visualizations

Seaborn – advanced statistical plots

What Was Done
--------------
1. Data Inspection
Used .info() and .describe() to get an overview of data types and summary statistics.

Checked for missing values and their percentages.

2. Univariate Analysis – one variable at a time
Plotted survival distribution (38% survived, 62% did not).

Distribution of passenger classes (Pclass) – most were in 3rd class.

Gender distribution – more males than females.

Age histogram – most passengers between 20–40 years old.

Fare histogram – strongly right-skewed (most fares low, a few very high).

3. Bivariate Analysis – two variables at a time
Pclass vs Survival: Higher class → higher survival rate.

Sex vs Survival: Females had much higher survival rates than males.

Age vs Survival: Children had a slight survival advantage.

Fare vs Survival: Higher fares were linked to higher survival chances.

4. Correlation Analysis
Encoded categorical variables (Sex, Embarked) into numeric form.

Heatmap: Showed strongest correlations between survival and gender, fare, and passenger class.

Pairplot: Confirmed patterns — clusters of higher survival for females and higher-fare passengers.

Key Findings
---------------
Passenger Class: 1st class passengers had the highest survival rates.

Gender: Females survived far more often than males.

Fare: Paying more for a ticket was associated with better survival odds.

Age: Children had a small advantage in survival.

Cabin Data: Mostly missing, but could be turned into a binary “Cabin Known” feature.

 Conclusion
 ---------------
 Passenger class, gender, and fare were the most important indicators of survival, with age having a secondary effect.
 These variables are crucial for predictive modeling.


