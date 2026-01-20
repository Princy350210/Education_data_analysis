## Analysis of Primary-Level Out-of-School Rates

## Project Description:

This project performs an exploratory data analysis (EDA) on a UNICEF dataset concerning out-of-school children at the primary education level. The work demonstrates a full data analysis pipeline, from initial data cleaning to visualization and insight generation, with a focus on identifying disparities.
## Methodology:

The analysis was conducted in a Python environment using Pandas for data manipulation and Matplotlib for visualization. The process involved:
1.  **Data Cleaning:** Standardizing column names, handling missing values, and ensuring correct data types in the raw dataset.
2.  **Focused Queries:** The data was explored through three primary lenses to understand different dimensions of the crisis:
       Identifying the 10 countries with the highest out-of-school rates for girls.
       Isolating countries where the out-of-school rate for boys was higher than or equal to that for girls.
       Creating a combined view of the top 10 countries by female out-of-school rate to visualize the gender gap directly.
3.  **Visualization:** Key findings were visualized in bar charts to communicate scale and comparison effectively.
4.  
## Key Findings
The analysis segmented the countries with the highest out-of-school rates into distinct categories:

### 1. Countries with Extreme Gender Disparity
**Suriname** is a pronounced outlier. The data shows **82.8%** of primary-age girls are out of school, compared to **16.2%** of boys—a gap of over 66 percentage points.

### 2. Countries with Systemic Challenges
In countries like **South Sudan** and **Equatorial Guinea**, out-of-school rates are critically high for both genders (e.g., 67.8% and 58.3% in South Sudan). This suggests challenges within the broader education system.

### 3. Countries with Notable Patterns
A subset of countries, including **Burkina Faso** and **Liberia**, showed a reverse pattern where the male out-of-school rate slightly exceeded the female rate, indicating a different set of barriers.



