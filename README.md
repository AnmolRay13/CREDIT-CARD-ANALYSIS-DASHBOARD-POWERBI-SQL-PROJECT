# Credit Card Analytics Dashboard | Power BI + SQL Project

## Project Overview

This project is an end-to-end Data Analytics solution built using **MySQL, Power BI, and DAX**.
The objective is to analyze **credit card transactions and customer behavior** and generate meaningful business insights through an interactive dashboard.

The workflow includes **data cleaning, transformation, modeling, and visualization**.

---

## Tech Stack

*  Power BI
*  MySQL
*  DAX (Data Analysis Expressions)
*  CSV Data Files
*  Power Query Editor

---

##  Project Workflow

### 1️. Data Source

* Raw data provided in CSV format:

  * `credit_card.csv`
  * `customer.csv`

---

### 2️. Database Creation (MySQL)

* Created database: `ccdb`

* Created tables:

  * `cc_detail` (Transaction Data)
  * `cust_detail` (Customer Data)

* Imported data using SQL queries (`LOAD DATA INFILE`)

---

### 3️. Data Cleaning & Transformation

* Used Power Query Editor
* Handled missing values
* Removed duplicates
* Fixed data types
* Standardized columns

---

### 4️. Data Modeling & DAX

#### • Calculated Columns

* Age Group
* Income Group
* Week Number

#### • Measures

* Total Revenue
* Current Week Revenue
* Previous Week Revenue
* Week-over-Week (WoW) Growth

---

##  Dashboard Overview

### • Credit Card Transaction Report

* Revenue by Card Type
* Revenue by Expenditure Type
* Revenue by Job Type
* Revenue by Education Level
* Quarterly Revenue Trend

### • Credit Card Customer Report

* Revenue by Income Group
* Revenue by Age Group
* Revenue by Gender
* Revenue by Marital Status
* Top 5 States Analysis

---

##  Key Insights

* Blue card category generates the highest revenue
* Swipe transactions dominate over chip and online payments
* Businessman and White-collar customers contribute the most revenue
* High-income group customers generate the largest share
* Maximum revenue comes from the 40–60 age group
* Top performing states include TX, NY, and CA

---

##  Key Metrics

* Total Revenue: 55M
* Total Interest Earned: 7.8M
* Transaction Amount: 45M
* Transaction Count: 656K
* Total Income: 576M

---

##  Dashboard Features

* Interactive slicers (Quarter, Gender, Card Type, Income Level)
* Dual dashboards: Transaction Report & Customer Report
* Professional dark theme UI
* KPI cards, charts, and detailed tables for deep insights

---

##  Objective

To design and develop an end-to-end analytics solution for credit card data that identifies key revenue patterns, customer behavior patterns, and transaction trends, enabling data-driven decision-making using SQL, Power BI, and DAX.

---

##  Conclusion

This project showcases an end-to-end data analytics solution — transforming raw data into meaningful insights through data modeling, DAX calculations, and interactive dashboards, highlighting real-world business intelligence capabilities.

---
