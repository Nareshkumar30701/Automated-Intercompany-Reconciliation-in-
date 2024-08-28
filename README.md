# Automated-Intercompany-Reconciliation-in-
This project automates the reconciliation process for sample account data stored in CSV files. The reconciliation script compares two CSV files containing account information to identify discrepancies, ensuring that records are accurate and consistent. The tool is designed to streamline the reconciliation process and improve data accuracy.
## Overview
This project automates the reconciliation of sample account data from CSV files using a Tkinter-based graphical user interface (GUI). The application allows users to select input files and specify the output location where the reconciled file will be saved. The script compares records from two CSV files and generates a reconciliation report highlighting discrepancies.

## Contents
Data Files: Sample CSV files for reconciliation
GUI Script: Python script using Tkinter for user interaction
Reconciliation Logic: Script for automating the reconciliation process

## Requirements
To run this project, you need Python and the following libraries:

pandas – For data manipulation and comparison
numpy – For numerical operations 
tkinter – For creating the graphical user interface

## Data Files
Company_A.csv: First CSV file containing account data for reconciliation.
Company_B.csv: Second CSV file containing account data for reconciliation.

## GUI Script
Application Script
reconciliation.py: This script creates a Tkinter-based GUI that allows users to:

Select the two input CSV files for reconciliation.
Specify the output location for saving the reconciled report.

## How It Works
Select Input Files: The user selects the two CSV files to be reconciled.
Specify Output Location: The user chooses where the reconciled report will be saved.
Perform Reconciliation: The script reads the selected files, compares records, and generates a reconciliation report.
Save Report: The reconciled report is saved to the specified location.

## Results
The reconciliation results will be saved in the user-specified location under the filename reconciliation_report.csv. The report includes:

Records found in one file but not in the other
Mismatches in key fields
Summary statistics of discrepancies
