# Retail Store Performance Analysis

This repository contains a Jupyter notebook focused on analyzing the performance of retail stores using various SQL queries and visualizations. The analysis covers areas such as security incidents, theft, sales impact from boycotts, and employee reporting of empty packages.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Queries](#queries)
- [Stored Procedures](#stored-procedures)
- [Views](#views)
- [Results & Conclusions](#results--conclusions)

## Introduction

This project aims to analyze the performance of retail stores through SQL queries executed against a database. The analysis includes generating insights on security incidents, theft, sales trends, and employee reports. The project utilizes a Jupyter notebook for running queries and visualizing the results.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/danielshort3/target-packaging-analysis-mssql.git
    cd target-packaging-analysis-mssql
    ```

2. Install the required packages (make sure you have `pip` and `virtualenv` installed):
    ```bash
    pip install pandas numpy matplotlib pyodbc
    ```

3. Unfortunately, the source database file is not public, so it is unavailable. However, the results from the code are provided in the notebook.

## Usage

1. Open the `MSSQL.ipynb` notebook.
2. Run the cells sequentially to establish a database connection, execute queries, and generate visualizations.

## Queries

### 1. Which store format has the highest average security incidents per store?

#### Objective:
To identify which store format experiences the highest average security incidents per store.

### 2. Which states have the highest average recorded daily theft?

#### Objective:
To determine which states have the highest average recorded daily theft.

### 3. Has the recent boycott actually affected our store?

#### Objective:
To assess the impact of a recent boycott campaign on our stores by comparing sales data before and after the boycott started.

### 4. Which employees have reported the most empty packages in the current month?

#### Objective:
To identify the employees who have reported the most empty packages in the current month.

## Stored Procedures

### Create a stored procedure to pull specific employee information

#### Objective:
To simplify the process of pulling comprehensive information about employees, including their employment history, roles, and current projects.

## Views

### Create a view to pull recent return divisions

#### Objective:
To provide an easy way to see the categories of items that are most frequently returned, aiding in quality control and inventory management.

## Results & Conclusions

### Key Findings:
- **Security Incidents Across Store Formats:** StoreFormat_47 exhibited the highest average security incidents per store.
- **States with Highest Theft:** The states with the most alarming rates of average recorded daily theft are State_38, State_03, and State_20.
- **Impact of Recent Boycott on Sales:** Sales have been in decline year-over-year, with a sharp decline in 2023.
- **Employee Reporting of Empty Packages:** Employees 231, 098, and 196 have reported the highest number of empty packages for the current month.

### Recommendations:
- **Allocate More Security Resources:** Given the high rate of security incidents at StoreFormat_47 locations.
- **Targeted Loss Prevention:** Focus more on States 38, 03, and 20 for loss prevention initiatives.
- **Investigate the Impact of Boycotts:** Conduct a thorough analysis of customer sentiment and public relations effectiveness.
- **Investigate Employee Reports:** Recognize the vigilance of high-reporting employees and understand whether their sections are more prone to theft or loss.
