# SALARY DATA ANALYSIS

This repository contains both Python and R scripts for analyzing salary data. The Python script is provided as a Jupyter Notebook and includes the following functionality:
   •	Importing and processing salary data.
   •	A function to return employee details based on their name.
   •	Exporting employee data. The R script is used for unzipping a folder and displaying the employee data.

## CONTENTS
SalaryDataAnalysis.ipynb: Python notebook for salary data analysis.
EmployeeDataExtractor.R : R script for extracting employee data.

## INSTALLATION 
PYTHON
 Ensure Python 3.x is installed along with the following libraries: pandas
 To install pandas, use: pip install pandas
R
 Ensure R is installed on your system.

## USAGE
•	PYTHON NOTEBOOK
 1. Loading Data:
    The notebook starts by loading salary data from a CSV file:
      import pandas as pd
      df = pd.read_csv('path_to_your_data.csv')
 2. Fetching Employee Details:
    Use the _get_employee_details_ function to fetch details for a specific employee:
      employee_details = get_employee_details(employee_name)
      print(employee_details) 
•	R SCRIPT
 1. Loading Data:
    The R script begins by setting the working directory, unzipping the folder, and displaying the data.
