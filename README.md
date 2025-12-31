# 🍽️ Zomato Bangalore Restaurant EDA
<img width="1280" height="720" alt="zomato_pic" src="https://github.com/user-attachments/assets/edc76ef6-eee1-4f88-9818-8fe929a9bcf5" />

## 📌 Project Overview
This project performs **Exploratory Data Analysis (EDA)** on the **Zomato Bangalore restaurant dataset** to uncover insights related to restaurant locations, cuisines, ratings, pricing, and customer preferences.  
The goal is to understand food trends in Bangalore and support **data-driven decision making** in the restaurant industry.

The analysis is implemented in a Jupyter Notebook using Python and popular data analysis libraries.

---

## 🎯 Objectives
- Identify locations with the highest number of restaurants  
- Analyze the **Top 10 most popular cuisines** in Bangalore  
- Compare **Online Orders vs Table Booking** trends  
- Study **rating distribution across different cost categories**  
- Detect restaurants with **high votes but low ratings**  
- Locate **top low-cost, high-rated restaurants** using map-based analysis  

---

## 📂 Dataset Information
- **Source:** Zomato Bangalore Restaurants Dataset  
- **Records:** Restaurants listed in Bangalore  

### Key Columns
- `name` – Restaurant name  
- `location` – Area in Bangalore  
- `cuisines` – Types of cuisines served  
- `rate` – Restaurant rating  
- `votes` – Number of user votes  
- `approx_cost(for two people)` – Average cost for two  
- `online_order` – Online ordering availability  
- `book_table` – Table booking availability  
- `rest_type` – Type of restaurant  

---

## 🛠️ Tools & Technologies Used
- **Python**
- **Jupyter Notebook**

### Libraries
- **Pandas** – Data manipulation  
- **NumPy** – Numerical operations  
- **Matplotlib** – Data visualization  
- **Folium** – Map-based visualization  

---

## 🔄 Project Workflow

### 1️⃣ Data Loading
- Import dataset
- Inspect structure and data types

### 2️⃣ Data Cleaning
- Handle missing values  
- Convert rating and cost columns to numeric format  
- Remove duplicates and irrelevant columns  

### 3️⃣ Exploratory Data Analysis (EDA)
- Location-wise restaurant distribution  
- Top 10 cuisines analysis  
- Online orders vs table booking comparison  
- Rating distribution by cost category  
- High votes but low ratings analysis  
- Low-cost, high-rated restaurants identification  

### 4️⃣ Data Visualization
- Bar charts for location and cuisine distribution  
- Pie chart for online orders vs table bookings  
- Box plots for rating vs cost categories  
- Scatter plot for votes vs ratings  
- **Geographical map visualization using Folium**

---

## 📊 Key Insights

### 1️⃣ Which Location Has the Most Restaurants
<img width="1000" height="1000" alt="cost_vs_rating" src="https://github.com/user-attachments/assets/ff2d08b1-ed10-4094-9915-2ec24de7888c" />


**Insight:**  
BTM has the highest number of restaurants, followed by Koramangala 5th Block and HSR, indicating these areas are major food hubs driven by high demand and commercial activity.

---

### 2️⃣ Top 10 Most Popular Cuisines
<img width="1000" height="1000" alt="Top 10 Cusines" src="https://github.com/user-attachments/assets/85b72b99-f9d1-4e40-a884-9f515ae2cb9d" />


**Insight:**  
North Indian cuisine dominates Bangalore’s restaurant landscape, followed by Chinese and South Indian cuisines, reflecting strong customer preference for familiar and comfort food options.

---

### 3️⃣ Online Orders vs Table Booking
<img width="500" height="500" alt="Online_vs_offline" src="https://github.com/user-attachments/assets/dc2abee0-a320-4879-90dc-8a1fe62a23e6" />

**Insight:**  
More than **80% of restaurants support online orders**, highlighting a strong shift toward convenience-based dining and digital food delivery platforms.

---

### 4️⃣ Rating Distribution by Cost Category
<img width="700" height="700" alt="rating_distribution" src="https://github.com/user-attachments/assets/84169dd8-2bad-4925-86a5-a4fe7b7860e3" />

**Insight:**  
Mid-range and premium restaurants generally receive higher and more consistent ratings, while budget restaurants show wider variation in customer satisfaction.

---

### 5️⃣ Restaurants with High Votes but Low Ratings
<img width="600" height="600" alt="votes_vs_rating" src="https://github.com/user-attachments/assets/0e733b09-74e3-4ef5-96e2-f0b77789107f" />

**Insight:**  
Some restaurants attract large customer volumes despite lower ratings, suggesting popularity driven by factors such as location, pricing, or brand visibility rather than food quality alone.

---

### 6️⃣ Top 10 Low-Cost, High-Rated Restaurants & Map Analysis
![Best_locations](https://github.com/user-attachments/assets/159038b8-df0a-4115-a9ff-7c53b227c130)

**Insight:**  
Several affordable yet highly rated restaurants are concentrated in high-demand areas, proving that quality dining in Bangalore is not limited to expensive restaurants.

---

## ✅ Conclusion
This analysis highlights how **location, cuisine preference, pricing, and convenience** strongly influence restaurant success in Bangalore.  
The insights can help restaurant owners, food delivery platforms, and customers make informed decisions.
