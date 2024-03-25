# Predicting Student Performance with Linear Regression

## Purpose:

The Predicting Student Performance with Linear Regression project aims to predict the final grade (G3) of students based on various features from the student performance dataset using linear regression. The project provides hands-on experience in data exploration, preprocessing, model training, evaluation, and interpretation.

## Data Science Task:

Conduct predictive analysis on a student performance dataset to forecast students' final grades using linear regression. Employ Python and relevant data science libraries to preprocess the data, train the model, evaluate its performance, and visualize the results.

## Objectives:

1. **Data Exploration and Understanding:** Explore the student performance dataset to gain insights into the distribution of grades, relationships between variables, and potential predictors of final grades.
2. **Data Preprocessing:** Clean the dataset by handling missing values, duplicates, and categorical variables. Prepare the data for modeling by performing feature engineering and transformation.
3. **Model Training and Evaluation:** Train a linear regression model to predict students' final grades based on selected features. Evaluate the model's performance using metrics such as Mean Squared Error (MSE), Mean Absolute Error (MAE), and R-squared score (R2).
4. **Visualization:** Visualize the actual vs. predicted final grades to assess the model's effectiveness and identify areas for improvement.

## About Dataset:

The student performance dataset contains information about students' demographic characteristics, family background, study habits, and academic performance across three periods (G1, G2, G3). It includes features such as school, sex, age, address, family size, parental education, study time, failures, extracurricular activities, and final grades.

## File Locations:

- **Code:** `student_performance.ipynb`
- **Data Location:** `student-mat.csv`
- **Readme File:** `README.md`
- **Final Report:** `final_report.md`

## Dataset Overview:

The student performance dataset offers valuable insights into factors influencing students' academic outcomes. It serves as a valuable resource for educators, researchers, and policymakers seeking to understand the determinants of student success and implement targeted interventions to support student learning and achievement.

## Dataset Features:

- **school:** Student's school (binary: 'GP' - Gabriel Pereira or 'MS' - Mousinho da Silveira)
- **sex:** Student's sex (binary: 'F' - female or 'M' - male)
- **age:** Student's age (numeric: from 15 to 22)
- **address:** Student's home address type (binary: 'U' - urban or 'R' - rural)
- **famsize:** Family size (binary: 'LE3' - less or equal to 3 or 'GT3' - greater than 3)
- **Pstatus:** Parent's cohabitation status (binary: 'T' - living together or 'A' - apart)
- **Medu:** Mother's education (numeric: 0 - none, 1 - primary education (4th grade), 2 – 5th to 9th grade, 3 – secondary education or 4 – higher education)
- **Fedu:** Father's education (numeric: 0 - none, 1 - primary education (4th grade), 2 – 5th to 9th grade, 3 – secondary education or 4 – higher education)
- **Mjob:** Mother's job (nominal: 'teacher', 'health' care related, civil 'services' (e.g. administrative or police), 'at_home' or 'other')
- **Fjob:** Father's job (nominal: 'teacher', 'health' care related, civil 'services' (e.g. administrative or police), 'at_home' or 'other')
- **reason:** Reason to choose this school (nominal: close to 'home', school 'reputation', 'course' preference or 'other')
- **guardian:** Student's guardian (nominal: 'mother', 'father' or 'other')
- **traveltime:** Home to school travel time (numeric: 1 - <15 min., 2 - 15 to 30 min., 3 - 30 min. to 1 hour, or 4 - >1 hour)
- **studytime:** Weekly study time (numeric: 1 - <2 hours, 2 - 2 to 5 hours, 3 - 5 to 10 hours, or 4 - >10 hours)
- **failures:** Number of past class failures (numeric: n if 1<=n<3, else 4)
- **schoolsup:** Extra educational support (binary: yes or no)
- **famsup:** Family educational support (binary: yes or no)
- **paid:** Extra paid classes within the course subject (Math or Portuguese) (binary: yes or no)
- **activities:** Extra-curricular activities (binary: yes or no)
- **nursery:** Attended nursery school (binary: yes or no)
- **higher:** Wants to take higher education (binary: yes or no)
- **internet:** Internet access at home (binary: yes or no)
- **romantic:** With a romantic relationship (binary: yes or no)
- **famrel:** Quality of family relationships (numeric: from 1 - very bad to 5 - excellent)
- **freetime:** Free time after school (numeric: from 1 - very low to 5 - very high)
- **goout:** Going out with friends (numeric: from 1 - very low to 5 - very high)
- **Dalc:** Workday alcohol consumption (numeric: from 1 - very low to 5 - very high)
- **Walc:** Weekend alcohol consumption (numeric: from 1 - very low to 5 - very high)
- **health:** Current health status (numeric: from 1 - very bad to 5 - very good)
- **absences:** Number of school absences (numeric: from 0 to 93)
- **G1:** First period grade (numeric: from 0 to 20)
- **G2:** Second period grade (numeric: from 0 to 20)
- **G3:** Final grade (numeric: from 0 to 20, output target)

The dataset provides a rich source of information for analyzing and predicting student
