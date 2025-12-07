Customer Churn Prediction Using Machine Learning

This project predicts whether a customer is likely to churn using customer behavior, service usage, and billing information.

The goal is to help businesses identify at-risk customers and take preventive actions.
 Models Implemented
- Logistic Regression  
- Decision Tree Classifier  
- Random Forest Classifier  
 Problem Type
- Binary Classification  
- Target Variable: Churn (`0` = No, `1` = Yes)
 Dataset Information
The dataset contains customer details such as:
- Tenure
- Monthly Charges
- Total Charges
- Contract Type
- Internet Service
- Payment Method
- Gender
- Senior Citizen
- Partner & Dependents

Missing values were handled and categorical variables were encoded before training.
Project Workflow
1. Load Libraries  
2. Data Loading  
3. Exploratory Data Analysis (EDA)  
4. Data Preprocessing  
5. Feature Engineering  
6. Model Building  
7. Model Evaluation  
8. Model Comparison Summary  
Model Performance Comparison
Model	Accuracy	F1-Score
Logistic Regression	80%	0.80
Decision Tree	76%	0.75
Random Forest	79%	0.78

Conclusion
Random Forest gives the best performance for churn prediction among all three models.
 Technologies Used
- Python  
- NumPy  
- Pandas  
- Matplotlib  
- Seaborn  
- Scikit-learn  
How to Run the Project

1. Clone the repository:
```bash
git clone https://github.com/your-username/customer-churn-prediction.git
cd customer-churn-prediction
