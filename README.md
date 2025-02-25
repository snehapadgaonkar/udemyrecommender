# Udemy Course Analysis and Recommendation System
![Udemy Logo](https://teach.udemy.com/wp-content/uploads/2021/08/Udemy_Logo_3280x1712-scaled.jpg)

## Overview
This project analyzes Udemy course data to generate a recommendation system that suggests courses based on user preferences (free or paid, specific subject). It also predicts whether a course is paid or free using machine learning models, and generates business insights to improve course offerings.

## Features
- **Data Preprocessing**: Cleans the dataset by handling missing values, removing unnecessary columns, and converting data types.
- **Exploratory Data Analysis (EDA)**: Visualizes course distribution by price, subject, and skill level to gain insights.
- **Machine Learning Models**: Trains models like Logistic Regression, Decision Trees, Random Forest to predict whether a course is paid or free.
- **Recommendation System**: Recommends courses based on user preferences such as price (free or paid) and subject.
- **Business Insights**: Provides actionable recommendations to improve course offerings and reduce churn.

## Requirements
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `sqlite3`

Install the required packages using:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```
## Files
- udemy_courses.csv: Dataset of Udemy courses.
- course_analysis.db: SQLite database storing course data and model predictions.
- storytellingassignment.ipynb: Script for analysis, model building, and generating recommendations

## Conclusion
This project helps analyze Udemy's course offerings and provides a recommendation system based on user preferences. By using machine learning, the model predicts whether a course is free or paid and helps businesses make data-driven decisions to enhance course engagement and reduce churn.