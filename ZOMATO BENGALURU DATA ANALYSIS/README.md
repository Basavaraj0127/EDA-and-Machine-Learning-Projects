<h1 align="center">🍽️ Zomato Bengaluru Data Analysis</h1>

<p align="center">
  <img src="https://raw.githubusercontent.com/Basavaraj0127/EDA-and-Machine-Learning-Projects/main/ZOMATO%20BENGALURU%20DATA%20ANALYSIS/plots/banner.png" 
       alt="Zomato Bengaluru Banner" 
       width="400">
</p>




<p align="center">
    <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python Badge">
    <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas Badge">
    <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy Badge">
    <img src="https://img.shields.io/badge/Matplotlib-E34F26?style=for-the-badge&logo=matplotlib&logoColor=white" alt="Matplotlib Badge">
    <img src="https://img.shields.io/badge/Seaborn-4B8BBE?style=for-the-badge&logo=seaborn&logoColor=white" alt="Seaborn Badge">
    <img src="https://img.shields.io/badge/EDA-F7DF1E?style=for-the-badge&logo=chartdotjs&logoColor=black" alt="EDA Badge">
</p>

<p align="center">
  <i>End-to-end Data Analysis Project on Bengaluru's restaurant ecosystem using Zomato data</i>
</p>

---

## 📖 Table of Contents
1. [Problem Statement](#-problem-statement)  
2. [Project Overview](#-project-overview)  
3. [Objectives](#-objectives)  
4. [Analysis & Insights](#-analysis--insights)  
5. [Key Takeaways](#-key-takeaways)  
6. [Top Recommendations](#-top-recommendations-for-new-restaurants-in-bengaluru)  
7. [Tools Used](#-tools-used)  
8. [Author & GitHub](#-author--github)  

---

## 🚩 Problem Statement
The rapid expansion of the food industry in Bengaluru has led to an overwhelming number of dining options for customers. With thousands of restaurants offering diverse cuisines, it has become increasingly challenging for new entrants to stand out and for customers to make informed choices. While demand continues to grow, so does competition — making data-driven insights more crucial than ever.

---

## 📊 Project Overview
This project explores Bengaluru’s restaurant ecosystem using Zomato data. Through data cleaning, visualization, and analysis in Python, we uncover how cost, cuisine, and facilities influence customer satisfaction and business success.

---

## 🎯 Objectives
- Identify patterns in restaurant performance across Bengaluru.
- Analyze customer ratings, pricing, and service impact.
- Discover which cuisines and dishes drive the highest satisfaction.
- Provide strategic insights for new restaurant ventures.

---

## 📈 Analysis & Insights

### 1️⃣ Geographic Distribution of Restaurants in Bengaluru
[![Geographic Distribution](plots/Geographic%20Distribution%20of%20Restaurants%20in%20Bengaluru.png)](plots/Geographic%20Distribution%20of%20Restaurants%20in%20Bengaluru.png)  
**Insights:**  
- Top 5 locations (Koramangala, Indiranagar, etc.) have dense restaurant presence.  
- Bottom 5 areas show market gaps — good opportunity for new entrants.  

### 2️⃣ Various Types of Restaurants
[![Restaurant Types](plots/Various%20Types%20of%20Restaurant%20we%20have%20in%20Bangalore.png)](plots/Various%20Types%20of%20Restaurant%20we%20have%20in%20Bangalore.png)  
**Insights:**  
- Casual Dining dominates (~7,400 outlets).  
- Bars and Dessert Parlors serve niche audiences.  

### 3️⃣ Average Customer Ratings Across Restaurant Types
[![Avg Ratings](plots/Average%20Customer%20Ratings%20Across%20Restaurant%20Types.png)](plots/Average%20Customer%20Ratings%20Across%20Restaurant%20Types.png)  
**Insights:**  
- Casual Dining Bars highest rating (>4.0).  
- Quick Bites and Delivery lower (~3.5–3.6).  

### 4️⃣ Customer Ratings Skewed Towards Positive Reviews
[![Rating Distribution](plots/Customer%20Ratings%20Skewed%20Towards%20Positive%20Reviews%20in%20Zomato%20Dataset.png)](plots/Customer%20Ratings%20Skewed%20Towards%20Positive%20Reviews%20in%20Zomato%20Dataset.png)  
**Insights:**  
- 33% of ratings between 4–5.  
- Only ~6% below 1 — mostly positive reviews.  

### 5️⃣ Cost vs Rating
[![Cost vs Rating](plots/Cost%20vs%20Rating.png)](plots/Cost%20vs%20Rating.png)  
**Insights:**  
- High-rated restaurants cost ₹200–₹1000 for two.  
- Expensive restaurants (>₹3000) don’t guarantee higher ratings.  

### 6️⃣ Analysing Cuisine and Dish Popularity
[![Cuisine Popularity](plots/Analysing%20Cuisine%20and%20Dish%20Popularity.png)](plots/Analysing%20Cuisine%20and%20Dish%20Popularity.png)  
**Insights:**  
- Biryani is most loved.  
- Fried Rice, Paneer Butter Masala popular.  
- International dishes like Pasta, Burgers trending.  

### 7️⃣ Top Rated Restaurants from Each Area
[![Top Rated](plots/The%20Top%20rated%20restaurants%20from%20each%20Area.png)](plots/The%20Top%20rated%20restaurants%20from%20each%20Area.png)  
**Insights:**  
- Top-rated restaurants: 4.3–4.9.  
- Local favorites dominate each neighborhood.  

### 8️⃣ Best Choice of Restaurant for Different Cuisine
[![Best Choice](plots/Best%20choice%20of%20the%20Restaurant%20for%20different%20Cuisine%20in%20Banagalore.png)](plots/Best%20choice%20of%20the%20Restaurant%20for%20different%20Cuisine%20in%20Banagalore.png)  
**Insights:**  
- Belgian Waffle Factory, Milano Ice Cream top desserts.  
- Punjab Grill dominates North Indian cuisine.  

### 9️⃣ Most Liked Dish by Restaurant Type
[![Most Liked Dish](plots/Most%20Liked%20Dish%20by%20Restaurant%20Type.png)](plots/Most%20Liked%20Dish%20by%20Restaurant%20Type.png)  
**Insights:**  
- Biryani dominates Quick Bites and Casual Dining.  
- Dessert Parlors specialize in Waffles.  

### 🔟 Location Wise Cost
[![Location Cost](plots/Location%20wise%20cost.png)](plots/Location%20wise%20cost.png)  
**Insights:**  
- Brigade Road & Church Street costliest (>₹1400).  
- HSR, Old Airport Road affordable (~₹600).  

### 11️⃣ Dish Liked with Type and Cost for Two
[![Dish Type Cost](plots/Dish%20liked%20with%20type%20and%20cost_for_two.png)](plots/Dish%20liked%20with%20type%20and%20cost_for_two.png)  
**Insights:**  
- Casual Dining leads offline category.  
- Dessert Parlors & Delivery rely on online orders.  

### 12️⃣ Do Restaurants with Table Booking Have Better Ratings?
[![Table Booking](plots/Do%20restaurants%20with%20table%20booking%20have%20better%20ratings.png)](plots/Do%20restaurants%20with%20table%20booking%20have%20better%20ratings.png)  
**Insights:**  
- Restaurants with booking have higher median ratings.  

### 13️⃣ Which Restaurant Has the Best Rating per Rupee Spent?
[![Best Value](plots/Which%20restaurant%20has%20the%20best%20rating%20per%20rupee%20spent.png)](plots/Which%20restaurant%20has%20the%20best%20rating%20per%20rupee%20spent.png)  
**Insights:**  
- Srinidhi Sagar tops “rating per rupee.”  
- Brahmin’s Coffee Bar & Taaza Thindi: high value at low cost.  

### 14️⃣ Are Higher-Rated Restaurants More Likely to Accept Online Orders?
[![Online Orders](plots/Are%20higher-rated%20restaurants%20more%20likely%20to%20accept%20online%20orders.png)](plots/Are%20higher-rated%20restaurants%20more%20likely%20to%20accept%20online%20orders.png)  
**Insights:**  
- Online-ordering restaurants show more rating variability.  
- Non-online-ordering have slightly higher median ratings.  

---

## 📚 Key Takeaways
- Affordable restaurants achieve strong ratings — cost isn’t everything.  
- Digital convenience (bookings & online orders) improves satisfaction.  
- Popular items like Biryani, Pasta, and Burgers dominate menus.  
- Choosing less saturated localities offers competitive advantage.  

---

## 📌 Top Recommendations for New Restaurants in Bengaluru

| Recommendation Area | Insights | Suggested Action |
|--------------------|----------|----------------|
| **Location** | Koramangala & Indiranagar dense; HSR & Old Airport Road affordable | Consider opening in under-served areas |
| **Cuisine Type** | Biryani, North Indian, Desserts most popular | Focus on popular cuisines or unique desserts |
| **Restaurant Type** | Casual Dining dominates; Bars & Dessert Parlors niche | Explore Casual Dining for mass appeal or niche concepts |
| **Cost Range** | ₹200–₹1000 offers best value | Maintain moderate pricing for better ratings |
| **Digital Features** | Table booking increases ratings; online ordering shows variability | Offer table booking and online ordering |
| **Value Metrics** | High rating per rupee seen in budget-friendly outlets | Deliver high-quality experience at reasonable prices |

---

## 🛠️ Tools Used
- Python (Pandas, NumPy, Matplotlib, Seaborn)  
- Jupyter Notebook  
- PowerPoint (for storytelling and visualization)  

---

⭐ **Author:** Basavaraj Chakalabbi  
🌐 **GitHub Profile:** [https://github.com/Basavaraj0127](https://github.com/Basavaraj0127)  
📂 **Project Repository:** [Zomato Bengaluru Data Analysis Files](https://github.com/Basavaraj0127/EDA-and-Machine-Learning-Projects/tree/main/ZOMATO%20BENGALURU%20DATA%20ANALYSIS)
