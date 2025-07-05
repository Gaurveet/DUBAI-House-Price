# 🏙️ Dubai Real Estate Intelligence Dashboard

![Dashboard Banner](dubai_housing_dashboard_insights.png)

## 📌 Overview

This project presents an interactive Power BI dashboard built to analyze Dubai's residential real estate market. It helps investors, real estate agents, and policymakers make informed decisions based on real-time insights and data visualizations.

---

## 🎯 Objective

To transform raw housing data into an intuitive dashboard that highlights trends in property prices, types, and locations, along with calculated metrics like price per sqft and property age.

---

## 🧩 Dataset Summary

The dataset includes:

- `SquareFeet` – Property size in sqft  
- `Bedrooms`  
- `Bathrooms`  
- `Neighborhood` – Area classification (Urban, Suburb, Rural)  
- `YearBuilt`  
- `Price`  

### ➕ Added Fields:
- **PricePerSqft** = Price / SquareFeet  
- **PropertyAge** = 2025 - YearBuilt  
- **ListingCategory** = Budget / Mid-Range / High-End (based on price quantiles)

---

## 📊 Dashboard Features

- **KPI Cards**:  
  - Total Listings  
  - Average Price  
  - Avg. Size (sqft)  
  - Max Price  
  - Price per Sqft  

- **Visualizations**:  
  - 📍 Map: Avg. price by location  
  - 📊 Bar Chart: Price by property type  
  - 📈 Line Chart: Price trend (if time data)  
  - 🧱 Stacked Column: Listings by bedrooms & type  
  - 🌳 TreeMap: Developer vs. property type  
  - 📉 Box Plot & Histogram: Price and property age distributions  
  - 🎯 Scatter Plot: Price vs. Size by category  

- **Interactive Filters (Slicers)**:  
  - Bedrooms  
  - Bathrooms  
  - Neighborhood  
  - Listing Category  
  - Price Range  
  - Developer  
  - Furnishing Status  

---

## 📈 Key Insights

- **Downtown Dubai** & **Palm Jumeirah** have the highest average prices.
- **Suburban listings** offer better size-to-price ratio.
- **Apartments dominate** the market; villas are premium-priced but less common.
- **3+ bedroom listings** are concentrated in the high-end category.
- **New constructions** are limited, indicating market potential for developers.

---

## ✅ Suggested Actions

- **Investors** should consider growing suburbs with high ROI potential.  
- **Agents** should promote value per square foot in budget-friendly neighborhoods.  
- **Policy Makers** should support balanced development across districts.

---

## 📁 Files Included

| File | Description |
|------|-------------|
| `housing_price_dataset.csv` | Original dataset |
| `DUBAI HOUSE PRICE.pptx` | Slide summary presentation |
| `DUBAI House Price.docx` | Project brief |
| `dubai_housing_dashboard_insights.png` | Visual insights preview |
| *(Optional)* `Dubai_Real_Estate_Insights_Report.pdf` | Insights report PDF |
| *(Optional)* `dubai_dashboard.pbix` | Final Power BI file (if shared) |

---

## 🛠 Tools Used

- **Power BI** – Data modeling & dashboarding  
- **Microsoft Excel** – Data cleaning (Power Query)  
- **Python (Pandas, Seaborn)** – Exploratory analysis & visuals  
- **Canva / PowerPoint** – Final slide export

---

## 📜 License

This project is for educational and portfolio purposes. Feel free to fork and customize it for learning.

---

## 🙌 Acknowledgments

- Dataset inspired by real estate data structure  
- Dashboard requirements and KPIs adapted from business intelligence best practices

---

## 📬 Contact

Feel free to connect on [LinkedIn](https://www.linkedin.com/) or email me at [youremail@example.com].

