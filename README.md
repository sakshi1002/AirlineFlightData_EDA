#  Airline Flights Data - Exploratory Data Analysis (EDA)

## 📌 Project Overview
This project performs **Exploratory Data Analysis (EDA)** on airline flight data to uncover patterns in pricing, routes, stops, and airline revenue contribution.  
The goal was to clean, visualize, and interpret the dataset to extract **business insights** useful for airlines and travelers.

---

## ⚙️ Tech Stack
- **Python**: Data processing & visualization  
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn  

---

## 🔍 Key Steps in Analysis
1. **Data Cleaning & Preparation**
   - Handled missing values and duplicates.
   - Removed outliers in `price` and `duration` using the **IQR method**.
   - Created new features such as **route** (`source_city -> destination_city`).

2. **Exploratory Analysis**
   - Flight distribution across airlines and stops.
   - Airline-wise median ticket pricing & class distribution.
   - Route demand and flight density.
   - Airline revenue contribution and price elasticity with stops.

3. **Visualization**
   - Boxplots for outlier detection.
   - Bar plots for categorical comparisons.
   - Pie charts for revenue contribution.
   - Route-based analysis for demand hotspots.

---

## 📊 Business Insights
- **Airline Operations**  
  - A few airlines dominate in flight count and revenue share (e.g., IndiGo, Air India).  
- **Pricing Patterns**  
  - Median price provides stable cost benchmarks.  
  - Flight prices vary widely by airline and **increase with number of stops**.  
- **Stops & Routes**  
  - Most flights are **non-stop or single-stop**.  
  - High-demand routes (Delhi–Mumbai, Bangalore–Hyderabad) drive significant revenue.  
- **Revenue Contribution**  
  - Revenue is concentrated among a few major airlines, highlighting market leaders.  

---

## 📈 Visuals
- **Boxplot of Flight Prices (Before & After Outlier Removal)**  
- **Airline Revenue Share (Pie Chart)**  
- **Flight Distribution by Stops (Bar Chart)**  

---

## 🚀 Impact
- Helped identify **pricing strategies** and **demand-heavy routes**.  
- Provided insights to improve **revenue optimization** and **capacity planning**.  
- Created a clean, analysis-ready dataset suitable for **predictive modeling**.  

---

## 📂 Repository Structure
