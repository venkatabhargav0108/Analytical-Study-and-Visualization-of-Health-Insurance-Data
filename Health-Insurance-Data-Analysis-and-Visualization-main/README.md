# Health Insurance Data Analysis and Visualization

## Project Description
This project involves a detailed analysis of a health insurance dataset. The aim is to understand the factors affecting insurance claims and to identify significant patterns through data cleaning, exploratory data analysis (EDA), and visualization techniques.

## Table of Contents
- Project Description
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Visualizations
- Conclusion
- Technologies Used

## Data Cleaning
1. **Handling Missing Values**:
   - Filled missing values in the `age` column with the median age.
   - Filled missing values in the `region` column with the mode (most frequent value).

2. **Checking for Duplicates**:
   - Ensured there were no duplicate rows.

3. **Correcting Data Types**:
   - Verified and corrected data types where necessary.

## Exploratory Data Analysis (EDA)
1. **Basic Statistics**:
   - Generated summary statistics for numerical and categorical features.

2. **Feature Distribution Analysis**:
   - Plotted histograms for continuous variables such as `age`, `bmi`, and `claim`.
   - Created count plots for categorical variables like `gender`, `diabetic`, `smoker`, and `region`.

3. **Correlation Analysis**:
   - Computed the correlation matrix.
   - Visualized the correlation matrix using a heatmap.

## Visualizations
1. **Distribution of Age**:
   - Plotted the age distribution to understand the demographic spread.

2. **Count of Genders**:
   - The count plot shows the number of male and female clients, with the exact counts of each gender."

3. **Charges by Region**:
   - Analyzed and visualized insurance claims across different regions.

4. **Charges by Smoker Status**:
   - Compared insurance claims between smokers and non-smokers.

5. **Charges by BMI**:
   - Explored the relationship between BMI and insurance claims.

6. **Correlation Heatmap**:
   - Visualized correlations among variables to identify significant relationships.

## Conclusion
The analysis revealed several key insights:
- The majority of the insured population falls within the 20-50 age range, with a median age of 39.
- There is a positive correlation between BMI and insurance claims, indicating that higher BMI values tend to be associated with higher claims.
- The southeast region has the highest number of claims, while the northwest has the lowest.
- Smokers have significantly higher insurance claims compared to non-smokers, highlighting the financial impact of smoking on health insurance.
- There is no significant difference in the average claim amount between genders.
- Diabetic patients have slightly higher claims on average compared to non-diabetic patients.
- The correlation heatmap shows strong correlations between age, BMI, and claims, and weak correlations between other variables.

## Technologies Used
- Python
- pandas
- seaborn
- matplotlib
