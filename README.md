# Customer-Segmentation for a subscription service-Analysis-
Project work
customers segmentation Analysis for a subscription service
#

[Project overview](#project-overview)

Data sources

Tools used

Data cleaning and preparation

Exploratory data analysis

[Data analysis](#data-analysis)

Data visualization

### Project overview
The aim of this project is to analyze customer data from a subscription service to identify customers segments and emerging trends. The goal is to understand customer behaviour, track the subscription types and identify the key trends in cancellations and renewal. Through this analysis, actionable insights will be derived to support strategic business decisions. It shows the regional revenue generated on three different subscription type i. e. Basic, Premium and Standard subscription. The East has the highest revenue been generated with a total of 16,958,778 as against others. The Basic type subscription has the highest figure of 33,776,735. The Basic subscription also has the highest Customer Count of 16,921 as against the Premium and Standard of 8,446 and 8,420 Customer Count respectively.

### Data sources
The dataset used for this analysis was provided by incubator Hub, an educational technology organization. The data includes customers records from a subscription service provider for a learning purpose.
---
### Tools used
1. Microsoft Excel [Download Here](https://microsoft.com)
-  for data cleaning and preparation.
- utilized excel formulars to calculate Average subscription duration and identify the most popular subscription types.
-   Created data visualizations using pivot table and charts to identify subscription pattern based on their revenue, the trending subscription types, the duration of cancellation renewal duration.
  
 2. SQL -Structured Query Language of data
   - for quering the dataset to retrieve the total number of customers from each region using SQL Command.
   - to find the most popular subscription type by the number of customers using SQL Command.
   - To calculate the total revenue by subscription type using SQL Command.
     
  3. POWERBI -Power Business Intelligence
     - Creation of  dashboard that will visualizes key customer segments
     - Uses of slicers for interactive analysis on the dashboard
- Github for portfolio building
---
### Data cleaning and preparation
In the initial phase of the data cleaning and preparation,we perform the following action;
1.  Microsoft Excel:
- data loading and inspection of the entire dataset
- Highlight the entire table to remove duplicates
- Cleaned data is ready to calculate Average subscription duration and use of  pivot tables and charts like pie chart, bars, column charts to find the subscription patterns that will aids decision making.
  
2.  SQL; Stuctured Query Language:
     - imported data from excel by creating a new database in SQL Server under LITA_DB
     - Used SQL Commands to remove excess columns and rows directly
     - Write queries on the data set provided to determine the total revenue by subscription type and to find the total number of active and cancelled subscriptions that will help the subscription provider in     
       their business decison making.
       
3.  POWERBI ;Power Business Intelligence:
    - Loaded a cleaned data via Get data option on Home Menu and entered Power Query Editor; to transform the data
    - Examined the data column quality, column profile and column distibution to check for error, empty, uniqueness and distinct of the data
    - Visual the data by creating dashboard to make use of tables, cards, matrix, slicers/filter and column, bar and pie chart etc. to determine the total revenue by region,
      sum of revenue by subscription type, average subscription duration, the count of customer that cancel or renew to help in providing insight on how the subscription provider has made progress over the years,   through DAX functions.
      To beautify the dashboard/report through the use of format tool (pencil icon) to make use of different size and style, padding, call out value, title, font size, colour, slicer etc. 
      
   ### Exploratory data analysis
   EDA involved the exploring of the data to answer some questions about the data such as;
   - What are the customer behaviour
   - which subscription type is the most popular
   - To identify key trends in cancellation and renewals.
    ```
     ### Data analysis
     ---
     This is where we include some basic lines of code or queries or even some of DAX expressions used during your analysis;

     ```SQL
     SELECT*FROM TABLE 1
     WHERE CONDITION =TRUE
     ```
    ### Data visualization









   
   |heading1|heading2|heading3|
   |-------|---------|--------|
   |Table1|Table2|Table3|
