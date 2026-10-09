# Student Dropout Prediction

This is my first machine learning project. I made a model that predicts whether a student will drop out of college or not. I built it while following the 100 Days of Machine Learning course.

## About the data
- The dataset has 100,000 students and 34 columns
- Some columns are GPA, attendance, units passed, missed deadlines, stress level, etc.
- The column I predict is `dropout` (1 = dropped out, 0 = did not)

## What I did
1. Loaded the data and checked for missing values, duplicates and outliers
2. Removed some columns that didn't help much (like person_id, 'nationality',etc)
3. Converted the text columns into numbers
4. Split the data into train and test
5. Trained a logistic regression model
6. Checked how good it is

## Result
My model got **83.5% accuracy** on the test data.

## Things I learned
- How to clean data and handle categorical columns
- Accuracy alone is not enough, so I also looked at the confusion matrix
- Feature importance shows which columns matter most. For me the top ones were [your top 3]

## What I want to improve
- try to improve the accuracy
- Try tuning the model and other algorithms
- Check if the classes are balanced
- Try it on real data some day
  

## Tools used
Python, pandas, matplotlib, Google Colab

## How to run
Open the notebook in Google Colab, upload the dataset and run all the cells.

By Abhishek
