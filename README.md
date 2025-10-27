# Elevate-Labs-Projects-

📌 Objective

The main objective of this project is to analyze HR data to identify key factors contributing to employee attrition (resignation) and predict which employees are most likely to leave in the future.
This project helps HR teams to take proactive measures to improve employee retention.

⚙️ Tools & Technologies Used
Category	Tools
Programming Language	Python
Libraries	Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, SHAP
Visualization	Power BI
IDE	Jupyter Notebook / VS Code
📊 Dataset Description

The dataset contains detailed information about employees, including demographics, job roles, salary, performance, and attrition status.

Key Columns:

EmployeeID – Unique ID for each employee

Department – Department of the employee

Gender – Male/Female

Age – Age of the employee

Education – Education level

JobRole – Designation of the employee

SalaryBand – Income category

PromotionFlag – Whether the employee was promoted (Yes/No)

Attrition – Whether the employee left the company (Yes/No)

Performance – Performance rating

TenureMonths – Number of months the employee has been with the company

🧩 Project Workflow
🪜 Step 1: Data Cleaning

Removed null values and duplicates

Converted categorical values to proper text format

Created derived columns (e.g., Tenure Group)

🪜 Step 2: Exploratory Data Analysis (EDA)

Performed EDA using Python (Pandas, Seaborn):

Department-wise attrition distribution

Salary band vs Attrition

Promotion vs Attrition

Age and Tenure vs Attrition trend

🪜 Step 3: Model Building (Machine Learning)

Target Variable → Attrition (Yes/No)

Features → Age, JobRole, Department, SalaryBand, TenureMonths, Performance, etc.

Algorithms Tested → Logistic Regression, Decision Tree Classifier

Model Evaluation → Accuracy Score, Confusion Matrix, Classification Report

🪜 Step 4: Explainability with SHAP Values

Used SHAP (SHapley Additive exPlanations) to understand feature importance and interpret how each factor influences attrition prediction.

🪜 Step 5: Power BI Dashboard

Visualized major insights in an interactive dashboard:

Department-wise Attrition (Pie Chart)

Job Role vs Attrition (Clustered Bar Chart)

Salary Band vs Attrition (Stacked Column Chart)

Promotion vs Attrition (Stacked Bar Chart)

Tenure Group vs Attrition (Bar Chart)

📈 Key Insights

Departments like Sales and R&D showed higher attrition rates.

Employees who were not promoted in the last few years tend to leave more.

Lower salary bands and shorter tenure employees had higher turnover.

Younger employees (<30 years) are more likely to resign.

💡 Recommendations for HR Team

Implement reward and recognition programs.

Focus on career growth & promotion opportunities.

Provide salary benchmarking and fair compensation.

Conduct regular engagement and feedback sessions.

Identify at-risk employees early using predictive analytics.

📊 Dashboard Preview (Power BI)

Department-wise Attrition (%)

Job Role Attrition Ranking

Promotion vs Attrition

Tenure Group vs Attrition

Gender vs Attrition

(You can attach dashboard screenshots here)

🧾 Deliverables

Power BI Dashboard

ML Model Accuracy Report + Confusion Matrix

SHAP Value Analysis

PDF Report: Attrition Insights & Prevention Suggestions
