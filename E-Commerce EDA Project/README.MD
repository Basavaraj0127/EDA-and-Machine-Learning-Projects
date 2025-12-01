<!-- Optional Banner: put a banner image named banner.png in repo or link to external URL -->
<p align="center">
  <img src="./banner.png" alt="Project Banner" width="100%" />
</p>

# 📦 E-Commerce Data Analysis (EDA)  
### 🔍 Comprehensive Sales, Profit & Customer Insights using Python

[![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python&logoColor=white)]()  
[![Pandas](https://img.shields.io/badge/Pandas-1.5-green?logo=pandas&logoColor=white)]()  
[![NumPy](https://img.shields.io/badge/NumPy-1.24-yellow?logo=numpy&logoColor=black)]()  
[![Matplotlib](https://img.shields.io/badge/Matplotlib-3.7-orange?logo=matplotlib&logoColor=white)]()  
[![Seaborn](https://img.shields.io/badge/Seaborn-0.13-purple?logo=seaborn&logoColor=white)]()  
[![Plotly](https://img.shields.io/badge/Plotly-5.14-blue?logo=plotly&logoColor=white)]()  
[![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter&logoColor=white)]()  

This project performs an in-depth **Exploratory Data Analysis (EDA)** on a real-world **E-Commerce Superstore Dataset**.  
The goal is to uncover **sales trends**, **profit patterns**, **customer behavior**, and **regional performance** to support data-driven decisions.

---

## 📁 Project Repository  
[E-Commerce EDA Project on GitHub](https://github.com/Basavaraj0127/EDA-and-Machine-Learning-Projects/tree/main/E-Commerce%20EDA%20Project)

---

## 📁 Project Overview  
This analysis explores:

- Regional, state & city-wise sales and profit performance  
- Category & sub-category profitability  
- Monthly & yearly sales trends  
- Customer segment performance  
- Impact of shipping mode & order priority  

Tools used: **Python, Pandas, NumPy, Seaborn/Matplotlib, Plotly, Jupyter Notebook**

---

## 🗂 Dataset Information  
**File:** `Superstore Dataset.csv`  
**Key Columns:**  
- Order Details → Order ID, Order Date, Ship Date, Ship Mode  
- Customer Info → Customer Name, Segment  
- Product Data → Category, Sub-Category, Product Name  
- Geography → Country, State, City, Region  
- Metrics → Sales, Quantity, Discount, Profit  

**Feature Engineering:**  
- `Order_Year`  
- `Order_Month`  
- `Sales_to_Profit_Ratio`

---

## 📊 Analysis Performed  

### 1️⃣ Monthly Sales & Profit Trend  
- Identified peak business months  
- Found months with high sales but low profit due to discounting  

### 2️⃣ Year-over-Year Growth  
- Sales increased YoY  
- Profit fluctuated due to rising costs/discounts  

### 3️⃣ Regional, State & City Insights  
- **Top regions:** West & East  
- **Top states:** California, Washington, New York  
- Certain cities showed repeated losses  

### 4️⃣ Category & Sub-category Performance  
- Best Category → **Technology**  
- Worst Sub-category → **Tables (negative profit)**  

### 5️⃣ Customer Segment Analysis  
- Largest revenue segment → **Consumer**  
- Corporate also provides stable profit  

### 6️⃣ Shipping & Priority Insights  
- Standard Class = most used shipping mode  
- Faster modes cost more but boost satisfaction  

### 7️⃣ Sales-to-Profit Ratio  
Helps detect:  
- High-profit low-sales items  
- High-sales low-margin items  

---

## 🧾 Key Business Insights

✔ **Top Categories:** Technology (Phones, Accessories)  
✔ **Worst Performer:** Tables → High sales, negative profit  
✔ **Top Regions:** West, East  
✔ **Growth:** Sales increasing yearly  
✔ **Recommendation:** Revisit discounting & supply chain efficiency  
✔ **Customer Insight:** Consumers = largest, most profitable segment  

---

## 🛠 Tech Stack  
- Python  
- Pandas  
- NumPy  
- Matplotlib / Seaborn / Plotly  
- Jupyter Notebook  

---

## 📘 How to Run the Project  

```bash
# Clone the repository
git clone <your-repo-url>

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter Notebook
jupyter notebook

