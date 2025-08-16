# Feature-engineering-using-Delhivery-dataset
Feature engineering and exploratory analysis of logistics trip data to extract insights, identify bottlenecks, and prepare a clean, training-ready dataset for predictive modeling
#  Logistics Case Study: Feature Engineering & Training-Ready Data  
**End-to-end analysis of logistics trip data — cleaning, feature engineering, and insights extraction — leading to a structured, training-ready dataset for predictive modeling.**

##  Project Overview  
- **Data Cleaning & Preparation** – Removed redundant identifiers, handled dwell time anomalies, and structured trip-level data for consistency.  
- **Feature Engineering** – Created meaningful features (e.g., hub dwell times, trip timing, route characteristics) for predictive modeling.  
- **Exploratory Analysis** – Identified demand hubs, seasonal spikes, and operational bottlenecks across source/destination centers.  
- **Training-Ready Dataset** – Final dataset curated with key features (time, distance, hub handling, trip schedule) for building an ETA prediction model.

## **Insights:**

**Insight 1:**
Gurgaon and Bengaluru dominate as leading source cities, contributing nearly equal shipment volumes, indicating their role as primary logistics hubs driving significant outbound movement in the supply chain.

**Insight 2:**
Bengaluru emerges as the top destination city with highest inbound shipments, while Mumbai and Gurgaon follow, reflecting strong demand concentration in these metropolitan regions for goods distribution and consumption.

**Insight 3:** 
Order volume peaked in 2018, with September alone driving the highest monthly demand, suggesting strong festive or Amazon or Flipkart's Great indian festival -driven consumption patterns during that period.

**Insight 4:**
The Allahabad–Allahabad lane shows reliability concerns, with median trip times 6.4x and P90 reaching 33.9x OSRM benchmarks across 15 trips, indicating systemic inefficiencies or potential operational/data quality issues.

**Insight 5:**
High-volume hubs such as Guwahati (Assam) and Jaipur (Rajasthan) show severe dwell delays, with P90 >3500 minutes despite moderate trip counts (75–94). The Gurgaon Bilaspur hub (Haryana), with 1063 trips, has sustained delays (median dwell 431 minutes, P90 3106 minutes) indicating systemic inefficiencies. On the destination side, Kolkata Dankuni hub (West Bengal) records extreme dwell (median 1286 minutes, P90 3355 minutes) across 197 trips, directly impacting delivery timelines.
