# 🚖 Ride Operations and Performance Analysis

An end-to-end **Data Analytics & Business Intelligence project** focused on analyzing ride-hailing operations using **SQL** and **Power BI**. This project simulates real-world OLA ride data and delivers actionable insights on bookings, revenue, cancellations, vehicle performance, and ratings.

---

## 📌 Project Overview

The objective of this project is to analyze ride operations and performance metrics to help business stakeholders:

* Understand booking trends and ride volume
* Identify cancellation patterns and root causes
* Analyze revenue streams and payment methods
* Compare vehicle-type performance
* Evaluate driver and customer ratings

The project uses **1 month of simulated ride data** (July 2024) for Bengaluru city.

---

## 🛠️ Tech Stack

* **SQL** – Data querying & analysis
* **Power BI** – Interactive dashboards & visualization
* **Excel / CSV** – Data storage & preprocessing

---

## 📊 Dashboards & Analysis Sections

### 1️⃣ Overall Analysis

* Total Bookings
* Total Booking Value
* Booking Status Breakdown (Success / Cancellations)
* Ride Volume Over Time
* <img width="1335" height="741" alt="Screenshot 2025-12-18 015453" src="https://github.com/user-attachments/assets/3ccf9a17-8669-4539-8210-9d7edc2f6bb8" />


### 2️⃣ Vehicle Type Analysis

* Total & Successful Booking Value per Vehicle Type
* Average Distance Travelled
* Total Distance Covered
* <img width="1327" height="737" alt="Screenshot 2025-12-18 015528" src="https://github.com/user-attachments/assets/e7d22c03-d28b-422b-a6b3-9f473f87d110" />


Vehicle Types:

* Prime Sedan
* Prime SUV
* Prime Plus
* Mini
* Auto
* Bike
* E-Bike

### 3️⃣ Revenue Analysis

* Revenue by Payment Method (Cash, UPI, Credit Card, Debit Card)
* Top 5 Customers by Booking Value
* Ride Distance Distribution per Day
* <img width="1331" height="743" alt="Screenshot 2025-12-18 015558" src="https://github.com/user-attachments/assets/0b7061b7-2436-4078-b980-ab106b005967" />


### 4️⃣ Cancellation Analysis

* Cancelled Rides by Customers (Reasons)
* Cancelled Rides by Drivers (Reasons)
* Cancellation Rate
* <img width="1325" height="739" alt="Screenshot 2025-12-18 015748" src="https://github.com/user-attachments/assets/77914ad8-a1e7-4f46-9c72-ba830d3605ca" />


### 5️⃣ Ratings Analysis

* Driver Ratings by Vehicle Type
* Customer Ratings by Vehicle Type
* <img width="1331" height="739" alt="Screenshot 2025-12-18 015856" src="https://github.com/user-attachments/assets/dac52773-e919-4fe0-b6e6-3f711908afef" />


---

## 📈 Key Metrics Tracked

* Total Bookings
* Successful Bookings
* Cancelled Bookings
* Cancellation Rate
* Booking Value
* Ride Distance
* Driver Ratings
* Customer Ratings

---

## 🗂️ Dataset Details

**Total Rows:** 100,000 (Simulated)

### Columns:

1. Date
2. Time
3. Booking_ID
4. Booking_Status
5. Customer_ID
6. Vehicle_Type
7. Pickup_Location
8. Drop_Location
9. V_TAT (Vehicle Arrival Time)
10. C_TAT (Customer Arrival Time)
11. Cancelled_Rides_by_Customer
12. Cancelled_Rides_by_Driver
13. Incomplete_Rides
14. Incomplete_Rides_Reason
15. Booking_Value
16. Payment_Method
17. Ride_Distance
18. Driver_Ratings
19. Customer_Rating

### Data Constraints:

* ✅ Success Rate ≈ **62%**
* ❌ Customer Cancellations ≤ **7%**
* ❌ Driver Cancellations ≤ **18%**
* ❌ Incomplete Rides ≤ **6%**
* 📈 Higher demand on weekends & match days
* 💰 Higher order value on weekends

---

## 🧮 SQL Analysis

Key SQL queries include:

* Retrieve successful bookings
* Average ride distance per vehicle type
* Total cancelled rides by customers
* Top 5 customers by number of rides
* Driver cancellations due to personal/car issues
* Max & Min driver ratings (Prime Sedan)
* UPI payment bookings
* Average customer rating per vehicle type
* Total successful booking value
* Incomplete rides with reasons

SQL Views were created for each analysis to improve readability and reusability.

---

## 📊 Power BI Visuals

* Line Chart: Ride Volume Over Time
* Pie Chart: Booking Status Breakdown
* Bar Charts: Vehicle Performance & Revenue
* Leaderboard: Top Customers
* Distribution Charts: Ride Distance & Ratings

The dashboard is fully interactive with **date slicers** and **category filters**.

---

## 📷 Dashboard Preview

> Screenshots included in the repository showcase:

* Overall Dashboard
* Vehicle Type Dashboard
* Revenue Dashboard
* Cancellation Dashboard
* Ratings Dashboard

---

## 🚀 Key Insights

* Majority of rides are **successfully completed (62%)**
* **Cash & UPI** dominate payment methods
* **Prime & Mini** vehicles contribute significantly to revenue
* Most cancellations occur due to **driver-related issues**
* Ratings across vehicle types are consistently around **4.0**



