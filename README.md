# SALARY DATA ANALYSIS

<p>This repository contains both Python and R scripts for analyzing salary data. <br> The Python script is provided as a Jupyter Notebook and includes the following functionality: </p>
<ul>
  <li>Importing and processing salary data</li>
  <li>A function to return employee details based on their name</li>
  <li>Exporting employee data. The R script is used for unzipping a folder and displaying the employee data</li>
</ul>

## CONTENTS
<ul>
<li>SalaryDataAnalysis.ipynb: Python notebook for salary data analysis</li>
<li>EmployeeDataExtractor.R : R script for extracting employee data</li>
<li>Total.csv : Dataset</li>
</ul>

## INSTALLATION 
### PYTHON
Ensure Python 3.x is installed along with the following libraries: 
<ul>
  <li>pandas</li>
</ul>
To install pandas, use:

`pip install pandas`

### R
 Ensure R is installed on your system.

## USAGE
### PYTHON NOTEBOOK
 1. <p>Loading Data:</br>
    The notebook starts by loading salary data from a CSV file</p>
    
      `import pandas as pd`
    
      `df = pd.read_csv('path_to_your_data.csv')`
 3. <p>Fetching Employee Details:</br>
    Use the _get_employee_details_  function to fetch details for a specific employee:</p>
    
      `employee_details = get_employee_details(employee_name)`
    
      `print(employee_details)` 
      
### R SCRIPT
 1. Loading Data:
    The R script begins by setting the working directory, unzipping the folder, and displaying the data.
