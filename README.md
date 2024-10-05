Practical Machine Learning Project Report

Overview

This project leverages machine learning techniques to analyze and predict exercise activities using data collected from various wearable devices. The dataset comprises accelerometer readings from participants during different exercises, allowing us to predict the manner of exercise based on these readings.

Table of Contents

Introduction
Data Preprocessing
Model Training
Model Evaluation
Results
Conclusion
Dependencies
License
Introduction

Using devices such as Jawbone Up, Nike FuelBand, and Fitbit, it is now possible to collect vast amounts of data about personal activity. This project aims to predict exercise modes using accelerometer data from participants, contributing to the quantified self movement.

Data Preprocessing

In this section, we describe the steps taken to prepare the data for analysis. This includes loading the datasets, cleaning the data by removing columns with excessive missing values and irrelevant metadata, and eliminating zero variance columns. The cleaned training data is then split into a training set (70%) and a validation set (30%).

Model Training

Multiple machine learning models are trained using the training set, including Decision Tree, Random Forest, Gradient Boosting Machine (GBM), and Support Vector Machine (SVM). Each model is trained using cross-validation to ensure robustness and minimize overfitting.

Model Evaluation

The performance of each model is evaluated using accuracy and out-of-sample error metrics. A confusion matrix is generated for each model to visualize the prediction outcomes, allowing us to assess the effectiveness of each model in classifying the exercise activities.

Results

The model performances are summarized to highlight the accuracy and out-of-sample error for each model. The Random Forest model is identified as the best-performing model, demonstrating superior accuracy compared to the other approaches.

Conclusion

The Random Forest model successfully predicts exercise activities with an accuracy of over 99%. This project demonstrates the effectiveness of machine learning in analyzing physical activity data and contributes valuable insights into personal health management.

Dependencies

This project requires the following R packages: caret, rpart, rattle, kernlab, ggplot2, lattice, and corrplot. Users should ensure these packages are installed to run the project successfully.

