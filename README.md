# Company: Highridge Construction Company

# Project: Payment Slip Generation for  Workers

## Introduction

This repository contains a Python and R script designed for Highridge Construction Company to generate weekly payment slips for workers. Employee levels are assigned based on salary and gender conditions while potential errors that could be encountered during code execution were handled.

## Table of Contents
* 1. Project Overview
* 2. Features
* 3. Requirements
* 4. Usage Instructions
*  - Running the Python Script
*  - Running the R Script
* 5. Error Handling
* 6. Code Structure
* 7. Optimization and Efficiency
* 8. Sample Output
* 9. References

## 1. Project Overview
This program generates payment slips for 400 workers with the following details:

* -Worker ID
* -Worker Name
* -Salary
* -Gender
* -Employee Level (determined based on salary and gender criteria)
Conditional statements were used to assign levels and includes error handling for potential issues (e.g., missing data, invalid values or indentation errors).

## 2. Features
* Random Worker List Creation: Creates a list of 400 workers with random IDs, names, salaries, and genders.
* Conditional Logic: Assigns employee levels based on predefined salary and gender conditions.
* Error Handling: Catches and handles errors for smooth script execution.
* Output: Generates and displays detailed payment slips for each worker.

## 3. Requirements
#### Python
* Python 3.6 or higher
* random module (built-in)

#### R
* R 3.5 or higher
Ensure you have Python and R installed on your system. Both codes can be run in Jupyter Notebook, RStudio, or the command line/terminal.

## 4. Usage Instructions
#### Running the Python Script
* Step 1: Clone the Repository or save the script to your local system.
* Step 2: Navigate to the Directory where the payment_slip_generator.py script is located.
Code:
===================
cd /path/to/script

* Step 3: Run the Python Script in the terminal or your Python IDE (e.g., VS Code, PyCharm):
Code:
================================
python payment_slip_generator.py

* Step 4: The program will display an output of each worker’s payment slip with their ID, name, salary, gender, and assigned level.

#### Usage Instructions for Python Script in Jupyter Notebook
* Paste the code into a notebook cell and execute the cell.
* The payment slips will be displayed in the output of the notebook cell.

#### Running the R Script
* Open RStudio or any R-compatible editor.
* Open the payment_slip_generator.R script.
* Run the Script by sourcing it in RStudio or executing in an R console:

Code:

===============================
 source("payment_slip_generator.R")
 
* Output: The payment slips will be generated and displayed in the R console.

## 5. Error Handling
* Invalid Salary Range: If a worker’s salary falls outside the expected range, the script will log an error.
* Missing Data: If any attribute (e.g., name, salary) is missing, the script will alert you to the issue and skip the entry.
* Invalid Gender Value: If a gender is neither "M" nor "F," it will be flagged as invalid.

## 6. Code Structure
#### Python Script
* Worker List Creation: Creates a list of 400 workers with randomly generated details.
* Loop for Payment Slips: Iterates through each worker to generate a payment slip.
* Conditional Statements: Determines employee level based on salary and gender.
* Error Handling: Catches exceptions and ensures valid entries.

#### R Script
* Worker List Creation: Similar to the Python script, generates a list of 400 workers.
* Loop for Payment Slips: Iterates through each worker to generate a payment slip.
* Conditionals: Uses if statements to set employee levels.
* Error Handling: Handles errors gracefully and provides feedback.

## 7. Optimization and Efficiency
Both scripts are optimized for efficiency:
* Minimal Code: Uses for loops and concise conditional statements.
* Random Sampling: Efficiently generates random salaries and genders.
* Exception Handling: Ensures the code runs smoothly even with unexpected data

## 8. Sample Output
### Python
#### Payment Slip for Worker_1:
ID: 1
Name: Worker_1
Salary: 15,000
Gender: M
Employee Level: A1

#### Payment Slip for Worker_2:
ID: 2
Name: Worker_2
Salary: 8,500
Gender: F
Employee Level: A5-F

### R
#### Payment Slip for Worker_1:
ID: 1
Name: Worker_1
Salary: 15000
Gender: M
Employee Level: A1

#### Payment Slip for Worker_2:
ID: 2
Name: Worker_2
Salary: 8500
Gender: F
Employee Level: A5-F

## 9.References
* Python random module documentation.
* R sample function documentation.
