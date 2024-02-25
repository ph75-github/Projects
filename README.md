
# SuperStore Sales - Dashboard

### Dashboard Link : https://app.powerbi.com/groups/me/reports/2304086f-ff1e-4fdb-82f8-fd361b26db1e/ReportSection?experience=power-bi

## Problem Statement

This dashboard helps the SuperStore understand their sales and gain valuable insights to drive business decisions. It helps the SuperStore know how their sales are going in each region and where there is a need for sales improvement. It also lets them know what the total sales are and what the profit gains are throughout the year, month by month.

The challenges include cleaning and transforming the raw data, performing exploratory analysis, and visualizing the findings in an intuitive and informative manner.

Tools used: SQL, Power BI

### Steps Followed
- Step 1: The csv file imported into a SQL database. 
- Step 2: SQL queries are utilized to extract relevant information and derive insights from the dataset. 
- Step 3: Load the csv file in Power BI an used it as the visualization tool to create interactive and visually appealing reports. 

Note: This repository showcases the Superstore Sales Analysis project, which aims to analyze and visualize the sales data of a fictional superstore. The project utilizes a combination of SQL, and Power BI to perform exploratory analysis, and create interactive reports.

# Insights

A single page report was created on Power BI Desktop & it was then published to Power BI Service.

Following inferences can be drawn from the dashboard:

### [1] Percentage of sales by segment

  - Consumer segment produce 48.09% of the total sales.
  - Corporate segment produce 32.55% of the total sales.
  - Home/Office segment produce 19.35% of the total sales.

           Thus, the consumer segment makes up most of the sales.
           
### [2] Percentage of profit by region

 - The West region of the US makes 38.72% of the total profit.
 - The East region of the US makes 30.47% of the total profit.
 - The Central region of the US makes 15.66% of the total profit.  
 - The South region of the US makes 15.15% of the total profit.  
  
  ### [3] Total sum of quantities by various ship modes  
  
 - Standard class shipping mode makes a total of 13.2K deliveries.
 - Second class shipping mode makes a total of 4.4K deliveries.
 - First class shipping mode makes a total of 3.6K deliveries.
 - Same day shipping mode makes a total of 1.2K deliveries.

            Thus, most people opt for standard class mode for their deliveries.
Note: The reason most people opt for standard class might be the high delivery charges on other shipping modes.
 ### [4] Percentage of sales by payment mode
 - 43% of the sales were made by Cash on Delivery.
 - 35% of the sales were made through online transactions.
 - 22% of the sales were made by card transactions.
 
       
       Thus, around 57% of the sales were made through online mode (card + online).

### [5] Total sales and profit

- Total sales - 1,566K
- Total profit - 175k
