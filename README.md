# Microlending

This Python script automates various calculations and operations related to a loan portfolio. It performs calculations on loan prices, analyzes loan data, and filters inexpensive loans. Additionally, it saves the results to a CSV file.

## Features

The script includes the following features:

- Loan Portfolio Calculations: Calculates various metrics for a list of loan prices, including the total number of loans, the total loan amount, and the average loan price.
- Loan Analysis: Analyzes a specific loan's data to calculate its present value, using the future value and remaining months. It also determines if the present value represents the loan's fair value based on a discount rate.
- Financial Calculations: Defines a function to calculate the present value of a loan, given the future value, remaining months, and annual discount rate. It also calculates the present value for a new loan using the defined function.
- Loan Filtering: Filters a list of loans to include only the inexpensive loans (loan price <= $500) and prints the list of inexpensive loans.
- Data Export: Saves the list of inexpensive loans to a CSV file for further analysis or reporting.

## Getting Started

Clone the repository or download the Python script (loan_analysis.py) to your local machine.

Ensure that Python 3 is installed on your machine.

Install the required dependencies by running the following command:

pip install csv 
Open the loan_analysis.py file in a Python IDE or text editor.

Modify the code as needed or run it as is.

Execute the script by running the following command:


Review the output in the console, which includes the loan portfolio calculations, loan analysis results, and the list of inexpensive loans.

Open the inexpensive_loans.csv file to view and analyze the saved data.

### Customize the Loan Data

You can customize the loan data by modifying the variables in the script:

Part 1: Loan Portfolio Calculations: Modify the loan_costs list to include the loan prices of your choice.

Part 2: Analyze Loan Data: Modify the loan dictionary to include the loan details for analysis. Update the values for loan_price, remaining_months, repayment_interval, and future_value.

Part 3: Perform Financial Calculations: Modify the new_loan dictionary to include the details of a new loan for present value calculation. Update the values for loan_price, remaining_months, repayment_interval, and future_value.

Part 4: Conditionally Filter Lists of Loans: Modify the loans list to include loans of your choice for filtering based on loan price.

## Output

The script provides the following output:

Loan portfolio calculations, including the total number of loans, total loan amount, and average loan price.

Loan analysis results, including the present value of a specific loan and a determination of whether it represents the loan's fair value.

The list of inexpensive loans based on the loan price filter.

The inexpensive_loans.csv file, which contains the saved data of the inexpensive loans.

## License

This project is licensed under the MIT License.
