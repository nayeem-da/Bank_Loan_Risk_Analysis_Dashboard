Bank Loan Analytics Dashboard | SQL Server + Power BI

This project analyzes more than 38,000 bank loan records to understand loan performance, customer risk profiles, and repayment behavior.
The goal is to transform raw financial data into interactive business insights using SQL-based data engineering and Power BI visualization.

Dataset Overview

The dataset includes the following key columns:

Loan application status

Funded amount and received amount

Interest rate (IR%)

Debt-to-income ratio (DTI)

Loan purpose and categories

State and region information

Employment length

Home ownership types

This data supports both performance monitoring and risk assessment.

Data Engineering and Modeling

Performed in SQL Server:

Loaded raw CSV data into SQL tables

Cleaned and standardized formats

Fixed inconsistent and missing values

Created transformations to define Good vs Bad loans

Verified reliability of numeric and financial fields

Data Model designed using Star Schema

Fact Table: FactLoanPerformance

Dimension Tables: DimCustomer, DimLoan, DimGeography

This model improves query speed and enables better business reporting.

Power BI Dashboard and Insights

Developed an interactive dashboard providing:

Total Loan Applications

Total Funded Amount and Total Received Amount

Good vs Bad loan comparison

Geographic loan distribution

Average Interest Rate and Average DTI

Analysis by loan purpose, employment length, home ownership, grade, and term

DAX measures were used for key performance metrics such as:

Month to Date (MTD) totals

Month over Month growth percentage

Average Interest Rate and Average DTI calculations

Loan segmentation logic

Project Objectives

Monitor overall loan disbursement performance

Reveal customer segments with higher loan risks

Support business decisions in lending policies

Provide a clear and simple interface for stakeholders

Tools and Technologies

SQL Server

T-SQL

Power BI

DAX

CSV data sources
