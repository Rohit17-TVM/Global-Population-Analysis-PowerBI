# Global-Population-Analysis-PowerBI
Interactive Power BI dashboard analysing global population trends, rankings, and growth insights using Power Query, DAX, and data visualisation.

# 🌍 Global Population Analysis Dashboard | Power BI Project

An interactive and data-driven Power BI dashboard designed to analyse global population distribution, country rankings, and population growth trends using advanced data visualisation and DAX calculations.

This project demonstrates practical Business Intelligence skills including data transformation, data modelling, DAX measures, interactive dashboards, and analytical storytelling using Power BI.


# 📌 Project Overview

The dashboard provides insights into:

* 🌎 Country-wise population distribution
* 📈 Population growth analysis
* 🏆 Ranking of countries based on population
* 🌐 Percentage contribution to world population
* 📊 Comparative analysis using interactive visuals
* 🔍 Dynamic filtering and drill-down analysis

The project was built to showcase real-world Power BI development skills suitable for data analytics portfolios, GitHub projects, and LinkedIn showcases.


# 🛠 Tools & Technologies Used

* Microsoft Power BI
* Power Query
* DAX (Data Analysis Expressions)
* Data Modeling
* Interactive Visualizations


# 📂 Dataset Information

The dataset includes:

* Country Names
* Population Data
* Population Growth Rates
* Country Rankings
* World Population Percentage


# 🔄 Data Transformation Performed

The following Power Query transformations were performed:

* Imported and cleaned raw datasets
* Removed unnecessary columns
* Changed data types
* Handled missing and invalid values
* Renamed columns for readability
* Merged datasets using country fields
* Expanded merged columns
* Created structured analytical tables
* Optimised data for reporting and visualisation


# 📊 Dashboard Features

## ✅ Interactive Visuals

* Tree Map
* Bar Charts
* KPI Cards
* Slicers
* Dynamic Filters
* Comparative Visualizations
* Population Distribution Charts

## ✅ Data Analysis Capabilities

* Country-wise population comparison
* Population growth tracking
* Ranking analysis
* Percentage contribution analysis
* Drill-through interactions
* Dynamic report filtering

## ✅ User Interaction

* Cross-filtering between visuals
* Dynamic slicers for country selection
* Responsive dashboard layout
* Interactive analytical exploration


# 🧮 DAX Measures & Calculations

This project demonstrates the use of DAX (Data Analysis Expressions) to create dynamic calculations and analytical insights within Power BI.

## 📌 DAX Functions Used

* `SUM()`
* `AVERAGE()`
* `RANKX()`
* `ALL()`
* `DIVIDE()`
* `CALCULATE()`


# 📈 Sample DAX Measures

## 🌍 Total Population

```DAX
Total Population = SUM(Countries_New[Population])
```

## 📊 Average Growth Rate

```DAX
Average Growth Rate =
AVERAGE(Growth_Rates[Population growth rate])
```

## 🏆 Population Rank

```DAX
Population Rank =
RANKX(
    ALL(Countries_New[Country]),
    [Total Population],
    ,
    DESC
)
```

## 🌐 Percentage of World Population

```DAX
% of World Population =
DIVIDE(
    [Total Population],
    CALCULATE([Total Population], ALL(Countries_New))
)
```


# 💡 Advanced Analytics Implemented

* Dynamic ranking calculations
* Percentage contribution analysis
* Context-aware filtering using `CALCULATE()`
* Interactive measure-driven visuals
* Aggregation and comparative analytics
* Drill-down and slicer-based exploration


# 🧠 Skills Demonstrated

* Data Cleaning & Transformation
* Data Modelling
* Dashboard Development
* Interactive Visualization
* Business Intelligence Reporting
* Analytical Thinking
* Advanced DAX Calculations
* Report Optimization


# 📈 Key Insights Generated

* Countries with the highest population were identified using ranking analysis
* Population growth trends highlighted rapidly growing regions
* Percentage contribution analysis showed distribution of World population
* Interactive visuals improved comparative and regional analysis
* Dashboard design enabled user-friendly data exploration


# 📷 Project Screenshots

This repository includes screenshots showcasing:

* Power Query transformation steps
* Query merge operations
* Data modelling relationships
* DAX calculations
* Interactive dashboard pages
* Population analysis visuals
* Slicer-based filtering


# 🚀 Project Objectives

* Transform raw population datasets into meaningful business insights
* Build an interactive analytical dashboard using Power BI
* Demonstrate practical data analytics and BI development skills
* Apply DAX calculations for dynamic reporting
* Create a professional portfolio-ready project



# 👨‍💻 Author

**Rohit P.B.**
Aspiring Data Analyst | Power BI Enthusiast | Business Intelligence Learner

---

⭐ If you found this project useful, feel free to star the repository and connect with me on LinkedIn!
