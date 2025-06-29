# Airbnb Dynamic Pricing Recommendation Engine

> **Project Title:** Airbnb Dynamic Pricing Recommendation Engine
> **Author:** Tanima Das
> **Date:** June 2025

## 🚀 Objective

Analyze historical Airbnb data from NYC (2019) to uncover insights and build a pricing recommendation engine. The goal is to support hosts and Airbnb stakeholders in optimizing listing prices based on factors like location, availability, listing quality, and guest engagement.

---

## 🛠️ Tools Used

* **Python (Jupyter Notebook)** – for data cleaning and building the pricing prediction model.
* **Excel** – for light preprocessing and data understanding.
* **Tableau** – for creating a professional, interactive dashboard mimicking Airbnb's design.

---

## 📊 Dashboard Overview

A comprehensive Tableau dashboard designed with Airbnb's color palette (pink & grey) to deliver portfolio-level aesthetics and clarity. The dashboard includes:

### 🔑 KPIs (Top Indicators)

* **Total Listings:** 48,895
* **Total Hosts:** 37,457
* **Average Revenue Per Listing:** \$19,811
* **Average Price:** \$152.70
* **Max Price:** \$10,000
* **Min Price:** \$10
* **Average Availability:** 112.8 days
* **Average Reviews Per Month:** 1.373

### 📌 Key Visualizations

* **Total Revenue by Room Type** – Identifies which room types generate the highest revenue.
* **Top Revenue-Generating Neighbourhoods** – Highlights Midtown, Hell's Kitchen, and more.
* **Impact of Reviews on Revenue** – Analyzes guest engagement vs. revenue potential.
* **Availability vs. Revenue (Pie Chart)** – Shows how low, medium, and high availability affect earnings.
* **Overpriced Neighbourhood Heatmap** – Detects areas with low reviews but high price (potential overpricing).
* **Minimum Nights vs. Revenue** – Understands how longer stays impact earnings.
* **Geographic Map View** – Outdoor-styled map showing listing concentration.
* **Filters Panel** – Slice data by neighborhood group, room type, availability, min. nights, review category.

* 📸 Sneak Peek into the Dashboard — crafted with Airbnb’s official branding and optimized to deliver clean, actionable insights. The dashboard offers interactive filters, professional KPIs, and portfolio-grade visualizations tailored for real-world use.

![airbnb_dashboard_screenshot.png](https://github.com/Tanima7/airbnb-dynamic-pricing-engine/blob/main/airbnb_dashboard_screenshot.png)

---

## 🧠 Python Model (Pricing Engine)

The Jupyter Notebook `airbnb_model_prediction.ipynb` includes:

* Data cleaning and transformation
* Feature selection (neighbourhood group, number of reviews, availability, etc.)
* Linear regression model to predict optimal listing price
* Evaluation metrics and price prediction examples

---

## 🚚 Deliverables

| Type                         | Description                                                                                                    |
| ---------------------------- | -------------------------------------------------------------------------------------------------------------- |
| 📊 **Tableau Dashboard**     | Filterable, Airbnb-themed dashboard showing key pricing and revenue insights from NYC 2019 listings.           |
| 🧠 **Python Pricing Engine** | Linear regression model to predict listing price using key variables. File: `airbnb_model_prediction.ipynb`.   |
| 📄 **Final Report**          | PDF summarizing methodology, insights, and recommendations. File: `Airbnb Dynamic Pricing Recommendation.pdf`. |
| 📷 **Dashboard Screenshot**  | High-res image of the final dashboard for quick viewing. File: `airbnb_dashboard_screenshot.png`.              |
| 🧹 **Cleaned Dataset**       | Processed and cleaned data used for modeling and dashboarding. File: `cleaned_airbnb_data.csv`.                |
| 🗂 **Original Dataset**      | Raw dataset from Kaggle. File: `AB_NYC_2019.csv`.                                                              |

---

## 🎯 Key Insights

* **Entire homes generate the highest revenue**, but private rooms offer consistency.
* **Low engagement listings (less reviews/month) still earn the most**, likely due to high listing volume.
* **Bronx and Brooklyn have overpriced listings** with low engagement, indicating poor pricing strategies.
* **High availability listings earn significantly more**, suggesting full-time hosts gain the most.
* **Short stays (2-5 nights) contribute highest revenue**, making them ideal for dynamic pricing.

---

## 📌 Design Language

* Airbnb pink (#FF5A5F) and grey theme
* KPI tiles at the top with bold figures
* Minimal, classy layout with soft drop shadows and rounded edges

---

## 🔗 Acknowledgements

* Dataset from Kaggle: [AB\_NYC\_2019](https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data)
* Logo and brand color reference: Airbnb Official Style Guide

---

## 💼 About Me

**Tanima Das**
Second year engineering student passionate about data analytics, dashboarding, and ML. Currently seeking internship opportunities to apply and grow my skills in real-world business problems.


---

## 🌐 Connect with Me

* [LinkedIn](https://www.linkedin.com/in/tanima-das-3b4289282/) 
* [GitHub](https://github.com/Tanima7/airbnb-dynamic-pricing-engine)

---

