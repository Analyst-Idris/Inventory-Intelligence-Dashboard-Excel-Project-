# Inventory-Intelligence-Dashboard-Excel-Project-

<img width="800" height="800" alt="Image" src="https://github.com/user-attachments/assets/3f93a7a1-b2a1-4043-8b3c-6be6815909b2" />

---

# Project Overview  

## Background  

A growing retail and distribution company managing over 1,000 inventory items across multiple product categories and warehouses was experiencing increasing operational pressure. Although operational data existed, it was fragmented and lacked a centralized reporting structure.

This created limited visibility into stock health, supplier performance, restocking pressure, and cost efficiency — leading to reactive decision-making.

The business required a structured analytical solution that could transform raw inventory data into actionable intelligence for both executive leadership and operational managers.

To address this gap, I designed and developed a **two-page Inventory Intelligence Dashboard in Microsoft Excel**, integrating data cleaning, modeling, and advanced calculations using Power Pivot.

---

# Business Problem  

The company lacked a centralized inventory intelligence framework capable of answering critical strategic questions:

- Which product categories hold the highest stock concentration?
- Where is restocking pressure increasing across warehouses?
- What percentage of inventory is sufficient versus at reorder risk?
- How does supplier performance affect cost efficiency and stock flow?
- Are restocking volumes seasonal, structural, or demand-driven?
- Are we over-invested in certain inventory categories?
- Which suppliers provide optimal cost-to-stock efficiency?

Without structured visibility, the organization faced:

- Risk of stockouts and emergency procurement
- Capital tied up in overstocked inventory
- Margin erosion from inefficient supplier selection
- Limited forecasting capability
- Inefficient warehouse resource allocation

The core issue was not lack of data — it was lack of structured inventory intelligence.

---

# Project Objectives  

The primary objective of this project was to design a two-page decision-support dashboard in Excel that provides both executive-level and operational-level visibility into inventory performance.

### Key Objectives

1. **Improve Inventory Health Visibility**
   - Measure total stock quantity
   - Quantify estimated restocked volume
   - Calculate average unit cost
   - Determine sufficient vs reorder rate

2. **Reduce Capital Lock-In from Overstocking**
   - Analyze stock distribution by category
   - Identify capital-heavy inventory segments
   - Detect potential overstock conditions

3. **Strengthen Restocking Strategy**
   - Monitor restocked quantity by warehouse
   - Track monthly restocking trends
   - Measure reorder rate percentage

4. **Optimize Supplier Performance and Cost Efficiency**
   - Evaluate suppliers by stock volume
   - Compare restocking performance
   - Analyze average unit cost variability

5. **Enhance Forecasting and Operational Planning**
   - Identify peak restocking months
   - Detect abnormal spikes or demand shifts
   - Improve procurement scheduling accuracy

---

# 1. Data Preparation & Technical Implementation  

## Data Cleaning & Transformation  

To ensure accuracy and analytical integrity, I performed the following:

- Standardized inconsistent supplier, category, and warehouse names
- Removed duplicate records
- Corrected missing and invalid stock values
- Standardized date formats for time-series analysis
- Fixed inconsistent reorder status labeling
- Created calculated columns for:
  - Reorder classification logic
  - Quarter derivation from month
  - Restocking variance tracking

This ensured a clean, analysis-ready dataset suitable for modeling.

---

## Data Modeling & Advanced Calculations (Power Pivot)

Power Pivot was used to build a structured analytical model:

- Established relationships between inventory attributes
- Created DAX measures for:
  - Total Stock Quantity
  - Estimated Restocked Quantity
  - Average Unit Cost
  - Reorder Rate (%)
  - Sufficient Rate (%)
- Developed supplier-level aggregation metrics
- Built time-based restocking measures

This approach improved scalability and performance compared to traditional worksheet formulas.

---

## Dashboard Development & Navigation  

The dashboard was structured into two analytical layers:

### Page 1 – Executive Summary
- High-level KPI cards
- Inventory health indicators
- Stock distribution by category
- Warehouse-level restocking overview

### Page 2 – Operational Inventory Intelligence
- Supplier performance breakdown
- Stock vs restock comparison by category
- Monthly restocking trend analysis

Additional features implemented:

- Page navigation buttons (Raw Data → Cleaned Data → Pivot → Report)
- Slicers for Year and Quarter filtering
- Visual hierarchy for executive readability

---

# 2. Key Insights & Business Impact  

## 1. Inventory Health Assessment  

- 79.2% of inventory is sufficient
- 20.8% requires reorder attention
- Total stock volume: 252.9K units
- Estimated restocked quantity: 164.6K units

**Impact:**  
Provided immediate visibility into inventory risk exposure and reorder pressure.

---

## 2. Category-Level Capital Concentration  

- Groceries and Electronics show highest stock volumes
- Uneven stock allocation across categories

**Impact:**  
Highlighted potential capital concentration and overstock risk in specific segments.

---

## 3. Warehouse Restocking Pressure  

- Significant variation in restocking demand across warehouses

**Impact:**  
Enabled targeted warehouse planning and resource allocation.

---

## 4. Supplier Cost & Efficiency Variability  

- Noticeable differences in average unit cost across suppliers
- Some suppliers deliver higher volume at lower cost

**Impact:**  
Created a foundation for procurement optimization and contract renegotiation.

---

## 5. Seasonal Restocking Trends  

- Peak restocking observed in March, May, and December
- Gradual increase toward year-end

**Impact:**  
Improved forecasting capability and proactive procurement planning.

---

# 3. Strategic Recommendations  

Based on the analysis, the following recommendations were proposed:

### 1. Rebalance Category-Level Inventory Investment  
Reduce capital concentration in high-volume categories and optimize allocation toward high-margin products.

### 2. Implement Automated Reorder Monitoring  
Create structured tracking for the 20.8% at-risk inventory to prevent stockouts.

### 3. Optimize Supplier Contracts  
Renegotiate high-cost supplier agreements and increase volume allocation to cost-efficient partners.

### 4. Align Warehouse Strategy with Demand Patterns  
Adjust staffing, storage, and procurement planning based on restocking intensity by warehouse.

### 5. Develop Seasonal Procurement Planning  
Prepare for peak restocking periods (Q1 and Q4) to reduce supply volatility and control costs.

---

# Strategic Outcome  

This project transformed fragmented operational data into a centralized inventory intelligence system.

The company shifted from reactive inventory management to proactive, data-driven decision-making — improving capital efficiency, supplier management, forecasting accuracy, and operational visibility.

---

**Core Insight:**  
The challenge was not inventory volume — it was the absence of structured inventory intelligence.  
This solution closed that gap.


## The Two-Page Report  

This project consists of a structured two-page analytical report:

### Page 1 – Executive Summary
Designed for strategic leadership visibility, including:
- High-level KPI cards
- Inventory health indicators (Sufficient vs Reorder Rate)
- Total stock and estimated restock metrics
- Stock distribution by category
- Warehouse-level restocking overview (geographic view)

<img width="4403" height="2508" alt="Image" src="https://github.com/user-attachments/assets/8e16da19-f524-4ee0-841d-57dc7db92a84" />

### Page 2 – Operational Inventory Intelligence
Designed for operational and procurement managers, including:
- Supplier performance breakdown
- Stock vs Restock comparison by category
- Monthly restocking trend analysis
- Supplier cost efficiency evaluation

<img width="4378" height="2508" alt="Image" src="https://github.com/user-attachments/assets/98c67a9c-ba20-46a7-8f3e-46359c67656b" />

# Author  

**Oladejo Idris**  
Data & Business Intelligence Analyst  
Data Analysis Trainer Expert  
Machine Learning Engineer Enthusiast  

---

# Tools Used  

- Microsoft Excel  
- Power Pivot  
- DAX (Data Analysis Expressions)  
- Pivot Tables  
- Advanced Excel Formulas  
- Data Cleaning & Transformation Techniques  

---

# Collaboration & Opportunities  

For collaboration, gigs, consulting projects, or job opportunities:

📞 +234 7025062857  
📧 oladejoidris55@gmail.com  
