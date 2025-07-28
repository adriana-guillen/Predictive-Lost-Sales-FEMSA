# Predictive Lost Sales – FEMSA

This project is inspired by a real business case I led during my time at a major retail group in Mexico (FEMSA).

It SIMULATES lost sales due to unexhibited inventory, using fully anonymized and simulated data based on the original business scenario.

This project simulates a real business case originally led at FEMSA, focused on estimating lost sales from unexhibited inventory in retail operations. 

The objective is to predict the financial impact of products stored in the warehouse but not visible on store shelves — a critical issue in retail execution.

---

## 🎯 Project Objective
To build a predictive model that estimates the value of lost sales per product category and store based on inventory levels, sales patterns, and visibility variables.

---

## 🛠️ Tools Used
- Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
- Jupyter Notebook
- CSV Simulated Data

---

## 📊 Data Used
The dataset simulates a subset of inventory and sales activity across retail stores.

**Filename**: `inventory_femsa_simulated_database.csv`  
*Note: Based on a real business case. No confidential data is shared.*

---

## ⚙️ Modeling Approach
The model uses regression techniques to estimate expected sales and identify the delta between expected and actual sales when items were not exhibited. Feature engineering, correlation analysis, and performance evaluation are included.

---

## 💡 Key Insights
- Product categories with high stock but low exhibition contribute most to lost sales.
- Regional variation plays a role in replenishment efficiency.
- Predictive modeling helps quantify potential recovery from better inventory visibility.

---

## 📘 Notebook
You can explore the full project implementation here:

👉 [Predictive_Lost_Sales_V6.ipynb](./Predictive_Lost_Sales_V6.ipynb)

The notebook includes:
- Data cleaning & preprocessing
- Exploratory data analysis
- Regression modeling using both scikit-learn and statsmodels
- Visualizations with Matplotlib and Seaborn
- Final business interpretation and conclusions

---

## 📬 Contact
For questions or collaboration inquiries, feel free to reach out via [LinkedIn](https://www.linkedin.com/) or check out my [portfolio](https://github.com/adriana-guillen).
