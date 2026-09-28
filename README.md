# AI/ML Recruitment Task - First Year

**Name:** Anirudh

## Tasks completed

- Task 1: Exploratory Data Analysis and Preprocessing on the Auto MPG dataset
- Task 2: Linear Regression to predict MPG

## Problem statement

Explore and clean the Auto MPG dataset, then use vehicle characteristics to predict miles per gallon (MPG).

## Approach

I checked the columns, missing values, and duplicate rows. I filled missing horsepower values with the median and removed exact duplicate rows. I used graphs and summary statistics to explore MPG and compare vehicle groups. For prediction, I tried a weight-only model and a multiple-feature linear regression model. I one-hot encoded origin and left the car name out of the model features.

## Notebook and data

- [Open the notebook in Google Colab](https://colab.research.google.com/github/anirudh220608-dev/AIML-Recruitment-2026-Anirudh/blob/main/AIML_First_Year_Auto_MPG.ipynb)
- The notebook creates `auto_mpg_cleaned.csv` when run.

## Technologies used

Python, Google Colab, pandas, NumPy, Matplotlib, Seaborn, and scikit-learn.

## Results

Run the notebook from top to bottom to create the graphs and model scores. The notebook includes notes about what to report for Task 1 and Task 2.

## Key learnings

- I learned how to inspect missing values and duplicate rows.
- I learned how plots and correlations can show relationships between variables.
- I learned how to split data into training and testing sets and evaluate a regression model.

## Challenge

Some horsepower values were missing, and car names are text. I filled missing horsepower values with the median and did not use car names as model features.
