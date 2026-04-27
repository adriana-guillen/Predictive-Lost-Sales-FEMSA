# The Bodega Problem: Revenue Leakage from Hidden Inventory.

## 1. Executive Summary
This project estimates revenue loss caused by inventory that is available in-store but not visible to customers due to display constraints.

Using a regression-based approach, the model quantifies the gap between expected and realized sales, translating operational inefficiencies into measurable financial impact.

The analysis demonstrates that unexhibited inventory is not a minor execution issue, but a significant source of revenue leakage that can be systematically identified and reduced.

---

## 2. Business Context
In retail operations, product availability does not guarantee product visibility.

At FEMSA, a recurring issue was identified where inventory was physically present in stores but remained unexhibited due to shelf space limitations, poor replenishment practices, or operational inefficiencies.

This resulted in lost sales opportunities, as customers could not purchase products that were not accessible on shelves.

---

## 3. Analytical Objective
To estimate the financial impact of unexhibited inventory by:

- Predicting expected sales based on demand drivers and product characteristics  
- Comparing expected vs. actual sales to quantify lost revenue  
- Identifying which product categories and store conditions generate the highest revenue leakage  

---

## 4. Approach
A regression modeling framework was applied to estimate expected sales under normal exhibition conditions.

Key elements include:

- Feature engineering on demand drivers, stock levels, and product attributes  
- Correlation analysis to identify key predictors of sales performance  
- Model training using regression techniques (scikit-learn and statsmodels)  
- Evaluation of model performance and residual analysis  

The difference between predicted (expected) sales and actual sales is interpreted as lost sales due to lack of visibility.

---

## 5. Key Results
- Significant revenue gaps were identified between expected and actual sales across multiple product categories  
- High-stock, low-visibility products consistently generated the largest losses  
- The model provides a scalable method to estimate lost sales at the SKU and store level  

---

## 6. Operational Implications
The results support a shift from reactive inventory management to visibility-driven execution.

Key applications include:

- Prioritizing shelf space allocation based on revenue impact  
- Identifying stores with systematic exhibition gaps  
- Improving replenishment and display strategies  
- Supporting operational audits with quantitative evidence  

---

## 7. Business Value
This solution reframes inventory visibility as a measurable financial lever rather than an operational detail.

By quantifying lost sales, organizations can:

- Recover hidden revenue without increasing inventory investment  
- Improve capital efficiency by aligning stock with actual demand exposure  
- Enable faster, data-driven decisions in store operations  

---

## 8. Data Disclaimer
The dataset used in this project is fully synthetic and anonymized.

It was designed to replicate real operational patterns observed in retail environments, including inventory behavior, demand variability, and product visibility constraints.

No proprietary or confidential data from FEMSA or any organization is included.

