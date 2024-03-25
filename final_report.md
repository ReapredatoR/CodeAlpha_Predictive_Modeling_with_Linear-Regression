# CodeAlpha Internship Project Report: Predicting Student Performance with Linear Regression

## Introduction

For the CodeAlpha Internship Project, I undertook the task of predicting student performance with linear regression. The primary objective was to develop a model capable of accurately predicting students' final grades based on various features from the student performance dataset. The project utilized Python programming language along with data science libraries such as pandas, numpy, seaborn, and scikit-learn.

## Project Overview

### Methodology

1. **Data Loading and Exploration:**

   - Loaded the student performance dataset from `student-mat.csv`.
   - Explored the dataset to understand its structure, features, and data types.

2. **Data Preprocessing:**

   - Conducted data cleaning to handle missing values and duplicates.
   - Transformed categorical variables using one-hot encoding for model compatibility.

3. **Exploratory Data Analysis (EDA):**

   - Visualized distributions of grades (G1, G2, G3) using histograms.
   - Analyzed correlations between different features using a correlation matrix heatmap.
   - Investigated relationships between study time and final grades using scatter plots.

4. **Model Training and Evaluation:**

   - Split the data into training and testing sets.
   - Initialized a linear regression model and fit it to the training data.
   - Made predictions on the testing data and evaluated the model's performance using metrics such as Mean Squared Error (MSE), Mean Absolute Error (MAE), and R-squared score (R2).

5. **Visualization of Results:**
   - Plotted actual vs. predicted final grades to visualize the model's performance.

### Technologies Used

- Programming Language: Python
- Libraries: pandas, numpy, seaborn, matplotlib, scikit-learn

## Results and Key Findings

### Model Evaluation Metrics

- **Mean Squared Error (MSE):** 5.65626518786708
- **Mean Absolute Error (MAE):** 1.6465770866297469
- **R-squared Score (R2):** 0.724152540888019

## Discussion and Insights

1. **Model Performance:**

   - The linear regression model achieved moderate performance in predicting students' final grades, as indicated by the R-squared score of 0.724.
   - The mean absolute error (MAE) of 1.65 suggests that, on average, the model's predictions deviate by approximately 1.65 grade points from the actual final grades.

2. **Feature Importance:**
   - Further analysis could be conducted to explore the importance of different features in predicting student performance.
   - Identifying key predictors of academic success could inform interventions and support strategies for students at risk of academic underachievement.

## Conclusion

In conclusion, the project successfully developed and evaluated a linear regression model for predicting student performance based on the student performance dataset. The project enhanced my skills in data preprocessing, exploratory data analysis, model training, and evaluation. Moving forward, additional analyses and model improvements could be explored to further enhance predictive accuracy and derive actionable insights for educational stakeholders.

## Project Details

- Project Done by: Malinga Rajapaksha
- Assigned by: CodeAlpha
