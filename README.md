# 🚲 Cyclistic Bike-Share Analysis (January–March 2023)

## 📌 Project Overview
This project analyzes Cyclistic bike-share data to understand how **annual members** and **casual riders** use the service differently.  
The objective is to identify usage patterns and generate **data-driven insights** that can help convert casual riders into annual members.

The analysis covers data from **January to March 2023**.

---

## 🎯 Business Task
Analyze Cyclistic bike-share trip data to:
- Compare ride frequency between members and casual riders
- Compare average ride duration by user type
- Identify monthly ride trends
- Provide actionable recommendations for marketing strategy

---

## 📂 Project Structure
Cyclistic_Project:
  Data_Raw:
    - Raw CSV files (Jan–Mar 2023)

  Data_Cleaned:
    - Cleaned datasets after preprocessing

  Analysis:
    - Pivot_Jan
    - Pivot_Feb
    - Pivot_Mar
    - Summary_Jan_Feb_Mar

  Visualizations:
    - Member_vs_Casual_Rides.png
    - Average_Ride_Duration.png
    - Total_Rides_Trend.png

  Report:
    - Cyclistic_Bike_Share_Analysis_Report.pdf

  README.md

---

## 📊 Data Source
- **Dataset:** Cyclistic bike-share trip data  
- **Provider:** Motivate International Inc.  
- **Time Period:** January 2023 – March 2023  
- **File Type:** CSV  

---

## 🧹 Data Cleaning Process
The following steps were performed:
- Removed duplicate records
- Ensured all `ride_id` values were unique
- Checked and handled missing or invalid values
- Calculated `ride_length` using start and end timestamps
- Removed rides with zero or negative duration
- Added derived columns:
  - `ride_length`
  - `day_of_week`

---

## 🔍 Analysis & Key Findings

### 1️⃣ Ride Frequency by User Type
- Annual members consistently took **more rides** than casual riders.
- Casual rider usage increased from January to March but remained lower than member usage.

### 2️⃣ Average Ride Duration
- Casual riders had **longer average ride durations** than members.
- Members used bikes more frequently for shorter trips, likely commuting.
- Casual riders likely used bikes for leisure purposes.

### 3️⃣ Monthly Ride Trend
- Total rides increased steadily from January to March.
- Indicates **seasonal growth** in bike usage as weather improves.

---

## 📈 Visualizations
Created using **Google Sheets**:
- Member vs Casual Rides (Column Chart)
- Average Ride Duration by User Type (Line Chart)
- Total Monthly Ride Trend (Column Chart)

---

## 💡 Recommendations
- Convert casual riders into members by offering **discounts to frequent long-duration riders**
- Promote memberships on **weekends**, when casual usage is higher
- Increase marketing campaigns before **spring and summer** to capture seasonal demand

---

## 🛠 Tools Used
- Google Sheets – Data cleaning, pivot tables, visualizations
- Google Docs – Final report
- GitHub – Project version control and sharing

---

## ✅ Conclusion
This analysis reveals clear behavioral differences between Cyclistic members and casual riders.  
Targeted marketing strategies focused on casual riders can significantly improve annual membership conversion.

---

## 👤 Author
**Soumya Prakash Sahoo**  
Aspiring Data Analyst
