AI-Intern-Attrition-Prediction
📌 Project Brief
This project aims to predict whether an employee is likely to leave the company (Attrition) using a Random Forest Classifier. The task involves data preprocessing, handling class imbalance using SMOTE, feature encoding, and model evaluation. Work was carried out in Google Colab.

📊 Dataset
The dataset contains various employee-related features such as age, job role, income, work experience, satisfaction levels, and more. The target variable is Attrition (Yes / No).
Key features include:

Age, BusinessTravel, Department, DistanceFromHome

Education, EducationField, Gender, JobRole

MonthlyIncome, TotalWorkingYears, WorkLifeBalance

YearsAtCompany, YearsInCurrentRole, OverTime

And many others (total: 35 columns)

⚙️ Methodology
Loaded and explored dataset

Encoded categorical variables

Applied SMOTE to handle class imbalance (initial recall without SMOTE was low)

Trained Random Forest Classifier with basic hyperparameter tuning

Evaluated using Accuracy, Precision, Recall, F1 Score, and Confusion Matrix

📈 Results
Using SMOTE + Random Forest:

Accuracy: 92.51%

Precision: 94.87%

Recall: 90.6%

F1 Score: 92.31%

The recall improved significantly after applying SMOTE compared to the normal Random Forest model without balancing.
