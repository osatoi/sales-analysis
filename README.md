# E-Commerce-Sales-Analysis

## Table of Content.
 - [](#Table-of-Content.)
 - [](#Project-Overview.)
 - [](#Data-source.)

### Project Overview.

This data analysis projectbaims to provide insights into the sales perfomance of an e-commerce company over the past year. By analyzing various aspects of the sales data, we seek to identify trends, make data-driven recommendation, and gain a deeper understanding of the company's perfomance.

### Data source.

Sales Data: The primary dataset used for this analysis is the "sales_data.csv" file, containing detailed information about each sale made by the company.

### Tools

- Python pandas - Data Cleaning
- SQL server - Data analysis
- PowerBI - creating reports and Dashboard.

### Data  Cleaning/Preparation

In the initial Data Preparaton, we performed the following tasks:
 1. Data loading and inspection.
 2. Handling Missing Values.
 3. Data cleaning and formatting.

### Exploratory Data Analysis

EDA involved exploring the sales data to answer key question, such as:
 - Whats is the overall sales trends?
 - Which products are top sellers?
 - What are the peak sales period?

### Data Analysis
This include some feature codes



```python
sample = {'Activities':['Tiktok','Tiktok','Tiktok', 'Instagram','Instagram','Instagram',
                    'favourite_Tv_Programme','favourite_Tv_Programme',
                    'favourite_Tv_Programme', 'Prayer','Prayer','Prayer',
                    'Bible_Studying','Bible_Studying','Bible_Studying'],
          'Category':['Instagram','Tiktok','Bible_Studying','favourite_Tv_Programme','Tiktok','Prayer','Tiktok','Bible_Studying','Prayer','Instagram','favourite_Tv_Programme', 'Tiktok','Instagram','favourite_Tv_Programme','Prayer'],
          'weekdays':['Monday','Monday','Monday','Tuesday','Tuesday','Tuesday','Wednesday','Wednesday','Wednesday',
                     'Thurdsday','Thurdsday','Thurdsday','Friday','Friday','Friday'],
          'HoursPerday':[5.5,6,5,4,5.5,6,5.6,6,4.5,1.2,0.9,0.4,0.2,0.5,1],
          'HoursPerweek':[27.5,30,25,20,27.5,35,28,30,22.5,6,4.5,2,1,2.5,5],
          'HoursPerYear':[5475,6205,4745,5110,4015,4380,5475,3650,2920,438,328.5,146,73,182.5,365]}
```

### Results/Findings
The analysis are summerized as follows:
 - The Company's sales has been steadily increasing over the past year, with a noticeable peak during the Holiday season.
 - Product Category A is the best-performing category in terms of sales and revenue.
 - Customer segments with high lifetime value (LTV) should be targeted for marketing efforts.


### Recommendations

Based on the analysis, we recommend the following actions:
 - Invest in marketing and promotions during peak sales seasons to maximize revenue.
 - Focus on expanding and promoting products in Category A.
 - Implement a customer segmentation strategy to target high-LTV customers effectively

### Limitations
I had to remove all zero values from budget and revenue colums because they would have affected the accuracy of my conclusions from the analysis. There are still a few outliers even after the omission despite that, we could still see there is a positive correlation between both budget and number of votes with revenue.

### References

 1. SQL for businesses by werty.
 2. [Stack Overflow](https://stackoverflow.com)
 
   
