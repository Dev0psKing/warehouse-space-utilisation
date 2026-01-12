# 📊 Warehouse Space Utilization Calculator

**File Name:** `Warehouse_Space_Utilization_Calculator.xlsx`  
**Format:** Microsoft Excel (.xlsx)  
**Macros:** ❌ None (Safe for corporate/restricted environments)

## 📝 Overview
This Excel model is the calculation engine behind the [Project Documentation](../docs/index.md). 

It is designed to solve the **"Paradox of Fullness"**—visualizing the discrepancy between Pallet Utilization (how many slots are full) and Cubic Utilization (how much volume is used).

---

## 📥 How to Download

**Option 1: Direct Download (Recommended)**  
[**Click here to download the .xlsx file**](../template/Warehouse_Space_Utilization_Calculator.xlsx?raw=true)

**Option 2: GitHub View**  
1. Click the file name `Warehouse_Space_Utilization_Calculator.xlsx` in the file list above.
2. Click the **Download** icon (or "View Raw") on the right side of the screen.

---

## ⚙️ How to Use This Tool

The spreadsheet follows a strict **Input (Yellow)** vs. **Output (Green)** color-coding standard to prevent accidental formula breakage.

### 1. Worksheet Structure
The workbook is divided into three key tabs:

| Tab Name | Function | Concept Mapping |
| :--- | :--- | :--- |
| **1. Dashboard** | High-level KPIs, Gauges, and Summary metrics. | *The Result* |
| **2. Config_Inputs** | Warehouse dimensions, Rack definition, and Operational constraints. | *The Box & The Grid* |
| **3. Inventory_Data** | SKU-level or Pallet-level data entry. | *The Object* |

### 2. Step-by-Step Guide

#### Step A: Define "The Box" & "The Grid" (Config Tab)
*   **Warehouse Dimensions:** Enter Length, Width, and Clear Height (m/ft).
*   **Operational Constraints:** Input your "Usable Space Factor" (default is roughly 85% to account for columns/panels).
*   **Rack Configuration:** Define your Rack Type, Beam Length, and Levels per Bay.

#### Step B: Define "The Object" (Inventory Tab)
*   **Inventory Data:** Paste your current WMS snapshot.
*   **Pallet Dimensions:** Ensure you input the *average* height of pallets (including the wood/plastic base).

#### Step C: Analyze (Dashboard Tab)
*   **Gross vs. Usable Volume:** The tool automatically subtracts aisle and flue space.
*   **Cubic Utilization %:** The strategic "Air Check."
*   **Pallet Utilization %:** The operational "Slot Check."

---

## 💻 Compatibility

| Software | Status | Notes |
| :--- | :--- | :--- |
| **Microsoft Excel** | ✅ Fully Compatible | Best experience (2016, 2019, 365). |
| **Google Sheets** | ✅ Compatible | formating may vary slightly. |
| **LibreOffice** | ⚠️ Likely Compatible | Formulas are standard, but charts may shift. |

---

## ⚠️ Disclaimer
*This tool is for estimation and planning purposes only. Always verify structural load capacities with a licensed structural engineer before changing racking configurations.*

---
*Return to the [Main Documentation](../README.md)*
