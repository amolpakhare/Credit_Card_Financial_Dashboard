# 📊 Credit Card Customer & Transaction Analysis Dashboard

## 📌 Project Overview
This project presents a comprehensive analysis of **credit card customer behavior and transaction patterns**, built using **Excel**, **SQL**, and **Power BI**.  
The aim is to help stakeholders identify **high-value customer segments**, understand **spending habits**, and improve **marketing & retention strategies**.

The dashboard integrates **customer demographic data** with **transaction records**, enabling deep exploration of:
- Revenue performance across different customer segments
- Preferred spending categories and transaction modes
- Seasonal and quarterly performance trends
- Key drivers of interest income and total transaction volumes

---

## 🗂 Dataset Description
The dataset consists of two major parts:
1. **Customer Dataset**  
   - Demographics: Age, Gender, Marital Status, Education, Job Type, Income Level, State  
   - Additional attributes: Number of Dependents, Credit Card Type, Card Category
2. **Transaction Dataset**  
   - Card Category (Silver, Blue, Gold, Platinum)  
   - Expenditure Type (Bills, Entertainment, Fuel, Grocery, Food, Travel, etc.)  
   - Transaction Mode (Swipe, Chip, Online)  
   - Transaction Amount, Interest Earned, Week & Quarter information

---

## 🔍 Methodology
1. **Data Collection & Cleaning** (Excel)  
   - Removed duplicates, handled null values, standardized category labels
   - Verified data types and ensured date formats for time-series analysis

2. **Data Transformation** (SQL)  
   - Joined customer and transaction datasets  
   - Created aggregated metrics (Sum of Revenue, Sum of Total Transaction Amount, Sum of Interest Earned)  
   - Derived calculated fields like Quarterly Revenue and CSS (Customer Satisfaction Score)

3. **Data Visualization** (Power BI)  
   - Developed two interactive dashboards:
     - **Customer Analysis Dashboard**
     - **Transaction Analysis Dashboard**
   - Used slicers and filters for dynamic exploration by quarter, demographic attributes, and card type

---

## 🚀 Dashboard Features

### **Customer Analysis Dashboard**
- KPIs: Total Revenue, Transaction Amount, Interest Earned, CSS
- Revenue Trends by Week & Quarter
- Segmentation:
  - By Age Group, Gender, Marital Status, State, Dependent Count
  - By Education Type and Income Level
- Revenue & Income split by Job Type
- Revenue distribution by Top 5 States

### **Transaction Analysis Dashboard**
- KPIs: Revenue, Transaction Amount, Interest, Transaction Count
- Performance by Card Category
- Quarterly Revenue vs Transaction Amount chart
- Spending Pattern:
  - Revenue by Expenditure Type
  - Revenue by Transaction Mode
- Revenue by Job Type and Education Level

---

## 📈 Key Insights & Findings
- **Blue card holders** generate the highest revenue (~46M), followed by Silver (~6M).
- **40–50 year old customers** contribute the most revenue (~12M).
- **Texas (TX)** is the highest-revenue state, followed by NY and CA.
- **Swipe transactions** dominate (35M revenue), with chip and online transactions trailing behind.
- **Graduates with high income** spend significantly more than other groups.
- **Bills, entertainment, and fuel** are the top expenditure categories.
- **Q3** recorded the highest quarterly revenue (~14.2M).

---

## 🛠 Tools & Technologies
- **Data Cleaning & Preprocessing**: Microsoft Excel
- **Data Analysis & Transformation**: SQL (Joins, Aggregations, Calculated Fields)
- **Data Visualization**: Power BI (DAX measures, Interactive Filters, Drilldowns)
- **Version Control & Portfolio**: GitHub

---

## 📷 Dashboard Preview

**Customer Analysis Dashboard**  
Review:=    (https://github.com/amolpakhare/Credit_Card_Financial_Dashboard/blob/main/Credit_card_Customerreport.png)

**Transaction Analysis Dashboard**  
Review:- 
---

## 📹 Demo Video
🎥 Watch the **3–4 minute walkthrough** where I explain dashboard navigation, filters, and insights:  
[Video Link](    link   ) 
---

## 📌 How to Use
1. Download the `.pbix` file from this repository.
2. Open in **Power BI Desktop**.
3. Use the filters (Quarter, Gender, Income Level, Card Category, Payment Mode) to explore insights.

---

## 📬 Contact
If you’re interested in collaborating or discussing this project:

**Name:** Amol Pakhare  
🔗 **Github:**  github.com/amolpakhare
🔗 **LinkedIn:** linkedin.com/in/pakhareamol   
**Email:** pakhareamol300@gmail.com  

---
