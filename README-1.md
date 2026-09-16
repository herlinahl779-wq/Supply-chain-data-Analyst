# Supply Chain Data Analyst

Exploratory data analysis and interactive dashboard on a supply chain dataset (100 SKUs), covering revenue performance, supplier evaluation, shipping cost & time by transportation mode, and product quality inspection results.

## 📌 Project Overview

This project analyzes a supply chain dataset to answer key business questions:

- Which product category and supplier generate the most revenue?
- How do shipping cost and shipping time vary across transportation modes (Road, Air, Rail, Sea)?
- What is the overall product quality performance based on inspection results and defect rates?
- Which SKUs are top performers, and which have quality issues (high defect rate)?

## 🗂️ Dataset

- **File:** `supply_chain_data.csv`
- **Rows:** 100 SKUs
- **Columns:** 24, including Product type, Price, Revenue generated, Supplier name, Shipping costs, Shipping times, Transportation modes, Defect rates, Inspection results, and more.

## 🛠️ Tools & Tech Stack

- **Python** (Pandas) — data cleaning, aggregation, and exploratory analysis
- **Matplotlib** — static visualizations (bar chart, pie chart, scatter plot)
- **Tableau Public** — interactive dashboard

## 📊 Key Analysis

1. **Revenue Analysis** — total revenue and units sold by product type
2. **Supplier Performance** — revenue contribution, average lead time, and defect rate per supplier
3. **Transportation & Shipping** — average shipping cost and shipping time by transportation mode
4. **Quality Control** — distribution of inspection results (Pass/Fail/Pending) and defect rate analysis
5. **Correlation Analysis** — relationship between price, revenue, defect rate, lead time, and cost

## 📁 Repository Structure

```
├── supply_chain_data.csv                      # Raw dataset
├── supply_chain_analysis.py                   # Full analysis script
├── supply_chain_analysis_pemula.py            # Beginner-friendly version (step-by-step, heavily commented)
├── supply_chain_analysis_pemula_visual.py     # Beginner-friendly version with visualizations
├── summary_revenue_by_type.csv                # Output: revenue summary by product type
├── summary_supplier_performance.csv           # Output: supplier performance summary
├── summary_transport_performance.csv          # Output: transportation mode summary
└── README.md
```

## 📈 Key Findings

- **Skincare** is the top revenue-generating product category, followed by haircare and cosmetics.
- Shipping cost and shipping time tend to increase for **Sea** and **Rail** transportation modes compared to Road and Air.
- Roughly **36%** of inspected products fail quality inspection, indicating room for improvement in supplier quality control.
- Supplier performance varies significantly in both revenue contribution and defect rate, suggesting an opportunity for supplier consolidation or renegotiation.

## 🚀 How to Run

```bash
# Install dependencies
pip install pandas matplotlib

# Run the analysis
python supply_chain_analysis.py
```

## 📊 Dashboard

An interactive dashboard was also built in **Tableau Public**, featuring:
- KPI summary cards (total revenue, units sold, average defect rate, SKU count)
- Revenue breakdown by product type and supplier
- Shipping cost & time comparison across transportation modes
- Quality inspection distribution (donut chart)

## 👤 Author

**Herlina**
Data Analyst | Logistics & Supply Chain Background
[LinkedIn](https://linkedin.com/in/herlina-st-cplm) · [GitHub](https://github.com/herlinahl779-wq)
