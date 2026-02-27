Project Overview
This project performs an in-depth analysis of credit card spending habits in India using a dataset of over 26,000 transactions. The objective is to derive actionable insights regarding consumer behavior across different cities, card types, and expense categories using advanced SQL techniques.

Dataset Description
The dataset used for this analysis includes:

City: The location of the transaction (e.g., Delhi, Bengaluru, Greater Mumbai).

Date: The date the transaction occurred.

Card Type: The category of the card used (Gold, Platinum, Signature, Silver).

Exp Type: The type of expenditure (Bills, Food, Entertainment, Fuel, etc.).

Gender: The gender of the cardholder (F/M).

Amount: The total value of the transaction.

Key Insights & Problem Statements
The following complex business questions were addressed using SQL queries:

Top Spenders: Identified the top 5 cities with the highest total spends and their percentage contribution to overall credit card spending.

Peak Performance: Determined the highest spend month and amount for each card type.

Milestone Tracking: Found the transaction details for each card type when it reached a cumulative total spend of 1,000,000.

Gold Card Analysis: Isolated the city with the lowest percentage spend for the "Gold" card type.

Expense Extremes: Generated a report showing the highest and lowest expense types for each city.

Demographic Spends: Calculated the percentage contribution of female spenders for each expense type.

Growth Metrics: Identified which card and expense type combination saw the highest month-over-month growth in January 2014.

Weekend Trends: Analyzed weekend spending to find which city has the highest ratio of total spend to transaction count.

Efficiency: Determined which city took the least number of days to reach its 500th transaction from its inception.

Tech Stack
Database: SQL Server (Transact-SQL)

Data Cleaning: Used SQL to handle date formats and column renaming for better readability.

Version Control: Git & GitHub

How to Run the Project
Download the Dataset: You can find the raw data on Kaggle.

Import: Load the CSV into your SQL environment (e.g., MS SQL Server).

Execute: Run the scripts provided in the .sql file in this repository to see the results of the analysis.

About the Author
I am Sanidhya Mandliya, a Chemical Engineering student at NIT Surat. I am passionate about data analytics, SQL, and non-core engineering roles. My background includes a management internship at Shailesh J. Mehta School of Management, IIT Bombay.
