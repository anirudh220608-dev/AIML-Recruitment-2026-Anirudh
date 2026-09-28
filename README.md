# AI/ML Recruitment 2026 - First Year

**Name:** [Your name]  
**Basic details:** [Add the details requested by the recruitment team]

## Tasks completed

- Task 1: Exploratory Data Analysis and Preprocessing on the Auto MPG dataset
- Task 2: Linear Regression to predict MPG

## Problem statement

Explore and clean the Auto MPG dataset, then use vehicle characteristics to predict miles per gallon (MPG).

## Approach

I inspected the columns, checked for missing values and duplicates, filled missing horsepower values with the median, and removed exact duplicate rows. I explored MPG with plots, compared MPG across cylinder counts and model years, and checked correlations. For Task 2, I tried a weight-only model and a multiple-feature linear regression model. Origin is one-hot encoded, and car name is not used as a feature.

## Files

- `AIML_First_Year_Auto_MPG.ipynb` - Google Colab notebook code
- `AIML_First_Year_Beginner_Submission.pdf` - Written task submission
- `auto_mpg_cleaned.csv` - Created when the notebook is run

## Colab link

[Paste the shareable Google Colab link here after setting viewer access.]

## Technologies used

Python, Google Colab, pandas, NumPy, Matplotlib, Seaborn, and scikit-learn.

## Results

Run the notebook and add the actual findings, graph observations, and regression scores here. Do not leave this section blank in the final submission.

## Key learnings

- I learned how to inspect missing values and duplicate rows.
- I learned how scatter plots and correlation can show relationships between variables.
- I learned how to split data into training and testing sets and evaluate a regression model.

## Challenge

The car name column is text, and some horsepower values are missing. I kept the car name out of the model features and filled missing horsepower values with the median.
