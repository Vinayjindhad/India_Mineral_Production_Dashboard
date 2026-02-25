# 🪨 India Mineral Production Dashboard
### Interactive Analytics Dashboard built with Python & Streamlit

---

## 📌 Project Overview

This project is an **interactive Streamlit dashboard** that analyzes mineral production across Indian states from **2010-11 to 2014-15**. It enables stakeholders in resource management, policy-making, and investment to explore production trends, compare state-level contributions, and gain actionable insights into India's key mineral sectors.

The dashboard covers five focused analytical dimensions — from overall mineral distribution to deep-dives into coal, lignite, natural gas, and offshore petroleum — making it a practical tool for data-driven decision-making in the energy and mining sectors.

---

## 📂 Dataset

- **Source:** Ministry of Mines, Government of India (via public dataset)
- **File:** `production.csv`
- **Time Period:** 2010-11 to 2014-15 (Provisional)
- **Key Variables:** Mineral name, State, Quantity produced, Value (₹), Year-wise columns
- **Minerals Covered:** Coal, Lignite, Natural Gas, Petroleum (Crude), and others

---

## 🎯 Objectives

1. Understand the **distribution of minerals** across India by quantity and value
2. Identify **top contributing states** to India's overall mineral wealth
3. Analyze **coal production patterns** at the state level
4. Explore **lignite and natural gas** production trends
5. Examine the **offshore petroleum sector's** contribution to national energy resources
6. Provide a tool for **strategic resource planning and policy formulation**

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Python 3.x | Core programming language |
| Streamlit | Interactive web dashboard framework |
| Pandas | Data loading and aggregation |
| Matplotlib | Chart rendering backend |
| Seaborn | Categorical visualizations (lignite/gas comparison) |

---

## 📊 Dashboard Sections & Key Findings

### 1. 🗺️ Mineral Distribution
- India's mineral output is dominated by **Coal and Petroleum (Crude)** in both quantity and value
- A long tail of smaller minerals contributes to diversity but limited economic scale

### 2. 🏛️ State-wise Analysis
- **Odisha (Orissa)** and **Rajasthan** emerge as the largest contributors to overall mineral production
- Significant production disparities exist across states, with a few driving the majority of national output
- **Jharkhand** is a critical hub for coal-heavy production

### 3. ⛏️ Coal Production Analysis
- Coal production is heavily concentrated in **Jharkhand and Odisha**
- These states collectively account for a disproportionate share of national coal output
- Production patterns vary significantly — some states show stable trends, others show volatility

### 4. 🔥 Lignite & Natural Gas Exploration
- **Tamil Nadu** leads lignite production, with limited competition from other states
- **Gujarat** dominates natural gas production, reflecting its strong energy infrastructure
- These two minerals are geographically concentrated, unlike coal

### 5. 🛢️ Offshore Petroleum Production
- **Rajasthan** and **Gujarat** are the primary contributors to crude petroleum extraction
- Offshore production plays a critical role in India's energy self-sufficiency goals

---

## 📁 Project Structure

```
mineral-production-dashboard/
│
├── mineral_dashboard.py        # Main Streamlit application
├── production.csv              # Dataset (Ministry of Mines)
└── README.md                   # Project documentation
```

---

## ▶️ How to Run

### Prerequisites
```bash
pip install streamlit pandas matplotlib seaborn
```

### Launch the Dashboard
```bash
streamlit run mineral_dashboard.py
```

The dashboard will open automatically in your browser at `http://localhost:8501`

---

## 💡 Business Insights Summary

| Focus Area | Key Finding |
|------------|-------------|
| Top mineral by value | Coal & Petroleum (Crude) |
| Highest producing state | Odisha & Rajasthan |
| Coal production leader | Jharkhand & Odisha |
| Lignite leader | Tamil Nadu |
| Natural gas leader | Gujarat |
| Petroleum leader | Rajasthan & Gujarat |

---

## 🔮 Future Scope

- Extend dataset to **2015–2023** for more recent trend analysis
- Add **year-over-year growth rate** calculations and trend lines
- Integrate **choropleth maps** for geographic visualization of state-wise production
- Build **forecasting module** using time-series models (ARIMA / Prophet)
- Add **filters and dropdowns** for user-driven mineral/state selection in the dashboard

---

## 🙏 Acknowledgements

- Data sourced from the **Ministry of Mines, Government of India**
- Built using the [Streamlit](https://streamlit.io/) open-source framework
- Visualization libraries: Matplotlib & Seaborn

---

## 👤 Author

**Vinay Kumar**  
PGDM – Big Data Analytics & Marketing | FORE School of Management, Delhi
