# Bank Loan Report Excel Dashboard

## Project Overview
This project is an Excel-based dashboard designed to analyze and visualize data on bank loan applications. It provides insights into loan applications, funding amounts, interest rates, and other key metrics through two main report views: **Summary** and **Overview**. These reports are fully interactive, allowing users to filter by loan grade, purpose, and other criteria, making it easier to identify trends and patterns in loan issuance.

## Data Cleaning
The data required extensive cleaning to ensure accuracy and consistency across reports. Some of the main data cleaning steps included:
- Handling missing values and ensuring consistency in loan application statuses.
- Formatting columns to the correct data types, such as currency and percentages.
- Standardizing loan grades and purposes to create meaningful filter options for the dashboard.

## Design Sheet
The **Design Sheet** is the foundation of the dashboard, where key calculations and pivot tables were created. Using pivot tables, the data was aggregated and categorized by relevant fields such as loan status, purpose, and grade. The pivot tables formed the basis for the visuals, allowing for a dynamic and easily updated dashboard.

### Key Pivot Tables:
1. **Loan Application Status by Month** – Displays monthly counts of loan applications for trend analysis.
2. **Loan Funding and Receipt** – Summarizes the total funded and received amounts for both good and bad loans.
3. **Loan Distribution by Term and Purpose** – Breaks down loan applications by the loan term (36 or 60 months) and the purpose of the loan.

## Summary Report
The **Summary Report** provides a high-level view of key metrics:
- **Total Loan Applications, Funded Amount, and Amount Received** – Shows the overall loan activity.
- **Good vs. Bad Loan Issuance** – A breakdown of loans issued, highlighting the percentage of good and bad loans.
- **Loan Application Status** – Visualizes the current status of loans (fully paid, charged off, current) to track loan health.

### Summary Report Snapshot
![Summary Report](path/to/summary_report_image.png)

## Overview Report
The **Overview Report** dives deeper into loan application trends and borrower profiles:
- **Monthly Application Trends** – Line chart showing the number of loan applications by month, allowing for seasonal trend analysis.
- **Geographic Distribution** – A map showing the volume of applications across the USA to identify regional trends.
- **Applications by Employment Length** – Displays loan applications segmented by borrower employment length.
- **Applications by Home Ownership** – Breakdown of loan applications based on home ownership status (rent, mortgage, own).

## Usage
This dashboard serves as a tool for stakeholders to monitor loan performance, assess borrower risk, and identify trends in loan demand. With its interactive features, users can drill down into specific segments of the data, making it a valuable resource for decision-making and reporting.
