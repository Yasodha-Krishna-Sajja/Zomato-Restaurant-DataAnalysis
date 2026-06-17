# 🍽️ Zomato Bangalore Restaurant EDA
<img width="1280" height="720" alt="zomato_pic" src="https://github.com/user-attachments/assets/edc76ef6-eee1-4f88-9818-8fe929a9bcf5" />

## 📌 Project Overview
This project performs Exploratory Data Analysis (EDA) on 51,717 Zomato restaurant listings across 30 Bangalore neighborhoods, analyzing 17 attributes spanning location density, cuisine diversity, pricing tiers, and rating patterns. Key findings include 1,018 high-visibility but underperforming restaurants, a 0.65-point rating gap between budget and luxury segments, and 65.3% online order adoption — delivering actionable insights to support data-driven decision-making in Bangalore's restaurant industry.

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
- BTM leads Bangalore's restaurant scene with 3,930 listings — 1.7x more than
  Koramangala 5th Block (2,319) and nearly 2x HSR (2,019)
- The top 3 hubs alone account for ~20% of all 41,665 restaurants, driven by IT workforce density and high commercial footfall.
---

### 2️⃣ Top 10 Most Popular Cuisines
<img width="1000" height="1000" alt="Top 10 Cusines" src="https://github.com/user-attachments/assets/85b72b99-f9d1-4e40-a884-9f515ae2cb9d" />


**Insight:**  
- North Indian dominates with 17,406 menu appearances, followed by Chinese (13,005)and South Indian (6,394).
- The top 2 cuisines alone account for 30,411 combined appearances — over 73% more than the next 8 cuisines combined —reflecting strong preference for familiar comfort food among Bangalore's urban population.

---

### 3️⃣ Online Orders vs Table Booking
<img width="500" height="500" alt="Online_vs_offline" src="https://github.com/user-attachments/assets/dc2abee0-a320-4879-90dc-8a1fe62a23e6" />

**Insight:**
- 65.3% of restaurants (27,206 out of 41,665) support online orders, while only 15.1% (6,304) offer table booking — a 4.3x gap.
- This signals a delivery-first restaurant ecosystem where digital platforms drive the majority of customer acquisition.

---

### 4️⃣ Rating Distribution by Cost Category
<img width="700" height="700" alt="rating_distribution" src="https://github.com/user-attachments/assets/84169dd8-2bad-4925-86a5-a4fe7b7860e3" />

**Insight:**
- A clear positive correlation exists between price and rating. Budget restaurants
  (₹0–300) average 3.56 stars while Luxury restaurants (₹3,000–6,000) average
  4.21 — a 0.65-point gap. Premium+ segments (₹600+) consistently outperform,
  suggesting price-quality alignment in Bangalore's dining market..

---

### 5️⃣ Restaurants with High Votes but Low Ratings
<img width="600" height="600" alt="votes_vs_rating" src="https://github.com/user-attachments/assets/0e733b09-74e3-4ef5-96e2-f0b77789107f" />

**Insight:**
- 1,018 restaurants have votes ≥ 198 (75th percentile) but ratings below the dataset mean — representing high-visibility, underperforming outlets.
- These restaurants are likely sustained by location or pricing rather than food quality, and represent a measurable platform quality risk for Zomato.
---

### 6️⃣ Top 10 Low-Cost, High-Rated Restaurants & Map Analysis
![Best_locations](https://github.com/user-attachments/assets/159038b8-df0a-4115-a9ff-7c53b227c130)

**Insight:**
- Filtering for cost ≤ ₹300 and rating ≥ dataset mean identified 10 best-value
  restaurants geocoded across 30 Bangalore neighborhoods. High-rated budget
  restaurants cluster in competitive high-footfall areas like BTM and Koramangala,
  confirming that quality and affordability co-exist where competition is highest.

---
💡 Business Insights Summary
- BTM and Koramangala are Bangalore's highest-density restaurant zones — ideal for competitive benchmarking
- Delivery infrastructure is critical — 65% online adoption signals where restaurant revenue is heading
- 1,018 restaurants with high visibility but poor ratings are at churn risk — actionable for platform quality teams
- Budget segment underperforms on ratings (3.56 avg) — opportunity for affordable restaurants that prioritize quality
- Best value clusters exist in specific Bangalore areas where low cost and high rating co-occur
  
## ✅ Conclusion
This analysis of 41,665 cleaned Zomato listings across 30 Bangalore neighborhoods
reveals that location, cuisine, pricing, and delivery adoption are the primary
drivers of restaurant success. BTM's 3,930 restaurants and 65.3% platform-wide
online order adoption confirm that proximity to IT hubs and delivery readiness
are non-negotiable competitive advantages. The 0.65-point rating gap between
budget and luxury segments and 1,018 high-visibility but underperforming outlets
highlight where quality gaps create actionable opportunities — for restaurant
owners to differentiate, for platforms like Zomato to enforce quality standards,
and for customers to identify best-value dining using data.
