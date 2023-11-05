# Hotel KPI Analysis

This project involves data cleaning, KPI evaluation, and data visualization for hotel expenses and revenues. The goal is to provide insightful metrics and visualizations for hotel management.

## Table of Contents
* [Project Overview](#project-overview)
* [Data Cleaning](#data-cleaning)
* [Key Performance Indicators (KPIs)](#key-performance-indicators-kpis)
* [Data Visualization](#data-visualization)
* [User Input](#user-input)
* [Dependencies](#dependencies)
* [Usage](#usage)
* [Contributing](#contributing)
* [License](#license)

<span id="project-overview"></span>
# Project Overview
This project focuses on cleaning a source CSV file by removing null values, renaming columns, handling duplicate KPI names and generating new columns that provide valuable insight into a hotel's expenses. The cleaned data is then used to evaluate Key Performance Indicators (KPIs) such as Cost Per Occupied Room (CPOR), percentage differences between two years, percentage expenses within expense groups, and expense ratios.
<span id="data-cleaning"></span>
## Data Cleaning
Data cleaning is an essential step to prepare the dataset for analysis. Null values are removed, columns are renamed for clarity, and duplicate KPI names are resolved to ensure accurate analysis and allow for correct row manipulation within dataframes.
<span id="key-performance-indicators-kpis"></span>
## Key Performance Indicators (KPIs)
* **CPOR (Cost Per Occupied Room)**: Calculated by dividing total operational expenses by the number of rooms sold.
* **Total Operational Expense**: This value is dictated by the management team as to what they would qualify as a rooms expense as some companies do not include some expenditures such as insurance, bonuses, etc in their room costs.
* **Percentage Differences**: Calculated to show the change in KPI values between last recorded Fiscal Year and the year prior to the last recording.
* **Percentage Expenses within Groups**: Visualization using pie charts to understand the proportion of individual expenses within grouped expense categories.
* **Expense Ratios**: Visualization using bar charts to compare revenue growth to expense growth for individual expenses.
<span id="data-visualization"></span>  
## Data Visualization
The project uses the Plotly library to create informative visualizations, including pie charts to illustrate the percentage of expenses within expense groups and bar charts to represent expense ratios.
<span id="user-input"></span>
## User Input
This project provides a user-friendly feature where hotel management can input the number of rooms sold for specific years. The Jupyter Notebook automatically runs the analysis, calculates CPOR, and generates visualizations based on the input.
<span id="dependencies"></span>
## Dependencies
* Python
* Pandas
* Numpy
* Plotly
* Jupyter Notebook
<span id="usage"></span> 
## Usage
1. Clone this repository.
2. Install the required dependencies listed in the requirements.txt file.
3. Open the Jupyter Notebook and run the cells to perform data cleaning, KPI evaluation, and data visualization.
<span id="contributing"></span>
## Contributing
Feel free to contribute to this project by forking the repository and submitting a pull request. Your contributions and improvements are highly appreciated.
<span id="license"></span>
## License
This project is licensed under the MIT License.

Enjoy exploring and analyzing hotel data to gain insights into expenses and revenues for better decision-making in the hospitality industry!
