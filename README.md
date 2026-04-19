# AdventureWorks - business analysis

A business intelligence dashboard developed in Microsoft Power BI for AdventureWorks, a fictional cycling equipment and accessories manufacturing company.

The AdventureWorks dataset includes data from 1-1-2020 to 6-30-2022, with tables related to the following core business data:-

<ul>
  <li> Sales and returns (transaction data like order number, order/return date, quantity ordered/returned) </li>
  <li> Products (product information like name, description, price)</li>
  <li> Customers (customer demographics like name, age, gender, income level)</li>
  <li> Geography (regions, countries and sales territories)</li>
</ul>

<i>The dataset used in this project was included in the <a href="https://www.udemy.com/course/microsoft-power-bi-up-running-with-power-bi-desktop/">Microsoft Power BI Desktop for Business Intelligence</a> course, available on Udemy.com </i>

## Data Model

The data model in this Power BI project is designed using a star schema structure, enabling efficient analysis of sales, customers, and product performance. A central sales table connects to multiple dimension tables that provide context for reporting and filtering.

<img width="1508" height="695" alt="Model view" src="https://github.com/user-attachments/assets/499b4050-e366-4847-8c1e-0df5a6bc6d99" />
<br>

One-to-many relationships from each dimension table to the central sales table, with filters flowing from the dimension tables to the fact table:-

<img width="867" height="762" alt="Table relationships" src="https://github.com/user-attachments/assets/88c6330d-8d3c-4657-8e7e-baa969a49a3a" />

## Dashboard Features

<ul>
<li> Monitor key performance indicators (KPIs) such as sales, revenue, profit, and returns </li>
<li> Compare performance across various countries to identify differences and trends </li>
<li> Analyze product-level trends to understand what is driving results </li>
<li> Identify and evaluate high-value customers for targeted insights and opportunities </li>
</ul>

## Project Tasks

<ul>
<li> Connecting and cleaning raw data sources from .csv files</li>
<li>Designing and setting up a relational data model</li>
<li>Creating calculated columns and measures using DAX</li>
<li>Building an interactive dashboard</li>
</ul>

## Dashboard views

### Executive Summary View

<ul>
<li>Card visuals and graphs showing top-level KPIs for profit, revenue, orders/return rates</li>
<li>Page level filtering by dates, products and product categories</li>
<li>Drill through per product for more details (leads to Product Detail view)</li>
</ul>


https://github.com/user-attachments/assets/6b945b54-e71d-4274-8943-9de4170ef768

### Map View

Interactive map with orders per country including filter options

<img width="1283" height="725" alt="image" src="https://github.com/user-attachments/assets/d30e1b6d-7fa4-4b24-9054-1c3ad7c7ad5c" />

### Product Detail

<ul>
  <li>Drill-down page to show detailed performance data for each product</li>
  <li>Includes graph to conduct a "what-if" analysis using price adjustment for forecasted profit</li>
  <li>Monthly orders, revenues and profits versus targets</li>
</ul>

<img width="1283" height="725" alt="image" src="https://github.com/user-attachments/assets/6b15b6cd-9fac-4255-994c-b4292f12715d" />


### Customer Detail 

Overview of total customers and drill-down analysis for individual customers

<img width="1283" height="725" alt="image" src="https://github.com/user-attachments/assets/fcbcb8d8-cf50-42b4-8e3c-2e61c692430e" />

### Decomposition Tree

Turns total orders KPI into an interactive breakdown for root cause analysis

<img width="1283" height="725" alt="image" src="https://github.com/user-attachments/assets/23d2240e-78c5-48b5-b30f-9df0b7c37240" />

### Key Influencers

AI-Powered visual to help determine what factors could be driving a specific outcome

<img width="1283" height="725" alt="image" src="https://github.com/user-attachments/assets/d4e752a4-7312-436e-8f85-972c28a3a47c" />

## Key insights

<ul>
<li>Approximately $24.9 million in revenue and $10.5 million in profit were generated between 1-1-2020 and 6-30-2022. A noticeable decline in revenue occurred between 01/06/2020 and 01/11/2020, potentially reflecting the simulated effects of the COVID-19 pandemic </li>
<li>Accessories are a big part of total orders (16,983 out of 25,164). Tires and tubes represent the most frequently ordered product category, while cycling shorts account for the highest return rates. Following mountain bike fenders, sports helmets rank among the top revenue-generating products, while still having high return rates</li>
<li>The number of total customers remained relatively flat from early 2020 to mid 2021, but then experienced a sharp increase around mid-2021, followed by sustained higher and more volatile growth through 2022.</li>  
<li>Marital status is the strongest driver of home ownership, with married individuals being about 1.62 times more likely to be homeowners than others</li>
<li>The United States is the largest market, with 8,700 orders generating $7.94 million in total revenue. However, Australia leads in revenue per customer, averaging $2,131</li>
</ul>






 




