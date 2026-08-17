
**UK-RAILWAY BOOKING AND SERVICE ANALYSIS USING POWER BI AND EXCEL (2023-2024)**



1.PROJECT OVERVIEW


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

4. DATA CLEANING (PREPROCESSING)
   
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

5. DATA TRANSFORMATION
   
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

<img width="944" height="443" alt="Screenshot 2026-05-14 104254" src="https://github.com/user-attachments/assets/4d2e19e0-63c4-4bc7-9903-ad4b25328c68" />


7.DATA ANALYSIS (EDA) & VISUALIZATION

INSIGHTS BASED CHARTS:

REVENUE TREND OVER TIME – INSIGHTS:

Descriptive Analytics: Revenue remained stable between 5K–7K with a few major
peaks and sudden drops during the observed period.
Diagnostic Analytics: Revenue fluctuations were mainly caused by high booking
demand, delays, cancellations, and operational issues.
Predictive Analytics: Revenue is likely to remain steady with occasional peaks
during high-demand travel periods.
Prescriptive Analytics: Improving on-time performance and reducing
cancellations can help increase revenue consistency and customer satisfaction.

INSIGHTS BASED ON COLUMN CHART


Descriptive Analytics: Standard Class generated the highest revenue, especially
Advance tickets with 242K revenue. First Class contributed comparatively lower
revenue across all ticket types.

Diagnostic Analytics: Passengers mostly preferred affordable Standard and Advance
tickets due to lower prices and better availability.
Predictive Analytics: Standard and Advance ticket bookings are likely to continue
generating the highest revenue in future periods.
Prescriptive Analytics: Focus on promoting Advance and Off-Peak tickets and
improve First Class offers to increase overall revenue.
INSIGHTS BASED ON PIE CHART

PAYMENT METHOD INSIGHTS:

Descriptive Analytics: Most customers used Credit Cards (60%), followed by
Contactless (34%), while Debit Card usage was very low (5%).
Diagnostic Analytics: Customers preferred Credit Cards and Contactless payments
because they are faster and offer better rewards.
Predictive Analytics: Contactless payments are likely to increase further in the future.
Prescriptive Analytics: Provide offers and cashback to encourage more Contactless
and Debit Card usage.

INSIGHTS BASED ON PIE CHART JOURNEY STATUS:


Descriptive Analytics: Most journeys were completed On Time (86.82%), while
Delayed journeys were 7.24% and Cancelled journeys were 5.94%.
Diagnostic Analytics: High on-time performance shows efficient operations, while
delays and cancellations may be caused by traffic, technical issues, or scheduling
problems.
Predictive Analytics: If current performance continues, most journeys will remain on
time, but delays and cancellations may increase during peak periods.
Prescriptive Analytics: Improve scheduling, monitor operations closely, and reduce
delays/cancellations through better planning and maintenance.

INSIGHTS BASED ON FUNNEL CHART ANALYSIS


Descriptive Analytics: York generated the highest total revenue, followed by London
Euston and Birmingham New Street. Revenue sharply decreases for other
destinations, with many showing very low totals.

Diagnostic Analytics: Major cities like York and London attract more travellers,
resulting in higher ticket sales. Smaller or less frequent routes naturally bring in fewer
passengers and lower revenue.
Predictive Analytics: High-demand destinations will continue to dominate revenue in
the future. Low-revenue locations are unlikely to grow significantly without targeted
action.
Prescriptive Analytics: Strengthen offerings and pricing for high-revenue routes to
maximize profit. Promote lower-performing destinations through discounts,
marketing, or improved services.

INSIGHTS BASED ON SCATTER PLOT ANALYSIS


Descriptive Analytics: Delays vary across different departure times, with some times
showing higher delay percentages. Larger bubbles indicate that transactions with
certain payment methods (especially credit card) occur during higher delay periods.
Diagnostic Analytics: Certain departure times likely face more congestion, leading to
increased delays. High transaction volumes at specific times may correlate with busier
travel periods and operational strain.
Predictive Analytics: Similar departure times will likely continue showing higher
delay percentages based on existing patterns. Increased passenger volume may further
raise delays during peak payment/booking times.
Prescriptive Analytics: Adjust schedules or add buffer time for departure slots that
consistently show higher delays. Improve operational efficiency during peak
transaction periods to reduce delay impact.

INSIGHTS BASED ON MAP VIEW:


Descriptive Analytics: Most train journeys are concentrated around major UK cities
like London, Birmingham, Manchester, and Leeds. Routes are heavily clustered in
central and southern UK, with fewer trips observed in northern and far-west regions.
Diagnostic Analytics: These highlighted cities are major travel hubs with higher
population density and more frequent rail services. Business centres and commuter
routes naturally attract more travel activity, causing dense mapping points.
Predictive Analytics: Travel will continue to be concentrated around major urban
centres due to sustained demand. Lesser-used routes may remain low unless new
services, attractions, or developments increase travel interest.
Prescriptive Analytics: Strengthen services, capacity, and connectivity between major
hubs to support high demand. Promote lesser-used routes through targeted marketing,
improved schedules, or better infrastructure.

FEATURES INCLUDED:

FILTERS(SLICERS):

Users can filter the data by Ticket Class, Purchase Type, and Payment Method to view
specific insights and customize the dashboard based on their needs.
Drill-down Capabilities: Visuals allow users to drill down into detailed levels such as ticket
type, destination, and time-based trends for deeper analysis.
Interactive Visuals: Charts, maps, and graphs respond dynamically to selections, enabling
users to explore patterns, compare performance, and gain clear insights in real time.

8. FINAL DASHBOARD:

   <img width="1782" height="804" alt="Screenshot 2026-05-12 124044" src="https://github.com/user-attachments/assets/cb44edfc-442e-4b98-b9ce-e6ed8d1722db" />


9.KEY INSIGHTS MENTIONED IN SMART WAYS

Improve on-time performance and increase revenue by addressing delays during peak
departure times and strengthening high-demand routes such as York, London Euston,
and Birmingham.
Reduce delay percentage from 7.24% to below 5%, increase on-time performance
from 86.82% to 90%, and grow monthly ticket revenue by at least 10% on
top-performing routes.
Implement targeted scheduling adjustments, enhance operational coordination, and
promote Off-Peak and Anytime tickets to balance demand and reduce congestion.
These improvements align directly with the dashboard insights showing delay issues,
high route concentration, and uneven revenue distribution—improving both customer
satisfaction and revenue growth.
Achieve delay reduction and service improvements within 3 months, and revenue
growth targets within the next financial quarter (3–4 months).

10. CONCLUSION
    
The UK Railway Booking and Service dataset reveals strong booking and
revenue concentration in major cities like York, London Euston, Birmingham, and
Manchester. Advance tickets generate the highest revenue, indicating strong customer
preference for lower-cost fare options. Overall service performance is good, with 86.82%
on-time journeys, though delays still occur during specific departure times. Credit card
payments dominate, reflecting a high adoption of digital payment methods. Improvements in
delay management and targeted promotion of low-performing routes can enhance both
customer experience and revenue.

