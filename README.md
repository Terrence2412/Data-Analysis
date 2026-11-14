# Data-Analysis
EDA using python
Description of datasets(Insurance.csv)

MEDICAL INSURANCE COST ANALYSIS
1. Introduction
Medical insurance plays an important role in helping individuals manage healthcare expenses. Insurance companies collect customer information to understand their customers and evaluate patterns in medical insurance costs.
This project focuses on analyzing a medical insurance dataset using Python. The main objective is to explore customer information, identify patterns and investigate factors associated with medical insurance expenses.
The analysis uses Python libraries such as Pandas & Matplotlib and Seaborn to perform data cleaning, exploratory data analysis (EDA), statistical analysis and data visualization.
The project also aims to demonstrate how data analytics can help organisations make informed, data-driven decisions.
2. Business Problem
An insurance company wants to understand the factors associated with differences in medical insurance expenses among its customers.
The company needs information that can help it understand customer groups and identify patterns in insurance costs.
The main business questions are:
1.	What is the average medical insurance expense?
2.	Do smokers have higher average insurance expenses than non-smokers?
3.	Does age have a relationship with insurance expenses?
4.	Does BMI have a relationship with insurance expenses?
5.	Which region has the highest average insurance expenses?
6.	Are there differences in insurance expenses between males and females?
7.	How does the number of children relate to insurance expenses?
By answering these questions, the analysis aims to provide useful insights into the dataset.
3. Dataset Description
The dataset used in this project is called insurance.csv.
It contains 1,338 customer records and seven columns.
The dataset includes the following variables:
Column	Description
age	Age of the customer
sex	Sex of the customer
bmi	Body Mass Index
children	Number of children
smoker	Smoking status (yes/no)
region	Customer's geographical region
expenses	Medical insurance expenses
The dataset contains both numerical and categorical variables.
Numerical variables include age, BMI, children and expenses.
Categorical variables include sex, smoker and region.
The expenses column is the main variable of interest because the project investigates patterns associated with medical insurance costs.
4. Data Cleaning
Data cleaning was performed to ensure that the dataset was suitable for analysis.
The following activities were considered:
•	Checking the dataset for missing values.
•	Identifying duplicated records.
•	Checking the data types.
•	Investigating unusual or unexpected values.
•	Ensuring that numerical columns contained appropriate data types.
•	Checking categorical columns for unexpected categories.
The initial investigation found:
•	1,338 records.
•	7 columns.
•	No missing values.
•	1 duplicated record.
The duplicated record should be investigated and removed if confirmed to be an accidental duplicate.
The data types were also checked to ensure that numerical variables were stored correctly.
5. Exploratory Data Analysis (EDA)
Exploratory Data Analysis was performed to understand the structure, distribution and characteristics of the dataset.
The analysis focused on identifying patterns and answering the business questions.
The following areas were investigated:
5.1 Descriptive Statistics
The descriptive statistics showed:
•	Average customer age: approximately 39.21 years.
•	Average BMI: approximately 30.67.
•	Average number of children: approximately 1.09.
•	Average insurance expenses: approximately 13,270.42.
•	Lowest insurance expense: 1,121.87.
•	Highest insurance expense: 63,770.43.
5.2 Smoking Status
Customers were grouped according to their smoking status to compare their average insurance expenses.
The analysis showed that smokers had considerably higher average insurance expenses than non-smokers.
5.3 Regional Analysis
Customers were grouped according to their geographical regions to investigate differences in average insurance expenses.
The Southeast region recorded the highest average expenses among the four regions.
5.4 Age Analysis
Age was investigated to understand whether older customers tended to have higher insurance expenses.
The relationship between age and expenses was also examined using correlation analysis and visualisations.
5.5 BMI Analysis
BMI was investigated to explore its relationship with medical insurance expenses.
A scatter plot and correlation analysis were used to examine the relationship.
6. Data Visualisations
Data visualisation was used to communicate patterns and make the results easier to understand.
The following visualisations were created or planned:
1.	Bar Chart: Average insurance expenses by region.
2.	Pie Chart: Distribution of smokers and non-smokers.
3.	Histogram: Distribution of medical insurance expenses.
4.	Scatter Plot: Relationship between age and insurance expenses.
5.	Box Plot: Comparison of insurance expenses between smokers and non-smokers.
These visualisations help identify differences between customer groups and patterns within the dataset.
7. Statistical Findings
The statistical analysis produced several important findings.
7.1 Average Expenses by Smoking Status
The average expenses were:
•	Smokers: 32,050.23
•	Non-smokers: 8,434.27
Smokers had substantially higher average insurance expenses than non-smokers in this dataset.
7.2 Average Expenses by Region
The average expenses were:
•	Southeast: 14,735.41
•	Northeast: 13,406.38
•	Northwest: 12,417.58
•	Southwest: 12,346.94
The Southeast region had the highest average expenses.
7.3 Average Expenses by Sex
The average expenses were:
•	Male: 13,956.75
•	Female: 12,569.58
Male customers had higher average expenses than female customers in this dataset.
7.4 Correlation Analysis
The correlation analysis showed the following relationships with insurance expenses:
Variable	Correlation
Age	0.299
BMI	0.199
Children	0.068
Age had the strongest positive correlation with insurance expenses among these three numerical variables.
However, these correlations do not prove that one variable causes changes in insurance expenses.
8. Business Insights
Based on the analysis, several observations can be made.
1. Smoking status
Smokers recorded considerably higher average insurance expenses than non-smokers. Smoking status is an important variable to investigate when studying differences in insurance costs.
2. Age
Age showed a positive correlation with insurance expenses. This suggests that older customers tended to have higher expenses in this dataset.
3. Geographical region
The Southeast region recorded the highest average insurance expenses. Further investigation could help determine what factors contribute to this difference.
4. Sex
Male customers recorded higher average insurance expenses than female customers in the dataset.
5. BMI
BMI showed a positive but relatively weak correlation with insurance expenses.
These observations can help an insurance company identify areas for further investigation and improve its understanding of customer expenses.
9. Limitations
Although the analysis provides useful information, there are some limitations.
1.	The dataset contains only 1,338 customer records, which may not represent all insurance customers.
2.	The dataset does not provide detailed medical histories.
3.	The analysis identifies relationships but cannot establish cause-and-effect relationships.
4.	Some important factors affecting insurance expenses may not be included in the dataset.
5.	The dataset may not represent current insurance costs or customer behaviour.
Therefore, the findings should be interpreted within the limitations of the available data.
10. Conclusion
This project analysed medical insurance expenses using Python and data analytics techniques.
The analysis included data exploration, data cleaning, descriptive statistics, grouping, filtering, correlation analysis and data visualisation.
One of the most noticeable findings was the difference in average insurance expenses between smokers and non-smokers.
Age also showed a positive relationship with insurance expenses, while the Southeast region recorded the highest average expenses.
Overall, the project demonstrates how Python and data analytics can be used to explore datasets, identify patterns and communicate meaningful findings.
The analysis provides a foundation for further investigation and demonstrates the importance of using data to support informed business decisions.

