# ✈️ Airline Operations & On-Time Performance Analytics

An end-to-end **Airline Data Analytics project using Python, SQL, and Microsoft Power BI** to analyze flight operations, delays, cancellations, delay causes, airline performance, and airport-level patterns.

This project was developed as an **independent portfolio project for an Emirates Group Elevate internship application**, demonstrating practical skills in data preparation, SQL analysis, Power BI dashboard development, KPI creation, and business insight generation.

> **Important:** This is an independent analysis using public airline data. It does **not** use Emirates internal data and should not be interpreted as an analysis of Emirates operations.

---

## 📊 Project Overview

Airline operations generate large volumes of data across flights, airports, airlines, delays, cancellations, and operational events.

The objective of this project is to transform raw flight records into an interactive business intelligence dashboard that helps identify:

* Flight performance patterns
* Delay and cancellation trends
* Major causes of delays
* Airline-level performance variation
* Airport-level operational patterns
* Monthly changes in operational performance
* Areas requiring deeper investigation

The project follows an end-to-end analytics workflow:

**Raw Data → Data Cleaning → SQL Analysis → Power BI → Business Insights**

---

## 🎯 Business Objectives

The dashboard was designed to answer key operational questions:

1. How many flights operated during the analysis period?
2. How many flights were delayed or cancelled?
3. What are the major causes of flight delays?
4. How does delay performance change over time?
5. How does performance vary between airlines?
6. Which airports show significant delay patterns?
7. Are high-volume airports also experiencing higher delays?
8. Which operational areas require further investigation?

---

## 🛠️ Tools & Technologies

| Tool                   | Purpose                                       |
| ---------------------- | --------------------------------------------- |
| **Python**             | Data cleaning and preparation                 |
| **Pandas**             | Data manipulation and transformation          |
| **NumPy**              | Numerical data processing                     |
| **SQL**                | Aggregation, filtering and analytical queries |
| **Microsoft Power BI** | Interactive dashboard and visualization       |
| **DAX**                | KPI and analytical calculations               |
| **Power Query**        | Data transformation within Power BI           |

---

## 📈 Key KPIs

The Power BI dashboard tracks the following operational KPIs:

* **Total Flights**
* **Delayed Flights**
* **Cancelled Flights**
* **Flight Delay Rate**
* **Diverted Flights**
* **Average Delay Minutes**
* **Total Delay Events**
* **Monthly Delay Trends**
* **Cancellation Patterns**

The dashboard also separates delay causes such as:

* Carrier delays
* Weather delays
* National Airspace System (NAS) delays
* Security delays
* Late aircraft delays

---

## 📊 Dashboard Analysis

### 1. Operational Overview

Provides a high-level view of airline operations through KPI cards and summary visualizations.

Key areas include:

* Total flight volume
* Delayed flights
* Cancelled flights
* Diverted flights
* Delay rate
* Overall operational trends

---

### 2. Delay Analysis

The dashboard investigates how flight delays vary throughout the year.

Analysis includes:

* Monthly delay trends
* Average delay duration
* Delayed-flight volume
* Delay categories
* Contribution of different delay causes

This helps distinguish between different operational drivers rather than treating every delay as the same issue.

---

### 3. Delay Cause Analysis

Delay events are separated into multiple categories:

**Carrier | Weather | NAS | Security | Late Aircraft**

This allows the analysis to identify which types of operational factors contribute to delays and where further investigation may be required.

---

### 4. Airline Performance

The dashboard compares airlines based on operational indicators such as:

* Delayed flights
* Cancellation rates
* Flight volume
* Delay performance

Differences between airlines are treated as areas for investigation rather than as standalone performance judgments, since route mix, airport exposure, scheduling and network structure can affect the results.

---

### 5. Airport Analysis

Airport-level analysis examines:

* Average arrival delay
* Number of delayed flights
* Flight volume
* Operational variation between airports

This helps distinguish airports with high delay volumes because of heavy traffic from airports where delay performance may warrant deeper operational investigation.

---

## 🔎 Key Findings

The analysis identified several patterns worth further investigation:

### Delay Concentration

Delay performance changes across the 2025 timeline rather than remaining constant throughout the year.

This suggests that months with elevated delays should be examined alongside:

* Traffic levels
* Weather
* Airport congestion
* Schedule design

### Multiple Delay Drivers

Flight delays are influenced by several categories, including carrier, weather, NAS, security and late-aircraft factors.

Separating these causes provides a more useful operational view than analyzing total delays alone.

### Airline-Level Variation

Delay counts and cancellation rates vary between airlines.

However, these differences can be influenced by route networks, airport exposure, scheduling and operational characteristics.

### Airport-Level Variation

Airports show differences in average delays and delayed-flight volume.

High-volume airports should therefore be analyzed alongside their traffic levels before drawing operational conclusions.

---

## 💡 Recommended Future Analysis

The current dashboard can be expanded into a more advanced airline analytics solution.

### Route-Level Analysis

Analyze individual origin-destination pairs to identify recurring delay and cancellation patterns.

### Airport Turnaround Analysis

Investigate:

* Taxi-out time
* Taxi-in time
* Late aircraft effects
* Turnaround bottlenecks

### Operational Segmentation

Analyze performance by:

* Time of day
* Day of week
* Aircraft type
* Flight distance
* Season

### External Data Integration

Combine airline data with:

* Weather data
* Airport congestion
* Calendar events
* Holiday information

### Customer Impact

Connect operational performance with:

* Passenger volume
* Customer satisfaction
* Revenue impact
* Customer disruption

---

## 🔄 Analytics Workflow

```text
Raw Airline Dataset
        ↓
Python / Pandas
        ↓
Data Cleaning & Preparation
        ↓
SQL Analysis
        ↓
Power BI Data Model
        ↓
DAX Measures & KPIs
        ↓
Interactive Dashboard
        ↓
Business Insights
        ↓
Further Investigation
```

---

## 📌 Skills Demonstrated

This project demonstrates practical experience in:

* Data Cleaning
* Exploratory Data Analysis
* Python
* Pandas
* NumPy
* SQL
* Microsoft Power BI
* Power Query
* DAX
* KPI Development
* Data Visualization
* Trend Analysis
* Operational Analytics
* Business Intelligence
* Dashboard Design
* Business Problem Solving
* Data-Driven Decision Making

---

## 💼 Portfolio Value

This project demonstrates the ability to move beyond simply creating visualizations.

The workflow focuses on:

**Understanding the business problem → preparing data → analyzing patterns → building KPIs → visualizing insights → identifying areas for operational investigation.**

It showcases how airline operational data can be transformed into a structured analytical solution using modern data analytics tools.

---

## ⚠️ Data & Scope

* Analysis period: **2025**
* Dataset: Public airline flight data
* Analysis type: Independent portfolio project
* The dataset is not Emirates internal data.
* Findings are limited to the available dataset and its data quality.
* Observed patterns should be treated as areas for investigation rather than definitive explanations of operational causes.

---

## 🚀 Future Improvements

Planned extensions could include:

* Real-time flight data
* Automated Power BI refresh
* Weather API integration
* Route profitability analysis
* Passenger satisfaction analysis
* Delay prediction using Machine Learning
* Flight cancellation prediction
* SQL-based data warehouse
* Power BI Service deployment
* Automated reporting

---

## 👨‍💻 Project Purpose

**Portfolio Project – Data Analytics / Business Intelligence**

Created to demonstrate practical application of **Python, SQL and Power BI** to an airline operations problem, with a focus on transforming raw operational data into business-focused insights.

### Project Stack

`Python` `Pandas` `NumPy` `SQL` `Power BI` `Power Query` `DAX` `Data Analytics` `Business Intelligence`
