# Warehouse Space Utilization Framework & Excel Calculator

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Status](https://img.shields.io/badge/status-stable-green.svg)
![Tools](https://img.shields.io/badge/tools-Excel%20%7C%20No%20Macros-success)

A practical, engineering-first approach to understanding and calculating warehouse space utilization using first principles and spreadsheet modeling.

This project breaks warehouse utilisation down to its fundamentals - **the box (warehouse), the grid (racking), and the object (pallet)** - and provides a reusable Excel-based calculator for capacity and utilization analysis.

<!-- 
    TODO: UPLOAD A SCREENSHOT OF YOUR EXCEL DASHBOARD TO assets/screenshots/dashboard.png 
    THEN UNCOMMENT THE LINE BELOW 
-->
<!-- ![Dashboard Preview](assets/screenshots/dashboard.png) -->

---

## 🎯 Project Objective

Many warehouses feel “full” while still wasting significant space.  
This project was built to answer two critical questions clearly and separately:

1.  **Are we running out of pallet slots right now?** (Pallet Capacity)
2.  **Are we efficiently using the physical volume of the building?** (Cubic Capacity)

By separating **Pallet Position Utilization** from **Cubic Utilization**, this framework helps warehouse and supply chain professionals make better operational and strategic decisions.

---

## 👥 Who This Is For

This project is designed for:
- **Warehouse Managers** looking to optimize current layouts.
- **Supply Chain Analysts** needing data for capacity planning.
- **Industrial Engineers** designing new racking configurations.
- **WMS Implementers** validating system volume calculations.

---

## 🧠 Core Concepts Covered

- **Warehouse Physics:** Treating dimensions as a 3-D physical system.
- **The Void:** Gross vs. Usable warehouse volume.
- **The Cube:** Detailed Inventory cube calculation formulas.
- **The Paradox:** Why warehouses can be "full" and "empty" at the same time.
- **Honeycombing:** The hidden efficiency killer in racking.

---

## 📊 Excel Template (Main Deliverable)

The Excel model included in this repository calculates:
- Total warehouse cubic capacity
- Usable warehouse volume (after operational constraints)
- Inventory cube consumption
- Cubic utilization percentage
- Pallet position utilization percentage
- SKU-level space usage

### Key Features
*   ✅ **Formula-driven:** No VBA/Macros required (Security friendly).
*   ✅ **Structured Inputs:** Clearly defined "Config" and "Data" tabs.
*   ✅ **Agnostic:** Works with Excel 2016+, Office 365, and Google Sheets.
*   ✅ **Visuals:** Auto-updating heatmaps and capacity gauges.

📁 **Location:**  
`/template/Warehouse_Space_Utilization_Calculator.xlsx`

📥 **Download:**  
[**Download the Excel Utilization Calculator**](https://github.com/Dev0psKing/warehouse-space-utilisation/blob/master/warehouse-space-utilization/Template/Warehouse%20Space%20Utilisation%20Calculator.xlsx)

*(Click link to download raw file directly)*

---

## 🗂 Repository Structure

```text
warehouse-space-utilization/
│
├── README.md              # Project Overview
├── LICENSE                # MIT License
│
├── docs/                  # The Engineering Framework
│   ├── index.md
│   ├── warehouse-physics.md
│   ├── cubic-utilisation.md
│   ├── pallet-utilisation.md
│   └── case-study.md
│
├── template/              # The Tool
│   └── Warehouse_Space_Utilization_Calculator.xlsx
│
└── assets/                # Images
    └── screenshots/
