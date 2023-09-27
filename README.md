# EmployeeAttrition
# Project Description:
In a work environment, attrition is basically the turnover rate of employees inside an organization.This can happen for many reasons like employees looking for better opportunities,excessive working hours, negative working environment or sudden death. Companies with high attrition rates needs to spend more time and cost to train new employees constantly and hard to maintain quality control.

# Objective:
  1. Discover the factors that affect employee attrition and provide suggestion to reduce
  2. Build a machine learning model based on employee factors to predict whether that employee is       likely to attrition or not?

# Approach:
I have first did some basic data exploration like checking whether the dataset contains Null values and duplicate values, and cheking the shape of the dataset,data description, data types of the columns etc. Then I performed Exploratory Data Analysis on the data using various libraries like pandas,seaborn,matplotlib.

Then I have also used feature selection techniques like RFE (a wrapper method )to select the features. The data is then oversampled using the SMOTE technique in order to deal with the imbalanced classes. 

Lastly I have trained Logistic Regression, Decision Tree, and Random Forest classifier from Scikit-Learn library for employee attrition and measure the accuracy of models that are built.
# About Dataset
The dataset is supplied by Kaggle and contains HR analytics data of employees that stay and leave. The data consists of nearly 1,500 current and former employees with information related to their job satisfaction, work life balance, tenure, experience, salary, and demographic data. The dataset comprises various attributes and features associated with employees 

Education
1 'Below College'
2 'College'
3 'Bachelor'
4 'Master'
5 'Doctor'

EnvironmentSatisfaction
1 'Low'
2 'Medium'
3 'High'
4 'Very High'

JobInvolvement
1 'Low'
2 'Medium'
3 'High'
4 'Very High'

JobSatisfaction
1 'Low'
2 'Medium'
3 'High'
4 'Very High'

PerformanceRating
1 'Low'
2 'Good'
3 'Excellent'
4 'Outstanding'

RelationshipSatisfaction
1 'Low'
2 'Medium'
3 'High'
4 'Very High'

WorkLifeBalance
1 'Bad'
2 'Good'
3 'Better'
4 'Best'
