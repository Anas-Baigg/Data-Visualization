# Data Visualization — Employment Statistics Analysis

Interactive data visualization project analyzing employment statistics in tech fields (Software Development, Data Science) across the United States. Demonstrates proficiency in data cleaning, exploratory visualization, and communicating insights through charts.

---

## 📋 Project Overview

| | |
|---|---|
| **Type** | Data Visualization / Business Analytics |
| **Status** | Complete |
| **Language** | Python (Jupyter Notebook) |
| **Dataset** | US Bureau of Labor Statistics - Employment Data (May 2021-2023) |
| **Focus** | Tech Industry Employment Trends |
| **Repository** | [Anas-Baigg/Data-Visualization](https://github.com/Anas-Baigg/Data-Visualization) |

---

## ✨ Features

- **Job Title Filtering** — Extract Software, Data Science, and Developer roles from comprehensive dataset
- **Employment Trends** — Compare headcount across 3 years (2021-2023) by job title
- **Sector Analysis** — Break down employment by ownership type (Private, Federal, State, Local Government)
- **Salary Distribution** — Box plots and histograms of mean annual wages
- **Comparative Visualization** — Grouped bar charts showing job distribution across sectors
- **Year-over-Year Comparison** — Pie charts tracking employment growth/decline
- **Wage Statistics** — Distribution analysis of compensation by role

---

## 🛠 Tech Stack

| Tool | Version | Purpose |
|---|---|---|
| Python | 3.7+ | Core language |
| Jupyter Notebook | Latest | Interactive environment |
| Pandas | 1.3+ | Data manipulation & aggregation |
| Matplotlib | 3.4+ | Static visualizations |
| Seaborn | 0.11+ | Statistical graphics |
| NumPy | 1.20+ | Numerical operations |
| OpenPyXL | Latest | Excel file reading |

---

## 📁 Project Structure

```
Data-Visualization/
├── ca1-Anas748-1-main/
│   ├── CA-1.ipynb              # Main analysis notebook (546 KB)
│   └── Ca-1.docx               # Assignment specification
└── README.md
```

---

## 🚀 How to Run

### Prerequisites
```bash
pip install jupyter pandas matplotlib seaborn numpy openpyxl
```

### Launch Notebook
```bash
# Navigate to project directory
cd ca1-Anas748-1-main

# Start Jupyter
jupyter notebook CA-1.ipynb
```

---

## 📊 Real Analysis Questions & Findings

### Question 1: Total Employment by Role
**Finding:** Total of **28.26 million** employees in filtered tech fields
- Software Developers: Largest cohort
- Data Scientists: Emerging role with growing demand
- Web Developers: Significant subset of development roles
- Computer Programmers: Established workforce

### Question 2: Employment by Sector
**Finding:** Private sector dominates with visualization showing:
- **Private Sector:** Significantly higher employment (~90%+ of filtered roles)
- **Federal Government:** Minimal representation in tech roles
- **State/Local Government:** Small but present tech workforce

### Question 3: Salary Distribution by Role
**Findings from Box Plots & Histograms:**
- Software Developers: Highest median salary
- Data Scientists: Competitive compensation
- Computer Programmers: Moderate salary range
- Wide salary distribution across all roles (geographic variation)

### Question 4: Year-over-Year Trends (2021-2023)
**Findings from Comparative Charts:**
- Employment shows growth trajectory in most tech roles
- Software development roles remain dominant
- Data Science roles growing proportionally
- Market adjustments visible in recent data

---

## 📚 Learning Outcomes

- Demonstrates **effective data filtering and aggregation** using pandas
- Shows **multi-perspective visualization** using appropriate chart types
- Implements **scale transformation** (log-scale) for better data visibility
- Applies **comparative analysis** across multiple dimensions (time, sector, role)
- Exhibits **data storytelling** with meaningful insights extraction
- Uses **statistical visualization** (box plots, histograms) for distribution analysis
- Shows **professional presentation** of business analytics

---

## 🔮 Future Improvements

- [ ] Add interactive Plotly/Dash dashboard
- [ ] Implement time series forecasting for employment trends
- [ ] Create geographic salary comparison (state-by-state)
- [ ] Add skill-based employment analysis
- [ ] Build automated report generation
- [ ] Integrate real-time BLS data API
- [ ] Add predictive modeling for job market

---

## 🎓 Academic Context

| | |
|---|---|
| **Course** | Data Visualisation and Communication |
| **Institution** | CCT College Dublin |
| **Student** | Muhammad Anas Baig (2021387) |
| **Assessment** | CA1 - Coursework Assignment |
| **Dataset Source** | US Bureau of Labor Statistics (May 2021-2023) |

> This repository represents university coursework in data visualization, demonstrating systematic exploration of employment trends and effective communication of insights through visual analytics.
