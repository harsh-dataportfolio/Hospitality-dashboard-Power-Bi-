# 🏨 AtliQ Grand Hotels Dashboard  

This project presents an **interactive Power BI dashboard** designed to analyze the performance of AtliQ Grands hotels across multiple cities in India.

---

## 📌 Project Overview  
AtliQ Grands, a leading chain of five-star hotels across India, has been facing challenges in retaining its market share and revenue in the luxury and business hotel segments. To counter this, the company decided to leverage **Business and Data Intelligence** for strategic decision-making.  

This project involves building an **interactive dashboard** that visualizes key hotel performance metrics such as **Revenue, ADR(Average Daily Rent), RevPAR(Revenue Per Available Room), Occupancy%, Realisation %, and customer ratings**, enabling AtliQ Grands to monitor trends, identify problem areas, and take data-driven actions.  

---

## 🎯 Objectives  
- Develop a performance monitoring dashboard for AtliQ Grands.  
- Provide actionable insights on **Revenue, Occupancy, ADR, RevPAR, and Realisation %**.  
- Identify **city-level performance trends** to highlight growth opportunities.  
- Recommend strategies for **improving customer satisfaction, revenue realization, and occupancy rates**.  

---

## 📂 Dataset Used  
The dataset is sourced from **[Codebasics.io](https://codebasics.io/)** and consists of A Metrics List File and **5 CSV files**:  

1. **dim_date** – Contains details of dates, weeks, and day type (Weekday/Weekend).  
2. **dim_hotels** – Provides hotel details (ID, Name, City, Category).  
3. **dim_rooms** – Contains room details (Room Type, Room Class).  
4. **fact_aggregated_bookings** – Aggregated bookings at hotel-room level, with capacity and successful bookings.  
5. **fact_bookings** – Detailed customer-level booking transactions, including booking status, platform, ratings, and revenue.  

---

## 🛠 Tools & Technologies Used  
- **Power BI** → Dashboard creation & visualization  
- **Power Query** → Data cleaning & transformation  
- **DAX (Data Analysis Expressions)** → Custom calculations & measures(ADR, RevPAR etc.)

---

## 📊 Key Insights  
1. **Overall Performance**  
   - Mumbai properties stand out as the top performers across KPI's like revenue, RevPAR, occupancy, ADR, DSRN, realization, and cancellations. They also hold the highest customer rating (~4.3). However, with a low rating of (~2.3) also present, there is an opportunity to Improve guest experience to further strengthen Mumbai’s leadership position.
     
2. **Revenue Distribution**  
   - Business category hotels contribute ~62% of total revenue, while Luxury accounts for ~38%.  
   - Mumbai properties generate the **highest revenue of more than 660M** among all cities.
   - Hyderabad properties generate the **lowest revenue of 35.6M** among all cities.

3. **Occupancy & Realisation %**  
   - Average **Occupancy Rate**: ~58% (needs improvement).  
   - **Realisation %** is stable around ~70%.
   - **Cancellation %** is also around ~25% across all cities.

4. **Booking Platforms**  
   - Direct Offline bookings had a good **ADR of 12,794** as compared to other online platforms but the Realisation %(which is 70%) needs improvement. 
   - Online platforms like **Tripster & Journey** provide consistent booking flows.  

5. **Customer Ratings**  
   - Mumbai shows the widest performnce gap: **highest average rating (~4.32)** as well as the **lowest average rating (~2.30)**.
   - Improving the lower-rated properties could uplift Mumbai's Overall market image and competitiveness.

---

## 💡 Recommendations  
- **Improve Occupancy** by running targeted campaigns in underperforming cities like Mumbai.  
- **Enhance Guest Experience** in low-rated hotels to improve ratings and repeat bookings.  
- **Leverage Direct Bookings** by offering discounts/loyalty programs, which helps in ensuring higher ADR and revenue realization.  
- **A Dynamic Pricing Strategy** to optimize ADR and RevPAR across weekdays and weekends.  
- **Focus on Business Hotels** since they contribute the majority of revenue, expand premium services to capture luxury travelers as well.  

---

## 📸 Dashboard Screenshots  

### 1️⃣ Overall Performance Dashboard  
![Dashboard 1](Dashboard%20Ss%201.png)  

### 2️⃣ City-Level Analysis (Mumbai Example)  
![Dashboard 2](Dashboard%20Ss%202.png)  

### 3️⃣ Monthly Breakdown (May Example)  
![Dashboard 3](Dashboard%20Ss%203.png)  
