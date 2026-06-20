# TRANSPORT-DEMAND-PREDICTION

## About the Project

This project uses Machine Learning to predict whether an upcoming transport trip will have **high demand** or **low demand** based on historical booking data.

The dataset comes from **MobiTicket**, a platform that helps transport operators manage ticket bookings and vehicle scheduling.

##  Objective

The goal of this project is to help transport companies:

* Predict passenger demand in advance
* Improve vehicle allocation
* Reduce empty seats
* Improve operational efficiency

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook
  
##  Dataset Features

Some important features used in the model:

* Travel Date
* Travel Time
* Departure Location
* Vehicle Type
* Maximum Capacity
* Seats Sold

Additional features such as **day of week** and **hour of travel** were created during preprocessing.

## Exploratory Data Analysis

I performed data cleaning, feature engineering, and visualization to understand travel patterns.

Some visualizations included:

* Seats sold by day of week
* Demand by hour
* Correlation heatmap
* Feature importance chart

##  Models Used

### Logistic Regression

Accuracy: **62%**

### Random Forest

Accuracy: **75%**

Random Forest performed better and was selected as the final model.

---

## Key Findings

* Travel location was the most important feature.
* Demand changes depending on the time of travel.
* Certain days of the week showed higher demand than others.

##  Future Improvements

* Include weather and holiday data
* Try XGBoost and other advanced models
* Build a web application for real-time predictions

##  Author

**Shivang**

B.Tech CSE (Data Science and Analytics)

DIT University, Dehradun
