Daily Transactions Data Analysis

Project Overview:
This project focuses on analyzing daily financial transactions to understand spending and income patterns. The dataset contains personal transaction records including expenses, income, payment modes, and categories. The analysis is performed using Python in Jupyter Notebook with exploratory data analysis (EDA) and visualizations.

Objectives:
Analyze daily income and expense transactions.
Identify spending patterns across categories.
Understand payment mode usage.
Perform time-based analysis on transactions.
Generate meaningful insights using visualizations.

Tools & Technologies Used:
Python
Jupyter Notebook
Pandas – data manipulation
NumPy – numerical operations
Matplotlib – basic visualizations
Seaborn – advanced visualizations

Dataset Description
The dataset contains 2461 transaction records with the following columns:
| Column Name    | Description                |
| -------------- | -------------------------- |
| Date           | Date of transaction        |
| Mode           | Payment mode used          |
| Category       | Transaction category       |
| Subcategory    | Detailed subcategory       |
| Note           | Description of transaction |
| Amount         | Transaction amount         |
| Income/Expense | Type of transaction        |
| Currency       | Currency (INR)             |

Data Cleaning Steps:
Converted Date column to datetime format
Handled mixed date formats using dayfirst=True
Removed rows with invalid or missing dates
Filled missing values in Subcategory and Note columns

Exploratory Data Analysis (EDA):
Distribution of Income vs Expense
Most used payment modes
Top expense categories
Boxplots for amount distribution
Daily transaction trend analysis
Comparison of spending behavior across categories

Visualizations Included:
Count plot of Income vs Expense
Count plot of payment modes
Category-wise transaction distribution
Boxplot of transaction amounts
Line plot showing daily transaction trends

Key Insights:
Expense transactions are more frequent than income
Cash and bank transfers are the most commonly used payment modes
Food and transportation dominate daily expenses
Transaction amounts show significant variability across categories
Daily transaction trends indicate fluctuating spending behavior

Project Structure:
Daily_Transactions_Project/
│
├── Daily Household Transactions.csv
├── Daily_Transactions_Analysis.ipynb
├── README.md

How to Run the Project:
Download the repository
Place the dataset in the same folder as the notebook
Open Jupyter Notebook
Run Daily_Transactions_Analysis.ipynb cell by cell

Conclusion:
This project demonstrates practical data analysis skills including data cleaning, visualization, and interpretation of financial transaction data. The insights derived can help in budgeting, expense tracking, and financial planning.
