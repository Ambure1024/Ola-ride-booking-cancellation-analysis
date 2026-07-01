# 🚖 Ola Ride Booking & Cancellation Analysis

An end-to-end **Data Analytics** project that analyzes OLA ride booking data to identify ride trends, booking performance, cancellation patterns, customer behavior, revenue insights, and operational efficiency using **SQL** and **Power BI**.

---

# 📌 Project Overview

Ride-booking platforms generate massive amounts of transactional data every day. Analyzing this data helps businesses understand customer behavior, improve ride completion rates, reduce cancellations, optimize fleet operations, and increase overall revenue.

This project focuses on analyzing OLA ride booking data to extract meaningful business insights through SQL queries and interactive Power BI dashboards.

---

# 🎯 Problem Statement

The objective of this project is to analyze OLA ride booking data and answer important business questions such as:

- How many rides are successfully completed?
- What are the major reasons behind ride cancellations?
- Which vehicle types are used the most?
- Which customers contribute the highest revenue?
- Which payment methods generate maximum revenue?
- How do customer and driver ratings compare?
- Which vehicle types cover the highest ride distance?

The analysis helps business stakeholders make data-driven decisions to improve customer satisfaction and operational efficiency.

---

# 🛠️ Tech Stack

| Technology | Purpose |
|------------|----------|
| SQL (MySQL) | Data Analysis |
| Power BI | Dashboard & Visualization |
| DAX | KPI Calculations |
| Microsoft Excel | Data Source |
| Power Query | Data Cleaning & Transformation |

---

# 📂 Dataset Information

The dataset contains OLA ride booking records with the following information:

- Booking ID
- Booking Date & Time
- Booking Status
- Customer ID
- Vehicle Type
- Pickup Location
- Drop Location
- Vehicle Arrival Time (VTAT)
- Customer Arrival Time (CTAT)
- Booking Value
- Ride Distance
- Payment Method
- Customer Rating
- Driver Rating
- Cancellation Reason
- Incomplete Ride Status

---

# 📊 Project Workflow

## Step 1 – Data Collection

Collected OLA ride booking data containing customer booking information, ride status, payment details, vehicle information, ratings, and cancellation records.

↓

## Step 2 – Data Cleaning & Transformation

Performed data preprocessing using Power Query:

- Checked missing values
- Removed duplicate records
- Standardized column names
- Corrected data types
- Validated booking status
- Cleaned cancellation records
- Prepared data for SQL analysis and dashboard creation

↓

## Step 3 – SQL Business Analysis

Imported the dataset into MySQL and solved business problems using SQL.

### Business Questions Solved

- Retrieve all successful bookings
- Calculate average ride distance by vehicle type
- Count customer cancellations
- Identify Top 5 customers by number of rides
- Analyze driver cancellation reasons
- Compare driver ratings for Prime Sedan rides
- Retrieve UPI payment rides
- Calculate average customer rating by vehicle type
- Calculate total successful booking revenue
- Identify incomplete rides and their reasons

Used SQL concepts including:

- SELECT
- WHERE
- GROUP BY
- ORDER BY
- Aggregate Functions
- Views
- Filtering

↓

## Step 4 – Dashboard Development

Connected SQL data with Power BI and built an interactive dashboard.

Created multiple dashboard pages for:

### Overall Analysis

- Ride Volume Over Time
- Booking Status Breakdown

### Vehicle Analysis

- Top Vehicle Types by Ride Distance

### Revenue Analysis

- Revenue by Payment Method
- Top Customers by Booking Value
- Ride Distance Distribution

### Cancellation Analysis

- Customer Cancellation Reasons
- Driver Cancellation Reasons

### Rating Analysis

- Customer Ratings
- Driver Ratings
- Customer vs Driver Rating Comparison

↓

## Step 5 – Business Insights

Analyzed booking trends and generated actionable business recommendations.

---

# 📈 Dashboard Features

✔ Ride Volume Over Time

✔ Booking Status Analysis

✔ Ride Distance Analysis

✔ Vehicle Type Performance

✔ Revenue by Payment Method

✔ Top Customers

✔ Customer Cancellation Analysis

✔ Driver Cancellation Analysis

✔ Customer Ratings

✔ Driver Ratings

✔ Interactive Filters & Slicers

---

# 📊 Key Business Insights

- Majority of rides are successfully completed.
- Customer cancellations mainly occur due to driver delays and change of plans.
- Driver cancellations are mostly caused by vehicle-related issues.
- UPI is one of the most frequently used payment methods.
- Prime Sedan and Prime SUV generate higher booking values.
- High-rated drivers generally receive better customer ratings.
- Certain vehicle categories contribute significantly higher ride distances.

---

# 💡 Business Recommendations

- Improve driver allocation to reduce waiting time.
- Monitor frequent ride cancellation patterns.
- Introduce incentives for highly rated drivers.
- Optimize vehicle availability during peak hours.
- Promote digital payment methods.
- Improve customer communication during ride allocation.

---

# 📚 Skills Demonstrated

- SQL Query Writing
- Data Cleaning
- Data Transformation
- Data Visualization
- Dashboard Development
- KPI Design
- Business Intelligence
- Exploratory Data Analysis (EDA)
- Data Storytelling

---

# 📁 Project Structure

```

Ola-Ride-Booking-Cancellation-Analysis
│
├── Dataset
│ └── ola_bookings.csv
│
├── SQL
│ └── ola_analysis_queries.sql
│
├── Dashboard
│ └── ola_dashboard.pbix
│
├── Images
│ └── dashboard-preview.png
│
├── Report
│ └── Ola_Ride_Analysis_Report.pdf
│
├── Presentation
│ └── Ola_Ride_Analysis_Presentation.pptx
│
└── README.md

```

---

# 📷 Dashboard Preview

<img width="1920" height="1156" alt="01_Overall_dashboard" src="https://github.com/user-attachments/assets/1a46f6ee-6e16-4540-a826-7bd37c3f1a85" />


Example:

```

<img width="970" height="585" alt="04_Cancellation_dashboard" src="https://github.com/user-attachments/assets/eb4b6738-a01b-4c78-b205-2fc603f1abac" />


```

---

# 🚀 How to Run the Project

## Clone Repository

```bash
git clone https://github.com/Ambure1024/Ola-Ride-Booking-Cancellation-Analysis.git
```

## Import Dataset

Import the dataset into MySQL.

## Execute SQL Queries

Run all SQL scripts available in the **SQL** folder.

## Open Power BI Dashboard

Open:

```
ola_dashboard.pbix
```

using **Power BI Desktop**.

---

# 📈 SQL Analysis Performed

- Successful Bookings
- Average Ride Distance
- Customer Cancellation Analysis
- Top Customers
- Driver Cancellation Analysis
- Driver Rating Analysis
- UPI Payment Analysis
- Customer Rating Analysis
- Revenue Analysis
- Incomplete Ride Analysis

---

# 🎯 Learning Outcomes

Through this project, I gained practical experience in:

- SQL for Business Analytics
- Data Cleaning
- Data Visualization
- Dashboard Development
- KPI Creation
- Ride Booking Analytics
- Business Intelligence
- Data Storytelling
- Analytical Problem Solving

---

# 🔮 Future Enhancements

- Real-time dashboard integration
- Ride demand forecasting using Machine Learning
- Peak-hour demand prediction
- Driver performance analytics
- Customer segmentation
- Dynamic route optimization analysis

---

# 👩‍💻 Author

**Komal Ambure**

📧 Email: komalambure40@gmail.com

💼 LinkedIn: linkedin.com/in/komal-ambure-7625b3292

🐙 GitHub: https://github.com/Ambure1024

---

## ⭐ If you found this project useful, don't forget to Star this repository!
