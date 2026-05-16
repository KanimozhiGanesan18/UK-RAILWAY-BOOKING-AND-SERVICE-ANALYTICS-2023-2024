PROJECT OVERVIEW


This project focuses on analysing a railway ticketing dataset to
uncover insights into customer booking behaviour, revenue trends, and train performance.
The dataset contains detailed information such as ticket purchases, journey schedules, delays,
cancellations, and refund requests. The goal of this analysis is to help stakeholders (railway
operators, management teams, and planners) make data-driven decisions to improve
operational efficiency, enhance customer experience, and maximize revenue.


2. OBJECTIVES
   
Analyse total revenue and ticket sales trends.
Identify patterns in customer purchase behaviour (online vs station).
Evaluate train performance (on-time, delayed, cancelled).
Understand key causes of delays (e.g., signal failure, weather, staffing).
Analyse refund requests and their drivers.
Compare performance across routes, stations, and ticket types.


3. DATA SOURCES
   
Dataset Source: https://mavenanalytics.io/data
Timeline: 2023-2024
Data Size: 30,000+ rows and 18 columns

6. DATA CLEANING (PREPROCESSING)
   
The following preprocessing steps were performed to ensure data quality.
Removed duplicate records using Transaction ID.
Corrected and changed date formats.
Standardized categorical values (Payment Method, Ticket Type).
Handled missing values (e.g., In delay reasons: None to “Right Away”).
Currency symbol “£” added in the Price column.

TOOLS USED:
Excel
Power BI (Power Query)
DAX

8. DATA TRANSFORMATION
   
To enhance the quality, usability, and analytical depth of the dataset, several data
transformation steps were performed using Power Query and DAX.
DEVELOPED CALCULATED TABLE:

A dedicated Calendar Table was created by the “Date of journey” column to enable
time-based analysis and support DAX functions such as YTD, MTD, and trend comparisons.

The table includes:

Year, Month Name, Quarter, Year-Quarter.

This ensured consistent date relationships and improved report performance.
DERIVED KEY PERFORMANCE INDICATORS (KPIS):
Key metrics were developed using DAX to evaluate business performance:

Total Amount
Total Bookings
On-Time Performance (%)
Delay Percentage (%)
Cancellation Rate (%)
MTD bookings

These KPIs provided a high-level summary of operational efficiency and financial
performance.
6. DATA MODELLING
Build relationships between tables to create a structured and scalable analytical data
