# 🚀 Space Mission Analysis Dashboard

An interactive Power BI dashboard designed to analyze historical space missions from 1957 to 2022. The dashboard provides insights into mission activity, companies, rockets, mission trends, rocket status, launch vehicles, and available launch-cost information.

---

## 📌 Introduction

Space missions generate large amounts of historical and operational data, including launch dates, companies, locations, rockets, mission outcomes, rocket status, and launch prices.

This project transforms raw space-mission data into an interactive Power BI dashboard that makes these patterns easier to explore and understand.

---

## 🎯 Business Problem

Analyzing space-mission data in raw tabular form can make it difficult to identify trends and patterns.

This dashboard addresses questions such as:

- How has space mission activity changed over time?
- Which companies have conducted the most missions?
- Which launch locations have recorded the highest mission activity?
- Which rockets or launch vehicles have been used most frequently?
- What is the distribution of active and retired rockets?
- What is the distribution of mission outcomes?
- How does recorded launch cost vary across launch vehicles?
- How has the availability of recorded price information changed over time?

---

## 🎯 Dashboard Goal

The goal of this project is to provide an interactive and easy-to-understand view of historical space mission data.

The dashboard helps users:

- Explore mission activity over time
- Compare companies and launch locations
- Analyze rocket usage and status
- Understand mission outcomes
- Identify the most frequently used launch vehicles
- Analyze available launch-cost information
- Navigate different levels of analysis through multiple dashboard pages

---

## 📊 Dashboard Overview

The dashboard is divided into three interactive pages:

- **Home** — Branded landing and navigation page
- **Overview** — High-level KPIs and mission analysis
- **Rocket Performance & Cost Analysis** — Rocket performance and cost analysis

---

## 📸 Dashboard Preview

### 🏠 Home

![Home Dashboard](https://github.com/anshanalytics/Space-Mission-Analysis-Dashboard/blob/main/Home.png)

### 📈 Overview

![Overview Dashboard](https://github.com/anshanalytics/Space-Mission-Analysis-Dashboard/blob/main/Overview.png)

### 🚀 Rocket Performance & Cost Analysis

![Rocket Performance & Cost Analysis](https://github.com/anshanalytics/Space-Mission-Analysis-Dashboard/blob/main/Rocket%20Performance%20%26%20Cost%20Analysis.png)

---

## 🔍 Key Highlights

After data cleaning and removing one exact duplicate record, the dataset contains:

- **4,629** mission records
- **62** companies
- **370** unique rockets
- **103** active rockets
- **267** retired rockets
- Historical coverage from **1957 to 2022**

### 🚀 Most Used Launch Vehicles

The two most frequently recorded launch vehicles in the cleaned dataset are:

| Launch Vehicle | Recorded Missions |
|---|---:|
| Cosmos-3M (11K65M) | 446 |
| Voskhod | 299 |

Together, these two launch vehicles account for **745 recorded mission entries**.

### 📅 Historical Mission Activity

The dashboard allows users to examine how mission activity changed across the historical period from 1957 to 2022.

### 🏢 Company Analysis

Mission activity can be compared across different space companies to identify differences in recorded launch activity.

### 🌍 Launch Location Analysis

The dashboard provides a geographic perspective by analyzing mission activity based on the location information available in the source dataset.

### 🚀 Rocket Status

The dashboard separates rockets into:

- Active
- Retired

This provides an overview of the operational status of the rockets represented in the dataset.

### 🎯 Mission Status

Mission outcomes are visualized to provide an overview of the recorded results of space missions.

### 💰 Cost Analysis

The dashboard analyzes available launch-price information by year and launch vehicle.

Because many records in the source dataset do not contain a price, cost-related analysis represents only the missions with recorded price values.

---

## 💡 Business Impact

This dashboard helps users quickly understand historical space-mission activity without manually analyzing thousands of rows of raw data.

The analysis can support:

- Historical trend analysis
- Company-level comparison
- Rocket usage analysis
- Launch vehicle analysis
- Mission outcome analysis
- Cost exploration
- High-level space industry research

The interactive structure allows users to move from a high-level dashboard view to more detailed mission and rocket analysis.

---

## 🧹 Data Preparation

The original dataset was prepared before building the dashboard.

Key preparation steps included:

- Removing one exact duplicate record
- Checking for duplicate records
- Validating column values
- Converting the Date column to the appropriate date format
- Converting Time to the appropriate time format
- Converting Price to a numeric format
- Creating a Year column for time-based analysis
- Extracting location information for geographic analysis
- Checking columns for errors and inconsistencies
- Retaining missing price values where the source dataset did not provide a price

The cleaned dataset contains **4,629 records**.

---

## 📂 Dataset

The dataset contains historical space mission information including:

- Company
- Launch Location
- Date
- Time
- Rocket
- Mission
- Rocket Status
- Price
- Mission Status

### Dataset Source

The dataset is based on the Space Missions dataset available through Maven Analytics Data Playground.

🔗 [Space Missions Dataset – Maven Analytics](https://mavenanalytics.io/data-playground/space-missions)

The source page describes the dataset as covering space missions from 1957 to August 2022, including information such as launch location, date, mission result, company, rocket name, price, and status.

---

## 📊 Dataset Summary

| Metric | Value |
|---|---:|
| Mission Records | 4,629 |
| Companies | 62 |
| Unique Rockets | 370 |
| Active Rockets | 103 |
| Retired Rockets | 267 |
| Analysis Period | 1957–2022 |

---

## 🛠️ Tools Used

- **Power BI Desktop** — Dashboard development and visualization
- **Power Query** — Data cleaning and transformation
- **DAX** — Measures and analytical calculations
- **CSV Dataset** — Source data

---

## 📈 Analytical Focus

The project focuses on answering practical analytical questions rather than simply displaying raw data.

The main analytical areas are:

**Mission Trends → Company Activity → Launch Locations → Rocket Usage → Mission Outcomes → Rocket Status → Cost Analysis**

This creates a structured story from historical space-mission data and allows users to explore different aspects of the dataset interactively.

---

## 🎯 Project Takeaway

The Space Mission Analysis Dashboard converts historical space-mission records into an interactive analytical experience.

It provides a structured way to explore mission activity, companies, launch locations, rockets, mission outcomes, rocket status, and available cost information.

The project demonstrates how Power BI can be used to transform raw historical data into a clear, interactive, and business-focused dashboard.

---

## 👤 Author

**Ansh Sharma**

Data Analytics | SQL | Python | Power BI

🔗 [GitHub](https://github.com/anshanalytics)
