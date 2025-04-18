
# Employee Turnover Prediction – Salifort Motors

This project was completed as part of the **Google Advanced Data Analytics Certificate** (Capstone Project).  
It focuses on analyzing HR data from Salifort Motors to identify patterns and build a predictive model that helps forecast which employees are likely to leave the company.

---

## Project Goals

- Predict employee turnover using machine learning
- Identify key drivers of attrition
- Provide actionable recommendations to HR and management

---

## Dataset

- Source: Kaggle HR Analytics Dataset  
- 14,999 employee records with features like:
  - Satisfaction level
  - Performance evaluation
  - Project count
  - Average monthly hours
  - Tenure
  - Promotion status
  - Department
  - Salary level (low, medium, high)

---

## Workflow Summary

1. **Exploratory Data Analysis (EDA)**  
   Visualized attrition patterns by features such as satisfaction, workload, and tenure.

2. **Feature Engineering**  
   Transformed and binned variables to improve predictive performance.

3. **Modeling**  
   Trained and compared:
   - Logistic Regression
   - Decision Tree
   - Random Forest
   - XGBoost

4. **Evaluation**  
   Measured performance using accuracy, precision, recall, and F1-score.

5. **Best Model**  
   Random Forest achieved ~98% accuracy and was chosen for its balance of performance and simplicity.

---

## Key Insights

- Employees with **low satisfaction**, **high workload**, **low salary**, and **no recent promotion** are more likely to leave.
- Departments like **Sales** showed higher turnover rates.

---

## Feature Importance

**Decision Tree Visualization:**  
![Decision Tree](https://github.com/AzadehHamidzad/Google_Capstone_Data_Driven_Suggestions_For_HR/blob/7d7f1fe11d4f97184c2f5bfa6cd62d4d3e684163/decision%20tree.png)

**Random Forest Feature Importance:**  
![Random Forest](https://github.com/AzadehHamidzad/Google_Capstone_Data_Driven_Suggestions_For_HR/blob/7d7f1fe11d4f97184c2f5bfa6cd62d4d3e684163/random%20forest1.png)

---

## Business Recommendations

- **Improve satisfaction** through regular feedback and engagement.
- **Monitor workloads** and prevent employee burnout.
- **Reward high performers** with recognition and advancement opportunities.
- **Adjust compensation** to be more competitive, especially for high-turnover roles.
- **Provide career growth paths** to reduce attrition due to stagnation.
- **Investigate departmental issues**, particularly in Sales.

---

## Project Files

- **[Jupyter Notebook – Full Analysis](https://github.com/AzadehHamidzad/Google_Capstone_Data_Driven_Suggestions_For_HR/blob/2e6164714d3d520126a2bc95eecc768f6e2a1370/Salifort_Motors_HR_Project.ipynb)**
- **[Project Report (PDF)](https://github.com/AzadehHamidzad/Google_Capstone_Data_Driven_Suggestions_For_HR/blob/080617bfcb6db58a9917bff983f9b9e101ce1d42/Employee_Turnover_Prediction_Salifort_Motors.pdf)**

---

## Author

**Alireza Saberi**  
*Google Advanced Data Analytics Certified*  
*Aspiring Data Analyst | Electrical Engineer | Problem Solver*

---

*Thanks for visiting! Feel free to explore the code, review the report, and share your thoughts.*
