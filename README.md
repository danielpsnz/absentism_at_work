# Absenteeism at Work Classification

## Overview:
The Human Resources department of a company has identified an absenteeism issue among its employees. To address this, they aim to develop a classification model capable of accurately categorizing employees based on whether they are absent for more than four hours per month. This model will aid in future hiring decisions and enable better monitoring of current employees.

## Objectives:
* Data reading and initial analysis to determine the dataset's dimensions and independent variable names.

Data preprocessing:
* Handling missing values.
* Creating the target variable based on "Absenteeism time in hours." Assign 0 for values <= 4 hours and 1 for values > 4 hours.
* Removing irrelevant variables such as IDs and "Absenteeism time in hours."

Visualization and correlation analysis:
* Descriptive statistics, boxplots, histograms, and correlation matrices.

Modelling:
* Standardization of data using StandardScaler.
* Dataset division into training and testing sets.
* Application of a logistic regression model and optimization of parameters such as C and class_weight.
* Representation of the ROC curve for model evaluation.
* Thresholding probabilities and computation of metrics such as confusion matrix, accuracy, sensitivity, and precision on the test dataset.

## Data Information:
The dataset consists of 20 independent variables (X) and one dependent variable (Y), derived from "Absenteeism time in hours." 

Key variables include:
* ID: Employee ID.
* Reason for absence: Absence reason.
* Month of absence: Month of absence.
* Day of the week: Day of the week.
* Seasons: Season.
* Transportation expense: Transportation cost.
* Distance from residence to work: Distance from home to work.
* Service time: Work duration.
* Age: Age.
* Workload average/day: Daily workload.
* Hit target: Achievement percentage.
* Disciplinary failure: Disciplinary action.
* Education: Education level.
* Son: Number of children.
* Social drinker: Social drinker status.
* Social smoker: Social smoker status.
* Pet: Number of pets.
* Weight: Weight.
* Height: Height.
* Body mass index: Body mass index.
