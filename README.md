# Layoffs Data Analysis

## Overview
This repository contains SQL queries and scripts for performing exploratory data analysis (EDA) on a dataset of company layoffs. The analysis includes calculations of various metrics, aggregation of data by different dimensions, and identification of trends over time.

You can check out the complete article on this this Project: [EDA in Layoff Dataset — Part 2](https://nsworldinfo.medium.com/eda-in-layoff-dataset-part-2-dcc866041ebd)

## Dataset
we've already performed some data cleaning in our world_layoffs dataset before. 

[Cleaned Layoff Dataset](https://github.com/nibeditans/Cleaning-Data-in-World-Layoffs-Dataset)

Now let's perform some EDA on the cleaned dataset, where our table includes the following fields:

- company: Name of the company
- total_laid_off: Total number of employees laid off
- percentage_laid_off: Percentage of the workforce laid off
- funds_raised_millions: Funds raised by the company in millions
- date: Date of the layoff
- industry: Industry to which the company belongs
- country: Country where the company is based
- stage: Stage of the company (e.g., Startup, Public, etc.)

## Usage
To use the SQL scripts, simply copy and paste the queries into your SQL environment and run them against the layoffs_staging2 table.

## Contributing
Contributions are welcome! If you have any suggestions or improvements, please create a pull request or open an issue.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.
