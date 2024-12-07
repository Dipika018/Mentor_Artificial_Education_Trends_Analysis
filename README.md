# Mentor_Artificial_Education_Trends_Analysis
# Team Name : Mentor Artificial
# Topic : Education Trends Analysis
# Description : Study trends in literacy rates, enrolment, and education spending globally.
# Group Members : 
# Dipika Gurjar          KU2407U397
# Jeeya Thakrar          KU2407U409
# Dhriti Soni            KU2407U396
# Malaviya Riya          KU2407U423

Objective :
This project analyzes global education trends using Python, focusing on literacy rates, enrollment rates, and education spending. It involves collecting data from reliable sources like the World Bank or UNESCO, cleaning and preprocessing the data (handling missing values, converting formats), and performing statistical analysis using pandas and numpy. Visualization is done with matplotlib to display trends over time, correlations, and comparisons between regions. Key visualizations include line plots for literacy rates, scatter plots for spending vs. literacy, and bar plots for regional comparisons. This project provides insights into the evolving education landscape and its influencing factors.

Tools and Libraries Used : 
•  Python: Programming language for data analysis and visualization.
•  pandas: Library for data manipulation and analysis, used for data cleaning, transformation, and analysis.
•  numpy: Library for numerical operations, used for statistical analysis and handling arrays.
•  matplotlib : Plotting library used for creating static, interactive, and animated visualizations (e.g., line plots, scatter plots, bar charts).
•  tabulate : Used to format data into readable tables for console output. It supports various table styles and is compatible with lists, dictionaries, and pandas DataFrames.

Data Source(s) : 
Kaggle: Offers various education-related datasets, such as literacy rates, enrollment statistics, and education spending.
•	Website: https://www.kaggle.com/datasets
World Health Organization (WHO): Although primarily focused on health data, WHO also provides education-related data, especially around health literacy and education in health fields.
•	Website: https://www.who.int/data
World Bank Education Statistics: Provides global data on education indicators like literacy rates, enrollment, and spending.
•	Website: https://data.worldbank.org/topic/education
And data set is created by own 


Execution Steps (How to run the project) : 
Install Required Libraries:
Install necessary Python libraries such as pandas, numpy, matplotlib, and tabulate.
Data Collection:
•	Download datasets from sources like Kaggle, World Bank, or Data.gov.
•	Ensure the data is in CSV or Excel format for easy processing.
Data Import:
•	Load the dataset into a pandas DataFrame for analysis.
Explore and Clean the Data:
•	Display the dataset using tabulate for better readability.
•	Print the first few rows to understand the structure.
•	Check for missing values and handle them:
o	Fill missing values in Literacy Rate and Enrollment Rate with the column mean.
Data Analysis:
o	Average Literacy Rate by Region using groupby().
o	Education Spending Trends over the years.
o	Correlation between Literacy Rate and Enrollment Rate.
Data Visualization:
•	Create visualizations using matplotlib:
o	Bar chart for Literacy Rate by Region.
o	Line chart for Education Spending Trends.
o	Scatter plot for Literacy Rate vs Enrollment Rate.

Summary of Results
The analysis of the education dataset revealed important insights about global education trends. After cleaning the data by filling missing values for literacy and enrollment rates and dropping rows with missing education spending data, we proceeded with the analysis.
•	Correlation Analysis: A strong positive correlation between literacy and enrollment rates was observed, indicating that as literacy rates increase, enrollment rates tend to rise as well.
•	Regional Literacy Trends: The average literacy rate was calculated for each region, showing disparities between regions with higher and lower literacy levels.
•	Education Spending: A line chart depicting global education spending trends highlighted the fluctuations in investment over time as a percentage of GDP.
•	Key Visualizations: Bar charts, line graphs, and scatter plots were used to visualize the data, revealing regional differences, trends in spending, and the relationship between literacy and enrollment rates.

Challenges Faced
1.	Data Quality:
•	Missing values in critical columns like Literacy Rate, Enrollment Rate, and Education Spending (% of GDP) required handling through imputation or removal.
2.	Limited Time-Series Data:
•	Insufficient data across multiple years limited the ability to analyze trends meaningfully over time.
3.	Correlation Analysis:
•	Understanding and interpreting the correlation between literacy rate and enrollment rate required statistical validation.
4.	Data Visualization:
•	Selecting appropriate visualizations and ensuring they were meaningful given the dataset's limitations.
5.	Data Cleaning:
•	Ensuring the dataset was free from anomalies and ready for analysis while retaining key insights.
6.	Technical Implementation:
•	Debugging Python code for reading, processing, and visualizing data efficiently.
