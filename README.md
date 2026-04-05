# Drinks_sales_dashboard
# 🥤 Beverage Sales Analytics — Power BI Dashboard

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)

An interactive Power BI dashboard built to analyze beverage sales performance across multiple retailers, regions, and brands throughout 2022. The dashboard helps stakeholders monitor revenue, units sold, and pricing — benchmarked against monthly targets.

---

## 📊 Dashboard Overview

This dashboard provides a comprehensive view of beverage sales operations across the United States in 2022. It enables quick insights into which retailers, brands, and regions are driving performance — and how results compare to monthly business targets.

---

## 🗂️ Dataset

**Source File:** `Start-Power-Bi-Essentials-Dataset.xlsx`

| Sheet | Description |
|---|---|
| `Data` | Core transactional sales records (3,739 rows) |
| `Dates` | Date dimension table (Year, Month, Weekday) |
| `Monthly Targets` | Revenue, quantity, and average price targets |
| `Cover Page` | Dataset metadata |

### Data Fields

| Column | Description |
|---|---|
| `Retailer` | Retailer name (Sodapop, BevCo, FizzySip, DreamCo) |
| `Retailer ID` | Unique retailer identifier |
| `Date` | Transaction date |
| `Month` | Month number derived from date |
| `Region` | US sales region |
| `State` | US state (48 states covered) |
| `Beverage Brand` | Product brand name |
| `Price per Unit` | Unit selling price ($0.10 – $1.10) |
| `Units Sold` | Number of units sold per transaction |

---

## 🏷️ Key Dimensions

- **Retailers:** Sodapop · BevCo · FizzySip · DreamCo
- **Beverage Brands:** Coca-Cola · Diet Coke · Sprite · Fanta · Powerade · Dasani Water
- **Regions:** Northeast · South · West · Midwest · Southeast
- **States:** 48 US states
- **Period:** January 2022 – December 2022

---

## 🎯 KPIs Tracked

| KPI | Target |
|---|---|
| Monthly Revenue | $1,000,000 |
| Monthly Units Sold | 1,500,000 |
| Monthly Average Price per Unit | $0.65 |

---

## ✨ Dashboard Features

- **Sales Performance Overview** — Total revenue, units sold, and average price vs. monthly targets
- **Time-Series Analysis** — Monthly trend lines for revenue and volume across 2022
- **Regional Breakdown** — Sales distribution across 5 US regions and 48 states
- **Brand Performance** — Comparison of all 6 beverage brands by revenue and units
- **Retailer Analysis** — Side-by-side performance of the 4 retail partners
- **Interactive Filters** — Slicers for date, region, retailer, and brand

---

## 🛠️ Tools & Technologies

| Tool | Usage |
|---|---|
| **Power BI Desktop** | Dashboard design and visualization |
| **Power Query (M)** | Data transformation and date table setup |
| **DAX** | KPI measures, calculated columns, target comparisons |
| **Microsoft Excel** | Source data and monthly targets |

---

## 📁 Project Structure

```
📦 Beverage-Sales-PowerBI
 ┣ 📊 nw.pbix                              # Power BI report file
 ┣ 📂 Start-Power-Bi-Essentials-Dataset.xlsx  # Source dataset
 ┗ 📄 README.md                            # Project documentation
```

---

## 🚀 How to Open

1. Download and install [Power BI Desktop](https://powerbi.microsoft.com/desktop) (free).
2. Clone or download this repository.
3. Open `nw.pbix` in Power BI Desktop.
4. If prompted, update the data source path to point to `Start-Power-Bi-Essentials-Dataset.xlsx`.
5. Click **Refresh** to load the latest data.

---

## 📌 Key Insights

- Sales data spans a full calendar year (2022), enabling seasonal trend analysis.
- 6 beverage brands are tracked across 4 retail partners and 5 US regions.
- Performance is benchmarked against pre-set monthly targets for revenue, volume, and price.
- The date dimension table supports advanced time intelligence calculations in DAX.

---

## 👤 Author

**Samsur**
Data Science & Power BI Portfolio Project

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com)

---

> 💡 *This project was built as part of a hands-on Power BI learning journey, covering data modeling, DAX, Power Query, and interactive dashboard design.*
