# 🚗 Ride Sharing Analytics – Power BI Web

## 📌 Project Overview
This project analyzes ride-sharing trip data (500+ rides) to uncover patterns in:
- Demand by time of day
- Route profitability
- Driver performance
- Customer satisfaction and tipping behavior

The report was built using **Power BI Web** (Mac-friendly) and published as an interactive dashboard.

---

## 🧩 Dataset
**File:** `RideSharing_Dataset.csv`  
**Rows:** ~500 trips  
**Key columns:**
- Pickup_Location, Drop_Location
- Distance_km, Trip_Time_min
- Fare, Tip, Payment_Method
- Rating, Time_of_Day, Date

I also created:
- `Route` column → `Pickup → Drop`
- Measures like `Total Revenue`, `Revenue per KM`,
  `Best Time of Day`, and `Top Route by Revenue`.

---

## 📊 Report Pages

1. **Overview Dashboard**
   - Total Trips, Total Revenue, Avg Fare, Avg Rating
   - Trips by Time of Day
   - Payment Method breakdown

2. **Demand Patterns**
   - Trips over time (line chart)
   - Heatmap of Pickup Location × Time of Day
   - Top Drop Locations

3. **Driver Performance**
   - Revenue by Driver
   - Rating vs Revenue (scatter)
   - Driver performance summary table

4. **Customer Behavior**
   - Fare vs Distance correlation
   - Fare vs Rating scatter
   - Average Tip by Payment Method
   - Rating distribution

5. **Profitability**
   - Top Routes by Revenue (`Pickup → Drop`)
   - Revenue by Time of Day
   - Revenue per KM (efficiency)
   - Revenue vs Rating trend

6. **Summary & Insights**
   - Business insights and conclusions
   - Best time of day (by trips & revenue)
   - Most profitable routes and behaviors

---

## 🔍 Key Insights (Example – update with your real numbers)
- Evening / Night shows the highest ride demand.
- Routes like **Airport → Downtown** generate the most revenue.
- **Card/Wallet** payments have higher average tips than cash.
- Higher-rated drivers (⭐ > 4.5) tend to earn more revenue.
- Fare is strongly correlated with distance, suggesting consistent pricing.

---

## 🛠 Tech Stack
- Power BI Web (Semantic Model, DAX)
- DAX Measures & Calculated Columns
- Data Modeling & Visualization
- CSV-based dataset

---

## 📁 Contents
- `RideSharing_Dataset.csv` – source data
- (Optional) Screenshots of dashboards
- This README documenting the analysis

---

## ✅ What this project shows (for recruiters)
- Ability to clean, model, and analyze data
- Build interactive dashboards in Power BI Web
- Use DAX to extract business insights
- Communicate findings clearly to stakeholders
