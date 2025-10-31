🚖 UrbanRide Trip Data Analysis – Power BI Dashboard
📊 Project Overview

Analyze UrbanRide trip data to gain insights on revenue, trip performance, vehicle types, surge pricing, and ratings trends.
Dataset: UrbanRide_Trip_Data.csv (trip-level data including City, Driver_ID, Fare, Distance, Duration, Vehicle Type, Rating, Date, Surge, Cancelled).

🛠 Workflow
1️⃣ Data Import

Home → Get Data → CSV → Transform Data

Load dataset into Power BI for cleaning and preparation.

2️⃣ Data Cleaning & Preparation

✅ Set data types: Date, Decimal, Text

✅ Trim & clean text columns (City, Driver_ID, Vehicle_Type, etc.)

✅ Remove duplicates (Trip_ID)

✅ Filter out cancelled trips

✅ Handle missing ratings (leave blank or handle in visuals)

✅ Filter unrealistic fares or distances

✅ Add derived columns:

Fare_per_km = Fare_Amount / Distance_km

DistanceBucket (Short/Medium/Long/Very Long)

Date parts: Month, Weekday

3️⃣ DAX Measures

Key KPIs: Total Trips, Total Revenue, Avg Fare, Avg Fare per km, Avg Rating, Total Drivers

Category Analysis: Revenue by City, Trips/Revenue with Surge

Rankings: Top Drivers, % of Total Revenue

Time Series: Revenue by Date (line chart)

4️⃣ Visualizations

KPI Overview: Card visuals for core metrics

City-level Analysis: Clustered Column Chart + Vehicle_Type Slicer

Time Trend: Line Chart (Date vs Revenue)

Performance Scatter: Distance vs Fare, colored by Vehicle_Type

Ratings by City: Stacked Column / Bar Chart

Surge Pricing: Clustered Column / Card comparison

Top Drivers: Table sorted by Revenue & Trips

Map Analysis: Filled Map showing revenue by State/City

5️⃣ Interactive Elements

Slicers: Vehicle_Type, Date, City

Tooltips: Avg Fare, Total Trips, Distance info

❓ Analysis Questions Overview

Which city generates the highest revenue?

Which vehicle type earns the highest average fare?

Does surge pricing significantly affect revenue?

Are ratings correlated with trip distance or vehicle type?

Who are the top-performing drivers?

How does revenue trend over time?

⚡ Power BI enables fast, interactive, and visually appealing data insights. This project demonstrates a complete end-to-end analytics workflow from raw data to actionable insights.
