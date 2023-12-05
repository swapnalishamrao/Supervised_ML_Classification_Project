# Airline_Passenger_Referral_Prediction
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
This project focuses on analyzing a dataset containing information on passenger reviews of various airlines to predict whether passengers are likely to recommend the airline to others by employing various machine learning techniques, including Logistic Regression, Decision Trees, Random Forest, Gradient Boosting, XGBoost, K Nearest Neighbor, Naive Bayes, and Support Vector Machine. The objective is to determine the most effective method for forecasting  passengers will  recommend the airline to others or not.

# Problem Statement

In the competitive airline industry, pleasing customers and keeping them loyal is crucial for success. Airlines are always looking for new ways to make passengers happier and improve their reputation. One big challenge is figuring out which passengers are likely to recommend the airline to others.

The goal is to create a model that can predict which passengers will refer the airline to their friends. This model will help airlines:

  -Make customers happier

  -Make more money

  -Advertise more effectively

  -Provide better service
Stay ahead of the competition

# Dataset Attributes

**airline:** Name of the airline.

**overall:** Overall point is given to the trip between 1 to 10.

**author:** Author of the trip

**review date:** Date of the Review

**customer review:**Review of the customers in free text format

**aircraft:** Type of the aircraft

**traveller type:** Type of traveler (e.g. business, leisure)

**cabin:** Cabin at the flight date flown: Flight date

**seat comfort:** Rated between 1-5

**cabin service:** Rated between 1-5

**foodbev:** Rated between 1-5

**entertainment:** Rated between 1-5

**ground service:** Rated between 1-5

**value for money:** Rated between 1-5

**recommended**: Binary, target variable.

# Data Cleaning and Preprocessing
-First, because the "aircraft" column has over 80% missing information, it's been removed.

-Next, duplicate rows were deleted, which helped to reduce some missing data.

-The "review date" and "date_flown" columns had the wrong data type, so they were changed to the correct type, which is datetime.

-Finally, a new column called "year" was created using information from the "date_flown" column.

# Exploratory Data Analysis (EDA)
EDA was performed to:

- Identify errors, outliers, and anomalies.
- 
- Understand data patterns and relationships between variables.

# Feature Engineering

Engineered new features:

- Created a binary column based on positive or negative reviews from the overall rating column.

- Applied one-hot encoding on cabin_type, Airlines, and traveller_type to create new features.

# Model Building 

Implemented various classification models:

1.Logistic Regression

2.Decision Trees

3.Random Forest
 
4.Support Vector Machines (SVM)

5.Naive Bayes

6.K-Nearest Neighbors (KNN)

7.Neural Networks

8.Gradient Boosting models

9.XGBoost

# conclusion

**Achieved strong model performances with accuracies averaging around 95%. Identified an opportunity for improvement in detecting anomalies and correcting the recommendation column.**

**Model evaluation metrics comparison, we can see that Support Vector Machine being the model with highest accuracy rate by a very small margin, works best among the experimented models for the given dataset**.

•**The most important feature are overall rating and Value for money that contribute to a model's prediction whether a passenger will recommended a particular airline to his/her friends.**


