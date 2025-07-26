# Coffee Shop Sales Dashboard

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Process](#process)
- [Features](#features)
- [Insights](#insights)
- [Learning](#learning)

## Overview

Transaction records for Maven Roasters, a fictitious coffee shop operating out of three NYC locations. Dataset includes the transaction date, timestamp and location, along with product-level details.  

The objective of this assignment is to analyze the sales data and identify key insights to help improve sales performance and optimize business strategies.  

![Overview 1](https://github.com/user-attachments/assets/6d6892dd-3b8d-4e99-b3a7-e66bfeeedd56)

![Overview 2](https://github.com/user-attachments/assets/6ce20f65-0ac7-4e5c-b410-9d415dbf790b)


## Dataset

Dataset taken from Maven Analytics - Data Playground.
https://mavenanalytics.io/data-playground  

**Coffee Shop Sales**

Transaction records for Maven Roasters, a fictitious coffee shop operating out of three NYC locations. Dataset includes the transaction date, timestamp and location, along with product-level details.  

**Dataset Explanation**  
transaction_id :Unique sequential ID representing an individual transaction.  
transaction_date :Date of the transaction (MM/DD/YY).  
transaction_time :Timestamp of the transaction (HH:MM:SS).  
transaction_qty :Quantity of items sold.  
store_id :Unique ID of the coffee shop where the transaction took place.  
store_location :Location of the coffee shop where the transaction took place.  
product_id :Unique ID of the product sold.  
unit_price :Retail price of the product sold.  
product_category :Description of the product category.  
product_type :Description of the product type.   
product_detail :Description of the product detail.  

## Process

Tools Used :- Microsoft Excel

Process:-   
-Familiarizing with the dataset.  
-Checking for any NULL values or Data errors.  
-Using calculations to generate the required columns.  
-Using Pivot Tables to analyze the data.  
-Inserting Slicers for convenience.  
-Generate Pivot Charts and gain Insights.  
-Making the Dashboard.  

## Features


### Essential Features of the Coffee Shop Sales Dashboard

### 1. **Revenue & Transactions Breakdown**
- **Monthly Trends Visualization:** Line or bar charts showing revenue and transactions per month to highlight growth and seasonality.
- **Daily Patterns:** Heatmaps or bar charts of revenue and transactions by day of the week for a quick view of peak days.

### 2. **Time-of-Day Analysis**
- **Hourly Distribution:** Interactive line or area chart showing revenue and transaction counts by hour; highlights morning rush and evening drop-off.
- **Peak Hours Indicator:** Visual emphasis (color or annotation) on 8–11 AM as key business hours.

### 3. **Product Category & Best Sellers**
- **Category Performance:** Bar chart or pie chart showing revenue share by product category (e.g., Coffee, Tea, Bakery).
- **Top 15 Product Table:** Dynamic table or horizontal bar chart listing top-selling product types by revenue and transactions, with the ability to filter by time-frame.

### 4. **Customer Behavior and Segments**
- **Customer Patterns Panel:** KPIs that summarize busiest day, hour, top products, and average transaction value.
- **Loyalty/Up-sell Opportunities:** Widget suggesting cross-sell opportunities based on pairing frequencies (e.g., "Coffee + Scone").

### 5. **Strategic Recommendations**
- **Actionable Insights Overlay:** Tiles with interpreted insights (e.g., “Weekday mornings drive 60% of revenue”; “Consider focusing promotions during 8–11 AM”).




## Insights

## Coffee Shop Sales Analysis

## 1. **Monthly Revenue & Transactions Trends**  
- **Increasing Trend:** Revenue and transactions both show a clear *upward trend* from January ($81,678; 17,314 transactions) to June ($166,486; 35,352 transactions). The revenue more than doubles, and transactions also follow a similar trajectory.
- **Strongest Months:** May and June are peak months. This could be due to seasonality, school/college breaks, or weather patterns favoring coffee sales.

## 2. **Day of the Week Patterns**
- **Top Earning Days:** Mondays and Fridays generate the highest revenue ($101,677, $101,373 respectively) and transactions (21,643 and 21,701). Tuesdays and Thursdays are slightly lower but consistent.
- **Lowest Days:** Saturday and Sunday have both lower revenue ($96,894, $98,330) and transactions (20,510, 21,096).
- **Insight:** Weekdays are stronger than weekends. The shop is more a weekday hub, possibly catering to commuters or office-goers.

## 3. **Hourly Revenue & Transactions**
- **Peak Hours:** Revenue per hour is highest from **8 AM–11 AM** (about $82,700 to $88,673 per hour) and **9–11 AM** have the highest transactions. This aligns with typical morning rush hours for coffee shops.
- **Afternoon Dip:** Post-noon hours see a dip but remain steady (~$40K/ hour until 5 PM). After 6 PM, there's a sharp decrease.
- **Lowest Hour:** By 8 PM, both revenue and transactions are almost negligible. Business tapers off in the evening.

## 4. **Product Category Performance**
- **Coffee dominates**: Coffee generates the highest revenue ($2,69,952, 58,416 transactions), followed by Tea ($1,96,406, 45,449 transactions).
- **Bakery and Chocolate:** Bakery products ($82,316 revenue; 22,796 transactions) and Drinking Chocolate ($72,416 revenue; 11,468 transactions) have substantial demand.
- **Smaller Segments:** Flavors, Coffee Beans, Loose Tea, Branded, and Packaged Chocolate are niche categories.

## 5. **Top Product Types**
- **Best Sellers by Revenue & Transactions:**
    1. **Barista Espresso:** $91,406 revenue, 16,403 transactions.
    2. **Brewed Chai Tea:** $77,082, 17,183.
    3. **Hot Chocolate:** $72,416, 11,468.
    4. **Gourmet Brewed Coffee:** $70,035, 16,912.
    5. **Brewed Black Tea/Herbal Tea:** ~$47K each, ~11,300 transactions.
- **Bakery Favorites:** Scones ($36,866, 10,173), Pastries ($25,656, 6,912), and Biscotti, emphasizing a strong "coffee and pastry" pairing.
- **Premium/Organic:** Premium Beans and Organic Beans, while niche, command significant revenue per transaction, indicating a high-value segment.

## 6. **Customer Behavior Patterns**
- **Morning Rush:** Majority of transactions and revenue happen during the first half of the day, affirming the morning-centric customer base.
- **Weekday Preference:** Likely catering to regulars (commuters, officers) during workdays.
- **Product Affinity:** Coffee (all forms), tea (especially chai and herbal), and chocolate drinks are customer mainstays, with bakery items as frequent add-ons.

## 7. **Strategic Recommendations:**
- **Focus on Weekday Campaigns:** Targeted morning/weekday promotions or loyalty programs may further boost core customer engagement.
- **Breakfast Combos:** Bundling coffee/tea with bakery could maximize spend during the morning rush.
- **Niche Up-selling:** Promote premium beans and organic/packaged offerings to high-value segments.
- **Optimize Evenings or Close Early:** With sharply lower evening sales, consider reducing hours, or launching late-afternoon happy hours/snacks to capture after-work crowd.

## 8. **Opportunities**
- **Expand Best Sellers:** Increase visibility or menu space for top-earning products, especially espresso bar and signature chai.
- **Introduce Loyalty for High-Volume Hours:** Reward basics during 8–11 AM to lock in repeat business.
- **Explore Under-performing Slots:** Analyze why weekends/afternoons lag—perhaps with events, limited-time offers, or seasonal feature drinks.

**Summary Table:**  
| Segment             | Top Performer(s)           | Action Point                          |
|---------------------|----------------------------|---------------------------------------|
| Month               | May, June                  | Prepare for increasing peak           |
| Day of Week         | Monday, Friday             | Leverage commuter market              |
| Hour                | 8–11 AM                    | Bundle/bulk offer                     |
| Product Category    | Coffee, Tea                | Diversify within strong segments      |
| Product Type        | Espresso, Chai, Bakery     | Boost visibility/promotions           |

**In summary:**
- The coffee shop thrives during weekday mornings, fueled by strong beverage (especially coffee, chai, chocolate) and pastry sales.
- Strategic focus should be on optimizing morning and weekday performance, leveraging peak products, and exploring new ideas to lift off-peak periods.


## Learning

### 1. **Data Analysis & Interpretation**
- Ability to work with raw sales data to generate meaningful **pivot tables** and derive actionable **insights**.
- Proficiency in identifying key business trends such as seasonality, customer behavior by time, and product performance.

### 2. **Dashboard Design & Data Visualization**
- Experience designing **interactive dashboards** with features tailored to business needs (e.g., KPIs, time-based drilldowns, product/category breakdowns).
- Skill in selecting appropriate **visualization types** (bar charts, line charts, heatmaps, tables) for different analytical questions.

### 3. **Business Intelligence Application**
- Translating analytical results into **actionable business recommendations** (e.g., focus points for promotions, operational optimizations).
- Understanding how analytics can inform real-world decisions in retail/food service.

### 4. **Product and Customer Analytics**
- Ability to segment products and customers, identify bestsellers, and interpret customer purchase timing and preferences.
- Competence in using data to uncover **up-sell/cross-sell opportunities** and optimize product offerings.  


This project showcases my ability to analyze complex retail sales data, design an interactive and insight-driven dashboard, and make actionable recommendations for business growth. Through advanced use of pivot tables, visualization tools, and business intelligence concepts, I developed an end-to-end analytics solution that reveals critical patterns in customer behavior, peak sales periods, and product performance. This project deepened my understanding of retail analytics, and refined my talent for transforming raw data into compelling, business-relevant stories.  
