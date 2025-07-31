# Used Car Lead Package Sales Analysis (Excel-Based)

This project simulates a Excel-based data analysis workflow I learned during my internship at **Dcar**, the automotive content platform of **ByteDance**.

It demonstrates how I processed lead package configuration data across 300+ cities in China to support the sales team in understanding trends, identifying new business opportunities, and optimizing regional strategy.

---

## Background

At Dcar, each day the sales team collected merchant purchase requests for used car lead packages. These requests included:

- Merchant ID & name
- Package type (Basic, Customized, Luxury, New Energy, Standard)
- Lead type (Exclusive / Shared)
- Unit price, lead quantity
- Start delivery date

My daily task was to:
- Match supply with demand by configuring leads 
- Export and clean data from the internal system
- Analyze sales distribution patterns
- Provide feedback for pricing and sales decisions

---

## Analysis Objectives

- Track daily lead package sales across cities and regions
- Calculate key sales indicators (e.g., revenue, unit price, delivery days)
- Monitor product preference and pricing sensitivity
- Compare performance across cities and identify new city entries
- Visualize pricing patterns across geography and product types

---

## Key Sales Metrics

| Metric | Description |
|--------|-------------|
| `Total Price` | Unit price × Quantity purchased |
| `Daily Budget` | Total price ÷ Estimated delivery days |
| `Avg Unit Price` | Mean price per lead in each group |
| `New City Today` | City without prior orders, flagged using VLOOKUP |
| `Delivery Volume` | Daily delivery quantity across cities |

---

## Analysis Dimensions

- **Geography**: Region (North, East, South, West, Central), City
- **Product**: Package Type (Basic, Customized, Luxury, New Energy, Standard)
- **Customer Behavior**: Exclusive vs Shared buyers
- **Temporal**: Daily changes in city participation and volume
- **Sales Force Focus**: Package popularity and pricing segmentation

---

## Sample Insights (from simulated data)

| Observation | Recommendation |
|-------------|----------------|
| North region has highest avg unit price across all products | Focus premium offerings here |
| Luxury and Customized packages dominate in revenue | Maintain them as core products |
| South shows low acceptance of Luxury package | Consider repositioning or discounting |
| Chengdu pays the highest price for Standard packages | Explore niche pricing strategies in small cities |
| New Energy packages lead unit pricing | Increase promotional visibility |

---

## Visualizations

**Pivot Tables**:
   - Regional sales breakdown by city and product type
   - Cross-tab view of average unit price by region × package
   - Daily new city entry and delivery tracking

---

## Tools Used

**Microsoft Excel**:
  - PivotTable
  - VLOOKUP (used for city matching across dates)
  - Basic filters and formula logic

---

## Data File

The core dataset used in this project is:

 [`sales_data_analysis.xlsx`](./sales_data_analysis.xlsx)

The file demonstrates my ability to manage end-to-end data analysis workflow in Excel, using formulas, filters, and pivot tables to derive business insights.

---

## Note

This is a reconstructed sample based on actual tasks I performed during my internship. Data has been anonymized and simplified to preserve confidentiality and focus on logic and methodology.

---

## Author

**Zhengjia LI**  
Master in Management – ESCP Business School  
