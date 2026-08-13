# ⚡ Quick Commerce Logistics & Operational Baseline Analysis

An end-to-end Power BI analytics project evaluating operational efficiency, SLA breach dynamics, customer sentiment, and revenue trends across major quick-commerce platforms (**Blinkit**, **JioMart**, and **Swiggy Instamart**).

---

## 📌 Project Overview

Quick commerce promises sub-30-minute deliveries, but fulfillment bottlenecks and high demand surges frequently challenge service-level agreements (SLAs). 

This project provides an executive and operational deep-dive into delivery performance, order volumes, refund risks, and product category bottlenecks. The report is structured into a interactive 2-page dashboard designed for decision-makers and operations managers.

---

## 📊 Dashboard Structure

### Page 1: Executive Overview
Designed for executive decision-makers to track baseline KPIs and top-line financial metrics.
* **Key Performance Indicators (KPIs):** Total Order Volume (~39.9K), SLA Breach Rate (~91.98%), and Baseline Delivery Time (~29.53 mins).
* **Cross-Platform Slicer:** Dynamic filtering across Blinkit, JioMart, and Swiggy Instamart.
* **Order Refund Rate (Expectation Gap):** Proportional distribution of orders resulting in refund requests (~45.74%).
* **Revenue by Product Category:** Horizontal bar analysis showing revenue leadership across Personal Care, Grocery, Beverages, Dairy, Fruits & Vegetables, and Snacks.

### Page 2: Demand Dynamics & Operational Bottlenecks
Designed for supply chain and logistics teams to perform root-cause analysis on operational failure points.
* **Peak Demand Hours vs. Delivery Time Spikes:** Dual-axis chart tracking hourly order volume surges against average delivery duration.
* **Average Delivery Time by Product Category:** Pinpoints operational dispatch and picking friction across individual product types.
* **Customer Rating Impact by Delivery Duration:** Correlates delivery speeds with service ratings (1 to 5 stars).
* **Refund Request Breakdown by SLA Breach Status:** 100% stacked bar chart revealing refund rates segmented by SLA compliance.

---

## 🛠️ Data Pipeline & Tech Stack

* **Business Intelligence:** Power BI Desktop
* **Data Transformation & Cleaning:** Python (`pandas`, `numpy`)
* **Source Dataset:** `quick_commerce_cleaned.csv`
* **UI/UX Design:** Dark Slate Theme (`#0F172A`), Custom Rounded Containers, High-Contrast Typography

---

## 🔑 Key Analytical Insights

1. **Widespread SLA Challenges:** SLA breaches sit near ~92% across platforms, indicating that standard fulfillment targets are regularly strained under current dark-store operational models.
2. **Refund Sensitivity:** Nearly 46% of orders result in refund requests, closely aligned with SLA failures—highlighting delivery delay as a primary driver for customer friction.
3. **Product Dispatch Uniformity:** Delivery times remain relatively flat (~29 minutes) across all product categories, suggesting that bottlenecks stem from dispatch and last-mile routing rather than in-store picking times.
4. **Volume Stability:** Order demand is distributed across peak operating hours, requiring optimized courier allocation during high-volume windows to curb delivery time spikes.
