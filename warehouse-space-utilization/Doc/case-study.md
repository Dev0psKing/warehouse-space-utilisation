# Case Study: The Paradox of "Full but Empty"

This scenario demonstrates the conflict between Operational metrics and Analyst metrics, and how to resolve it.

## The Scenario
*   **Operations Manager:** "We are full! Stop the inbound trucks. I have nowhere to put pallets."
*   **Supply Chain Analyst:** "My dashboard says Cubic Utilisation is only 12%. We have plenty of room."

## The Data
| Metric | Value | Status |
| :--- | :--- | :--- |
| **Pallet Position Utilisation** | **95%** | CRITICAL (Full) |
| **Cubic Utilisation** | **12%** | LOW (Empty) |

## The Analysis
**Who is right?** They are both right.
The warehouse is out of **slots** (2D floor spots), but it is full of **air** (3D volume).

**The Root Cause:**
The racking profile is designed for 2.0m tall pallets, but the current inventory consists of 0.8m tall pallets.
*   **Slot Status:** Occupied (100% used).
*   **Volume Status:** The 1.2m of space *above* the pallet is wasted air.

## The Solution
When this gap exists, **do not rent more space.** You must fix the profile.

1.  **Re-profile Racks:** Lower the beams to fit the shorter pallets tighter. This could create space for a 6th or 7th beam level.
2.  **Consolidate SKUs:** Identify pallets of the same SKU that are half-empty and merge them to free up a slot.
3.  **Tunneling:** Utilize space above cross-aisles for slow-moving bulk storage.

## Conclusion
*   Use **Pallet Utilisation** for daily execution (Receiving/Shipping).
*   Use **Cubic Utilisation** for strategic planning (Layout Design/Expansion).

---
*You have reached the end of the guide.*
👈 [**Previous: Pallet Utilisation**](pallet-utilisation.md) | 🏠 [**Back to Home**](index.md)