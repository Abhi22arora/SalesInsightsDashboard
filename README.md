# SalesInsightsDashboard
ATLIQ Hardware Sales Insights PowerBI Dashboard
# ATLIQ Hardware Sales Insights PowerBI Dashboard
### INTRODUCTION:

I recently completed this project utilizing PowerBI, which was modeled after the tutorials provided by Codebasics in their PowerBI YouTube playlist and supplemented with guidance from the End to End Power BI Project Series. This project allowed me to gain a deeper understanding of PowerBI and its capabilities.

[Codebasics youtube playlist](https://www.youtube.com/playlist?list=PLeo1K3hjS3uva8pk1FI3iK9kCOKQdz1I9)

### PROBLEM STATEMENT
The Sales Director of Atliq Hardware, a firm with multiple branches across India, is struggling to effectively track and understand the performance of their sales in a rapidly growing market. Despite having regional managers for North, South, and Central India, the Director is finding it difficult to gain accurate insights from the sales data provided in the form of multiple excel files. This makes it challenging to identify trends, patterns, and potential issues. The Director recognizes the importance of tracking sales to stay informed about the company's performance and make data-driven decisions to improve sales. In the event of a decline in sales, the Director wants to be able to quickly identify the cause and implement strategies such as promotional offers, marketing campaigns, or improved customer engagement to address the issue. To achieve this, the Director is seeking a more streamlined and easy-to-understand system for tracking sales, which would allow for more efficient communication and collaboration with regional managers.

### SOLUTION
Sales director decided to hire a group of analysts to build interactive PowerBI dashboards so that he can track sales to stay informed about the performance of the company and identify any potential issues or areas for improvement

### AIMS Grid

<div align="center">
<img height:"75" width:"75" src="https://github.com/Abhi22arora/SalesInsightsDashboard/blob/198689cf379db1321b0284c5b79f251f4249798d/Images/AimsGrid.png">
</div>

### DATA MODEL

### SOFTWARE AND TOOLS REQUIRED:

1. [Github Account](https://github.com)
2. [MYSQL](https://www.mysql.com/downloads/)
3. [PowerBI Desktop](https://www.microsoft.com/en-us/download/details.aspx?id=58494)


### DATA MODEL:
<div align="center" >
<img height:"100" width:"100" src="https://github.com/Abhi22arora/SalesInsightsDashboard/blob/198689cf379db1321b0284c5b79f251f4249798d/Images/Sales_Insights_DataModel.png">
</div>



### Steps followed in this project:
1. Performed basic analysis of data using SQL queries and observed the following
    *   The sales amount is in two different currencies INR and USD. It has to be converted to one currency either INR or USD so that we can analyse the data
    *   The data belongs to 2017,2018,2019 and 2020
    *   Sales amount can???t be negative let???s find if there are any records with negative sales amounts.
2. Connected the SQL data to PowerBI
3. Performed ETL and data cleaning on the imported data
    *   Removed irrelevant data like rows where sales amount is 0 or negative.
    *   removed other countries as we are looking for sales insight in India.
    *   Converted the sales amount to a single currency (INR)
4. Created measures like Revenue, Sales Quantity
5. After the initial report reviewed by stakeholders made further changes based on their feedback

## FINAL RESULT

### DASHBOARD
<div align="center">
<img height:"75" width:"75" src="https://github.com/Abhi22arora/SalesInsightsDashboard/blob/198689cf379db1321b0284c5b79f251f4249798d/Images/sales%20insights21_page-0001.jpg">
</div>





