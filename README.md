# Weekly Earnings Analysis for Restaurant

This repository contains a Jupyter Notebook that analyzes the weekly earnings of a restaurant. It processes data from an .xlsb Excel file, consolidates the information, and generates visualizations to understand the income distribution across different days and sessions (lunches and dinners).

## Table of Contents
* [Overview]()
* [Features]()
* [Installation]()
* [Usage]()
* [Data]()
* [Analysis]()
* [Results]()
* [License]()
* [Acknowledgements]()

## Overview
The notebook performs the following tasks:

1. Data Extraction: Reads data from multiple sheets in an .xlsb Excel file.
2. Data Transformation: Converts the Excel serial date to a standard date format.
3. Data Consolidation: Combines data from various sheets into a single DataFrame.
4. Data Visualization: Generates boxplots and bar charts to visualize earnings by day and session.

## Features
* Data Handling: Efficient reading and processing of .xlsb files.
* Data Visualization: Detailed visualizations including boxplots and bar charts to understand income distribution.
* Automated Analysis: Functions to read, process, and analyze data from multiple sheets.
* Customizable: Easily adaptable to analyze similar data sets from other weeks or restaurants.

## Installation
To set up the project, follow these steps:

1. Clone the repository:


``git clone https://github.com/Rams-TMP/weekly_incomes``\
``cd restaurant-earnings-analysis``


2. Set up the virtual environment:


``python -m venv venv``\
``source venv/bin/activate`` # On Windows: venv\Scripts\activate


3. Install the dependencies:


`pip install -r requirements.txt`


4. Ensure Jupyter Notebook is installed (if not already):


`pip install notebook`


## Usage


1. Run Jupyter Notebook:


``jupyter notebook``

2. Open the notebook: Navigate to 3_7_first_step.ipynb and open it.

3. Follow the steps in the notebook to execute the code cells and analyze the data.

## Data
* File: The data is extracted from the file Weekly Sheets 15.03.24.xlsb.
* Structure: Data from each sheet includes information about earnings in different categories such as Kitchen, Wine, Liqueurs, Cigars, Bar, etc.
* Preprocessing: The notebook handles conversion from Excel serial dates to standard dates and skips completely empty rows.

## Analysis
* Data Consolidation: Combines data from multiple sheets into a single DataFrame.
* Boxplot Visualization: Shows the distribution of earnings by day and session.
* Bar Chart Visualization: Displays the total income for each session (lunch and dinner) for each day of the week.

## Key Functions
* `excel_date(num)`: Converts Excel serial numbers to standard dates.
* `read_sheet(file_path, sheet_name)`: Reads data from a specific sheet.
* Visualization cells: Generate boxplots and bar charts to analyze earnings.

## Results
The analysis provides insights into how earnings vary by day of the week and session type (lunch or dinner). It highlights the importance of optimizing restaurant operations based on these patterns.

## License
This project is licensed under the MIT License. See the [LICENSE]() file for details.

## Acknowledgements
Libraries Used: pandas, pyxlsb, matplotlib, datetime\
Data Source: Restaurant weekly earnings data.\
For any questions or suggestions, please [open an issue]().
