# 🚆 UK Railway Ticket Sales & Journey Performance Analysis (2023–2024)

## 📌 Project Overview

This project focuses on analyzing a UK railway ticketing dataset to uncover insights into customer booking behavior, revenue trends, journey performance, delays, cancellations, and refund requests.

The analysis is designed to help railway operators, management teams, and planners make data-driven decisions to improve operational efficiency, enhance customer experience, and maximize revenue.

---

## 🎯 Project Objectives

The main objectives of this project are to:

- Analyze total revenue and ticket sales trends.
- Identify customer purchase behavior across online and station bookings.
- Evaluate train journey performance, including on-time, delayed, and cancelled journeys.
- Identify key causes of delays such as signal failure, weather, and staffing.
- Analyze refund requests and their potential drivers.
- Compare performance across routes, stations, destinations, and ticket types.

---

## 📊 Dataset Description

### Data Source

**Dataset Source:** Maven Analytics  
**Timeline:** 2023–2024  
**Dataset Size:** 30,000+ rows and 18 columns

The dataset contains detailed railway ticketing information covering:

- Ticket purchases
- Journey schedules
- Departure and arrival information
- Delays
- Cancellations
- Refund requests
- Payment methods
- Ticket types
- Routes and destinations

---

# 🧹 Data Cleaning & Preprocessing

The following preprocessing steps were performed to improve data quality and prepare the dataset for analysis:

- Removed duplicate records using **Transaction ID**.
- Corrected and standardized date formats.
- Standardized categorical values such as **Payment Method** and **Ticket Type**.
- Handled missing values, including delay reasons.
- Added the **£ currency symbol** to the Price column.

---

# 🛠️ Tools Used

- Microsoft Excel
- Power BI
- Power Query
- DAX

---

# 🔄 Data Transformation

Data transformation was performed using **Power Query and DAX** to improve the quality, usability, and analytical depth of the dataset.

## 📅 Calendar Table

A dedicated Calendar Table was created using the **Date of Journey** column.

The Calendar Table includes:

- Year
- Month Name
- Quarter
- Year-Quarter

This enabled effective time-based analysis and supported calculations such as:

- YTD – Year-to-Date
- MTD – Month-to-Date
- Monthly trends
- Year-over-year comparisons

---

# 📈 Key Performance Indicators (KPIs)

The following KPIs were developed using DAX:

| KPI | Purpose |
|---|---|
| Total Amount | Measures overall ticket revenue |
| Total Bookings | Measures total booking volume |
| On-Time Performance (%) | Measures the percentage of journeys completed on time |
| Delay Percentage (%) | Measures the proportion of delayed journeys |
| Cancellation Rate (%) | Measures the percentage of cancelled journeys |
| MTD Bookings | Tracks bookings for the current month |

These KPIs provide a high-level view of both **financial performance and operational efficiency**. :contentReference[oaicite:1]{index=1}

---

# 🧩 Data Modelling

Relationships were created between the relevant tables to build a structured and scalable analytical data model.

## Data Model

<img width="944" height="443" alt="Railway Data Model" src="https://github.com/user-attachments/assets/4d2e19e0-63c4-4bc7-9903-ad4b25328c68" />

---

# 🔍 Exploratory Data Analysis & Visualization

The dashboard uses multiple visualizations to analyze revenue, ticket types, payment methods, journey status, destinations, departure times, and geographical travel patterns.

---

## 1️⃣ Revenue Trend Analysis

### Key Findings

**Descriptive Analytics**

- Revenue remained relatively stable between **5K–7K**.
- Several major peaks and sudden drops were observed during the analysis period.

**Diagnostic Analytics**

- Revenue fluctuations were mainly associated with booking demand, delays, cancellations, and operational issues.

**Predictive Analytics**

- Revenue is likely to remain relatively stable, with occasional peaks during high-demand travel periods.

**Prescriptive Analytics**

- Improving on-time performance and reducing cancellations can help improve revenue consistency and customer satisfaction.

---

## 2️⃣ Revenue by Ticket Class & Ticket Type

### Key Findings

- **Standard Class** generated the highest revenue.
- **Advance tickets** generated approximately **242K revenue**.
- First Class contributed comparatively lower revenue across the ticket types.

### Business Interpretation

Passengers largely preferred affordable **Standard and Advance tickets**, which offer lower prices and better availability.

### Recommendation

- Promote Advance and Off-Peak tickets.
- Improve First Class offers and promotions.
- Use targeted pricing strategies to increase overall revenue.

---

## 3️⃣ Payment Method Analysis

### Key Findings

| Payment Method | Share |
|---|---:|
| Credit Card | 60% |
| Contactless | 34% |
| Debit Card | 5% |

Credit Card payments were the most widely used, followed by Contactless payments, while Debit Card usage was relatively low.

### Recommendation

- Encourage Contactless payments through targeted offers.
- Introduce cashback or promotional incentives.
- Continue supporting convenient digital payment methods.

---

## 4️⃣ Journey Status Analysis

### Key Findings

| Journey Status | Percentage |
|---|---:|
| On Time | 86.82% |
| Delayed | 7.24% |
| Cancelled | 5.94% |

### Business Interpretation

The high on-time percentage indicates generally efficient railway operations. However, delays and cancellations remain areas for improvement.

### Recommendation

- Improve scheduling.
- Monitor operational performance closely.
- Reduce delays through better planning and maintenance.
- Develop strategies to minimize cancellations during peak periods.

---

## 5️⃣ Destination Revenue Analysis

### Key Findings

- **York** generated the highest total revenue.
- **London Euston** ranked second.
- **Birmingham New Street** also generated significant revenue.
- Several other destinations recorded considerably lower revenue.

### Business Interpretation

Major cities and travel hubs attract higher passenger volumes, resulting in greater ticket sales and revenue.

### Recommendation

- Strengthen services on high-revenue routes.
- Optimize pricing on high-demand destinations.
- Promote lower-performing destinations through discounts and marketing.
- Improve services on routes with consistently low demand.

---

## 6️⃣ Departure Time & Delay Analysis

### Key Findings

- Delay percentages varied across different departure times.
- Certain departure time slots showed higher delay percentages.
- Higher transaction volumes were observed during some periods associated with increased delays.

### Business Interpretation

Certain departure periods may experience congestion and operational pressure due to increased passenger and booking volumes.

### Recommendation

- Adjust schedules for consistently high-delay departure slots.
- Add buffer time where required.
- Improve operational coordination during peak periods.
- Monitor high-volume travel periods more closely.

---

## 7️⃣ Geographical / Map Analysis

### Key Findings

Most train journeys were concentrated around major UK cities, including:

- London
- Birmingham
- Manchester
- Leeds

Travel activity was heavily concentrated in central and southern parts of the UK, with fewer journeys observed in northern and far-west regions.

### Business Interpretation

Major cities act as important transportation and business hubs, resulting in higher passenger demand and more frequent railway services.

### Recommendation

- Strengthen capacity and connectivity between major hubs.
- Improve services on high-demand routes.
- Promote lesser-used routes through targeted marketing.
- Improve schedules and infrastructure where appropriate.

---

# 🎛️ Dashboard Features

## Filters / Slicers

Users can dynamically filter the dashboard using:

- Ticket Class
- Purchase Type
- Payment Method

This allows users to explore specific customer segments and performance categories.

## Drill-Down Capabilities

The dashboard supports deeper analysis through drill-downs such as:

- Ticket Type
- Destination
- Time-based trends

## Interactive Visualizations

The dashboard includes:

- Charts
- Maps
- Graphs
- KPI cards
- Interactive filters

These visuals allow users to explore patterns, compare performance, and identify trends dynamically. :contentReference[oaicite:2]{index=2}

---

# 📊 Final Dashboard

<img width="1782" height="804" alt="UK Railway Dashboard" src="https://github.com/user-attachments/assets/cb44edfc-442e-4b98-b9ce-e6ed8d1722db" />

---

# 💡 Key Business Insights & Recommendations

## Revenue & Route Performance

- Major destinations such as **York, London Euston, and Birmingham New Street** contribute significantly to revenue.
- Revenue is unevenly distributed across destinations.
- Advance tickets are a strong revenue contributor.

### Recommendation

Focus on high-demand routes while using targeted promotions to improve performance in lower-revenue destinations.

---

## Operational Performance

- **86.82%** of journeys were completed on time.
- **7.24%** were delayed.
- **5.94%** were cancelled.

### Recommendation

Target departure periods with higher delays and improve scheduling, maintenance, and operational coordination.

---

## Payment Behaviour

- Credit Card is the dominant payment method.
- Contactless payments represent a significant share of transactions.
- Debit Card usage is comparatively low.

### Recommendation

Use promotional offers and cashback campaigns to encourage digital and Contactless payment adoption.

---

# 🎯 SMART Business Recommendations

Based on the dashboard analysis, the following measurable targets are proposed:

### Operational Target

- Reduce the delay percentage from **7.24% to below 5%**.
- Increase on-time performance from **86.82% to 90%**.

### Revenue Target

- Increase monthly ticket revenue by at least **10% on top-performing routes**.

### Action Plan

- Implement targeted scheduling adjustments.
- Improve operational coordination.
- Strengthen high-demand routes.
- Promote Off-Peak and Anytime tickets.
- Use targeted promotions for lower-performing destinations.
- Monitor peak departure periods to reduce congestion.

### Target Timeline

- Achieve delay and service improvements within **3 months**.
- Target revenue growth within the next **financial quarter (3–4 months)**.

---

# 🚀 Future Scope

The project can be further enhanced through:

- Advanced sales forecasting.
- Predictive analysis of passenger demand.
- Customer segmentation.
- Route-level demand forecasting.
- Advanced Power BI dashboards.
- Automated reporting.
- Predictive delay analysis.
- Real-time railway performance monitoring.

---

# 🏁 Conclusion

The UK Railway Ticket Sales and Journey Performance Analysis provides valuable insights into **ticket sales, revenue, customer purchasing behavior, payment preferences, journey performance, delays, cancellations, and route-level performance**.

The analysis shows strong revenue concentration in major destinations such as **York, London Euston, Birmingham, and Manchester**. Advance tickets contribute significantly to revenue, while Credit Card payments dominate customer transactions.

Overall railway service performance is strong, with **86.82% of journeys completed on time**. However, delays and cancellations remain important areas for improvement.

By improving delay management, optimizing high-demand routes, promoting suitable ticket types, and targeting lower-performing destinations, railway operators can improve **customer satisfaction, operational efficiency, and revenue growth**.

---

## 👩‍💻 Author

**Kanimozhi G**

Aspiring Data Analyst

📍 Tamil Nadu, India
