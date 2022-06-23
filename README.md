# Folder Structure

- data folder
	- raw
	- clean
- code
	- analysis
	- cleaning
- results

# Data collection

Students collected data from the field following a template (LINK).

# Cleaning data

The cleaning of the data can be done by using the scirpt "merge-xlsx.R". This script creates a .csv file in the data > clean subdirectory.

Instrucitnos:
- open the script "merge-xlsx.R"
- check all of the raw data are imported
- run the script
- column names are made machine readable
- harmonized Mass units with the assumption data entry has to be grams
	- reported values with a decimal are assumed to be in kg, therefore we resize these to grams
- Replaced string values 'unknown'or 'no'or similar to NA/MISSING
- Number of eggs containted string values. These were replaced as follows:
	- Probably 14 --> 14
	- 5? --> 5




# Analysis