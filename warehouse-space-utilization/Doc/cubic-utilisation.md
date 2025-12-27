# Metric #1: Cubic Utilisation (The "Air" Check)

Cubic Utilisation tells you how much of your usable space is occupied by solid product, and how much is just air. This is a **Strategic Metric**.

## 1. The Inventory Cube
We must measure the volume of the goods inside the box. Every pallet occupies a specific volume defined by its footprint and loaded height.

**Example Pallet:**
*   Dims: 1.2m (L) x 1.0m (W) x 1.5m (H)
*   **Single Pallet Cube:** $1.2 \times 1.0 \times 1.5 = 1.8 m^3$

If the WMS reports **1,000 pallets** in stock:
$$ Inventory Cube = 1,000 \times 1.8 m^3 = 1,800 m^3 $$

## 2. The Formula
$$ Cubic Utilisation = \frac{Inventory Cube}{Usable Warehouse Cube} $$

Using our previous warehouse data:
$$ \frac{1,800}{18,000} = 0.10 (10\%) $$

## 3. What this means
In this scenario, only **10%** of the usable space is physically occupied by goods. The rest is air—empty aisles, space above pallets, or flue space.

> **Analyst Note:** While 10% seems low, world-class facilities rarely exceed 25-30% true cubic utilisation due to accessibility requirements. However, if this number is dropping while pallet count is rising, you are wasting vertical space.

---
*We know the volume, but do we have enough physical slots?*
👈 [**Previous: Physics**](warehouse-physics.md) | 👉 [**Next: Metric #2 - Pallet Utilisation**](pallet-utilisation.md)