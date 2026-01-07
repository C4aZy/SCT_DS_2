# Titanic Dataset EDA

## Overview
Exploratory data analysis (EDA) on Titanic dataset to understand survival factors.

## Contents
- `train.csv` → cleaned dataset
- `EDA_Notebook.ipynb` → notebook with all cleaning and plots
- `analysis.md` → detailed EDA with insights
- `report.md` → concise report for submission

## Highlights
- Missing data handled for Age, Embarked, and Cabin
- Encoded categorical variables (Sex, Embarked)
- Plots:
  - Survival Count
  - Survival vs Gender
  - Survival vs Passenger Class
  - Age Distribution
  - Age vs Survival
  - Fare Distribution
  - Fare vs Survival
- Consistent color scheme: Survived=red, Not Survived=blue

## Insights
1. Females had higher survival than males.
2. 1st class passengers had higher survival than lower classes.
3. Middle-aged adults had higher mortality.
4. Higher fare passengers survived more.

## Usage
- Open `EDA_Notebook.ipynb` to run analysis and generate plots.
- Use `train.csv` for modeling or further analysis.
