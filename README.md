# Glassdoor Salary Prediction Project
📁 Project Overview
This project aims to Analyze and Predict salaries from Glassdoor Job Data.
Using a rich set of job attributes (such as job title, location, company size, and more), we:

✅ Performed extensive Exploratory Data Analysis (EDA) (univariate, bivariate, multivariate)
✅ Handled missing values, outliers, and applied encoding & scaling
✅ Built and evaluated Multiple Machine Learning models
✅ Performed Hyperparameter Tuning and Model Validation (CV)
✅ Finalized Random Forest Regressor as the best model for salaries’ prediction
✅ Derived insightful answers to key questions:

How salaries vary by job position (e.g., Data Scientist vs DevOps Engineer).

Impact of company size on salaries.

Difference in salaries across locations (e.g., San Francisco, New York).

Ability to predict salaries based on job attributes.

🛠 Tech Stack
Python

Pandas, NumPy for data manipulation

Matplotlib, Seaborn for visualization

Scikit-learn for ML algorithms, hyperparameter tuning, and validation

Jupyter Notebook for interactive analysis

🔹 Methodology
1️⃣ Data Cleaning & Preprocessing
Handled missing values by imputation

Encoded categorical variables

Standardized features using StandardScaler

Capped outliers to handle skewness

2️⃣ Exploratory Data Analysis (EDA)
Univariate (distribution of salaries, job roles, locations, etc.)

Bivariate (salary vs company size, job title, and location)

Multivariate (combining factors to find patterns)

3️⃣ Feature Engineering
Encoded categorical variables

Standardized numerical variables

Capped outliers to minimize their influence

4️⃣ Model Training and Hyperparameter Tuning
Models tried:

Linear Regression

Lasso Regression

Random Forest Regressor

Gradient Boosting Regressor

Hyperparameter tuning performed to maximize performance.

5️⃣ Model Validation
5-fold Cross Validation to compute Mean CV R² and Standard Deviation

Final Model (Random Forest Regressor) chosen due to highest Mean CV R² (0.61) and low variance (std 0.15)

📊 Summary of Model Performance:
Model	Mean CV R²	Std
Linear Regression	0.61	0.21
Lasso	0.60	0.20
Random Forest (Chosen)	0.61	0.15
Gradient Boosting	0.60	0.19

🔹 Final Conclusion:
✅ The Random Forest Regressor performs well with:

Mean CV R² ≈ 0.61

Standard deviation ≈ 0.15

✅ It shows stability across different folds and performs comparably or better than the other models.
