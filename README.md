# Uber 2025 Booking Analytics

> Explore booking trends, key performance indicators, revenue, and operational insights.

## 📊 Project Overview

This project presents an interactive Power BI dashboard built to analyze Uber ride booking data. The dashboard consolidates booking, revenue, distance, vehicle, and rider information into a multi-page report that helps identify booking performance trends, revenue patterns, and operational insights.

The report is organized into four pages: **Overview**, **Vehicle**, **Revenue**, **Rider**, and **Location**, each focused on a specific analytical view of the booking data.

## 🎯 Business Objective

The project is based on a documented set of business requirements defining the KPIs and analysis needed to understand Uber booking performance, including completed vs. lost bookings, revenue generation, distance travelled, vehicle-wise performance, and rider behavior.

## 📌 Key KPIs

| KPI | Description |
|---|---|
| Completed Bookings | Number of successfully completed ride bookings |
| Lost Bookings | Number of bookings that were cancelled or not completed |
| Revenue | Total revenue generated from bookings |
| Total Distance | Total distance travelled across all bookings |
| Avg Distance | Average distance travelled per booking |
| Avg Rider Rating | Average rating given by riders |
| Avg Driver Rating | Average rating given to drivers |

## 📈 Dashboard Features

Based on the documented business requirements, the dashboard includes:

**Overview Page**
- KPI cards for Completed Bookings, Lost Bookings, Revenue, Total Distance, and Avg Distance
- Vehicle filter
- Monthly analysis of Bookings Completed and Revenue
- Quarterly analysis of Bookings Completed and Revenue
- Revenue by Vehicle Type
- Top pickup and drop locations by booking count
- Average Rider and Driver ratings

**Vehicle Page**
- Detailed vehicle-wise breakdown: Booking Count, Revenue, and Contribution

**Revenue Page**
- Revenue by Customer, Vehicle, and Payment Method
- Monthly and quarterly revenue breakdown

**Rider Page**
- Cancelled rides by reason
- Breakdown by Payment Method
- Monthly and quarterly rider trends
- Detailed data table covering First Rider, Return Rider, and Regular Rider segments

**Location Page**
- Monthly total distance
- Total distance by vehicle
- Busy time slots
- Busy areas

**General**
- Show/hide filter panel for clean, uncluttered viewing
- Multiple interactive filters across report pages

## 🖼️ Dashboard Preview

*Dashboard page screenshots (Overview, Vehicle, Revenue, Rider, Location) will be added here once exported from Power BI Desktop.*

> Note: The `Images/` folder currently contains custom icon and background assets used within the Power BI report (e.g., vehicle icons, UI icons, background shapes) rather than full dashboard page screenshots.

## 🛠️ Tools & Technologies

- Microsoft Power BI (Power BI Desktop)
- Power Query (data transformation)
- DAX (calculated measures and KPIs)
- Microsoft Excel (source dataset)

## 📂 Repository Structure

```
uber-2025-booking-analytics/
├── README.md
├── Uber Dashboard.pbix                              # Power BI dashboard file
├── Uber Problems and Bussiness Requirements.docx    # Documented business requirements and KPI definitions
├── Dataset/
│   └── uber.xlsx                                     # Source Uber booking dataset
└── Images/
    └── Icon and background assets used within the Power BI report
```

## 🔍 Key Insights

The dashboard is designed to support insights such as completed vs. lost booking trends, monthly and quarterly revenue and booking patterns, revenue distribution by vehicle type and payment method, top pickup/drop locations, busy time slots and areas, and rider segmentation (first-time, returning, and regular riders). Specific numeric insights depend on the underlying dataset within the Power BI file.

## 🚀 Conclusion

Uber 2025 Booking Analytics demonstrates the application of Power BI, Power Query, and DAX to translate raw ride-booking data into a structured, multi-page analytical dashboard covering bookings, revenue, vehicles, riders, and locations — supporting data-driven business decision-making.
