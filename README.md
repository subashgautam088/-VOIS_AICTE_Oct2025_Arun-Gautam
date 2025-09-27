
---

# 🏡 Airbnb Data Analysis Project

## 📌 Overview

This project explores and analyzes **Airbnb listings dataset** to uncover insights about pricing, availability, host behavior, reviews, and neighborhood trends.
The goal is to **clean, preprocess, and analyze** the data to support better decision-making for both **hosts** and **guests**.

---

## 🎯 Objectives

* Understand the distribution of property types (Entire home, Private room, etc.).
* Identify which neighborhoods and neighborhood groups have the **highest number of listings**.
* Analyze **average prices** across different regions.
* Study the **relationship between property construction year and pricing**.
* Identify the **top 10 hosts** by the number of listings.
* Check whether **verified hosts** receive better reviews.
* Explore correlation between **price and service fee**.
* Compare **review ratings** across room types and neighborhoods.
* Examine how **host listing count relates to availability**.

---

## 🛠️ Steps Performed

1. **Data Cleaning & Preprocessing**

   * Dropped irrelevant and high-null columns (`house_rules`, `license`, etc.).
   * Handled missing values for categorical and numerical features.
   * Removed duplicates and invalid rows (future dates, negative availability).
   * Outlier treatment for `price`, `minimum nights`, and `number of reviews`.
   * Feature engineering:

     * `days_since_last_review`
     * `log_minimum_nights`
     * `has_reviews`, `full_year_availability`, etc.

2. **Exploratory Data Analysis (EDA)**

   * Distribution of property types.
   * Listings count by neighborhood groups.
   * Average prices across neighborhoods.
   * Correlation heatmap for numerical variables.
   * Boxplots and histograms for outlier detection.

3. **Insights**

   * Majority listings are **Entire homes/apartments**.
   * **Manhattan & Brooklyn** dominate in listing counts.
   * **Manhattan** has the highest average prices, while Staten Island has the lowest.
   * Verified hosts receive **slightly better review scores**.
   * Strong positive relationship between **price and service fee**.
   * Hosts with more listings often maintain **higher availability**.

---

## 📊 Visualizations

* Countplots for property types and neighborhood groups.
* Scatter plots (Price vs Service Fee, Construction Year vs Price).
* Heatmaps for correlations and review ratings by region.
* Boxplots to analyze outliers.

---

## 🔮 Future Work

* Apply **Machine Learning models** to predict **Airbnb prices**.
* Perform **time-series analysis** on reviews.
* Build a **dashboard (Tableau/Power BI/Streamlit)** for interactive visualization.

---

## 👨‍💻 Author

* **Arun Gautam**
* GitHub: [subashgautam088](https://github.com/subashgautam088)

---

