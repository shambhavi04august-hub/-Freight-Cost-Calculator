# 🚚 Freight Cost Calculator

A modern logistics web application that helps users estimate shipping costs for **Air Freight** and **Sea Freight** shipments. The calculator automatically determines chargeable weight, calculates freight charges, and provides a detailed cost breakdown for better logistics planning and decision-making.

## 📌 Project Overview

Freight Cost Calculator is designed for freight forwarders, exporters, importers, and logistics professionals who need quick and accurate shipment cost estimates.

The application calculates freight charges based on shipment weight, dimensions, destination, and transportation mode while providing transparent pricing insights.

## ✨ Features

### 📦 Shipment Information

* Origin & Destination Selection
* Shipment Type Selection
* Package Dimensions
* Actual Weight Input
* Cargo Details

### 📏 Volumetric Weight Calculator

Automatically calculates volumetric weight using:

**Air Freight Formula**

```text
Volumetric Weight = (Length × Width × Height) / 5000
```
The system automatically selects the higher value between:

* Actual Weight
* Volumetric Weight

to determine the **Chargeable Weight**.

### 🚚 Freight Modes

* Air Freight
* Sea Freight (LCL)
* Sea Freight (FCL)

### 💰 Cost Breakdown

* Freight Charges
* Fuel Surcharge
* Documentation Charges
* Customs Charges
* Insurance Charges
* Taxes/GST

### 📊 Analytics Dashboard

* Cost Summary Cards
* Charge Distribution Charts
* Freight Cost Breakdown
* Transit Time Estimation
* Shipment Summary Report

## 🛠️ Tech Stack

| Technology   | Purpose              |
| ------------ | -------------------- |
| React.js     | Frontend Development |
| JavaScript   | Business Logic       |
| HTML5        | Structure            |
| CSS3         | Styling              |
| Chart.js     | Data Visualization   |
| React Icons  | UI Components        |
| GitHub Pages | Deployment           |

## 📂 Project Structure

```text
freight-cost-calculator/

├── public/

├── src/
│
├── components/
│   ├── FreightForm.jsx
│   ├── CostSummary.jsx
│   ├── VolumetricCalculator.jsx
│   ├── CostBreakdownChart.jsx
│   ├── TransitEstimator.jsx
│
├── data/
│   └── freightRates.js
│
├── App.js
├── App.css
├── index.js
│
├── package.json
├── README.md
└── LICENSE
```

## 🖥️ Dashboard Preview

![Freight Cost Calculator Dashboard.png](freight-cost-calculator)

## 📊 Sample Calculation

### Shipment Details

| Parameter   | Value           |
| ----------- | --------------- |
| Origin      | India           |
| Destination | USA             |
| Weight      | 50 kg           |
| Dimensions  | 60 × 50 × 40 cm |
| Mode        | Air Freight     |

### Volumetric Weight

```text
(60 × 50 × 40) ÷ 5000
= 24 kg
```
### Chargeable Weight

```text
Actual Weight = 50 kg
Volumetric Weight = 24 kg

Chargeable Weight = 50 kg
```

## 🎯 Business Benefits

* Faster Freight Quotations
* Accurate Pricing Estimates
* Reduced Manual Calculations
* Better Shipment Planning
* Improved Customer Experience
* Enhanced Cost Transparency

## 📈 Future Enhancements

* Real-Time Freight Rate API
* Multi-Currency Support
* Shipment Tracking Integration
* Carrier Rate Comparison
* AI-Based Cost Prediction
* Export PDF Quotations
* Customer Login System

## 💼 Use Cases

* Freight Forwarding Companies
* Logistics Service Providers
* Import & Export Businesses
* Supply Chain Professionals
* Shipping Consultants

## 🌟 Key Highlights

* Real-time Freight Cost Calculation
* Volumetric Weight Estimation
* Interactive Cost Analytics
* Modern Responsive UI
* Logistics Industry Use Case
* MBA Logistics Portfolio Project

## 👩‍💻 Author

**Shambhavi Tripathi**

MBA (Logistics & Supply Chain Management)

AirVault Express & Logistics – Internship Project

## 📄 License

This project is developed for educational, internship, and portfolio purposes. Feel free to use and modify it for learning and professional development. 🚚📦✨
