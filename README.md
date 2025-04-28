# CMSC408-SP2025-HW8: World Bank Indicator Analysis

This repository contains SQL queries for analyzing World Bank indicators data. The assignment explores various aspects of the World Bank's country classification data, including regions, income categories, and relationships between these factors.

## Project Structure

- **reports/**: Contains the main analysis document (report.qmd) and helper functions
- **source-data/**: Contains the data loading scripts and source data information
- **.env**: Contains database connection information (not included in repo)

## Requirements

- Python 3.11+
- Poetry for dependency management
- MySQL database with World Bank data preloaded
- Required libraries: matplotlib, plotly, jupyter, pandas, sqlalchemy, pymysql, etc.

## Analysis Overview

The analysis performs a series of SQL queries on World Bank data to:
- Explore country classifications and regional distributions
- Analyze income categories across different regions
- Identify patterns and relationships between regions and income levels
- Create contingency tables and percentage distributions

Each query builds on previous ones to develop a deeper understanding of global economic patterns in the World Bank data.

## Getting Started

1. Clone this repository
2. Create a `.env` file with database credentials (see example in code)
3. Run `poetry install` to install dependencies
4. Run the Quarto document in the reports folder