# Project Documentation

# Mental Health Care Analysis in the United States
### 1. Project Overview

This project focuses on analyzing mental healthcare data collected across different states in the United States using Pandas for data cleaning and analysis, and Matplotlib and Seaborn for data visualization. The goal is to identify mental health trends, compare mental health indicators across demographic groups and states, and generate insights that can support healthcare planning and policy-making.

### 2. Tools Used

* **Pandas** – Data cleaning and manipulation
* **NumPy** – Numerical operations
* **Matplotlib** – Basic data visualization
* **Seaborn** – Advanced and statistical visualizations
* **Jupyter Notebook** – Development environment

### 3. Dataset

* **Source:** U.S. Mental Healthcare Dataset
* **Description:** The dataset contains mental healthcare survey information collected from different states in the United States with the following key columns:

  * Indicator
  * Group
  * State
  * Subgroup
  * Phase
  * Time Period
  * Time Period Label
  * Time Period Start Date
  * Time Period End Date
  * Value
  * LowCI
  * HighCI
  * Confidence Interval

### 4. Steps Followed

1. Imported the dataset using Pandas.

2. Cleaned the data by:

   * Checking and handling missing values
   * Removing duplicate records
   * Removing rows with missing values in the Value column
   * Converting date columns to datetime format
   * Creating derived columns such as Year and Month

3. Performed Exploratory Data Analysis (EDA) using Pandas:

   * Univariate analysis
   * Bivariate analysis
   * Multivariate analysis
   * Correlation analysis
   * Pivot table analysis

4. Created visualizations using Matplotlib and Seaborn, such as:

   * Histograms for value distribution
   * Box plots for outlier detection
   * Bar charts for gender-wise, age-wise, and state-wise comparisons
   * Line charts for year-wise trends
   * Pie charts for indicator distribution
   * Scatter plots for confidence interval analysis
   * Heatmaps for correlation analysis

5. Interpreted the results to extract meaningful insights.

### 5. Key Insights

* Mental health values increased steadily from 2020 to 2022.
* Female respondents reported higher average mental health values than male respondents.
* The 18–29 years age group showed the highest average mental health values.
* Utah, Oregon, and the District of Columbia reported the highest average values among states.
* Strong positive correlations were observed between Value, LowCI, and HighCI.
* Mental health service usage and counseling indicators increased over the study period.

### 6. Visualizations

* Histogram showing distribution of mental health values
* Box plot for identifying outliers
* Bar chart representing gender-wise average values
* Bar chart representing age-group-wise average values
* Bar chart showing top states by average value
* Line chart showing year-wise trends
* Pie chart showing distribution of mental health indicators
* Scatter plot displaying LowCI vs HighCI relationship
* Heatmap showing correlations between numerical variables

*(Screenshots of plots can be added here if required.)*

### 7. Files Included

* **[Mental_Health_Care_in_the_Last_4_Weeks.csv](https://github.com/Rahana1737/Mental_Healthcare_Data_Analysis/blob/main/Mental_Health_Care_in_the_Last_4_Weeks.csv)** – Raw dataset
* **mental_health_analysis.ipynb** – Analysis and visualizations
* **README.md** – Project description and usage instructions

### 8. How to Use

1. Open **mental_health_analysis.ipynb** using Jupyter Notebook or JupyterLab.
2. Run the notebook cells step by step to view:

   * Data loading
   * Data cleaning
   * Exploratory Data Analysis (EDA)
   * Visualizations
3. Review the generated insights and charts.
4. Modify the code to explore additional findings if required.

### 9. Conclusion

This project demonstrates how Python libraries such as Pandas, Matplotlib, and Seaborn can be effectively used for real-world healthcare data analysis. The insights gained from this analysis help identify mental health trends across different states, demographic groups, and time periods. These findings can support healthcare professionals, researchers, and policymakers in understanding mental health patterns and making data-driven decisions.
