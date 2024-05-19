# Personal-Loan-Data-Analysis-Exploratory-Data-Analysis-EDA-

Project Overview
This project involves performing an exploratory data analysis (EDA) on a dataset provided by HBFC bank to identify potential target customers for personal loans. The goal is to help the bank improve the effectiveness of their marketing campaigns by understanding the profile of customers who are more likely to accept personal loan offers.

Dataset Description
The dataset consists of information on 5000 customers and includes the following columns:

ID: Customer ID
Age: Customer's age in years
Experience: Years of professional experience
Income: Annual income of the customer ($000)
ZIPCode: Home Address ZIP code
Family: Family size of the customer
CCAvg: Avg. spending on credit cards per month ($000)
Education: Education Level (1: Undergrad; 2: Graduate; 3: Advanced/Professional)
Mortgage: Value of house mortgage if any ($000)
Personal Loan: Whether the customer accepted the personal loan offered in the last campaign
Securities Account: Whether the customer has a securities account with the bank
TD Account: Whether the customer has a Term deposit account with the bank
Online: Whether the customer uses internet banking facilities
CreditCard: Whether the customer uses a credit card issued by the bank
Income Categorical: A categorical column created for reference

Objectives
The main objectives of this analysis are:

Determine the percentage of customers who availed personal loans versus those who did not.
Generate summary statistics (min, max, median, average) for all numeric variables.
Create a new categorical variable for Experience and plot a bar graph.
Create a scatter plot of Age and Experience and analyze the observations.
Identify the top 3 areas (ZIP Codes) where the bank’s customers are located.
Determine how many customers have a combination of Fixed Deposits and Credit Cards but not Personal Loan.
Compare the median income of customers who availed personal loans with those who did not.
Create and analyze pivot tables for various categorical variables against Personal Loan.
Identify key categorical variables for further analysis to determine which customers are most likely to take personal loans.
Develop a strategy to optimize the cost of the marketing campaign by identifying the correct target base.

Files
Bank.xls: The dataset containing information about the customers.
EDA.ipynb: Jupyter Notebook with the exploratory data analysis and visualizations.
README.md: This file, providing an overview and instructions for the project.
Requirements
Python 3.x
Jupyter Notebook
Pandas
Matplotlib
Seaborn

Installation
To set up the project locally, follow these steps:

Clone the repository:
sh
Copy code
git clone https://github.com/your-username/personal-loan-eda.git
Navigate to the project directory:
sh
Copy code
cd personal-loan-eda
Install the required packages:
sh
Copy code
pip install pandas matplotlib seaborn
Usage
Open the Jupyter Notebook and run the cells to perform the EDA:

Start Jupyter Notebook:
sh
Copy code
jupyter notebook
Open EDA.ipynb and execute the cells to see the analysis and visualizations.
Analysis Steps
1. Loan Acceptance Percentage
Calculated the percentage of customers who accepted the personal loan.

2. Summary Statistics
Generated a table with min, max, median, and average for numeric variables.

3. Experience Categories
Created a new categorical variable for Experience and plotted a bar graph.

4. Scatter Plot
Created a scatter plot of Age vs. Experience and analyzed the results.

5. Top ZIP Codes
Identified the top 3 ZIP codes where the bank’s customers are located.

6. Fixed Deposits and Credit Cards
Determined the number of customers with Fixed Deposits and Credit Cards but no Personal Loan.

7. Median Income Comparison
Compared the median income of customers who availed and did not avail personal loans.

8. Pivot Tables
Created pivot tables for Education, TD Account, Online, and Income Category against Personal Loan.

9. Pivot Table Analysis
Analyzed pivot tables to identify key variables for targeting customers.

10. Marketing Campaign Strategy
Suggested a strategy to optimize the marketing campaign based on the analysis.
Results and Recommendations
Key Findings: Summarized key findings from the analysis.
Strategy Recommendation: Provided a targeted marketing strategy to optimize campaign costs and improve acceptance rates.

Conclusion
This project demonstrates the application of exploratory data analysis techniques to understand customer profiles and improve marketing strategies for personal loans. The insights gained can help HBFC bank enhance their future campaigns and increase their asset customer base efficiently.
