# Titanic Dataset Analysis Report

## Objective
Perform exploratory data analysis (EDA) on Titanic dataset to find patterns affecting survival.

## Cleaning Steps
- Removed irrelevant columns: PassengerId, Name, Ticket, Cabin
- Handled missing values:
  - Age → median
  - Embarked → mode
- Encoded categorical variables:
  - Embarked: one-hot (Embarked_Q, Embarked_S)

## Key Findings
1. **Survival Count:** More passengers did not survive.
2. **Gender:** Females had higher survival rates.
3. **Passenger Class:** 1st class passengers survived more than lower classes.
4. **Age:** Middle-aged adults (20–45) had higher mortality; children survived more.
5. **Fare:** Higher fare correlated with higher survival.

## Conclusion
Gender, socio-economic status, age, and fare were key factors affecting survival. These insights can guide predictive modeling.
