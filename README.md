# ✈️ TP2 — Airline Flights Data Analysis (Spark & Scala)

## 📌 **Project Overview**
This project is part of a Data Engineering / Big Data module focused on distributed data processing using **Apache Spark** and **Scala**.  
You act as a Data Analyst for an airline company analyzing the **Indian domestic flight market** using a real dataset containing flight characteristics, schedules, prices, and airline details.

The goal is to explore pricing strategies, market behavior, operational patterns, and factors influencing flight prices.

---

## 🗂️ **Dataset**
File included: **cleaned_airlines_flights_data.csv**

### **Available Columns**
- `airline` — Airline company  
- `flight` — Flight number  
- `source_city` — Departure city  
- `departure_time` — Departure time  
- `stops` — Number of stops  
- `arrival_time` — Arrival time  
- `destination_city` — Arrival city  
- `class` — Travel class  
- `Duration` — Flight duration (hours)  
- `days_left` — Days before departure  
- `price` — Ticket price (INR)

---

## 🎯 **Objectives**
- Learn and apply Spark fundamentals  
- Manipulate large datasets efficiently  
- Perform business-oriented analyses  
- Extract insights on pricing, routes, and airline competition  
- Build skills in distributed data processing  

---

## 🧪 **Analyses Implemented**
Below is the list of analyses performed in this project:

1. Average price per airline  
2. Identification of the most expensive routes  
3. Price analysis by departure time  
4. Price variation by number of stops  
5. Market share calculation based on number of flights  
6. Most popular routes (highest flight frequency)  
7. Price evolution based on reservation anticipation  
8. Correlation between duration and price  
9. Effect of stops on total flight duration  
10. Combined departure/arrival time price patterns  
11. Price segmentation into categories  
12. Best price-to-duration ratio  
13. Optimal booking windows using percentiles  
14. Duration variations by time slot  
15. Price volatility per route (relative standard deviation)  
16. In-depth analysis of connecting flights  
17. Competitive pressure on multi-airline routes  
18. Frequency distribution of flights by time and airline  
19. Temporal efficiency of airlines (duration vs price per route)  
20. Multifactor analysis of price determinants  

---

## 🛠️ **Technologies**
- **Apache Spark (Scala API)**
- **Scala 2.12+**
- **SBT / IntelliJ / spark-submit**
- **CSV data processing**

---


## ▶️ **How to Run**
1. Install Spark  
2. Place the dataset in the `data/` folder  
3. Run the Scala scripts using:
```bash
sbt run
```
---
## 📊 Output

The project generates:

Aggregated tables

Statistical metrics

Correlation indicators

Analytical insights

---
## 👤 Author

Khaoula Boughattas — Data Engineering Student @ ENET'COM

