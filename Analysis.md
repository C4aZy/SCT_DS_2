# Titanic Dataset Analysis

## 1. Dataset Overview
- Dataset contains Titanic passenger information.
- Key columns: Survived, Pclass, Sex, Age, SibSp, Parch, Fare, Embarked.
- Missing values:
  - Age (177), Cabin (687), Embarked (2)
- Dropped columns: PassengerId, Name, Ticket, Cabin

## 2. Data Cleaning
- Cabin removed due to excessive missing values.
- Age filled with median.
- Embarked filled with mode.
- Dropped PassengerId, Name, Ticket.
- Categorical encoding:
  - Embarked: one-hot encoding (Embarked_Q, Embarked_S)
- Survived mapped to strings ('Survived'/'Not Survived') for visualization.

## 3. Exploratory Data Analysis (EDA)

### 3.1 Survival Count
- Count plot shows more passengers **did not survive** than survived.

### 3.2 Survival vs Gender
- Females had a **higher survival rate** than males.
- Historical context: “Women and children first” policy.

### 3.3 Survival vs Passenger Class
- 1st class passengers survived more than 2nd and 3rd class.
- Suggests socio-economic status influenced survival.

### 3.4 Age Distribution
- Most passengers: 20–45 years old.
- Histogram and boxplot: middle-aged adults had higher deaths; children survived more.

### 3.5 Fare Analysis
- Fare distribution left-skewed (most cheap tickets).
- Survivors generally paid **higher fares**, confirming wealthier passengers had better access to lifeboats.

## 4. Key Insights
1. Gender: Females survived more than males.
2. Passenger Class: Higher classes survived more.
3. Age: Middle-aged adults had higher mortality; children survived better.
4. Fare: Higher fare positively influenced survival.
