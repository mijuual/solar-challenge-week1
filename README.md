# MoonLight Energy Solutions: Solar Investment Strategy Analysis

# Project Overview
MoonLight Energy Solutions aims to enhance its operational efficiency and sustainability by investing in solar energy solutions. As an Analytics Engineer, the goal is to analyze environmental data from various regions and produce insights that will help identify high-potential areas for solar installations. The analysis focuses on data quality checks, cleaning techniques, exploratory data analysis (EDA), and cross-country comparisons for countries: Benin, Sierra Leone, and Togo.

# Contributions

## Git & Environment Setup:

Set up the Git environment and created multiple branches for efficient version control.

Configured .gitignore to exclude irrelevant files (e.g., .venv) from version control.

Faced challenges with merging branches due to misunderstandings, but resolved them by learning the correct Git workflow and successfully merging eda-benin-branch into the default setup-branch.

## Data Profiling, Cleaning, and EDA for Benin:

Data Quality Checks: Identified missing values, negative readings, and statistical outliers using Z-scores.

### Data Cleaning:

* Replaced extreme outliers with median values.

* Handled missing values in the data through appropriate imputation.

### Exploratory Data Analysis (EDA):

* Created a variety of visualizations, such as:

* Line plots for temporal trends in irradiance, temperature, and wind.

* Scatter plots for relationships between different weather parameters.

* Heatmaps to identify correlations.

* Bubble charts to visualize the relationship between GHI, temperature, and relative humidity.

## Cross-Country Comparison (Benin, Sierra Leone, Togo):

* Plans to continue performing EDA for Sierra Leone and Togo.

# Implementation Process

## Git Setup:

* Created a Git repository for version control.

* Set up different branches for different tasks (e.g., setup-branch, eda-benin-branch).

* Used .gitignore to prevent unnecessary files from being committed to the repository.

## Data Quality Checks & Cleaning:

Performed data profiling by inspecting the raw data for inconsistencies, such as missing values and unrealistic negative values.

Applied Z-score method to identify outliers and replaced them with the median value.

Imputed missing values based on column medians for the solar irradiance data.

## Exploratory Data Analysis (EDA):

Visualized the data using various types of plots (e.g., line plots, scatter plots, heatmaps).

Identified key trends in the data, such as solar irradiance patterns, temperature behavior, and humidity levels.

Focused on creating actionable insights that would support the company's strategy for solar investments.

Cross-Country Analysis:

Focused on Benin first, and will proceed with Sierra Leone and Togo.

The goal is to compare solar radiation, temperature, and other key metrics across these countries to determine which areas offer the best potential for solar investment.

## Future Plans
EDA for Sierra Leone & Togo: Complete the EDA for the remaining countries.

Cross-Country Comparison: After completing the analysis for all three countries, compare key metrics across Benin, Sierra Leone, and Togo, providing actionable insights for the solar investment strategy.

Strategic Recommendations: Use the findings to create a report with a strategic approach for identifying high-potential regions for solar installation, aligned with the company's sustainability goals.

# Technologies Used

Git & GitHub: For version control and collaboration.

Pandas: For data manipulation and cleaning.

Matplotlib & Seaborn: For data visualization and EDA.

Jupyter Notebooks: For interactive analysis and documentation.

# Conclusion

This project provides an essential foundation for MoonLight Energy Solutions to make informed decisions on solar investments by leveraging data analytics. The process followed so far has been effective in cleaning and analyzing the Benin dataset, and we are confident that the analysis for the other countries will provide equally valuable insights.
