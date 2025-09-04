# \# Supply Chain Performance \& Freight Cost Analysis

# 

# This repository contains an exploratory analysis of the \*\*SCMS Delivery History Dataset\*\*, focusing on shipment modes, lead times, on-time delivery, and freight cost efficiency.

# 

# ---

# 

# \## Executive Summary

# \- \*\*Air freight dominates\*\* shipments (>60%) and costs, showing reliance on speed at a premium.  

# \- \*\*Trucking is cost-efficient\*\*, handling ~30% of orders but only ~22% of total costs.  

# \- \*\*Air Charter is expensive\*\*, used sparingly (6.5% of shipments) yet contributing ~13% of costs.  

# \- \*\*On-time delivery\*\* varies by region and vendor; several areas show frequent delays.  

# \- \*\*Freight cost per kilogram\*\* differs by mode and region → optimization opportunities.  

# 

# These findings highlight the trade-offs between \*\*speed, cost, and reliability\*\* in logistics operations.

# 

# ---

# 

# \## Repository Structure





# \## Data

# \- Source: SCMS **Delivery** History Dataset (link to original dataset \[here](https://www.kaggle.com/datasets/apoorvwatsky/supply-chain-shipment-pricing-data)).  

# \- Large files are not committed to this repository.  

# \- Please place the dataset under `data/` before running the notebook.

# 

# ---

# 

# \## Key Analyses \& Visuals

# 

# \### 1. Shipment Mode – Volume \& Cost Share

# \- Air accounts for over 60% of shipments, underlining its role as the primary mode.  

# \- Trucking follows with ~28%, essential for domestic and last-mile delivery.  

# \- Ocean freight remains limited at 3.7%.  

# 

# !\[Shipment Mode](D:\\Quyên\\DA by SQL\\Lớp Rikke Academy\\Python\\Project MD03\\supply-chain-freight-analysis\\Images/Shipment\_Mode\_Analysis\_by\_Cost.png)

# !\[Shipment Mode](D:\\Quyên\\DA by SQL\\Lớp Rikke Academy\\Python\\Project MD03\\supply-chain-freight-analysis\\Images/Shipment\_Mode\_Analysis\_by\_Number\_of\_Order.png)

# 

# ---

# 

# \### 2. Lead Time Analysis

# \- Countries differ significantly: Sierra Leone, Benin, Kazakhstan < 50 days, while Pakistan and Guatemala exceed 200–300 days.  

# \- Vendor performance also varies: S. Buys Wholesaler ~35 days, CIPLA Limited >140 days.  

# \- Shipment modes show clear contrasts: Ocean (~175 days) vs. Truck (~55 days).  

# 

# !\[Lead Time by Country](D:\\Quyên\\DA by SQL\\Lớp Rikke Academy\\Python\\Project MD03\\supply-chain-freight-analysis\\Images/Lead\_Time\_Analysis\_by\_Country.png)

# !\[Lead Time by Vendor](D:\\Quyên\\DA by SQL\\Lớp Rikke Academy\\Python\\Project MD03\\supply-chain-freight-analysis\\Images/Lead\_Time\_Analysis\_by\_Vendor.png)

# !\[Lead Time by Mode](D:\\Quyên\\DA by SQL\\Lớp Rikke Academy\\Python\\Project MD03\\supply-chain-freight-analysis\\Images/Lead\_Time\_Analysis\_by\_Shipmode.png)

# 

# ---

# 

# \### 3. On-time Delivery

# \- Trucking achieves higher reliability compared to air and ocean.  

# \- Certain vendors and regions show frequent delays.  

# 

# !\[On-time Delivery](D:\\Quyên\\DA by SQL\\Lớp Rikke Academy\\Python\\Project MD03\\supply-chain-freight-analysis\\Images/On-time Delivery\_Analysis\_by\_Vendor.png)





# 

# ---

# 

# \### 4. Freight Cost per Kilogram

# \- Air and Air Charter are the most expensive.  

# \- Trucking is the cheapest.  

# \- Ocean lies in between, suitable for heavy but less urgent shipments.  

# 

# !\[Freight Cost per Kg](D:\\Quyên\\DA by SQL\\Lớp Rikke Academy\\Python\\Project MD03\\supply-chain-freight-analysis\\Images/Freight\_Cost\_Analysis\_Distribution.png)

# !\[Freight Cost per Kg](D:\\Quyên\\DA by SQL\\Lớp Rikke Academy\\Python\\Project MD03\\supply-chain-freight-analysis\\Images/Freight\_Cost\_Analysis\_by Shipmode.png)



# !\[Freight Cost per Kg](D:\\Quyên\\DA by SQL\\Lớp Rikke Academy\\Python\\Project MD03\\supply-chain-freight-analysis\\Images/Freight\_Cost\_Relations.png)

# 

# 

# ---

# 

# \## Conclusion \& Recommendations

# This analysis confirms clear trade-offs between \*\*volume, cost, and timeliness\*\*:  

# 

# \- \*\*Air freight\*\* ensures speed but comes with high costs → best for critical shipments.  

# \- \*\*Trucking\*\* is cost-efficient → maximize for domestic/non-urgent deliveries.  

# \- \*\*Air Charter\*\* is disproportionately expensive → keep for emergencies only.  

# \- \*\*Ocean freight\*\* could be expanded for bulk, low-priority orders.  

# 

# \*\*Recommendations:\*\*  

# 1\. Rebalance orders between \*\*Air and Truck\*\* to reduce costs.  

# 2\. Improve \*\*on-time performance\*\* with stronger vendor coordination.  

# 3\. Investigate \*\*regional bottlenecks\*\* behind delays.  

# 4\. Increase \*\*use of Ocean freight\*\* where possible.  

# 

# ---

# \## 👤 Author

# 

# Trinh Nguyen

# 

# ng.trinh3023@gmail.com



