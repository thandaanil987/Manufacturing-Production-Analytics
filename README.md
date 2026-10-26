# 🏭 Manufacturing & Production Analytics

### End-to-End Manufacturing Analytics Solution | Python • Pandas • Power BI • DAX

## 📌 Project Overview

This project analyzes manufacturing production performance, machine downtime, product quality, and operational efficiency using Python and Power BI.

The goal is to transform production data into actionable business insights that help manufacturing teams monitor KPIs, identify performance gaps, investigate quality issues, and make data-driven operational decisions.

**Note:** This project uses a synthetic dataset created for portfolio and learning purposes. The findings represent sample data and are not actual factory performance results.

## 🎯 Business Objectives

- Compare actual production against production targets.
- Monitor production target achievement and production rates.
- Identify machines with higher downtime.
- Analyze defective units and defect rates across products.
- Compare production performance across shifts and production lines.
- Build an interactive, multi-page Power BI dashboard.
- Translate analytical findings into practical business recommendations.

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Python | Data inspection, quality checks, and analysis |
| Pandas | Data manipulation and preprocessing |
| NumPy | Numerical operations, where applicable |
| Power BI | Interactive dashboard development |
| DAX | KPI calculations and business measures |
| Power Query | Data transformation, where applicable |
| Excel | Basic data understanding and quick review |
| Generative AI | Productivity support during development |
| Git & GitHub | Version control and project documentation |

**SQL was not used in this project.** SQL-based analysis can be added as a future enhancement.

## 🔄 Project Workflow

1. Manufacturing dataset preparation.
2. Data understanding and structure inspection.
3. Data quality checks and preprocessing.
4. Exploratory data analysis and KPI identification.
5. Power BI data modeling and DAX measure development.
6. Interactive dashboard development.
7. Business findings and performance-gap analysis.
8. Recommendations and executive action planning.

## 📂 Dataset Description

The project uses a synthetic manufacturing dataset containing production, machine, quality, and operational information.

### Key Attributes

- `production_date` — Date of production.
- `production_line` — Manufacturing production line.
- `machine_id` — Machine identifier.
- `product_id` — Product identifier.
- `shift` — Production shift.
- `units_produced` — Actual units produced.
- `target_units` — Planned production target.
- `defective_units` — Number of defective units.
- `downtime_minutes` — Machine downtime in minutes.
- Production time and production-rate attributes.
- Energy consumption information.
- Maintenance type.
- Rework hours.
- Quality-check failures.

The dataset contains intentional missing values and duplicate records for data-quality practice.

## 📊 Dashboard Overview

The Power BI dashboard contains three pages designed for operational monitoring, machine and quality analysis, and management decision-making.

### 🏭 Page 1 — Production Overview

Provides a high-level overview of manufacturing output, production targets, quality, and downtime.

**Key Highlights**

- Total Production
- Total Defects
- Defect Rate (%)
- Total Downtime (Hours)
- Target Achievement (%)
- Production Rate (Units/Hour)
- Monthly Production Trend
- Production by Machine
- Production by Shift

![Production Overview](MFP.png)

### ⚙️ Page 2 — Machine & Quality Analysis

Analyzes machine-level performance and product quality to identify areas that require further investigation.

**Key Highlights**

- Defect Rate by Product
- Failed Quality Checks by Machine
- Machine Performance Details
- Production by Production Line
- Downtime Comparison Across Machines
- Product Quality Performance
- Machine-Level Operational Analysis

![Machine & Quality Analysis](MFP-1.png)

### 💡 Page 3 — Executive Insights & Action Plan

Summarizes the major findings from the sample dataset and translates them into recommended actions for production, maintenance, and quality teams.

**Key Highlights**

- Key Business Findings
- Recommended Actions
- Priority Investigations
- Responsible Teams
- Success Measures
- Management Action Plan

![Executive Insights & Action Plan](MFP-3.png)

## 📈 Key Performance Indicators (KPIs)

| KPI | Definition |
|---|---|
| Total Production | Sum of units produced |
| Total Target Units | Sum of planned production targets |
| Target Achievement (%) | Actual production ÷ target production × 100 |
| Total Defects | Sum of defective units |
| Defect Rate (%) | Total defective units ÷ total units produced × 100 |
| Total Downtime (Hours) | Total downtime minutes ÷ 60 |
| Production Rate | Units produced ÷ production hours, where applicable |

## 🔍 Key Findings

Based on the sample dataset and dashboard calculations:

- **Total Production:** 549,408 units.
- **Target Production:** 647,994 units.
- **Target Achievement:** 84.79%.
- **Production Gap:** 98,586 units below target.
- **Total Defects:** 19,554 units.
- **Overall Defect Rate:** 3.56%.
- **Total Machine Downtime:** Approximately 2,642 hours.
- **Highest Downtime Machine:** M-03, with approximately 699 hours.
- **Highest Defect Rate Product:** P-102, at approximately 4.01%.
- **Shift Analysis:** The morning shift recorded the highest total production volume.

*These figures are calculated from the synthetic dataset. They are illustrative portfolio results, not verified industrial benchmarks.*

## 🧠 Business Recommendations

### 1. Investigate Machine M-03 Downtime

**Finding:** Machine M-03 recorded the highest downtime in the sample data.

**Recommended Actions**
- Review breakdown and maintenance logs.
- Investigate recurring machine stoppages.
- Examine preventive maintenance schedules.
- Compare downtime across machines and shifts.

**Responsible Team:** Maintenance Team  
**Success Measure:** Downtime hours by machine.

### 2. Investigate Product P-102 Quality

**Finding:** Product P-102 recorded the highest displayed defect rate.

**Recommended Actions**
- Review defect categories and inspection records.
- Investigate material batches and process settings.
- Compare defect patterns across machines and shifts.
- Track corrective actions and subsequent defect rates.

**Responsible Team:** Quality Team  
**Success Measure:** Defect rate by product.

### 3. Improve Production Target Achievement

**Finding:** Actual production was below the planned target in the sample data.

**Recommended Actions**
- Review production schedules and capacity utilization.
- Investigate downtime and changeover periods.
- Compare performance across shifts and production lines.
- Monitor actual output against targets regularly.

**Responsible Team:** Production Manager  
**Success Measure:** Target achievement percentage.

### 4. Establish Regular KPI Monitoring

- Track production, quality, and downtime KPIs.
- Compare results against validated operational baselines.
- Assign owners to corrective actions.
- Review improvements over time before claiming measurable benefits.

**Important:** These recommendations identify areas for investigation. The dashboard alone does not establish root causes or prove cost savings.

## 📚 Skills Demonstrated

- Data understanding and data-quality checks.
- Python-based data inspection and preprocessing.
- Exploratory data analysis.
- Manufacturing KPI analysis.
- Power BI dashboard development.
- DAX measure creation.
- Interactive charts, filters, and slicers.
- Machine downtime and product-quality analysis.
- Business insight generation.
- Action-oriented recommendations.
- GitHub documentation and portfolio presentation.

## 📁 Repository Structure

```text
Manufacturing-Production-Analytics/
│
├── README.md
├── day1_manufacturing_production_dataset.csv
├── day1_manufacturing_data_dictionary.csv
├── MFP.png
├── MFP-1.png
└── MFP-3.png
```

Add your Python notebook or script and Power BI `.pbix` file if you intend to share them. Keep the file names in this structure consistent with the files you actually upload.

## 🚀 Future Enhancements

- Add SQL-based analysis and reporting.
- Perform deeper root-cause analysis using machine and maintenance logs.
- Develop predictive maintenance indicators.
- Track corrective actions and improvement outcomes.
- Automate data refresh and KPI reporting.
- Integrate additional manufacturing data sources.

## 👨‍💻 Author

**Anil Kumar**  
Aspiring Data Analyst | Python | SQL | Power BI | Excel

- **GitHub:** [thandaanil987](https://github.com/thandaanil987)
- **LinkedIn:** Add your actual LinkedIn profile URL here.

---

⭐ If you find this project useful, consider giving the repository a star.
