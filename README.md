# End-to-End Telecom Customer Churn Project

## Project Overview
Customer churn is one of the biggest challenges faced by telecom companies. This project focuses on analyzing customer behavior and building machine learning models to predict whether a customer is likely to churn or not.

The project includes:
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Analysis
- Machine Learning
- Model Evaluation
- Power BI Dashboard

---

## Business Problem
Telecom companies lose revenue when customers leave their services. Identifying customers who are likely to churn helps businesses improve retention strategies and reduce customer loss.

---

## Dataset Information
Dataset used: IBM Telco Customer Churn Dataset

The dataset contains customer information such as:
- Demographics
- Internet services
- Contract details
- Payment methods
- Monthly charges
- Tenure
- Churn status

---

## Technologies Used

### Programming & Analysis
- Python
- Pandas
- NumPy

### Visualization
- Matplotlib
- Seaborn
- Plotly

### Machine Learning
- Scikit-learn

### Dashboard & Reporting
- Power BI

### Data Storage
- SQL

---

## Project Workflow

### 1. Data Cleaning
- Handled missing values
- Converted datatypes
- Removed inconsistencies
- Prepared clean dataset for analysis

### 2. Exploratory Data Analysis (EDA)
Performed analysis on:
- Customer demographics
- Contract types
- Payment methods
- Internet services
- Monthly charges
- Customer tenure

### 3. Machine Learning
Models used:
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

### 4. Model Evaluation
Evaluation metrics:
- Accuracy Score
- Confusion Matrix
- Classification Report
- ROC-AUC Score

### 5. Dashboard Visualization
Created interactive Power BI dashboard for:
- Churn trends
- Customer segmentation
- Revenue analysis
- Service-based churn analysis

---

## Key Insights
- Month-to-month contract customers showed higher churn rates.
- Customers with higher monthly charges were more likely to churn.
- Electronic check payment users had high churn probability.
- Long-term customers were more likely to stay.

---

## Project Structure

```text
end-to-end-telecom-churn-project/
│
├── data/
│   ├── Telco_customer_churn.xlsx
│   └── cleaned_telco_churn.csv
│
├── notebook/
│   └── IBM_Telecom_Customer_Churn_Project.ipynb
│
├── powerbi/
│   └── IBM_Telecom_Customer_Churn.pbix
│
├── README.md
└── requirements.txt
```

---

## How to Run the Project

### 1. Clone the Repository
```bash
git clone <your-repository-link>
```

### 2. Install Required Libraries
```bash
pip install -r requirements.txt
```

### 3. Open Jupyter Notebook
```bash
jupyter notebook
```

### 4. Run the Notebook
Open:
```bash
IBM_Telecom_Customer_Churn_Project.ipynb
```

---

## Future Improvements
- Feature Engineering
- Hyperparameter Tuning
- Cross Validation
- Deployment using Streamlit
- Pipeline Automation

---

## Author
Lucky Singh
Aspiring Data Scientist
