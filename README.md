# 🚴‍♂️ Bike Rental Analysis Dashboard (Excel)

## 📌 Project Overview
This project analyzes **hourly bike rental data** using Microsoft Excel to uncover patterns in customer behavior, demand trends, and the impact of weather and time. The dashboard provides actionable insights to improve business decisions and operational efficiency.

--------------------------------------------------------------------------------------------------------------------------------------------------------------

## 🎯 Objectives
- Analyze rental demand across different hours and days  
- Understand the impact of weather conditions on rentals  
- Compare casual vs registered users  
- Identify peak demand periods  
- Provide business recommendations  

--------------------------------------------------------------------------------------------------------------------------------------------------------------

## 📊 Dashboard Preview
Link - https://github.com/radhikarathod/Bike-Rental-Data-Analysis/blob/main/Dashboard.png

--------------------------------------------------------------------------------------------------------------------------------------------------------------

## 📂 Dataset Description
The dataset contains hourly-level data with the following features:

- `dteday` → Date  
- `hr` → Hour (0–23)  
- `season` → Season (1–Spring, 2–Summer, 3–Fall, 4–Winter)  
- `holiday` → Holiday flag  
- `weekday` → Day of week  
- `weathersit` → Weather condition  
- `temp` / `atemp` → Temperature  
- `hum` → Humidity  
- `windspeed` → Wind speed  
- `casual` → Casual users  
- `registered` → Registered users  
- `cnt` → Total rentals  

--------------------------------------------------------------------------------------------------------------------------------------------------------------

## ⚙️ Data Processing (Excel)
- Cleaned and formatted raw data  
- Handled missing values  
- Created calculated columns:
  - Time Buckets (Morning, Afternoon, Evening, Night)
  - Weather Labels  
- Used **Pivot Tables** for aggregation  
- Applied **charts and slicers** for interactivity  

--------------------------------------------------------------------------------------------------------------------------------------------------------------

## 📈 Key Insights

- 🚴 Peak rentals occur during **8 AM and 5–6 PM** (commute hours)  
- 👥 **Registered users dominate** overall demand  
- 📅 Rentals are higher on **weekdays vs weekends**  
- 🌦️ Demand drops significantly during **poor weather conditions**  
- 📆 Friday shows the **highest weekly demand**  
- 🎉 Holidays have **minimal impact on rentals**  

--------------------------------------------------------------------------------------------------------------------------------------------------------------

## 🚀 Business Recommendations

- Increase focus on **subscription plans**  
- Optimize bike availability during **peak hours**  
- Introduce **weather-based promotions**  
- Launch **weekend offers** to boost demand  
- Expand operations near **offices and metro areas**  

--------------------------------------------------------------------------------------------------------------------------------------------------------------

## ⚠️ Challenges Faced

- Low correlation between some variables  
- High correlation between `temp` and `atemp`  
- Imbalance between casual and registered users  
- Required feature engineering for better insights  

--------------------------------------------------------------------------------------------------------------------------------------------------------------

## 📚 Learnings

- Importance of **feature engineering**  
- Value of **data visualization in Excel**  
- Need for **multi-variable analysis**  
- Real-world data has **complex relationships**  

--------------------------------------------------------------------------------------------------------------------------------------------------------------

## 🔮 Future Scope

- Build **demand forecasting models (ML)**  
- Implement **dynamic pricing strategies**  
- Add **location-based analysis**  
- Develop **real-time dashboards**  

--------------------------------------------------------------------------------------------------------------------------------------------------------------

## 🛠️ Tools Used

- Microsoft Excel  
  - Pivot Tables  
  - Charts & Visualizations  
  - Conditional Formatting  
  - Formulas (IFS, WEEKDAY, etc.)  

--------------------------------------------------------------------------------------------------------------------------------------------------------------

## 🧠 Conclusion

This project demonstrates how **Excel can be used for end-to-end data analysis**, from data cleaning to dashboard creation. The insights derived help improve customer understanding and business performance in a bike rental system.

