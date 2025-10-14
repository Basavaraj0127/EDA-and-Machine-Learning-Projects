<h1 align="center">🚌 RedBus Data Analysis & Predictive Modeling</h1>

<p align="center">
    <a href="https://github.com/Basavaraj0127/EDA-and-Machine-Learning-Projects/tree/main/RedBus-Data-Analysis" title="Go to Project Repository">
        <img src="./RedBus_logo.png" width="200" alt="RedBus Logo">
    </a>
</p>

<p align="center">
    <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python Badge">
    <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas Badge">
    <img src="https://img.shields.io/badge/Machine_Learning-F7931E?style=for-the-badge&logo=tensorflow&logoColor=white" alt="ML Badge">
    <img src="https://img.shields.io/badge/EDA-F7DF1E?style=for-the-badge&logo=chartdotjs&logoColor=black" alt="EDA Badge">
</p>

<p align="center">
  <i>End-to-end Data Science Project on bus travel data inspired by RedBus</i><br>
  <b>Synthetic dataset created for demonstration purposes</b>
</p>

---

## 📘 Overview

This project demonstrates a complete **data science workflow** on bus travel data, including:

- **Exploratory Data Analysis (EDA)** to uncover travel patterns, pricing, and occupancy trends.  
- **Feature engineering** to create derived variables such as revenue per trip, seat occupancy, and weekend indicators.  
- **Predictive modeling** for ticket price and seat occupancy.  

> **Note:** The dataset is **synthetically created** to mimic real-world bus travel scenarios. It is intended for demonstration, analysis, and predictive modeling purposes only.

---

## 🧩 Dataset Overview

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

## 💡 Exploratory Data Analysis (EDA)

Key insights from the EDA include:

- Distribution of ticket prices, bus ratings, and seat occupancy.  
- Trip duration vs ticket price analysis.  
- Top 10 routes and most popular bus operators.  
- Correlation between key features for predictive modeling.  

> Plots and visualizations can be generated in the notebook for further exploration.

---

## 🔧 Feature Engineering

- `Revenue_per_Trip` – `(Total_Seats - Seats_Available) * Ticket_Price_INR`  
- `Is_Weekend` – Indicator for weekend trips  
- `Bus_Category` – Categorized as Premium or Economy  
- One-hot encoding for categorical variables for machine learning models  

---

## 📊 Predictive Modeling

### Ticket Price Prediction
- Model: Random Forest Regressor  
- MAE ≈ ₹222, R² ≈ 0.93  
- Predicts ticket prices based on distance, duration, bus type, day, and operator.

### Seat Occupancy Prediction
- Model: Random Forest Regressor  
- MAE ≈ 2.51%, R² ≈ 0.99  
- Predicts passenger demand for route planning and fleet optimization.

> Note: High accuracy is due to the **synthetic nature of the dataset**.

---

## 🏆 Key Insights

- High-demand routes: **Bangalore → Chennai**, **Mumbai → Pune**  
- Weekend travel shows higher occupancy  
- Premium buses have higher ticket prices and higher revenue per trip  
- Predictive models help in **pricing strategy, fleet optimization, and demand forecasting**

---

## 📂 Repository Structure

📁 RedBus-Data-Analysis
│
├── RedBus_Data_Analysis.ipynb

├── dataset_redbus.csv

├── RedBus_logo.png

└── README.md


---

## 🔗 References

- Project inspired by the RedBus app for bus travel in India  
- Synthetic dataset created for demonstration purposes

---

## ✨ Author

**Basavaraj Chakalabbi**  
📎 [GitHub Profile](https://github.com/Basavaraj0127)  
📂 [Project Repository](https://github.com/Basavaraj0127/EDA-and-Machine-Learning-Projects/tree/main/RedB
