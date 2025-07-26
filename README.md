# E‑Commerce Sales Dashboard

A Power BI dashboard showcasing key sales metrics, trends, and high-revenue product/category insights based on the 2009–2010 UK online retail dataset.

---

## 📁 Repository Structure

```
.
├── data/
│   └── cleaned_sales.csv         # Cleaned & prepared sales data
├── dashboard/
│   └── E‑Commerce sales dashboard.pbix  # Power BI .pbix dashboard file
├── docs/
│   └── PowerBI_Dashboard_Guide.pptx      # Build guide & data model diagram
└── README.md                     # This file
```

---

## 🚀 Getting Started

### Prerequisites

- **Power BI Desktop** (Windows)  
  Download from the Microsoft Store or https://powerbi.microsoft.com/desktop/.

- **Git** (optional, for cloning)  
  ```bash
  git clone https://github.com/your‑username/ecommerce‑sales-dashboard.git
  cd ecommerce‑sales-dashboard
  ```

### Opening the Dashboard

1. Launch **Power BI Desktop**.  
2. From the **Home** tab, choose **Open** and navigate to:
   ```
   dashboard/E‑Commerce sales dashboard.pbix
   ```
3. Power BI will prompt to load the data model. Ensure it points to:
   ```
   data/cleaned_sales.csv
   ```

---

## 📊 Dashboard Contents

- **KPI Cards**:  
  - Total Revenue  
  - Total Orders  
  - Distinct Customers  

- **Date Slicer**: Filter by Month

- **Line Chart**: Monthly revenue trend

- **Map Visual**: Revenue by country (bubble size = revenue)

- **Bar Chart**: Top N products by revenue

- **Decomposition Tree**: Drill into revenue by product → country → month

- **Custom Tooltips**:  
  - Customer count  
  - Average order value  
  - Quantity sold  
  - % of total revenue  

---

## 📑 Power BI Build Guide

For an in‑depth step‑by‑step on data model, DAX measures, and report layout, see:

```
docs/PowerBI_Dashboard_Guide.pptx
```

---

## 🛠️ Customizing & Extending

- **Data Updates**  
  - Replace `data/cleaned_sales.csv` with your own cleaned dataset (same schema).  
  - In Power BI, click **Transform Data** → **Data Source Settings** to re-point the CSV source.

- **Adding Categories**  
  - To slice by product category, import a `Products` lookup table with `StockCode → Category`, then define a model relationship.

- **New Measures**  
  - Open **Modeling → New measure** and paste or adjust DAX formulas in the guide.

- **Visual Tweaks**  
  - Use the **Visualizations** pane to change chart types, colors, or enable drill‑through.



## 🔗 Useful Links

- [Power BI Documentation](https://docs.microsoft.com/power‑bi/)  
- [DAX Reference](https://docs.microsoft.com/dax/)  

