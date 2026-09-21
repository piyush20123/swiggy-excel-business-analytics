# Swiggy Business Analytics Dashboard — Microsoft Excel

An interactive business analytics dashboard built in Microsoft Excel to analyze food-delivery business performance across orders, restaurants, delivery, customers, payments, and menu items.

## 📊 Project Overview

This project transforms a large food-delivery dataset into an interactive analytical dashboard using Excel's data preparation, data modeling, visualization, and automation capabilities.

The dashboard allows users to explore business performance dynamically using filters such as:

- City
- Service Type
- Year
- Month

## 🛠️ Tools & Technologies

- Microsoft Excel
- Power Query
- Excel Data Model
- DAX Measures
- PivotTables
- PivotCharts
- Slicers & Timeline
- VBA Automation

## 📈 Dashboard Pages

### Business Overview
Provides a high-level view of business performance through KPIs such as:

- Total Orders
- Delivered Orders
- Cancelled Orders
- Delivered Value
- Net Revenue
- Average Order Value
- On-Time Rate
- Cancellation Rate

### Restaurant Performance
Analyzes:

- Top restaurants by delivered value
- Restaurant partner types
- Cuisine performance
- Price-range contribution

### Delivery Performance
Analyzes:

- Average delivery time
- On-time delivery rate
- Delivery performance by city
- Traffic impact on delivery time
- On-time vs late deliveries

### Customer Experience
Analyzes:

- Active customers
- Customer age groups
- Membership performance
- Customer reviews
- Food ratings
- Review sentiment

### Payments & Revenue
Analyzes:

- Monthly net revenue
- Payment methods
- Payment status
- Cancellation reasons

### Menu & Item Sales
Analyzes:

- Delivered units
- Item sales
- Menu categories
- Item cuisines
- Veg vs non-veg sales
- Top menu items

## ⚙️ Key Features

### Interactive Analysis
City, Service Type, Year and Timeline filters are connected across the dashboard pages, allowing users to analyze the same business metrics from different perspectives.

### Data Preparation
Power Query was used for data cleaning, transformation and preparation before analysis.

### Data Modeling
An Excel Data Model was used to connect the analytical tables and support reusable DAX measures.

### KPI & Business Metrics
Custom DAX measures were created for business metrics including revenue, delivered orders, customer activity, delivery performance, reviews and item sales.

### VBA Automation
VBA was used to add dashboard automation features including:

- Reset Filters
- Refresh Dashboard
- Export Current Page to PDF

### VBA Data Assistant
The project also includes a VBA-based Data Assistant that allows users to enter questions in natural-language style.

Example:

> "Tell me the Mumbai revenue from June 2025"

The assistant interprets the city, month, year and requested metric and retrieves the corresponding result from the analytical model.

## 🖼️ Dashboard Preview

### Business Overview

<img width="1079" height="625" alt="Screenshot 2026-09-20 at 7 41 10 PM" src="https://github.com/user-attachments/assets/af6e40c0-95e7-468c-8ebb-e72bf059a9b4" />


### Customer Experience

<img width="1030" height="573" alt="Screenshot 2026-09-20 at 7 41 31 PM" src="https://github.com/user-attachments/assets/8eccb95c-d01f-4884-ad00-477ddbf48b80" />


### VBA Data Assistant

<img width="930" height="532" alt="Screenshot 2026-09-20 at 7 41 46 PM" src="https://github.com/user-attachments/assets/bebc4ff0-701f-4d0c-b681-909809fd5962" />


## 📁 Repository Structure

```text
swiggy-excel-business-analytics/
│
├── README.md
│
├── dashboard/
│   └── swiggy_dashboard.xlsm
│
└── screenshots/
    ├── overview.png
    ├── customers.png
    └── chatbot.png
