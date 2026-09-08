# HR Analytics & Workforce Insights Dashboard (Power BI)

A hands-on Power BI project built to analyze workforce demographics, track employee retention, and help HR leadership make data-backed decisions around promotions and retrenchment.

---

## 📌 Project Overview
Managing talent pipelines requires clear visibility into who is performing well, who is overdue for promotion, and where departments might need restructuring. 
I built this multi-page interactive dashboard using raw HR employee records to answer questions like:
## 📊 Dashboard Pages & Visuals

### 1. Workforce Overview (`Home`)
Gives leadership a high-level pulse check on headcounts, workforce active rates, service years, and promotion-eligibility splits.
![Workforce Overview](Screenshots/img%20overview%20dashboard.png)

### 2. Employee Action Tracker (`Action`)
A focused operational view that lists specific employees identified for action:
- Overdue for promotion
- Candidates due for transition / retrenchment
  
![Action View](Screenshots/img%20talent%20actionslist.png)
### 3. Department Deep Dive (`Detail`)
Drills into departmental trends, showing job satisfaction distributions, overtime exposure, and specific job roles affected by transition policies.

![Department Details](Screenshots/img%20department%20breakdown.png)

## 💡 Key Highlights from the Data
- **Total Headcount:** 1,470 employees (60% Male / 40% Female)
- **Active Workforce:** 92.0% (1,353 active workers)
- **Promotion Pipeline:** 72 employees (4.9%) eligible for immediate advancement
- **Retrenchment/Transition List:** 117 employees (8.0%) flagged based on service criteria
- 
## 🛠️ Tech Stack & Methods
- **Power BI Desktop:** Dashboard design, layout UX, custom card visuals, and slicers.
- **DAX:** Dynamic metrics for headcount, gender percentages, and conditional flags.
- **Power Query:** Data cleaning, type transformations, and dataset merges.
- **Data Source:** CSV files containing employee profiles, promotion history, and separation criteria.
## 📂 Project Structure
├── Data/                       # Raw CSV datasets
├── Screenshots/                # Dashboard view captures
└── Power BI HR Dashboard.pbix  # Main Power BI file
