Calorie Burn Prediction (ML Project)
Overview

This project explores how different types of exercises impact calories burned, using data on duration, heart rate, body temperature, and exercise type. The goal is to identify which workouts burn the most calories and to build a predictive model for calorie expenditure.

Key Findings

Duration is the strongest predictor of calories burned.

Running at high speeds produces the highest calorie burn per session (average).

Cycling and stair machine dominate in total calories burned due to frequency and popularity.

Findings align with exercise physiology literature: sustained, high-intensity activity that elevates heart rate leads to greater calorie burn.

Methods

Data Cleaning & Exploration

Handled missing values, duplicates, and categorical variables.

One-hot encoded exercise types and gender.

Analysis

Grouped exercises by average and total calories burned.

Visualized calorie expenditure by exercise type.

Modeling

Built baseline linear regression models.

Evaluated predictors including duration, heart rate, body temperature, and exercise type.

Example Results

Top exercises by average calories/session: Running (10.9 mph, 9 mph, 8.6 mph), Cross-country skiing, High-speed cycling.

Top exercises by total calories burned: Cycling (14–15.9 mph), Stair machine, Stationary cycling (vigorous).

Files

fitnessOne.ipynb → Main analysis notebook.

df_merged_final.csv → Dataset used for analysis.

How to Use

Clone this repo and open the notebook:

git clone git@github.com:Kay-Abdi/calorie-burn-ml.git
cd calorie-burn-ml
jupyter notebook fitnessOne.ipynb
