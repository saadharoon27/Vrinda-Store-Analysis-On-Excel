# Vrinda-Store-Analysis-On-Excel
Vrinda Store wants to create an annual sales report for 2022. So that, Vrinda can understand their customers and grow more sales in 2023.

## Author
- [@saadharoon27](https://github.com/saadharoon27)

## Table of Contents
- [Business Problem](#business-problem)
- [Data Source](#vrinda-store-dataset)
- [Business Questions](#business-questions)
- [Method](#method)
- [Quick Glance At The Dashboard](#quick-glance-at-the-dashboard)
- [Step By Step Procedure](#step-by-step-procedure)

## Business Problem
Vrinda Store is gearing up to compile a comprehensive annual sales report for the year 2022. This report is envisioned as a crucial tool for Vrinda's business strategy moving forward, with the primary goal of gaining valuable insights into their customer base. By analyzing the data from the past year, Vrinda aims to identify trends, patterns, and customer preferences that will enable them to make informed decisions and devise targeted marketing strategies for the upcoming year, 2023.

## Data Source
- [Vrinda Store Dataset](https://www.kaggle.com/datasets/harunshah786/vrinda-store-dataset)

## Business Questions
These questions collectively aim to provide a comprehensive understanding of the sales and order data for 2022, enabling data-driven decision-making and strategy development for Vrinda Store's growth and improvement in 2023.

- 1.	Compare the sales and orders using single chart.
- 2.	Which month got the highest sales and orders?
- 3.	Who purchased more? Men or women in 2022?
- 4.	What are different order status in 2022?
- 5.	List top 5 stats contributing to the sales?
- 6.	Relation between age and gender based on number of orders.
- 7.	Which channel has the maximum contribution?

## Method
- Exploratory data analysis (EDA)

## Quick Glance At The Dashboard
![dashboard](assets/dashboard.png)

## Steps By Step Analysis

- **Data Cleaning**
  - **Gender column:** Replaced the categorical value ‘M’ and ‘W’ values to ‘Men’ and ‘Women’.
  - **Quantity column:** Replaced the values ‘One’ and ‘Two’ to ‘1’ and ‘2’ respectively.

- **Data Processing**
  - **Age Group:** To address the question *vi* Of business question, a new column has to be created named ‘Age Group’ to extract the relationship between ‘Age’, ‘Gender’, and the number of orders they made. 
  - **Categories:** >=50, Senior; >=30 and <50, Adult; <30, Young
  - **Month Column:** To address question 2, a ‘Month’ column has been created.

- **Analysis & Dashboarding**
  - Step 1:
    - To address question 1, and 2, created a new a pivot table in sheet ‘Q1 - Order vs Sales Chart’ comparing total monthly sales value and number of orders.
  - Step 2:
    - Created a new sheet, ‘Q3 – Most Purchases’ to analyse which gender purchased the most, addressing question 3.
  - Step 3:
    - Created a new sheet, ‘Q4 – Order Status’ to address question 4, which checks the status of the order compared to the total orders.
  - Step 4:
    - To address question 5, a new pivot table has been made in the sheet named: ‘Q5 – Top 5 States’.
  - Step 5:
    - To understand the relationship between age, gender, and number of orders, and to address question 6 a new sheet has been created named: ‘Q6 – Age, Gender, Orders’.
  - Step 6:
    - Addressing question 7: To check which channel has the highest contribution a pivot chart has been created in sheet: ‘Q7 – Channels’.

- Filters
