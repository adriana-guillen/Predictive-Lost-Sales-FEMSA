# The Bodega Problem: Revenue Leakage from Hidden Inventory.

## Executive Summary.

This project addresses a hidden source of revenue leakage in retail operations, where products remain in backroom inventory due to limited shelf space, making them effectively unavailable for purchase.

This initiative is based on a real operational challenge observed during my experience at FEMSA.

A predictive model was developed to quantify the financial impact of unexhibited inventory by estimating the relationship between product visibility and sales performance under realistic retail conditions.

At the store level, the analysis shows that approximately **12% of the assortment** is affected by hidden inventory, with an average estimated impact of **4,531 MXN per store** (≈ **257 USD**). The primary driver of lost sales is **product price**, with higher-value items experiencing disproportionately larger revenue losses when not displayed.

Following initial validation in a single store, the approach was expanded across **one Region (multi-store)**, confirming the consistency and scalability of the findings. The implementation of an **Inventory Visibility KPI** enabled continuous monitoring of merchandising execution and early detection of revenue leakage.

These results demonstrate that targeted **SKU-level visibility management** can help recover revenue by prioritizing high-impact products for display and improving in-store execution.

When extrapolated across a network of 13,000 stores (in 2013; Oxxo currently operates more than 23,000 stores in Mexico), this translates into a **simulated recoverable revenue of approximately** **58.9 million MXN*** (≈ **3.34 million USD**), demonstrating how small visibility gaps at the store level can compound into meaningful financial impact at scale.

*Note: Network extrapolation represents a directional estimate based on observed assortment-level impact and is intended to illustrate magnitude rather than exact realized value.*

*No proprietary or confidential data from FEMSA or any organization is included.*

---

## Full Analysis.

The complete methodology, data preparation, modeling approach, and detailed results are available in the notebook:
[View Notebook](https://github.com/adriana-guillen/bodega-revenue-leakage/blob/main/bodega_revenue_leakage.ipynb)



