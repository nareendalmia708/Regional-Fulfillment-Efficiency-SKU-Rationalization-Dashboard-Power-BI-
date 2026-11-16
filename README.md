# 📊 Regional Fulfillment Efficiency & SKU Rationalization Dashboard (Power BI)
**Built with Power BI | 2014–2017 Multi-Year Distribution Data | US Retail Supply Chain**

---

## 📌 Project Overview

An interactive **2-page Supply Chain, Regional Fulfillment & SKU Rationalization Power BI Dashboard** analyzing **5,009 orders**, **37,873 fulfilled units**, and **$2.30M in order volume** across **3 US regions, 3 categories, 17 sub-categories, and 1,850 unique SKUs** (2014–2017).

The objective of this project is to identify **regional distribution bottlenecks, unprofitable freight/fulfillment zones, high-volume/low-margin SKU drag, and discount-driven margin erosion** to help operations and supply chain leaders optimize warehouse allocation and product assortment.

---

## 📁 Dashboard Architecture & Operational KPIs

### **Page 1 — Regional Fulfillment & Network Profitability**
| Operational KPI | Value | Supply Chain Significance |
| :--- | :--- | :--- |
| **Total Fulfilled Order Volume** | **$2.30M** | 4-year cumulative distribution throughput across 3 regions |
| **Total Orders Processed** | **5,009** | Multi-region order fulfillment volume |
| **Net Operating Profit** | **$286.40K** | Net margin retained after regional fulfillment & discounting |
| **Overall Profit Margin** | **12.47%** | Baseline profitability benchmark across distribution zones |

### **Page 2 — SKU Assortment & Volume Velocity Analysis**
| Inventory / SKU KPI | Value | Supply Chain Significance |
| :--- | :--- | :--- |
| **Active SKU Catalog Size** | **1,850** | Total unique SKUs managed across warehouse locations |
| **Total Units Shipped** | **37,873** | Cumulative physical unit movement across 17 sub-categories |
| **Average Discount Rate** | **15.6%** | Promotional pricing impact on unit margin & demand spikes |
| **Product Sub-Categories** | **17** | Granular assortment segmentation for ABC/XYZ classification |

---

## 🔍 Key Supply Chain & Logistics Insights

| Focus Area | Operational Finding | Supply Chain & Logistics Implication |
| :--- | :--- | :--- |
| **High-Performing Distribution Hub** | **California — $0.46M** in fulfilled volume | Primary West Coast demand anchor requiring high-velocity replenishment |
| **Loss-Making Distribution Zone** | **Central Region — Net Loss** | High freight/fulfillment costs & heavy discounting eroding regional profitability |
| **High-Margin Core Category** | **Technology — $145K Profit** | **Class-A High-Value Inventory:** High margin per unit; prioritize stock availability |
| **Bulky / Low-Margin Drag** | **Furniture — 32% of Sales, Lowest Profit** | High cubic storage & heavy freight cost per unit eating into gross margins |
| **Promotional Margin Leakage** | **15.6% Avg Discount** | Aggressive discounting in select sub-categories creates demand spikes with negative net margin |

---

## 💡 Actionable Supply Chain Recommendations

1. **Central Region Network & Freight Audit:** Review warehouse-to-customer shipping distances, carrier rates, and promotional discount caps in the **Central Region** to turn loss-making routes profitable.
2. **Bulky Inventory (Furniture) Optimization:** Because **Furniture drives 32% of volume** but yields the lowest profit, shift toward **drop-shipping from suppliers** or regional cross-docking to reduce warehouse holding and LTL (Less-Than-Truckload) freight costs.
3. **SKU Rationalization (1,850 SKUs):** Conduct an **ABC-XYZ profitability matrix** across all 1,850 SKUs to phase out chronic loss-making sub-categories and reallocate warehouse bin space to high-margin **Technology** items.
4. **Sales & Operations Planning (S&OP) Alignment:** Align promotional discount calendars with inventory capacity so steep discounts do not trigger unfulfilled backorders or negative-margin shipments.

---

## 🛠️ Tools & BI Techniques Used

- **Power BI Desktop:** Multi-page interactive reporting with cross-filtering and drill-down visuals
- **DAX (Data Analysis Expressions):** Calculated measures for Profit Margin %, Total Units Shipped, Regional Variance, and Discount Impact
- **Data Modeling:** Star-schema relationship design across Order, Product/SKU, and Geographic dimensions
- **Power Query (ETL):** Data cleansing, type standardization, and hierarchy creation (`Region → State`, `Category → Sub-Category`)

---

## 📂 Dataset

- **Source:** [Kaggle — Superstore Retail & Fulfillment Dataset](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)
- **Scale:** 9,994 line-item records | 21 operational fields

---

## 📸 Dashboard Preview

**Page 1 — Regional Fulfillment & Network Analysis**
![Dashboard 1](dashboard1.png)

**Page 2 — SKU Assortment & Product Velocity Analysis**
![Dashboard 2](dashboard2.png)

---

## 🚀 How to Use

1. Download `SUPERSTORE DASHBOARD.pbix` and open it in **Power BI Desktop**.
2. Use the **slicers** to filter operational performance by **Year, Region, or Category**.
3. Click any **State, Region, or Sub-Category** visual to cross-filter unit velocity and margin metrics across the entire dashboard.
