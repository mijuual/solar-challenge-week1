# MoonLight Energy Solutions: Solar Investment Strategy Analysis

# Project Overview
MoonLight Energy Solutions aims to enhance its operational efficiency and sustainability by investing in solar energy solutions. As an Analytics Engineer, the objective is to analyze environmental data from multiple regions and generate insights to identify high-potential areas for solar installations. The project involves data quality checks, cleaning techniques, exploratory data analysis (EDA), and a cross-country comparison covering Benin, Sierra Leone, and Togo.

# Contributions

## Git & Environment Setup:
Set up Git and created multiple branches to manage tasks efficiently.

Configured .gitignore to exclude unnecessary files (e.g., .venv) from version control.

Resolved branch merge conflicts by learning and applying proper Git workflows.

## Data Profiling, Cleaning, and EDA:

### Common Steps Across All Countries:

Data Quality Checks: Identified missing values, negative readings, and statistical outliers using Z-scores.

Data Cleaning: Imputed missing or negative values in DHI, DNI, GHI with medians. Applied Z-score to detect outliers in selected columns and replaced them with median values to ensure data consistency.

## EDA Visualizations:

Line plots for temporal trends in irradiance, temperature, and wind speed.

Scatter plots to explore relationships between key weather parameters.

Heatmaps to identify correlations.

Bubble charts to assess the relationship between GHI, temperature, and relative humidity.

## Country-Specific Work:

Benin: Initial focus of the analysis; full EDA and cleaning pipeline implemented.

Sierra Leone & Togo: Applied the same data profiling and EDA workflow to understand their respective solar potential.

## Cross-Country Comparison:

Performed comparative analysis across Benin, Sierra Leone, and Togo using key solar metrics:

* Global Horizontal Irradiance (GHI)

* Direct Normal Irradiance (DNI)

* Diffuse Horizontal Irradiance (DHI)

Created a summary table presenting the mean, median, and standard deviation for each irradiance metric by country.

Used statistical hypothesis testing (p-values) to determine whether differences in irradiance distributions across countries are statistically significant.

### Insights drawn:

- Benin has the highest average and median GHI and DNI, suggesting it receives the most consistent and intense solar radiation — making it a strong candidate for solar installations.

- Sierra Leone shows a higher average and median DHI than the other countries, which may indicate more diffuse (scattered) sunlight due to cloud cover 

- Togo has relatively high GHI, but very low median DNI, suggesting that direct sunlight is more inconsistent 

# Implementation Process

## Git Setup:
Created a structured Git repository with clear branching per task (e.g., setup-branch, eda-benin-branch, etc.).

Used .gitignore to streamline the repository and prevent tracking of unnecessary files.

## Data Preparation:
Conducted thorough inspection of raw environmental data to identify inconsistencies such as missing values and negative readings.

### Initial Imputation:

For irradiance-related columns (DHI, DNI, GHI), which cannot have negative values, missing or invalid values were imputed using the column-wise median.

### Outlier Treatment:

Applied the Z-score method to selected numerical columns to detect statistical outliers.

Detected outliers were replaced with the respective column's median to reduce the impact of extreme values while preserving overall data integrity.

## Exploratory Data Analysis:
Visualized environmental data to understand temporal and spatial trends.

Used visualization techniques to uncover actionable patterns in irradiance, temperature, and other variables.

Developed a structured EDA pipeline that was consistently applied to each country.

## Cross-Country Insights:
Compared solar-related metrics to assess which country offers optimal conditions.

Synthesized insights into solar energy potential for strategic decision-making.

# Future Plans

EDA Expansion: Continue refining the analysis with additional weather and solar variables for greater granularity.

Streamlit Dashboard: Develop an interactive dashboard using Streamlit to allow stakeholders to explore solar metrics (GHI, DNI, DHI), comparisons, and visualizations dynamically.

# Technologies Used

Git & GitHub: For version control and collaboration.

Pandas: For data manipulation and cleaning.

Matplotlib & Seaborn: For data visualization and EDA.

Jupyter Notebooks: For interactive exploration and documentation.

# Conclusion
This project lays a strong analytical foundation for MoonLight Energy Solutions to drive data-informed solar energy investments. With comprehensive EDA completed for Benin, Sierra Leone, and Togo, and a comparative analysis providing cross-country insights, the company is well-positioned to make impactful, sustainability-focused decisions on where to deploy solar infrastructure.