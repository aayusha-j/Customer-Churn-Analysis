# Customer Churn Analysis

## Project Overview
This project explores customer churn in a telecommunications company using Python. The goal is to understand customer behaviour, identify factors associated with churn, and generate useful business insights through Exploratory Data Analysis (EDA).

## Dataset
- Dataset: IBM Telco Customer Churn
- Total Records: 7,043
- Total Columns: 21
- Target Variable: Churn

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

## Data Cleaning
- Checked missing values and duplicate records.
- Converted `TotalCharges` into numeric format.
- Handled 11 missing values in `TotalCharges` using the median.
- Confirmed that no duplicate records remained.

## Exploratory Data Analysis
The project includes the following analyses:

1. Customer churn distribution.
2. Contract-wise churn analysis.
3. Customer tenure analysis.
4. Monthly charges analysis.
5. Correlation analysis between numerical features.

## Key Findings
- The dataset contains 7,043 customer records.
- 1,869 customers have left the service.
- 5,174 customers have continued using the service.
- Approximately 26.54% of customers have churned.
- The analysis explores how contract type, tenure, and monthly charges relate to customer churn.

## Visualizations

### 1. Customer Churn Distribution
![Customer Churn Distribution](Customer_Churn_Visualizations/customer_churn_distribution.png)

### 2. Contract-wise Churn
![Contract-wise Churn](Customer_Churn_Visualizations/contract_wise_churn.png)

### 3. Customer Tenure Distribution
![Customer Tenure Distribution](Customer_Churn_Visualizations/customer_tenure_distribution.png)

### 4. Tenure vs Churn
![Tenure vs Churn](Customer_Churn_Visualizations/tenure_vs_churn.png)

### 5. Monthly Charges Distribution
![Monthly Charges Distribution](Customer_Churn_Visualizations/monthly_charges_distribution.png)

### 6. Monthly Charges vs Churn
![Monthly Charges vs Churn](Customer_Churn_Visualizations/monthly_charges_vs_churn.png)

### 7. Correlation Heatmap
![Correlation Heatmap](Customer_Churn_Visualizations/correlation_heatmap.png)

## Project Files
- `Task_1_Customer_Churn_Analysis.ipynb` – Complete Python notebook.
- `Customer_Churn_Visualizations/` – Project visualization images.
- `README.md` – Project documentation.

## Conclusion
This project demonstrates how Exploratory Data Analysis can help understand customer churn patterns. The findings can help businesses identify customer groups that may need better support and retention strategies.
