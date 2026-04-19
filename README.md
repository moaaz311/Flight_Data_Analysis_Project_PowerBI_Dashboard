# ✈️ Flight Delay Analysis Dashboard

## 📊 Project Overview
This project focuses on analyzing flight delay data using **Power BI**.  
The goal is to transform raw flight data into meaningful insights through data cleaning, modeling, and interactive dashboards.

---

## 🎯 Objectives
- Analyze flight delays and cancellations  
- Identify main causes of delays  
- Compare airline performance  
- Provide insights to improve decision-making  

---

## 🧹 Data Cleaning
The dataset was cleaned and prepared by:
- Removing duplicates  
- Handling missing values  
- Correcting data types (time, numeric fields)  
- Filtering invalid or inconsistent records  

---

## 🏗️ Data Modeling (Star Schema)
A **Star Schema** was implemented to optimize performance and analysis.

### 🔹 Fact Table
**Fact_FlightDelays**
- Arrival Delay  
- Departure Delay  
- Air Time  
- Distance  
- Carrier Delay  
- Weather Delay  
- NAS Delay  
- Security Delay  
- Late Aircraft Delay  

### 🔹 Dimension Tables
- **Dim_Carrier** → Airline information  
- **Dim_OriginAirport** → Departure airport  
- **Dim_DestAirport** → Destination airport  
- **Dim_Date** → Date and time attributes  

Relationships were created between fact and dimension tables to enable efficient filtering and aggregation.

---

## 📐 Data Model
![Data Model](./data_model.png)

---

## 📊 Key KPIs
- Average Arrival Delay  
- Average Departure Delay  
- Cancellation Rate (%)  
- Total Cancelled Flights  

---

## 📈 Dashboard Features
- Interactive filters (Airline, Date, Airport)  
- Delay trends over time  
- Airline performance comparison  
- Delay causes breakdown  

---

## 💡 Insights
- Identification of airlines with highest delays  
- Peak delay periods (seasonal trends)  
- Major causes of delays (weather, carrier, etc.)  
- High-risk airports for delays  

---

## 🛠️ Tools Used
- Power BI  
- Excel  
- Data Modeling (Star Schema)  

---

## 📦 Deliverables
- Interactive Power BI Dashboard  
- Cleaned dataset  
- Data model (Star Schema)  

---

## 🚀 How to Use
1. Open the `.pbix` file in Power BI  
2. Explore the dashboard using filters  
3. Analyze trends and insights  

---

## 📌 Conclusion
This project demonstrates a complete data analysis workflow:
**Data Cleaning → Data Modeling → Data Visualization → Insights**

---

## 👤 Author
**Moaz Asharf**  
Data Analyst | Power BI Developer  