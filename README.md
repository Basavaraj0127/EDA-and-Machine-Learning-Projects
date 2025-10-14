<p align="center">
    <img src="https://upload.wikimedia.org/wikipedia/commons/1/16/RedBus_logo.svg" width="200" alt="RedBus Logo">
</p>

# RedBus Data Analysis & Predictive Modeling

**Project Link:** [RedBus Data Analysis on GitHub](https://github.com/Basavaraj0127/EDA-and-Machine-Learning-Projects/tree/main/RedBus-Data-Analysis)

---

## Project Overview
This project demonstrates an **end-to-end data science workflow** on a bus travel dataset inspired by RedBus. The dataset has been **synthetically created** to simulate realistic travel scenarios.  

The goal of this project is to:

- Perform **Exploratory Data Analysis (EDA)** to understand travel patterns, pricing, and seat occupancy.
- Conduct **feature engineering** to create meaningful variables.
- Build **predictive models** for ticket price and seat occupancy.
- Derive actionable insights for bus route optimization and pricing strategy.

> **Important:** The dataset is **synthetically generated** for demonstration purposes and does not contain real customer or RedBus data.

---

## Dataset Overview
The dataset contains **5000 rows** simulating bus trips across major Indian cities.

| Column Name             | Description                                                                 |
|-------------------------|-----------------------------------------------------------------------------|
| `Route_ID`              | Unique identifier for each route                                           |
| `Source_City`           | City of departure                                                          |
| `Destination_City`      | City of arrival                                                            |
| `Distance_km`           | Distance between cities in kilometers                                      |
| `Departure_Time`        | Scheduled departure time                                                   |
| `Arrival_Time`          | Scheduled arrival time                                                     |
| `Duration_min`          | Trip duration in minutes                                                   |
| `Duration_hr`           | Trip duration in hours                                                     |
| `Day_of_Week`           | Day of the week of travel                                                  |
| `Bus_Type`              | Type of bus (AC Sleeper, Non-AC Seater, etc.)                              |
| `Operator_Name`         | Name of the bus operator                                                  |
| `Seats_Available`       | Number of seats available at booking                                       |
| `Total_Seats`           | Total seats on the bus                                                     |
| `Ticket_Price_INR`      | Price of the ticket in Indian Rupees                                       |
| `Rating`                | Customer rating of bus/operator                                            |
| `Reviews_Count`         | Number of customer reviews                                                |
| `Price_per_km`          | Derived column: Ticket_Price_INR ÷ Distance_km                             |
| `Seat_Occupancy_%`      | Derived column: (Total_Seats - Seats_Available) ÷ Total_Seats × 100       |
| `Revenue_per_Trip`      | Derived column: (Total_Seats - Seats_Available) × Ticket_Price_INR        |
| `Is_Weekend`            | Derived column: 1 if trip is on Friday, Saturday, or Sunday; else 0        |
| `Bus_Category`          | Derived column: Premium (AC/Sleeper) or Economy (Non-AC/Seater)           |

---

## Exploratory Data Analysis (EDA)
The EDA includes:

- Distribution of ticket prices and ratings
- Trip duration vs ticket price analysis
- Top 10 routes and top operators analysis
- Seat occupancy trends by day of the week
- Correlation between key features

---

## Feature Engineering
- `Revenue_per_Trip` – `(Total_Seats - Seats_Available) * Ticket_Price_INR`  
- `Is_Weekend` – Indicator for weekend trips  
- `Bus_Category` – Categorized as Premium or Economy  
- One-hot encoding of categorical variables for predictive modeling  

---

## Predictive Modeling
- **Ticket Price Prediction:** MAE ≈ ₹222, R² ≈ 0.93  
- **Seat Occupancy Prediction:** MAE ≈ 2.51%, R² ≈ 0.99  

> Note: Perfectly accurate results are due to the **synthetic nature of the dataset**, which reduces real-world variability.

---

## Key Insights
- High-demand routes: **Bangalore → Chennai**, **Mumbai → Pune**  
- Weekend travel shows higher occupancy  
- Premium buses have higher ticket prices and revenue  
- Predictive models enable **pricing strategy and fleet optimization**

---

## Tools & Libraries
- Python 3.x  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  

---

## Author
[Basavaraj Chakalabbi](https://github.com/Basavaraj0127)  

---

