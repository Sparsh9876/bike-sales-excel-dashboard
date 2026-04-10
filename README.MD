# 🚲 Bike Sales Analytics — Excel Dashboard

> **Customer purchase behaviour analysis across 1,026 customers in 3 global regions,
> identifying which age groups, occupations, and commute profiles drive bike sales**

![Excel](https://img.shields.io/badge/Excel-Advanced-217346?style=flat&logo=microsoftexcel&logoColor=white)
![Dashboard](https://img.shields.io/badge/Dashboard-Interactive-orange?style=flat)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen?style=flat)
![Domain](https://img.shields.io/badge/Domain-Retail%20Sales-blue?style=flat)

---

## 🎯 Business Problem

A bike retailer with customers across **North America, Europe, and Pacific**
needs to understand who is buying bikes — and who isn't — so the marketing
team can target campaigns more effectively and the sales team can focus on
high-conversion customer profiles.

---

## 📦 Dataset

| Property | Detail |
|---|---|
| Records | 1,026 customers |
| Regions | North America, Europe, Pacific |
| Target Variable | Purchased Bike (Yes / No) |
| Key Features | Age, Income, Occupation, Commute Distance, Marital Status, Gender |

---

## 🔧 Tools Used

| Tool | Purpose |
|---|---|
| Microsoft Excel | Data cleaning, pivot tables, dashboard |
| Pivot Tables | Multi-dimension aggregation |
| Excel Charts | Bar, pie, and grouped charts |
| Calculated Fields | Conversion rate, income grouping, age banding |

---

## 🗂️ Project Structure

```
bike-sales-excel-dashboard/
│
├── data/
│   └── bike_sales_rawdata.xlsx       ← Original unmodified source data
│
│
├── bike_sales_database.xlsx               ← Main file with 6 sheets
│   ├── bike_buyers original data          ← original raw data excel file 
│   ├── cleaned data                       ← cleaned and processed data 
│   └── pivot tables                       ← pivot tables and kpis 
│   └── pivot charts                       ← pivot charts using pivot tables 
│   ├── dashboard                          ← Visual dashboard ( charts + KPI cards)
│   └── key insights                       ← Written findings with business context
│
│
└── README.md

```

---

## 🧹 Data Cleaning Applied

| Step | Action |
|---|---|
| Age banding | Grouped raw ages into: 18-25, 26-35, 36-45, 46-55, 56+ |
| Income banding | Created Income Range column (10K-19K through 160K+) |
| Marital Status | Expanded M/S codes to Married/Single for readability |
| Gender | Expanded M/F codes to Male/Female |
| Duplicates | Checked and confirmed 0 duplicate IDs |

---

## 📊 Dashboard — 10 Charts + 6 KPI Cards

### KPI Cards (Top Row)
| KPI | Value |
|---|---|
| Total Customers | 1,026 |
| Bike Buyers | 495 |
| Conversion Rate | 48.2% |
| Avg Income (Buyers) | $57,475 |

### Chart 1 — Buyers vs Non-Buyers by Age Group
- 36-45 age group converts best at **57.7%**
- 56+ age group converts lowest at **31.4%**
- 18-25 highest conversion (66.7%) but only 6 customers — low confidence

### Chart 2 — Purchase Rate by Commute Distance
- **0-1 Mile** commuters are the largest buyer group (207 purchases)
- Purchase rate drops significantly beyond 5 miles
- Insight: Zepto's bike buyers are **leisure/fitness riders**, not long commuters

### Chart 3 — Buyer Distribution by Region
- North America: **49.5%** of all customers
- Europe: 30.8%
- Pacific: 19.7%

### Chart 4 — Purchase Rate by Occupation
- **Professional** is the largest customer segment (280 customers)
- Skilled Manual and Professional tie for highest buyer counts

### Chart 5 — Purchase Rate by Education 
- **Partial college** is the largest customer segment (278 customers)

### Chart 6 — customers who owned home 
- 68% customers have there own owned 

### Chart 7 — buyer distribution who owned cars 
- maximum 348 customers having 2 cars at the purchase of bike.

### Chart 8 — Purchase Rate by income 
- maximum 166 purchases has made by the people whose salry come in range between 60k-69k.

### Chart 9 — Purchase Rate by married status 
- purchase rate by married people is 549 vs single people purchase rate is 477.

### Chart 10 — Purchase Rate by Gender
- **Male** is the largest customer segment (525 customers).

---

## 💡 Key Business Insights

| # | Insight | Action |
|---|---|---|
| 1 | **Age 36-45 converts at 57.7%** | Focus ad spend on mid-career professionals |
| 2 | **Short-commute customers buy most** | Market bikes as fitness/lifestyle, not just transport |
| 3 | **Income gap is only $2,447** | Price sensitivity is low — focus on product fit, not discounts |
| 4 | **North America = 50% of market** | Prioritise NA inventory and campaigns |
| 5 | **56+ converts at only 31.4%** | Introduce e-bike / comfort range to re-engage older customers |
| 6 | **48.2% overall conversion** | Strong baseline — small improvements = large revenue impact |

---

## 🚀 How to Open

1. Download `bike_sales_dashboard.xlsx`
2. Open in Microsoft Excel (2016 or later recommended)
3. Navigate tabs: **bike_buyers original data ** → **cleaned data** → **pivot tables** → **pivot charts** → **dashboard** → **key insights**
4. All charts are interactive — click chart elements to filter

---

## 👤 Author

**Sparsh Bhatnagar** — Data Analytics | MCA (ML & AI), Amity University
[LinkedIn](https://www.linkedin.com/in/sparshbhatnagar/) | Ghaziabad, India
[![Email](https://img.shields.io/badge/Email-Reach%20Me-D14836?style=flat&logo=gmail&logoColor=white)](mailto:Sparsh.Bhatnagar13@gmail.com)
