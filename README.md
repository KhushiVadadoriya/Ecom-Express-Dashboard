## Project Overview

This project analyzes end-to-end e-commerce performance using an interactive Power BI dashboard. The goal is to help stakeholders clearly understand revenue trends, product performance, category insights, state-wise demand, and the financial impact of cancellations.
The dashboard brings all business metrics into one place, enabling faster, data-driven decisions.

## Objective

To create a simple yet powerful analytical dashboard that answers key business questions such as:

Which products and categories generate the most revenue?

Which states drive the highest sales?

Why is revenue dropping after July?

How much revenue is lost due to cancellations?

Which areas need operational improvement?


## Key Features of the Dashboard

KPI Cards: Total Revenue, Total Sales, AOV, Cancellation Rate, Lost Revenue

Product Performance: Top and bottom revenue-generating products

Category Analysis: Laptops, Mobiles, Accessories, Tablets, etc.

State-wise Revenue: Identifying top and low-performing regions

Monthly Revenue Trend: Clear drop from July onward

Cancellation Impact: 29.72% cancellation rate causing ₹525M+ revenue loss

Interactive Filters: Category and product-level analysis

## About the Dataset – Ecom Express

The dataset is divided into three main tables: Customers, Orders, and Products.
Together, they simulate a real e-commerce environment and allow analysis of revenue, customer behavior, product performance, and delivery patterns.

**1. Customers Table**

Contains customer-related information to understand buyer profiles and regional performance.

Columns:

CustomerID – Unique ID for each customer

Full Name – Customer’s name

Phone – Contact number

Phone Brand – Mobile phone brand used

City – Customer’s city

State – Customer’s state

Custom – Additional custom field included in dataset


**2. Orders Table**

Includes transaction and operational information for each order placed.

Columns:

OrderID – Unique ID for each order

CustomerID – Linked to the Customers table

ProductID – Linked to the Products table

Date and Time – Timestamp of the order

Quantity – Number of units ordered

Delivery Status – Delivered / Cancelled

Delivery Time – Time taken for delivery


**3. Products Table**

Contains details about each product sold by the company.

Columns:

ProductID – Unique product identifier

Product Name – Name of the product

Category – Product category (Laptop, Mobile, Accessories, etc.)

Price – Price per unit

Rating – Customer rating

Number of People Rated – Rating count


## Tools & Technologies Used

Power BI – Dashboard creation and visualization

Excel / CSV – Data cleaning and preparation

DAX – Measures and calculations


## Contact

For questions or collaboration:
Khushi Vadadoriya
vadadoriyakhushi18@gmail.com
