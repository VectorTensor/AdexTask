# Data Analysis

The analysis is in the file [DataAnalysis.ipynb](https://github.com/VectorTensor/AdexTask/blob/main/DataAnalysis.ipynb).

## Process
First we performed various data preprocessing such as: 
1. Handling missing values. There were two columns with missing values age and Gender. Since age is continuous value we replace it using mean and gender is categorical value we replace it using mode.
2. We removed the duplicates 


Then we did some data transformations like creating age groups, counting purchases per item and creating summary table for age column.

Then we performed various analysis like Item popularity, average age of the customer for item purchased. We also count the purchase for different age groups. We also calculated the number of purchases for top three items for different age groups and also the most purchased item for each group. 

We also visualized various pie chart and bar graph using dataframe.plot()

## Report
We finally created a report for all the findings in [Data Analysis Report](https://github.com/VectorTensor/AdexTask/blob/main/Data%20Analysis%20Report.pdf)


