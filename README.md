# Philadelphia Emergency Response & Hazard Vulnerability Analysis

**ArcGIS Pro Project | SRA 468 | Fall 2025**

## Overview

This project integrates spatial analysis, statistical clustering, and federal risk data to evaluate emergency service coverage, traffic safety, and social vulnerability in Philadelphia, PA.

Three maps were developed to support data-driven decision-making for urban resilience planning.

---

## Maps

### 1. Fire Station Response Coverage
- **Analysis:** 3-, 5-, and 7-minute drive time service areas
- **Tool:** Network Analyst (ArcGIS Online Routing Service)
- **Finding:** Underserved areas identified in North and Southwest Philadelphia
- **Data:** HIFLD Fire/EMS Stations (PASDA)

[View PDF](1_Philly_Fire_Coverage.pdf)

---

### 2. Statistically Significant Crash Clusters
- **Analysis:** Optimized Hot Spot Analysis (Getis-Ord Gi*)
- **Dataset:** PennDOT crash data, Philadelphia (2020–2024)
- **Finding:** High-confidence crash clusters (95–99%) concentrated at key intersections
- **Data:** OpenDataPhilly

[View PDF](2_Philly_Crash_HotSpots.pdf)

---

### 3. FEMA Vulnerability Index
- **Analysis:** Composite score = Risk Index + Social Vulnerability - Community Resilience
- **Dataset:** FEMA National Risk Index (v1.20, Dec 2025)
- **Finding:** High-vulnerability tracts correlate with areas of reduced emergency access
- **Data:** FEMA Open Data Portal

[View PDF](3_Philly_FEMA_Vulnerability.pdf)

---

## Project Package

The complete ArcGIS Pro project is included as a **Project Package (.ppkx)**.

[`Philly_Emergency_Response.ppkx`](Philly_Emergency_Response.ppkx)

*Double-click to open in ArcGIS Pro 3.0+ (requires Network Analyst extension).*

---

## Data Sources

- **Fire Stations:** HIFLD / PASDA
- **Crashes:** City of Philadelphia / PennDOT
- **Risk Index:** FEMA National Risk Index v1.20
- **Boundaries:** City of Philadelphia Open Data

---

## Author

**Manuel Badel**  
Penn State University | Security and Risk Analysis  
mab8068@psu.edu  
[GitHub](https://github.com/mab8068)
