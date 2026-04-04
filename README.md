# Pharmacy Sales Performance & Regional Health Trend Analysis

> **Dataset:** Nigerian Pharmacy Sales | **Period:** January 2024 – May 2025 | **Records:** 503 transactions  
> **Tools Used:** Microsoft Excel (Power Query, Pivot Tables, Dashboard Visualizations)

---

## Table of Contents

1. [Project Overview](#project-overview)
2. [Dataset Description](#dataset-description)
3. [Key Performance Indicators (KPIs)](#key-performance-indicators)
4. [Sales Performance Analysis](#sales-performance-analysis)
   - [Revenue Trend Over Time](#revenue-trend-over-time)
   - [Drug Category Performance](#drug-category-performance)
   - [Sales Rep Performance](#sales-rep-performance)
   - [Regional Revenue Distribution](#regional-revenue-distribution)
5. [Regional Health Trend Analysis](#regional-health-trend-analysis)
   - [Drug Demand by Region](#drug-demand-by-region)
   - [Seasonal Drug Demand Patterns](#seasonal-drug-demand-patterns)
6. [Key Insights & Interpretations](#key-insights--interpretations)
7. [Recommendations](#recommendations)
8. [Dashboard Previews](#dashboard-previews)

---

## Project Overview

This project analyses pharmacy sales data across four Nigerian regions **Western, Southern, Northern, and Eastern Nigeria** to uncover sales performance trends, regional health patterns, and drug demand seasonality. The analysis spans approximately 17 months and covers four drug categories sold by five sales representatives across multiple outlets.

The dashboard was built entirely in **Microsoft Excel**, featuring interactive slicers for filtering by year and sales rep, enabling dynamic exploration of the data.

---

## Dataset Description

| Field | Description |
|---|---|
| `Date` | Transaction date (Jan 2024 – May 2025) |
| `Region` | Sales region (Western, Southern, Northern, Eastern Nigeria) |
| `Drug Name` | Name of the pharmaceutical product sold |
| `Category` | Drug class (Antibiotic, Cardiovascular, Diabetes Care, Pain Relief) |
| `Sales Rep` | Name of the assigned sales representative |
| `Units Sold` | Number of units sold per transaction |
| `Unit Price` | Selling price per unit (USD) |
| `Revenue` | Total revenue per transaction |
| `Cost` | Cost of goods sold |
| `Profit` | Net profit per transaction |

**Total records after cleaning:** 503 rows across 4 drug categories, 4 regions, and 5 sales reps.

---

## Key Performance Indicators

| KPI | Value | YoY Change |
|---|---|---|
|  Total Revenue | **$3.6M** | -56.6% vs Prior Year |
|  Total Profit | **$272.9K** | -57.3% vs Prior Year |
|  Quantity Sold | **55,987 units** | -58.2% vs Prior Year |
|  Average Unit Price | **$65** | — |
|  Overall Profit Margin | **7.6%** | — |

> **Note on YoY decline:** The 2025 figures currently cover only January–May (5 months) versus a full 12 months in 2024. The steep YoY percentage drops are therefore a **function of incomplete year data**, not necessarily a true performance decline. Annualised, 2025 revenue is on a comparable trajectory.

---

## Sales Performance Analysis

### Revenue Trend Over Time

Monthly revenue tells a clear story of two distinct performance phases:

| Phase | Months | Revenue Range | Observation |
|---|---|---|---|
| **High Season** | Jan – May | $344K – $514K/month | Strong and rising demand |
| **Low Season** | Jun – Dec | $203K – $236K/month | Sharp drop, relatively flat |

- **May** is the peak revenue month at **$514,282** — 2.5× the July trough of **$203,434**
- Revenue spikes in **February–May** before collapsing sharply in **June**, suggesting a seasonal demand cliff likely tied to the end of the cold/flu and harmattan season
- The trendline shows a **downward slope** over the full period, though this is heavily skewed by the mid-year seasonal dip rather than structural decline

---

### Drug Category Performance

| Drug Category | Total Revenue | Profit | Profit Margin |
|---|---|---|---|
|  Cardiovascular | **$1,008,080** | $72,187 | 7.2% |
|  Antibiotic | $913,319 | $69,310 | 7.6% |
|  Diabetes Care | $896,484 | $66,509 | 7.4% |
|  Pain Relief | $795,882 | **$64,866** | **8.2%** |

**Key Takeaways:**
- **Cardiovascular drugs** are the highest revenue generator ($1M+), driven largely by consistent year-round demand
- **Pain Relief** has the lowest revenue but the **highest profit margin (8.2%)**, making it the most efficient category per dollar earned
- All four categories operate within a narrow margin band of **7.2%–8.2%**, indicating uniform pricing and cost structures

**Top-Performing Individual Drugs:**

| Rank | Drug Name | Revenue |
|---|---|---|
| 1 | Heartzol | $552,239 |
| 2 | Maxilin | $501,628 |
| 3 | Glucorin | $487,601 |
| 4 | Relipain | $480,212 |
| 5 | CardioVex | $455,841 |

---

### Sales Rep Performance

| Sales Rep | Revenue | Profit | Units Sold | Margin |
|---|---|---|---|---|
| Mohammed Bello | **$882,447** | $63,763 | 13,712 | 7.2% |
| Grace Umeh | $757,817 | $54,205 | 11,683 | 7.2% |
| Emeka Obi | $700,598 | $50,739 | 9,900 | 7.2% |
| Laila Hussein | $651,908 | **$53,545** | 10,462 | **8.2%** |
| Jane Akins | $620,995 | $50,620 | 10,230 | **8.2%** |

**Key Takeaways:**
- **Mohammed Bello** leads in both revenue and units sold, with ~42% more revenue than the lowest performer (Jane Akins)
- **Laila Hussein and Jane Akins** generate lower revenue but achieve the highest profit margins (8.2%), suggesting they focus more on high-margin products like Pain Relief
- Revenue is somewhat proportional to units sold across reps, validating consistent average selling prices
- The gap between top and bottom rep (~$261K) signals an opportunity for performance coaching or territory review

---

### Regional Revenue Distribution

| Region | Revenue | Revenue Share |
|---|---|---|
| Southern Nigeria | ~$990K | **27%** |
| Northern Nigeria | ~$950K | **26%** |
| Eastern Nigeria | ~$880K | **25%** |
| Western Nigeria | ~$800K | **22%** |

The regional revenue split is notably **balanced**  no single region dominates, suggesting the sales strategy is geographically diversified. Southern and Northern Nigeria hold a slight edge, collectively accounting for 53% of revenue.

---

## Regional Health Trend Analysis

### Drug Demand by Region

| Drug Category | Western Nigeria | Southern Nigeria | Northern Nigeria | Eastern Nigeria |
|---|---|---|---|---|
| Cardiovascular | **4,321** | 3,978 | 3,690 | 3,363 |
| Diabetes Care | **3,873** | 3,412 | 3,699 | 3,308 |
| Antibiotic | 3,786 | 2,932 | **4,045** | 3,495 |
| Pain Relief | 2,924 | **4,128** | 2,746 | 2,287 |

**Regional Health Signatures:**

- 🏙️ **Western Nigeria** — Highest demand for **Cardiovascular** and **Diabetes Care** drugs. This likely reflects urban lifestyle factors (sedentary work, processed diets) and better healthcare access that enables chronic disease diagnosis and treatment
- 🌿 **Southern Nigeria** — Leads significantly in **Pain Relief** consumption. This could indicate higher rates of musculoskeletal conditions, labour-intensive occupations, or greater accessibility of over-the-counter analgesics
- 🌬️ **Northern Nigeria** — Highest **Antibiotic** usage across all regions. This is consistent with epidemiological data linking dust exposure (harmattan), higher rates of respiratory and gastrointestinal infections, and potentially looser antibiotic prescription norms in the region
- ⚖️ **Eastern Nigeria** — Shows the most **balanced distribution** across all four drug categories, without extreme spikes in any direction, suggesting a more diversified health burden or uniform prescription practices

---

### Seasonal Drug Demand Patterns

| Month | Antibiotic | Cardiovascular | Diabetes Care | Pain Relief | Pattern Note |
|---|---|---|---|---|---|
| Jan | 2,006 | 921 | 1,295 | 1,365 | High antibiotic demand — flu/cold season |
| Feb | 1,709 | 1,764 | 1,542 | 1,371 | CV demand surges |
| Mar | 1,248 | 1,165 | 1,938 | 2,206 | Pain relief peaks |
| Apr | 2,038 | 1,773 | 1,613 | 805 | Antibiotic resurgence |
| May | 2,030 | 2,178 | 1,815 | 1,583 | Across-the-board peak |
| Jun | 381 | 1,042 | 959 | 813 | **Sharp antibiotic cliff** |
| Jul–Dec | ~500–1,000 | ~700–1,300 | ~300–1,100 | ~350–1,100 | Demand stabilises at lower levels |

**Key Seasonal Observations:**
- **Antibiotics** exhibit the most dramatic seasonality demand is nearly **5× higher in April/May than in June** (2,038 vs. 381 units). This strongly correlates with the end of the harmattan/dry season when respiratory infections peak
- **Cardiovascular drugs** maintain the most **stable year-round demand**, consistent with the chronic, non-seasonal nature of heart conditions
- **Pain Relief** spikes sharply in **March** (2,206 units) possibly linked to peak agricultural activity, physical labour season, or end-of-harmattan conditions
- **Diabetes Care** shows a notable dip in December (317 units), which may reflect patient holiday non-compliance or supply distribution gaps at year-end

---

## Key Insights & Interpretations

### 1. Seasonality is the Dominant Revenue Driver
The ~2.5× swing between peak (May) and trough (July) months means that **seasonality not sales rep performance or regional factors is the primary driver of revenue volatility**. Planning inventory, staffing, and promotions around this cycle is critical.

### 2. Antibiotic Misuse Risk in Northern Nigeria
Northern Nigeria's disproportionately high antibiotic demand warrants attention. While some of this is driven by legitimate infection burden (dust, fomites), it also raises the possibility of **antibiotic overprescription or self-medication**. This is a public health risk beyond the commercial opportunity.

### 3. Western Nigeria is the Chronic Disease Hub
The concentration of cardiovascular and diabetes drug demand in Western Nigeria the most urbanised region reflects a growing non-communicable disease (NCD) burden. This region should be the **strategic priority for chronic disease drug stocking and specialist rep deployment**.

### 4. Pain Relief is the Margin Champion
Despite ranking last in revenue, Pain Relief consistently delivers the **best profit margins (8.2%)**. Sales reps (Laila Hussein, Jane Akins) who skew toward this category achieve better efficiency. A deliberate push to grow Pain Relief sales could improve overall profitability without proportional cost increases.

### 5. Rep Performance Gap Signals Coaching Opportunity
A ~42% revenue gap between the top and bottom sales reps, combined with uniform product margins, suggests the difference is **activity-based** (visit frequency, territory coverage) rather than pricing strategy. Targeted coaching and performance incentives could close this gap.

---

## Recommendations

| Priority | Recommendation | Rationale |
|---|---|---|
| 🔴 High | Build inventory reserves for **Jan–May peak season** | 2.5× seasonal demand swing; stockouts = lost revenue |
| 🔴 High | Increase **Western Nigeria** focus for CV/Diabetes products | Highest chronic disease drug demand; urban growth trend |
| 🟡 Medium | Develop **antibiotic stewardship** initiative in Northern Nigeria | High usage could mask misuse and AMR risk |
| 🟡 Medium | Design **Pain Relief promotion** campaigns | Highest margin category; relatively underleveraged |
| 🟡 Medium | Investigate **December diabetes dip** (317 units vs. 1,076 in August) | May signal supply gap or patient non-compliance |
| 🟢 Low | Implement **sales rep coaching** for bottom 2 performers | Revenue gap is closeable with activity-based interventions |
| 🟢 Low | Explore **Southern Nigeria pain relief expansion** | Already highest regional demand; room to grow market share |

---

## Dashboard Previews

### Dashboard 1 — Sales Performance Analysis
![Sales Performance Dashboard](dashboard_preview_1.png)

*Features: Revenue trend line, drug category bar chart, profit-quantity scatter plot, rep performance bar chart, regional revenue donut chart*

### Dashboard 2 — Monthly & Regional Health Trend
![Health Trend Dashboard](dashboard_preview_2.png)

*Features: Seasonal drug demand table by month, regional drug consumption breakdown, annotated insights panel*

---

## Tools & Techniques Used

- **Microsoft Excel** — Data cleaning, Power Query transformations
- **Pivot Tables** — Aggregations by region, month, category, and sales rep
- **Excel Charts** — Line chart (revenue trend), Bar charts (category/rep performance), Scatter plot (quantity vs. profit), Donut chart (regional share)
- **Slicers** — Interactive filtering by Year and Sales Rep
- **Conditional Formatting** — KPI callout cards with YoY comparison indicators

---

*Analysis by Ike Nwaogu. Data covers Nigerian pharmacy transactions from January 2024 to May 2025*
