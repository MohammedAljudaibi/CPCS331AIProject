# Machine Learning Example on Students Tests

## Table of Contents
- [Problem Statement](#Problem-Statement)
- [Dataset Description](#Dataset-Description)
- [Implementation](#Implementation)
- [Conclusion](#Conclusion)

## Problem Statement

The problem that will be discussed in this paper relates to students and what factors affect their grades in exams. The objective is to use machine learning algorithms to predict student grades and determine which factors have the most significant impact on their performance.

## Dataset Description

The dataset used in this project consists of 1000 entries of students who took exams. It contains information on their gender, race, parents' education, school lunch, and test scores.

## Implementation

To apply machine learning algorithms from the SKLearn library, the categorical data must be converted into numerical data. The following nominal variables will be converted using SKLearn's OneHotEncoder:

- Gender
- Race
- Lunch
- Test Preparation Course

Since parents' education is an ordered category, it will be manually encoded to be able to order and convert them to numerical type.

The target variable will be the average score, while everything else will be in the predictor variables array.

The dataset will be split into training and testing sets, and the following classifiers will be used to train the model:

- AdaBoost Classifier

- Random Forest Classifier

- Gradient Boosting Classifier

After training the model, the performance of each algorithm will be compared to select the best one.

## Conclusion

In conclusion, this project aims to predict student grades using machine learning algorithms and determine the factors that most significantly impact their performance. Although the initial implementation may have room for improvement in accuracy, this project provides an excellent foundation for future research and analysis.

## ToDo
Improve accuracy, find what is causing the prediction accuracy to be lower than expected.
