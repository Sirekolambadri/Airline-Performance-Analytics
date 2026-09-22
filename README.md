✈️ Airline Performance Analytics – Power BI

📌 Project Overview

Airline Performance Analytics is an interactive Power BI dashboard designed
to analyze Indian domestic airline performance for the period 2024–2025.

The dashboard provides insights into flights, passengers, revenue, load factor,
routes, delays, cancellations, and performance trends.

🎯 Business Objective

The main objective of this project is to understand airline operational
performance and identify areas for improvement.

The project focuses on:

- Understanding overall airline operational performance
- Comparing airline performance using key KPIs
- Identifying important airports and high-volume routes
- Analyzing major delay and cancellation reasons
- Tracking flight, passenger, and revenue trends over time

📊 Dataset

- Records:5,000 synthetic flight records
- Period: 2024–2025
- Type: Synthetic airline flight dataset
- Geography: Indian domestic airlines
- Time Zone: IST
- Currency: INR
- Columns: 25

 Key Dataset Fields

- Flight ID
- Date
- Airline
- Origin
- Destination
- Flight Times
- Passenger Count
- Available Seats
- Load Factor
- Delays
- Flight Status
- Delay / Cancellation Reason
- Ticket Price
- Revenue

 🛠️ Tools & Technologies

- Power BI
- Power Query
- DAX
- CSV Dataset

🔄 Data Preparation

The dataset was imported into Power BI through Power Query.

The following preparation steps were performed:

1. Checked and corrected data types
2. Retained meaningful blanks where logical
3. Removed duplicate flight data
4. Created a dedicated DateTable using DAX
5. Created a relationship between the DateTable and flight data
6. Sorted month and weekday fields correctly

 🧮 DAX Measures

The dashboard includes the following major measures:

- Total Flights
- Total Passengers
- Total Revenue
- Average Load Factor
- On-Time Flights
- On-Time %
- Delayed Flights
- Cancelled Flights
- Cancellation %

A calculated Route column was also created using:

`Origin City → Destination City`

📈 Dashboard Sections

1. Executive Overview

Provides a high-level view of:

- Flights
- Passengers
- Revenue
- Load Factor
- On-Time %
- Flight Status
- Airline Comparison

2. Airline Performance

Analyzes:

- Revenue by airline
- Load factor by airline
- On-time percentage by airline
- Passenger volume by airline

3. Airport & Route Analysis

Analyzes:

- Flights by origin airport
- Flights by destination airport
- Top routes by flight count
- Top routes by revenue

4. Delay & Cancellation Analysis

Analyzes:

- Delayed flights
- Cancelled flights
- Delay reasons
- Cancellation reasons
- Airline delay performance
- On-time performance against an 85% target

 5. Trend Analysis

Tracks:

- Monthly flight trends
- Monthly passenger trends
- Monthly revenue trends
- Flight status distribution over time

🎛️ Interactive Filters

The dashboard includes interactive slicers for:

- Airline
- Year
- Flight Status
- Aircraft Model

These filters allow users to interact with the dashboard and analyze
specific parts of the airline data.

 💡 Business Value

The dashboard can be used to:

- Monitor airline operational performance
- Identify delay and cancellation problem areas
- Analyze airport and route performance
- Compare airline performance
- Track flights, passengers, and revenue trends
- Support data-driven decision-making

 
