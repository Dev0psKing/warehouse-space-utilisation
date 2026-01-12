# Warehouse Space Utilization Framework & Excel Calculator

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Status](https://img.shields.io/badge/status-stable-green.svg)
![Tools](https://img.shields.io/badge/tools-Excel%20%7C%20No%20Macros-success)

A practical, engineering-first approach to understanding and calculating warehouse space utilisation using first principles and spreadsheet modeling.

This project breaks warehouse utilisation down to its fundamentals - **the box (warehouse), the grid (racking), and the object (pallet)** - and provides a reusable Excel-based calculator for capacity and utilisation analysis.

<!-- 
    TODO: UPLOAD A SCREENSHOT OF YOUR EXCEL DASHBOARD TO assets/screenshots/dashboard.png 
    THEN UNCOMMENT THE LINE BELOW 
-->
 ## **Dashboard Preview**
 
 <img width="1043" height="194" alt="image" src="https://github.com/user-attachments/assets/07081033-e7f3-4bae-a83c-89718ec3b1e6" />



---

## 🎯 Project Objective

Many warehouses feel “full” while still wasting significant space.  
This project was built to answer two critical questions clearly and separately:

1.  **Are we running out of pallet slots right now?** (Pallet Capacity)
2.  **Are we efficiently using the physical volume of the building?** (Cubic Capacity)

By separating **Pallet Position Utilisation** from **Cubic Utilisation**, this framework helps warehouse and supply chain professionals make better operational and strategic decisions.

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

```

- **docs/** → Technical explanations and framework logic  
- **template/** → Excel utilisation calculator  
- **assets/** → Visual references (screenshots, diagrams)

---

## 🚀 How to Use This Project

1.  **Review the Theory:** Read `/docs/warehouse-physics.md` to understand the logic.
2.  **Open the Template:** Download the Excel file from the `/template` folder.
3.  **Input Data:**
    - Enter Warehouse dimensions (The Box)
    - Enter Rack configuration (The Grid)
    - Enter Inventory counts (The Object)
4.  **Analyze:** Use the "Dashboard" tab to identify bottlenecks and support redesign decisions.

---

## 📌 Why This Project Matters

Warehouse utiliSation is often misunderstood because volume and slot availability are mixed together.

This framework helps teams:
- **Stop guessing** about capacity.
- **Avoid premature expansion** (CapEx avoidance).
- **Improve storage efficiency** using data, not intuition.

---

## 📄 Related Article

This project is based on the concepts explained in the article:

**A Definitive Guide to Warehouse Utilisation**  
[Read the full article on Forem](https://forem.com/devopsking/a-definitive-guide-to-warehouse-utilisation-3b33)

---

## 🤝 Contributing

Contributions are welcome! If you have ideas for better formulas, Python automation scripts, or visualization improvements:
1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Open a Pull Request

---

## 👤 Author

**Uwabor**  
*Building technical solutions for Supply Chain & Logistics.*

*   **Blog:** [Forem](https://forem.com/devopsking)
*   **Connect:** [LinkedIn](https://linkedin.com/in/collins-uwabor)

---

*Starred this repo? ⭐ Feel free to fork it and adapt it for your own facility!*
```
