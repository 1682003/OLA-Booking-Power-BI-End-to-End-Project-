# OLA-Booking-Power-BI-End-to-End-Project-
End-to-end data analytics project using SQL and Power BI with booking data.


# End-to-End Data Analytics Project: Ride Booking Analysis (SQL + Power BI)
This project demonstrates a complete end-to-end data analytics workflow:
data extraction, cleaning, SQL view creation, and interactive dashboard
development in Power BI.

---

#🚀 Project Workflow

1. 🗂️ Data Source
Synthetic ride booking data was generated containing:
- Booking ID
- Vehicle Type
- Pickup/Drop Location
- Ride Distance
- Fare
- Payment Type
- Booking Status (Success/Cancelled)
- Timestamps

---

2. 🧹 Data Cleaning & SQL Processing

All preprocessing was performed using SQL.

Key steps:
- Removed inconsistent and missing values
- Standardized categorical fields
- Converted timestamps into proper datetime formats
- Created analytical SQL views

 ✔ Example SQL Views Used
- `Successful_Bookings`: filters all successful ride records  
- `ride_distance_for_each_vehicle`: average distance by vehicle type  
- `cancelled_rides_by_customers`: total customer cancellations  

All SQL files are available inside the SQL folder.

---

 3. 📊 Power BI Dashboard

An interactive dashboard was created using the cleaned dataset.

 Dashboard Highlights:
- Booking success vs cancellations
- Demand trends over time
- Average ride distance by vehicle type
- Customer behaviour insights
- Revenue and fare trends

Screenshots are available in the **Images** folder.

---

 4. 📁 Repository Structure
SQL/               -> All SQL scripts (cleaning, views, transformations)
Data/              -> Raw and cleaned datasets
PowerBI/           -> PBIX dashboard file
Images/            -> Dashboard screenshots
README.md          -> Documentation


---
5. 📥 How to Use
1. Download the project or clone the repository.
2. Open the SQL scripts from the `/SQL` folder.
3. Load the cleaned dataset into Power BI.
4. Open `PowerBI/Ola_Booking_Dashboard.pbix` to explore the dashboard.

6. 📌Tools Used
- SQL
- Power BI Desktop
- Excel / CSV
- DAX (Basic)
- Data Modeling

7. ⭐ Key Learnings
- Designing an end-to-end analytics flow  
- Writing optimized SQL queries and views  
- Building interactive dashboards  
- Turning raw data into actionable insights  

This project is ideal for Data Analyst roles and showcases:
- SQL proficiency  
- Problem-solving  
- Dashboard building  
- Real-world analytics flow  



