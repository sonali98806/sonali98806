## Employee Attrition Prediction Model

### Overview

This project aims to build a predictive model for employee attrition using machine learning techniques. Employee attrition refers to the process of employees leaving an organization. This model uses various features such as employee demographics, job satisfaction, and work environment factors to predict the likelihood of an employee leaving the organization.

### Objective

The primary goal of this project is to:

- Predict whether an employee will leave the company or not (binary classification problem).
- Understand the key factors that influence employee attrition.

### Datasets

The model is built using an employee dataset that includes features like:

- Age
- Job Role
- Department
- Monthly Income
- Job Satisfaction
- Performance Rating
- Years at Company
- Overtime (Yes/No)
- Attrition (Target: Yes/No)

### Tools and Libraries

The following Python libraries are required to run the model:

- *pandas*: For data manipulation and analysis
- *numpy*: For numerical computations
- *matplotlib* and *seaborn*: For data visualization
- *scikit-learn*: For machine learning models and evaluation
- *XGBoost* (Optional): For gradient boosting model

Install the libraries using pip:

bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost


### Model Building Process

1. *Data Preprocessing*:  
   - Handling missing values
   - Encoding categorical variables
   - Scaling numerical features

2. *Exploratory Data Analysis (EDA)*:  
   - Visualizing relationships between features and the target variable
   - Checking for feature correlations

3. *Model Selection*:  
   - Logistic Regression
   - Decision Trees
   - Random Forest
   - XGBoost (Optional)

4. *Model Training*:  
   - Split the dataset into training and testing sets (usually 80-20 split)
   - Train the selected models
   - Evaluate using metrics like Accuracy, Precision, Recall, F1-Score, ROC-AUC

5. *Hyperparameter Tuning*:  
   - Use techniques like GridSearchCV or RandomizedSearchCV to optimize model performance.

6. *Model Evaluation*:  
   - Compare the models based on evaluation metrics
   - Select the best-performing model for deployment
  
Employees working in R&D department are more, but employees from sales department or at position like sales executive,sale Representative leaves the job early.
Males are more under Attrition then Females
Age column is very well normalized, most of employees are age between 25 to 40.
we are having some of the numerical columns which are lebel encoded for us, they are ordinal labels, so let's have a look at them first
Employees from Bachelor are more, then from Masters background. Attrition wrt to bachelor can be seem more because they have more and more expectation from companies and it will be interesting to see the reason behind this in this dataset.
Accuracy Score - 0.645748987854251¶

