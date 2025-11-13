# Ola-Cabs-SQL-Analytics-Dashboard

_Performed advanced SQL analysis on ride-sharing data using CTEs, Window functions, Ranking and revenue analytics to derive actionable insights on customer retention, driver performance and pricing optimization._

# Project Overview
_This project analyzes OLA CABS RIDE DATA to uncover meanningful insights about customer behaviour, revenue trends and operational efficiency.
The aim was to use SQL for data analysis and POWE BI for creating an interactive dashboard that highlights key business metrics and problem areas._

# Business Problem 
_Ola cabs wants to improve its operational performance and customer satisfaction. They need answers to key questions like:_
- Which vechile type generates the most revenue?
- Which routes are the most revenue generating?
- Which areas of pickup are in demand from earning point of view?
- What type of payment methods are more convenient for customers to use?
- What are the trends in ride volume over time?

_By solving these questions, the company can optimise driver allocation, pricing and customer retention strategies._

# Database
| Schema | Description |
|:-----------------------|--------------:|
| booking_id | INT |
| customer_id | INT |
| driver_id | INT |
| vehicle_type | TEXT |
| pickup_loaction | TEXT |
| drop_location | TEXT |
| booking_status | TEXT |
| date | DATE |
| booking_value | INT |
| ride_distance | INT |
| payment_method | TEXT |
| driver_rating | DOUBLE |
| customer_rating | DOUBLE |


# Tools & Technologies
- SQL(MYSQL): Data extraction, transformation and analysis
- POWER BI: Data Visualisation and Interactive Dashboard
- EXCEL: Version control and project showcase.

# SQL ANALYSIS
_ 1. Rank pickup loacation by total revenue and total rides_
<img width="1385" height="98" alt="image" src="https://github.com/user-attachments/assets/4b681969-3cec-476a-a230-a07fafdd9280" />



_2. Revenue trend month over month_
<img width="1087" height="238" alt="image" src="https://github.com/user-attachments/assets/0fabf766-7ca0-44b1-a1ed-21fc8b3e1772" />



_3. Revenue share by payment method._
<img width="1280" height="130" alt="image" src="https://github.com/user-attachments/assets/884b7827-33d1-4baa-aec5-05072c4bcc7e" />



_4. Find the busiest routes(most booked pickup-drop pairs_
<img width="453" height="208" alt="image" src="https://github.com/user-attachments/assets/f64c70ae-9636-4681-a043-154eaebdcaa4" />



_5. Weekday vs weekend booking patterns._
<img width="516" height="178" alt="image" src="https://github.com/user-attachments/assets/454eead1-43a4-4316-9559-bcb11f1a63e7" />


_6. Find top 3 performing vechike types by revenue._
<img width="672" height="183" alt="image" src="https://github.com/user-attachments/assets/7d9df137-1df5-4e5c-92d0-4bc2f548dfe4" />




# POWER BI DASHBOARD
_Dashboard Components:_
- Funnel chart: Tracks total rides of each day to identify total revenue per day
- Revenue KPIs: Shows revenue by month, vehicle type and payment method
- Trend chart: Displays rides and revenue over time
- Problem Areaa: Cancelled rides

# How to run this project 
-  Open MYSQL Workbench
- Import data_ola.csv
- Execute queries
- Open Ola_cabs_dashboard.pbix in Power BI Desktop
- Explore filters for city, vehicle type, and payment method

# Future Scope 
- Add predictive analysis using Python(ride cancelltion forecasting)
- Integrate real-time API data to monitor ongoing rides
- Automate report refresh in POER BI service

# About Me
_Ishika Jain_                                                                                                                                            

_Aspiring Data Analyst/ Skilled in SQL, POWER BI, EXCEL/Learning Python
Being passionate about turning data into decisions._

# Conclusion 
_This project demonstrates end-to-end analytical capability- from data extraction in SQL< to business insight generation in Power BI and storytelling through visual dashboards._

_"Numbers tell the story-visualisation makes is unforgettable."_




  
