<div align="center">

# 📊 Millennial vs Baby Boomer Employment Analysis
### United States Labor Market · 2007 – 2013

[![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=flat-square&logo=python&logoColor=white)](https://python.org)
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=flat-square&logo=pandas&logoColor=white)](https://pandas.pydata.org)
[![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?style=flat-square&logo=powerbi&logoColor=black)](https://powerbi.microsoft.com)
[![License](https://img.shields.io/badge/License-MIT-4B2E83?style=flat-square)](LICENSE)

**[🔴 Live Dashboard](https://beingjassi101.github.io/millennial-vs-boomer-employment-analysis/powerbi_dashboard.html)** &nbsp;|&nbsp; **[📑 View Presentation](https://github.com/beingjassi101/millennial-vs-boomer-employment-analysis/blob/main/Millennial_vs_BabyBoomer_Employment.pptx)** &nbsp;|&nbsp; **[🌐 Portfolio](https://beingjassi101.github.io)**

---

*How differently did Baby Boomers and Millennials experience the Great Recession — and did either generation truly recover?*

</div>

---

## 🗂️ Repository Structure

```
millennial-vs-boomer-employment-analysis/
│
├── powerbi_dashboard.html          ← Interactive 4-page Power BI-style dashboard
├── portfolio_showcase.html         ← Full project showcase page
├── Millennial_vs_BabyBoomer_Employment.pptx  ← 10-slide presentation deck
└── README.md
```

---

## 📦 Dataset

| Sheet | Rows | Description |
|-------|------|-------------|
| `National, 2-digit` | 46 | 23 broad sectors × 2 generations |
| `National, 5-digit` | 1,559 | Specific SOC occupations — 785 BB + 774 ML |
| `States` | 102 | All 51 states × 2 generations |
| `Metropolitan Areas` | 732 | 366 MSAs × 2 generations |

**Source:** EMSI (Economic Modeling Specialists International) — U.S. employment data 2007–2013.

---

## 📈 Key Results

### National Summary

| | 🔵 Baby Boomers | 🟢 Millennials |
|--|----------------|----------------|
| **2007 Jobs** | 21,357,823 | 40,797,493 |
| **2013 Jobs** | 23,303,488 | 40,907,412 |
| **Net Change** | **+1,945,665** | **+109,919** |
| **% Growth** | **+9.7%** | **+0.3%** |
| **Avg sector growth** | +9.7% (22/23 grew) | +0.9% (13/23 grew) |

> Baby Boomers added nearly **18× more jobs** than Millennials despite having half the workforce — revealing a profound experience premium during recession recovery.

---

### Sector Divergence — Same Industry, Opposite Outcomes

| Sector | 🔵 Baby Boomers | 🟢 Millennials | Gap |
|--------|----------------|----------------|-----|
| Computer & Math | +19.8% | +2.0% | **17.8 pp** |
| Production | +4.8% | −12.7% | **17.5 pp** |
| Construction | −3.0% | −19.2% | **16.2 pp** |
| Transportation | +9.6% | −5.7% | **15.3 pp** |
| Office & Admin | +9.7% | −3.6% | **13.3 pp** |
| Management | +2.8% | −6.1% | **8.9 pp** |
| Healthcare Support | +26.5% | +15.6% | 10.9 pp *(both grew)* |
| Food Prep | +20.0% | +17.7% | 2.3 pp *(both grew)* |

---

### Top 10 States — Baby Boomers

| Rank | State | % Change | Net Jobs |
|------|-------|----------|----------|
| 1 | North Dakota | +27.95% | +16,545 |
| 2 | Texas | +17.76% | +265,713 |
| 3 | South Dakota | +15.62% | +10,281 |
| 4 | Utah | +15.54% | +23,757 |
| 5 | Wyoming | +14.38% | +6,980 |
| 6 | Colorado | +13.58% | +49,143 |
| 7 | Alaska | +13.37% | +6,813 |
| 8 | Nebraska | +13.05% | +19,726 |
| 9 | Minnesota | +12.78% | +53,191 |
| 10 | Massachusetts | +12.25% | +60,549 |
| 51 ⬇️ | Nevada | −2.35% | −4,526 |

### Top 10 States — Millennials

| Rank | State | % Change | Net Jobs |
|------|-------|----------|----------|
| 1 | North Dakota | +33.54% | +36,551 |
| 2 | Texas | +8.21% | +268,968 |
| 3 | Alaska | +7.91% | +8,382 |
| 4 | District of Columbia | +6.56% | +16,392 |
| 5 | South Dakota | +5.73% | +6,986 |
| 6 | Louisiana | +4.61% | +27,440 |
| 7 | New York | +3.96% | +99,706 |
| 8 | Wyoming | +3.83% | +3,341 |
| 9 | Massachusetts | +3.78% | +36,477 |
| 10 | Minnesota | +3.44% | +28,009 |
| 51 ⬇️ | Nevada | −8.79% | −33,447 |

> 📌 Baby Boomers grew in **all 51 states**. Millennials declined in **28 of 51**.

---

### Top Occupations by Absolute Job Growth

**🔵 Baby Boomers**

| Occupation | Jobs Added | % Growth |
|------------|-----------|----------|
| Registered Nurses | +111,017 | +25.3% |
| Personal Care Aides | +78,831 | +43.6% |
| Retail Salespersons | +62,691 | +11.0% |
| Office Clerks, General | +59,747 | +11.8% |
| Cashiers | +57,791 | +21.4% |
| Home Health Aides | +48,877 | +46.9% |
| Customer Service Reps | +45,678 | +17.8% |
| Janitors & Cleaners | +43,731 | +10.4% |

**🟢 Millennials**

| Occupation | Jobs Added | % Growth |
|------------|-----------|----------|
| Fast Food / Food Prep Workers | +204,545 | +27.8% |
| Waiters & Waitresses | +149,992 | +15.8% |
| Cashiers | +127,939 | +14.0% |
| Personal Care Aides | +98,461 | +43.8% |
| Home Health Aides | +77,619 | +38.2% |
| Registered Nurses | +61,405 | +11.1% |
| Retail Salespersons | +60,186 | +4.5% |
| Restaurant Cooks | +57,909 | +16.6% |

**🔴 Biggest Millennial Job Losses**

| Occupation | Jobs Lost | % Loss |
|------------|----------|--------|
| Carpenters | −112,211 | −28.0% |
| Construction Laborers | −73,274 | −15.7% |
| Team Assemblers | −54,240 | −16.1% |
| Secretaries & Admin Assistants | −53,846 | −8.6% |
| Heavy Truck Drivers | −45,785 | −12.4% |
| Electricians | −42,044 | −17.8% |

---

### Top Metro Areas

| Metro | 🔵 BB Growth | 🟢 ML Growth | Driver |
|-------|-------------|-------------|--------|
| Midland, TX | +43.7% | +38.6% | Oil & Gas Boom |
| Odessa, TX | +34.7% | +34.7% | Oil & Gas Boom |
| Bismarck, ND | +29.9% | +18.3% | Bakken Oil Fields |
| Fargo, ND-MN | +25.2% | +14.3% | Regional Growth |
| Houston-Sugar Land, TX | +22.9% | — | Energy Hub |
| Columbus, IN | — | +14.6% | Manufacturing Recovery |

| Metro | 🔵 BB Decline | 🟢 ML Decline | Driver |
|-------|--------------|--------------|--------|
| Carson City, NV | −9.9% | −14.3% | Housing Bust |
| Dalton, GA | −6.9% | −23.4% | Carpet/Textile Collapse |
| Prescott, AZ | −5.4% | −15.0% | Construction Bust |
| Hickory-Lenoir, NC | −5.7% | −12.5% | Furniture Manufacturing |

---

## 💡 Key Findings

**1. The Experience Premium** — Boomers leveraged seniority and skill depth to retain and grow jobs while Millennials were first to be laid off. The gap (18× more net jobs) reflects structural bias toward experienced workers during economic contraction.

**2. Structural Blue-Collar Displacement** — Millennials lost 478K construction + 317K production jobs. These weren't temporary layoffs — the sectors never fully recovered for this age group, signalling lasting structural displacement.

**3. Healthcare Is Recession-Proof** — Registered Nurses, Home Health Aides, and Personal Care Aides appeared in the top growth lists for *both* generations, confirming healthcare as a cycle-independent growth sector driven by demographics, not economics.

**4. Energy Saved Millennials** — North Dakota (+33.5%), Texas (+8.2%), Alaska (+7.9%). Without the Bakken oil boom and Texas energy expansion, Millennial national job figures would have been deeply negative.

**5. Nevada Was the Canary** — The only state where *Baby Boomers* lost jobs (−2.4%) and the worst for Millennials (−8.8%). Post-housing-crash Nevada showed what happens when both construction and hospitality collapse simultaneously.

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| **Python 3 + Pandas** | Data loading, cleaning, aggregation, statistical analysis |
| **Power BI** | Interactive dashboard (replicated as HTML for web) |
| **Excel / EMSI Dataset** | Raw data source — 4 sheets, 2,439 total rows |
| **PptxGenJS** | Automated 10-slide presentation generation |
| **HTML / Chart.js** | Portfolio showcase + interactive dashboard |

---

## 🚀 How to Explore

**View the live dashboard:**
```
https://beingjassi101.github.io/millennial-vs-boomer-employment-analysis/powerbi_dashboard.html
```

**Clone the repo:**
```bash
git clone https://github.com/beingjassi101/millennial-vs-boomer-employment-analysis.git
```

---

## 👤 Author

**Jaspreet Singh Bharaj** — Software Engineer · MEng Western Ontario

[![Portfolio](https://img.shields.io/badge/Portfolio-beingjassi101.github.io-4B2E83?style=flat-square&logo=github)](https://beingjassi101.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-beingjassi-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/beingjassi)
