# Mentor Artificial - Education Trends Analysis

## Team Name:
**Mentor Artificial**

## Project Title:
**Education Trends Analysis**

## Description:
Study trends in literacy rates, enrolment, and education spending globally.
  
The insights gained help to understand the evolving global education landscape and its influencing factors.

## Group Members:
- Dipika Gurjar - [KU2407U397]  
- Jeeya Thakrar - [KU2407U409]
- Dhriti Soni - [KU2407U396]
- Malaviya Riya - [KU2407U423]  

---

## Objective:
This project uses Python to analyze global education trends, focusing on literacy rates, enrollment, and education spending. Data from reliable sources like UNESCO is cleaned and analyzed with pandas and numpy, while matplotlib visualizes trends, correlations, and regional comparisons. It provides insights into how education evolves and the factors driving change.

---

## Tools and Libraries Used:
- **Python:** Programming language for data analysis and visualization.
- **pandas:** For data cleaning, manipulation, and analysis.
- **numpy:** For numerical operations and statistical calculations.
- **matplotlib:** For creating various visualizations (line plots, scatter plots, bar charts).
- **tabulate:** For formatting data into readable tables for console output.

---

## Data Source(s)
• Dataset Name: Education_data(1).csv

• Size: 10 records

• Fields: Country,	Year,	Literacy Rate,	Enrollment Rate,	Education Spending (% of GDP),	Region.

---

## Execution Steps:

### 1. **Install Required Libraries:**
    - Install necessary Python libraries such as pandas, numpy, matplotlib, and tabulate.

### 2. **Data Collection:**
   - Download datasets from sources like Kaggle, World Bank, or Data.gov.
   - Ensure the data is in CSV or Excel format for easy processing.

### 3. **Data Import:**
   - Load the dataset into a pandas DataFrame for analysis.
### 4. **Explore and Clean the Data:**
   - Display the dataset using tabulate for better readability.
   - Print the first few rows to understand the structure.
   - Check for missing values and handle them:
       - Fill missing values in Literacy Rate and Enrollment Rate with the column mean.
### 5. **Data Analysis:**
   - Average Literacy Rate by Region using groupby().
   - Education Spending Trends over the years.
   - Correlation between Literacy Rate and Enrollment Rate.
### 6. **Data Visualization:**
   - Create visualizations using matplotlib:
       - Bar chart for Literacy Rate by Region.
       - Scatter plot for Literacy Rate vs Enrollment Rate.

## Summary of Results
The analysis of the education dataset revealed important insights about global education trends. After cleaning the data by filling missing values for literacy and enrollment rates and dropping rows with missing education spending data, we proceeded with the analysis.
 -	**Correlation Analysis:** A strong positive correlation between literacy and enrollment rates was observed, indicating that as literacy rates increase, enrollment rates tend to rise as well.
 -	**Regional Literacy Trends:** The average literacy rate was calculated for each region, showing disparities between regions with higher and lower literacy levels.
 -	**Education Spending:** A line chart depicting global education spending trends highlighted the fluctuations in investment over time as a percentage of GDP.
 -	**Key Visualizations:** Bar charts, line graphs, and scatter plots were used to visualize the data, revealing regional differences, trends in spending, and the relationship between literacy and enrollment rates.

## Challenges Faced
- **Data Quality:**  Missing values in critical columns like Literacy Rate, Enrollment Rate, and Education Spending (% of GDP) required handling through imputation or removal.
- **Limited Time-Series Data:** Insufficient data across multiple years limited the ability to analyze trends meaningfully over time.
- **Correlation Analysis:**  Understanding and interpreting the correlation between literacy rate and enrollment rate required statistical validation.
- **Data Visualization:**	Selecting appropriate visualizations and ensuring they were meaningful given the dataset's limitations.
- **Data Cleaning:**	Ensuring the dataset was free from anomalies and ready for analysis while retaining key insights.
- **Technical Implementation:**	Debugging Python code for reading, processing, and visualizing data efficiently.


## Credits

-Malaviya Riya for making the dataset with help of search engines (kaggle, WHO, etc).

-Jeeya Thakrar and Dhriti Soni for working on the code giving such exceptional python program putting efforts for a great output.

-Dipika Gurjar for handling the documents and making a fine overall organization and professionalism of the repository consisting of Data , Visuals , Assets and Output report.
