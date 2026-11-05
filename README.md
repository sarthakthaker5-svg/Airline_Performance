# ✈️ Airline Flight Delays Analysis Dashboard

<div align="center">

<img src="https://img.shields.io/badge/Power_BI-Data_Visualization-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI">

<img src="https://img.shields.io/badge/Power_Query-Data_Transformation-2673B8?style=for-the-badge" alt="Power Query">

<img src="https://img.shields.io/badge/DAX-Data_Analysis-CC0000?style=for-the-badge" alt="DAX">

<img src="https://img.shields.io/badge/Project-Airline_Flight_Delays-CC0000?style=for-the-badge" alt="Airline Flight Delays">

<br>

# ✈️ Airline Flight Delays Analysis

### Interactive Power BI Dashboard for Flight Performance, Delays, Cancellations and Trends

</div>

---

## 📖 Project Overview

The **Airline Flight Delays Analysis Dashboard** is an interactive Power BI project designed to analyze airline operations and flight performance from **2019 to 2023**.

The project transforms raw flight data into an interactive multi-page dashboard that helps analyze flight volume, airline performance, departure delays, cancellations, airport activity, and monthly trends.

The dashboard provides insights into:

- Total flight operations and airline performance.
- Flight cancellations and cancellation reasons.
- On-time versus delayed flight performance.
- Airport and state-level flight activity.
- Monthly flight volume trends.
- Average departure delays across different years.
- Airline-specific drill-through analysis.
- Forecasting future flight volume.

The report contains **five main analytical pages** and one custom tooltip page.

---

## 🎯 Project Objectives

- Import and transform airline flight data using Power Query.
- Prepare and clean flight-related columns for analysis.
- Create calculated measures using DAX.
- Analyze total flights, cancellations, delays, and on-time performance.
- Compare airline performance using interactive charts.
- Analyze cancellation rates by airline and year.
- Visualize airport activity using Bubble Maps.
- Analyze cancellation rates geographically using Filled Maps.
- Create interactive slicers and report navigation.
- Implement Drill-Through functionality for airline-level analysis.
- Analyze monthly flight volume and departure delay trends.
- Create a parameter-based analysis for minimum delay minutes.
- Build a professional multi-page Power BI dashboard.

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| **Power BI Desktop** | Dashboard development and visualization |
| **Power Query** | Data cleaning and transformation |
| **DAX** | Creating measures and calculations |
| **Power BI Maps** | Geographic analysis of airports and states |
| **Power BI Bookmarks** | Interactive show/hide filter functionality |
| **Drill-Through** | Airline-level detailed analysis |
| **Numeric Parameter** | Dynamic minimum delay analysis |

---

## 📊 Dashboard Pages

### 🏠 Page 1 – Overview

The Overview page provides a high-level summary of airline flight performance.

**Key Visuals:**

- KPI Cards for important flight metrics.
- Multi-row KPI summary.
- Cancellation Reason Breakdown.
- Flight Outcome Analysis.
- On-Time Rate Gauge.
- Airline slicer.
- Delay Status slicer.
- Interactive slicer panel.
- Metric Selector.
- Airline comparison chart.

---

### ✈️ Page 2 – Airline Performance

This page focuses on comparing airlines based on cancellations, delays, and on-time performance.

**Key Visuals:**

- Top 10 Airlines by Cancellations.
- Top 10 Airlines by Average Departure Delay.
- Cancellation Rate by Airline and Year Matrix.
- White-to-Red conditional formatting heatmap.
- Airline performance table.
- Year slicer.
- Drill-down hierarchy for Airline and Year.

---

### 🗺️ Page 3 – Route & Airport Map

This page provides geographical insights into flight operations and cancellations.

**Key Visuals:**

- Bubble Map showing Origin Airport activity.
- Bubble size based on Total Flights.
- Airport performance based on Average Departure Delay.
- Filled Map showing Cancellation Rate by State.
- Synchronized Year slicer.
- Custom Airport Tooltip.

---

### 🔍 Page 4 – Drill-Through Detail

This page provides detailed information about a selected airline.

Users can right-click an airline and navigate to this page using the **Drill-Through** feature.

**Key Visuals:**

- Total Flights KPI.
- Cancellation Rate KPI.
- Total Cancelled by Month.
- Cancellation Reason Donut Chart.
- On-Time Rate Trend by Year.
- Flight Details Table.
- Back Button for easy navigation.

---

### 📈 Page 5 – Trends & Forecast

This page focuses on historical flight trends and future analysis.

**Key Visuals:**

- Monthly Flight Volume by Year.
- Flight volume trend analysis.
- Monthly Average Departure Delay by Year.
- Flight Volume Forecast.
- Month range slicer.
- Minimum Delay Minutes parameter.
- Flights Above Minimum Delay KPI.

---

## 📐 Data Transformation

The dataset was prepared using **Power Query**.

Key transformation steps include:

- Setting correct data types.
- Extracting Year and Month from flight dates.
- Creating a continuous monthly date field.
- Replacing cancellation codes with readable names.
- Handling null values in delay-related columns.
- Creating a `Delay_Status` column.
- Preparing geographic fields for map visualizations.

### Delay Status Categories

Flights are categorized into:

- 🟢 On Time
- 🟡 Delayed
- 🔴 Cancelled
- 🔵 Diverted

---

## 🧮 Key DAX Measures

The dashboard uses DAX measures to calculate important business metrics.

Some key measures include:

| Measure | Purpose |
|---|---|
| `Total_Flights` | Calculates the total number of flights |
| `Total_Cancelled` | Calculates total cancelled flights |
| `Cancellation_Rate%` | Calculates the cancellation percentage |
| `On_Time_Rate%` | Calculates the percentage of on-time flights |
| `Avg_Dep_Delay` | Calculates average departure delay |
| `Flights_Above_Min_Delay` | Counts flights above the selected minimum delay |

---

## 🎛️ Interactive Features

The dashboard includes several interactive Power BI features:

### Slicers
Users can filter the report by:

- Airline.
- Year.
- Delay Status.
- Month.
- Minimum Delay Minutes.

### Drill-Through

Users can right-click an airline and open a detailed airline-specific analysis page.

### Navigation

A navigation bar allows users to move between:

**Overview → Airlines → Map → Detail → Trends**

### Metric Selector

Users can dynamically change the metric used for airline comparison.

### Numeric Parameter

The **Minimum Delay Minutes** parameter allows users to select a delay threshold and dynamically view the number of flights exceeding that value.

---

## 📊 Key Insights Supported by the Dashboard

The dashboard helps answer questions such as:

- Which airlines have the highest number of cancellations?
- Which airlines experience the highest average departure delays?
- How does cancellation performance change over time?
- Which airports handle the highest flight volume?
- Which states have higher cancellation rates?
- How did flight volume change between 2019 and 2023?
- How do monthly departure delays vary across years?
- How many flights exceed a selected delay threshold?

---

## 🎨 Dashboard Design

The report follows a consistent **Red and White professional design theme**.

| Design Element | Configuration |
|---|---|
| Primary Colour | `#CC0000` |
| Background | `#F5F5F5` |
| Visual Background | `#FFFFFF` |
| Layout | 16:9 |
| Navigation | Consistent across all main pages |
| Visual Style | Clean, professional and interactive |

---

## 🚀 How to Use the Project

1. Download or clone this repository.
2. Open the `.pbix` file using **Power BI Desktop**.
3. Refresh the dataset if required.
4. Use the navigation bar to move between pages.
5. Use slicers to filter the data.
6. Right-click an airline to access the Drill-Through Detail page.
7. Adjust the Minimum Delay Minutes parameter to perform dynamic analysis.

---

## 📁 Project Structure

```text
Airline-Flight-Delays-Analysis/
│
├── Airline_Flight_Delays.pbix
├── README.md
└── Dataset/
    └── flights_sample_3m.csv
```

---

## 📌 Project Features

✔ Multi-page Power BI Dashboard  
✔ Data Cleaning with Power Query  
✔ DAX Measures and KPIs  
✔ Interactive Slicers  
✔ Conditional Formatting  
✔ Bubble and Filled Maps  
✔ Custom Tooltips  
✔ Drill-Through Analysis  
✔ Report Navigation  
✔ Numeric Range Parameter  
✔ Trend and Forecast Analysis  

---

## 👨‍💻 Author

**Sarth Thakar**
