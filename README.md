# Titanic Survival Prediction Project

## Overview
This project aims to predict the survival of passengers aboard the Titanic using machine learning techniques. The Titanic dataset is a well-known benchmark for practicing data analysis, feature engineering, and model optimization. Through this project, I gained valuable insights into real-world applications of machine learning.

## Dataset
The Titanic dataset contains information on 891 passengers, with features including:
- **PassengerId:** Unique identifier for each passenger
- **Survived:** Survival status (0 = No, 1 = Yes)
- **Pclass:** Passenger class (1st, 2nd, 3rd)
- **Name:** Name of the passenger
- **Sex:** Gender of the passenger
- **Age:** Age in years
- **SibSp:** Number of siblings/spouses aboard
- **Parch:** Number of parents/children aboard
- **Fare:** Ticket fare
- **Embarked:** Port of embarkation (C = Cherbourg; Q = Queenstown; S = Southampton)

## Key Steps

### 1. Data Cleaning
- Addressed missing values, particularly in the Age and Cabin columns.
- Implemented imputation techniques to fill missing ages based on median values from similar passengers grouped by class and gender.

### 2. Exploratory Data Analysis (EDA)
- Utilized **Seaborn** and **Matplotlib** for data visualization.
- Identified key patterns, such as the higher survival rate among women and first-class passengers.
- Explored correlations between features to understand their impact on survival.

### 3. Feature Engineering
- Extracted the **Title** from passenger names to capture social and cultural context.
- Created a **FamilySize** feature by combining the number of siblings/spouses and parents/children, enhancing the model's ability to assess family structure and survival likelihood.

### 4. Model Selection
- Experimented with various machine learning algorithms, including:
  - **Logistic Regression**
  - **Random Forest**
  - **Gradient Boosting**
- Selected the top-performing models based on accuracy and balanced precision/recall scores.

### 5. Evaluation Metrics
- Focused on precision and recall due to the dataset's imbalance.
- Developed a model that effectively minimized misclassifications, particularly for survivors, achieving a strong balance in predictions.

## Key Takeaways
- **Data Preprocessing is Vital:** The quality of input data directly influences model performance.
- **Feature Engineering = Performance Boost:** Thoughtfully designed features can significantly enhance prediction accuracy.
- **EDA Guides Decision-Making:** Visualization provides insights that shape feature selection and modeling strategies.
- **Choosing the Right Metrics Matters:** Precision and recall are essential in classification tasks where misclassification costs differ.

## Tools & Technologies Used
- **Python**: Primary programming language
- **Pandas**: Data manipulation and analysis
- **Seaborn & Matplotlib**: Data visualization
- **Scikit-learn**: Machine learning model building and evaluation
- **Jupyter Notebook**: Workflow organization and documentation


